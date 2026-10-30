# Blinkit Landing Page Clone

**Purpose** – A static, responsive clone of the Blinkit (blinkit.com) homepage built with **only HTML5 and CSS3**. The project demonstrates proper use of semantic markup, Flexbox, CSS Grid, and media queries to achieve a layout that adapts to desktop, tablet, and mobile screen sizes.

---

## 📂 Project Structure
```
blinkit-clone/
│
├─ index.html          # Main page – all sections: header, banner, promos, categories, footer
├─ style.css           # CSS3 styling (Flexbox, Grid, breakpoints)
├─ assets/             # Images and icons used by the page (currently only logo.svg)
│   └─ logo.svg
├─ screenshots/        # Required screenshots for evaluation
│   ├─ desktop.png      # Full‑screen desktop view (replace placeholder)
│   └─ mobile.png       # Phone view captured at 1080 × 2400 (Moto G54)
└─ README.md           # This file
```

---

## 🛠️ Technologies Used
- **HTML5** – semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **CSS3** – custom properties, Flexbox, CSS Grid, media queries (`max‑width: 900px` & `max‑width: 600px`).
- No JavaScript, frameworks, or external libraries.

---

## 📱 Responsiveness
| Device | Breakpoint | Layout changes |
|--------|------------|----------------|
| **Desktop** | ≥ 901 px | 3‑column promo grid, 10‑column category grid, header items inline. |
| **Tablet** | ≤ 900 px | Header wraps, promo grid → 2 columns, category grid → 5 columns. |
| **Mobile** | ≤ 600 px | Header stacked, promo grid → 1 column, category grid → 4 columns. |

---

## 📸 How to generate the required screenshots
### Desktop screenshot (Windows)
1. Open `index.html` in any browser and press **F11** for full‑screen.
2. Press **Print Screen** (or use **Snipping Tool**). Paste into Paint, crop to the viewport, and **Save As** `desktop.png`.
3. Move the file to `blinkit-clone/screenshots/desktop.png`.

### Mobile screenshot (Moto G54 5G) – **directly from the laptop**
1. **Enable USB debugging** on the phone: `Settings → About phone → tap Build number 7× → Settings → System → Developer options → USB debugging`.
2. Connect the phone to the laptop via a data‑capable USB‑C cable and accept the *Allow USB debugging?* prompt.
3. Open **Google Chrome** on the laptop and load the page:
   ```text
   file:///C:/Users/VATSAL%20JAIN/Desktop/New%20folder%20(4)/blinkit-clone/index.html
   ```
4. Press **F12** to open DevTools, then click the **device‑toolbar** (phone icon) and choose **Responsive** → **Edit…** → **Add custom device**.
   - Width: **1080**
   - Height: **2400**
   - Device pixel ratio: **3** (Moto G54 default)
   - Name it “Moto G54 Exact”.
5. Select the newly created device, reload the page if needed, then click the **⋮** menu in the device toolbar → **Capture screenshot**.
6. Chrome saves a PNG in `Downloads`. Rename/move it to:
   ```text
   blinkit-clone/screenshots/mobile.png
   ```
   The image will be **1080 × 2400 px**, matching the phone’s native resolution.

---

## ✅ How to run / view the project
1. Open the repository folder.
2. Double‑click `index.html` (or run `start index.html` from a PowerShell/Command Prompt).
3. The page loads offline – no server required.

---

## 📊 Evaluation Criteria (provided by the assignment)
| Category | Weight |
|----------|--------|
| Visual similarity to Blinkit homepage | **35 %** |
| Responsiveness (desktop / tablet / mobile) | **30 %** |
| HTML & CSS code quality (semantic, valid, well‑structured) | **20 %** |
| Spacing, fonts, alignment, images | **15 %** |

---

## 📂 Submission instructions
- **GitHub**: push the entire `blinkit-clone` folder to a repository (e.g., `https://github.com/<username>/blinkit-clone`). Ensure the repo is **public** or share the link with view‑only permission.
- **Google Drive** (if required): zip the folder and upload it, then share the link with “Anyone with the link can view”.

Make sure the screenshots (`desktop.png` and `mobile.png`) are the **final images**, not the placeholder zero‑byte files that were initially created.

---

## 🎉 Got everything?
You now have a clean, responsive Blinkit landing‑page clone ready for evaluation. If you need any further tweaks (e.g., swapping the SVG logo for a raster version, adding extra category icons, or fine‑tuning colors), just edit `index.html` or `style.css` and re‑capture the screenshots.

*Happy coding!*