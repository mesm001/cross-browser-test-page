# Cross Browser Test Page

This repository hosts a simple **demo page** for testing **cross-browser automation, self-healing locators, and UI differences**.  
It intentionally behaves differently in Chrome, Edge, Safari, and Firefox.

---

## 🚀 Live Demo
Once you enable **GitHub Pages**, your page will be available at:


## 📄 Features on the Page

1. **Navigation with multiple "pages"**
   - `Home` → shows an OpenText logo image.
   - `Form` → shows form fields and buttons.
   - `About` → explains browser differences.

2. **Cross-Browser Differences**
   - **`:has()` CSS Selector**
     - Chrome/Edge/Safari → section around the button has a **red border**.
     - Firefox (older versions) → section keeps a **gray border**.
   - **`<input type="date">`**
     - Chrome/Edge/Safari → renders a **date picker** widget.
     - Firefox (desktop) → falls back to a **plain text input**.

3. **Form Elements**
   - Textbox: `Name`
   - Date Input: `<input type="date">`
   - Button: `Save` (with alert action)

4. **Image**
   - OpenText logo loaded from [Wikimedia](https://commons.wikimedia.org/wiki/File:OpenText_logo.svg).

---

## 🛠 How to Use

### 1. Clone this repo
```bash
git clone https://github.com/<your-username>/cross-browser-test-page.git
cd cross-browser-test-page
