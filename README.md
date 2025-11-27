# Multi-Search

Multi-Search is a tiny single-page tool to search **multiple free-media websites at once**.  
Type a term once, pick a category (Videos / Photos / Public Domain / PNGs), and it opens all the enabled sites in new tabs.

![CleanShot 2025-11-27 at 10 49 45](https://github.com/user-attachments/assets/b049da45-98c0-4e54-9422-820f5847a7f5)


## Who Is This Tool Useful For?

- **Content creators** — find visual assets fast for YouTube, podcasts, and social posts.
- **Video editors** — quickly gather B-roll, intro clips, overlays, and cutout PNGs.
- **Graphic designers** — search multiple photo or PNG sites at the same time.
- **Researchers & writers** — pull reference images or public-domain materials in one click.
- **Teachers & students** — gather visual resources for presentations or school projects.
- **Social media managers** — speed up searching for on-brand images across different sources.
- **Anyone who saves time by not searching site-by-site**
  Multi-Search removes the repetitive part of browsing multiple stock or media libraries.

## Features

- **Search many sites at once**
  Instead of checking websites one by one, type your search term once and Multi-Search opens all the sites you choose in separate tabs.  
  Great for quickly finding videos, photos, public-domain images, or PNGs.

- **Turn sites on or off with a click**
  Every site appears as a small rounded button (a “chip”).  
  Click one to **temporarily disable it** — useful when:
  - you only want results from your favorite sites  
  - you want to compare a few sites at a time  
  - you want to keep some as “backup” options  
  Click again to turn it back on.

- **Customize your own list of sites**
  The **Manage Sites** button opens an editor where you can:
  - rename sites  
  - add new ones  
  - remove ones you don’t use  
  - move a site to a different category (Video, Photo, Public Domain, PNG)  
  After making changes, click **Save** to apply them. Your updated list appears immediately in the main interface.

- **Export and import your setup**
  You can save your entire configuration (your site list, names, categories, and which ones are enabled) into a portable `.json` file.
  - **Export** → creates a backup you can save or share.  
  - **Import** → loads your setup on another computer or browser.
  This makes it easy to bring your Multi-Search preferences anywhere.

- **Dark mode / Light mode**
  Click the moon or sun icon to switch themes.  
  Multi-Search remembers your choice the next time you open the page.

- **English or Spanish**
  Switch languages with the flag buttons.  
  The whole interface updates instantly.  
  If your browser is in Spanish, Multi-Search selects Spanish automatically.

- **Helpful popup reminder**
  The first time you use Multi-Search, it shows a small warning explaining you may need to **allow pop-ups** so the tool can open several sites at once.  
  Click “Got it” and you won’t see it again.

- **Your settings stay private**
  Everything is saved **only in your own browser**:
  - your custom site list  
  - your theme (dark/light)  
  - your language  
  - which sites are enabled  
  Nothing is uploaded anywhere.  
  If you clear your browser’s storage, everything returns to default.

## Multi-Search vs browser extension

MultiSearch works like a “search-in-many-sites” tool, but without the problems that come with browser extensions.

**1. No installation.** No browser store, no permissions, no updates.  Just open the HTML file or GitHub page and use it.

**2. Works everywhere.** Extensions only work in specific browsers. MultiSearch works on any device or browser, including mobile.

**3. No permissions or tracking.** Extensions often read your tabs or browsing data. MultiSearch requests nothing and stores everything locally on your own browser.

**4. Lightweight and fast.** Extensions run in the background and slow the browser down.  MultiSearch is a simple page that does nothing unless you click a button.

**5. Fully transparent and customizable.** You see every line of code. You can modify it, add your own sites, or restyle it however you want.

**6. Portable.** Save the file, email it, or host it anywhere. You’re not tied to one browser or one machine.

**In short:** MultiSearch gives you the same multi-site searching convenience as an extension, but with no risks, no tracking, and full control.

## Works Offline (Interface Only)

Multi-Search is a single HTML file. The interface loads instantly and works offline:
- You can open the page  
- Change settings  
- Manage your site list  
- Switch themes or languages  

Only the **search results** require internet — external sites won’t load without a connection (so tell your mom to hang up the phone).

## Use It Locally (Save the Code)

You don’t need a server or installation. Multi-Search can live on your computer like any normal file.

How to save it locally:
1. Open the HTML file on GitHub.  
2. Click **Raw**.  
3. Right-click → **Save As…**  
4. Save as **multisearch.html**.  
5. Open it anytime in your browser.

Everything still works:
- Search buttons (when online)
- Dark/light mode  
- Language switch  
- Your custom site list (saved in your browser)

Using the local version is great if you want speed, portability, or a backup when you’re offline.



## Usage

1. Open the page (GitHub Pages or a local file). [↗ Open Multi-Search](https://blizky.github.io/multisearch)
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
  
⚠️ **To open several sites at once, your browser must allow pop-ups for this page the first time.**

Search something, go back to the Multi-Search page and click **Preferences**

![CleanShot 2025-11-27 at 10 27 52](https://github.com/user-attachments/assets/9a2aa2ce-96fb-43d5-857a-f8c9501ec589) 
![CleanShot 2025-11-27 at 10 38 18](https://github.com/user-attachments/assets/7b7cda05-108a-4b37-9fe6-738d48b69fa9)

---

[![Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/blizky)


## Is Multi-Search legal? (Short answer: Yes.)

MultiSearch is safe to use and does not violate any website’s terms. Here’s why:

**1. MultiSearch does *not* copy or scrape anything.** The tool does **not** download, mirror, embed, or store content from any external site. It simply opens normal search URLs in new browser tabs — just like clicking a bookmark.

**2. It sends users *to* the official websites.** All searches open on the real platforms (Pixabay, Pexels, Unsplash, etc.). Users still see ads, licensing info, download pages, and login prompts exactly as intended. MultiSearch **increases** traffic to those platforms, not the opposite.

**3. No licensing or content is bypassed.** Users must still follow each site’s official rules and licenses. Nothing in MultiSearch modifies, hides, or avoids this requirement.

**4. This is equivalent to:**
- opening multiple bookmarks at once  
- using a “search-in-many-sites” browser extension  
- clicking a list of links on a webpage

  This is standard, normal web behavior.

**5. What MultiSearch does *not* do**
To be extra clear, MultiSearch **never**:

- scrapes thumbnails or text  
- embeds protected media  
- calls private APIs  
- downloads anything on behalf of the user  
- sells or redistributes assets  
- pretends to be any of the listed sites  

All trademarks and content remain property of their respective owners.

**Optional user note:** Some sites may block multiple pop-ups by default. Users simply need to click “Allow pop-ups” once for the tool to work smoothly.

**Conclusion:**  MultiSearch is essentially a **visual bookmark manager** that opens the official search pages for you. There is no legal conflict, and the tool stays fully within safe, respectful, standard web behavior.


## How Preferences Are Stored (Local Only)

Multi-Search does not use a server or database.  
**All your settings are saved only inside your browser**, using the built-in `localStorage` API.  
This means your preferences stay private and never leave your device.

### What gets stored
The app saves a few small JSON objects:

| Key | Purpose |
|-----|---------|
| `ms-sites-v4` | Your custom list of search sites (name, URL, category, enabled/disabled) |
| `ms-theme` | Your selected theme: `"dark"` or `"light"` |
| `ms-lang` | Interface language: `"en"` or `"es"` |
| `ms-popup-seen` | Whether you've dismissed the “allow pop-ups” warning |

### Important details
- **Each browser keeps its own settings.**  
  If you open the page in Chrome, Firefox, and Edge, each one will have its own separate site list and theme.  

- **Your preferences persist even if you close the browser** — until you clear your cache or local storage.

- **Updating the HTML file does not reset user preferences.**  
  Anyone using your tool will keep all their custom sites after you update or replace the file on GitHub Pages.

- **No data is uploaded anywhere.**  
  Everything is stored locally, client-side only.

### How to reset your settings
If someone wants to return to default settings:

1. Open the browser’s Developer Tools.  
2. Go to **Application → Local Storage** (Chrome) or **Storage → Local Storage** (Firefox).  
3. Delete the keys starting with `ms-` (e.g., `ms-sites-v4`, `ms-theme`, etc.).  
4. Refresh the page.

This fully resets the tool to a clean state.

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

## License
**© 2025 Alex — Licensed under CC BY-NC-SA 4.0**<br>
Free for personal use. Not for commercial use.<br>
https://creativecommons.org/licenses/by-nc-sa/4.0/
