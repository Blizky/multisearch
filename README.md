# Multi-Search

Multi-Search is a tiny single-page tool to search **multiple free-media websites at once**.  
Type a term once, pick a category (Videos / Photos / Public Domain / PNGs), and it opens all the enabled sites in new tabs.

**Visit this page to use it:**
https://blizky.github.io/multisearch

⚠️ **To open several sites at once, your browser must allow pop-ups for this page.**

---
![CleanShot 2025-11-26 at 22 45 25](https://github.com/user-attachments/assets/6610ef2c-d8c2-454e-b12d-df31f590c7de)

## Features

- **One search, many sites**
  - Videos: Pixabay, Pexels, Mixkit (or whatever you configure)
  - Photos: Pixabay, Pexels, Unsplash
  - Public domain: Picryl, Wikimedia Commons, OpenVerse (CC0)
  - PNGs (transparent): RawPixel PD, KindPNG, PNGEgg
- **Category buttons**
  - `Videos`, `Photos`, `Public`, `PNGs`  
  - Press **Enter** to search Videos, or click a button to choose a category.
- **Site toggles**
  - Each site appears as a pill under its category.
  - Click a site name to enable/disable it for that category.
  - Only enabled sites will open in tabs.

- **Dark / light theme**
  - Simple **moon/sun toggle** at the bottom right.
  - Choice is saved in `localStorage`.

- **Language toggle**
  - EN / ES switch (with flags).
  - All UI text (headings, tip, popup warning, manage dialog) changes instantly.
  - Language preference is saved in `localStorage`.

- **Manage Sites**
  - Button at the bottom opens a modal editor with a JSON list of sites:
    - `id` – unique string
    - `name` – label shown in the UI
    - `category` – `"videos" | "photos" | "public" | "pngs"`
    - `url` – search URL containing `%s` where the term should go
    - `enabled` – `true` / `false`
  - Edits are stored only in your browser via `localStorage`.

- **Popup-permission hint**
  - Thin warning bar at the very top:
    - EN: “To open multiple sites at once, please allow pop-ups for this page.”
    - ES: “Para abrir varios sitios a la vez, permite las ventanas emergentes (pop-ups) de esta página.”
  - “Got it” button hides it and remembers your choice.

---

## How it works

1. **User input**
   - You type a term in the main search bar.
   - Hit **Enter** or click one of the category buttons.

2. **URL expansion**
   - For the chosen category, the app:
     - loads the site list from `localStorage` (or defaults on first run),
     - filters only `enabled` sites with a matching category,
     - replaces `%s` inside each `url` with the URL-encoded search term.

3. **Opening tabs**
   - It calls `window.open()` for each site.
   - Most browsers will block this until pop-ups are allowed for the page, which is why the warning exists.

4. **State & settings**
   - Enabled/disabled sites, language, theme and the “popup warning seen” flag are all saved in `localStorage` under keys like:
     - `ms-sites-v5`
     - `ms-theme`
     - `ms-lang`
     - `ms-popup-seen`

---

## Usage

1. Open the page (GitHub Pages or a local file).
2. **Allow pop-ups** when your browser asks.
3. Type a term: `forest`, `retro computer`, `anatomy`, etc.
4. Click a category:
   - `Videos` → opens all enabled video sites for that term.
   - `Photos` → opens all enabled photo sites.
   - `Public` → opens public-domain/CC0 results.
   - `PNGs` → opens transparent PNG sources.
5. Click site pills under each category to turn individual sites on/off.
6. Use **Manage sites** if you want to:
   - rename sites,
   - add new ones (just include `%s` in the URL),
   - disable defaults permanently.

---

## Customization

- **Add a new site**

  In *Manage sites*, add an object like:

  ```json
  {
    "id": "example_v",
    "name": "Example (video)",
    "category": "videos",
    "url": "https://example.com/search/%s?type=video",
    "enabled": true
  }
