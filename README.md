# Wplace Dark/Light Toggle (UserScript)

![Preview](https://github.com/Anybody4506/wplace-theme/blob/main/iRvKW9me4c.png)

---

## Installation (Tampermonkey)

1. Install **Tampermonkey** or another userscript manager (Violentmonkey, Greasemonkey).
2. Open the `wplace-toggle.user.js` file or paste its content into a new script in your userscript manager.
3. Save and enable the script. It runs at `document-start`.
4. Open any `*.wplace.live/*` page. A theme toggle button will appear in the top-left control panel.

## Usage

- The script adds a small circular button to the top-left control stack.
- Click it to switch between **dark** (Fiord) and **light** (Liberty) map styles.
- The selected theme is saved in `localStorage` under the key `wplace_unified_theme`.
  - Value `light` → Liberty style and UI theme `custom-winter`.
  - Any other value (or missing) → Fiord style and UI theme `dark`.
- Toggling updates the stored value and reloads the page to fully apply the change.
