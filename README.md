# Advanced Tab Groups  
_⬇️continue to main repo below⬇️_

## ✨Soon! ✨

With the release of Firefox 135, tab groups will be enabled by default. The dev (Maruo) had said that he will begin working on tab groups/folders (and better split views, with visual indication of what tabs are split!) once they were out of beta, now that this has happened we hope to see native implimentation soon -making this repo obsolete! 
[**PR for Firefox 135 update!**](https://github.com/zen-browser/desktop/pull/4675)
![Screenshot 2025-01-28 at 16-49-00 Updated to firefox RC 135 0 by mauro-balades · Pull Request #4675 · zen-browser_desktop](https://github.com/user-attachments/assets/586a15c7-26c7-4da4-ac81-bf216dae8909)

---

CSS for Zen Browser's experimental Tab Groups using `userChrome.css`.  

![Advanced Tab Groups](https://github.com/user-attachments/assets/9541500c-4c91-4bf0-97b2-f8a519a0144f)  

---

## ⚠️ Notice  


_To use this CSS, you must configure Zen Browser's `userChrome.css` and enable the listed preferences in `about:config`._  

If you're unfamiliar with `userChrome.css`, please refer to [this guide](https://docs.zen-browser.app/guides/live-editing). If you encounter any issues, feel free to create an issue on this repository.  

---

## How to Use  

1. Enable `browser.tabs.groups.enabled` in `about:config` to activate Firefox's experimental Tab Groups feature (works in all versions of Zen Browser).  
2. Follow [this guide](https://docs.zen-browser.app/guides/live-editing) to set up `userChrome.css`.  
3. Copy the CSS from this repository into your `userChrome.css` file.  
4. Add the configuration booleans listed below in `about:config` and adjust them to your liking.  
5. Enjoy your customized tab groups!  

---

## Configuration Options  

Add these preferences to `about:config` to enable additional features:  

- **`tab.groups.add-arrow`**  
- **`tab.groups.background`**  
- **`tab.groups.borders`**  
- **`tab.groups.theme-folders`**  
- **`tab.groups.fill-folders`**
- **`tab.groups.display-tab-range`**

---

## What Does This Do?  

This CSS improves the functionality and appearance of Zen Browser's experimental Tab Groups.  

---

## Features  

### 1. **Custom Background for Tab Groups**  
Apply a background that matches the tab group color for a cleaner and more cohesive look.

![Group Background](https://github.com/user-attachments/assets/072399e3-6d1a-4e18-bcb6-d4ffc14e99b4)

---

### 2. **Border Around Tab Groups**  
Add a subtle border to enhance the visual separation of tab groups (requires background to be enabled).  

![Group Background With Borders](https://github.com/user-attachments/assets/45e87a2a-da2b-485f-bcb0-7dc1c35da1ac)

---

### 3. **Expandable Tab Groups with Arrows**  
Add an arrow icon to indicate whether a tab group folder is open or closed.  

![Add Arrows](https://github.com/user-attachments/assets/b813a989-5622-4b79-9aa6-0528b48d9850)

---

### 4. **Themed Folder Icons**  
Color folder icons based on the tab group color to visually differentiate groups.  

![Theme Icons](https://github.com/user-attachments/assets/cb4e4c1e-73d6-4688-bb41-76675ef4afae)

---

### 5. **Folder Icon Fill**  
Customize the folder icon fill with your tab group color—or leave it empty, depending on your preference.  

![Fill Icons](https://github.com/user-attachments/assets/befc0ac8-2861-4ff8-9b16-e5ce00cf647a)

---

### 5. **Display Tab Range**  
Have a line sowing where the folder starts and stops  

![Tab Range](https://github.com/user-attachments/assets/e0bf30d3-39df-46da-b746-7cfb54f82f09)

---

## Suggestions  

Have an idea for a feature? Start a discussion! I'm happy to explore any Zen CSS-related requests.  

---

## Credit  

Special thanks to [https://github.com/nieffka/bubble-clean-zen](https://github.com/nieffka/bubble-clean-zen) for the original CSS theme and inspiration!

<img src="https://github.com/heyitszenithyt/zen-browser-badges/raw/fb14dcd72694b7176d141c774629df76af87514e/light/zen-badge-light.png" alt="Made For Zen Badge">
