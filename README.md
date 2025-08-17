# Ethical Hacker Portfolio Themes

A curated gallery of **hacker-style portfolio themes** with live preview, built using  **HTML, Tailwind CSS, and JavaScript** .

Easily browse, preview, and download portfolio templates stored in the `/themes` directory.

---

## 🚀 Features

* **Full-Screen Layout** – Clean UI with responsive sidebar and preview section.
* **Theme Gallery** – Displays all available portfolio themes from `/themes`.
* **Live Preview** – Instantly loads themes in an embedded iframe.
* **Search & Filter** – Quickly find themes by name, file, or author.
* **Toolbar Actions** :
* Reload the preview
* Open theme in a new tab
* Copy embed code
* **Download Source** (HTML file)
* **Manifest Support** – Use `/themes/manifest.json` for custom theme metadata.
* **Custom Contact Info** – Sidebar includes creator contact for portfolio site development.

---

## 📂 Project Structure

```
/index.html        # Main gallery app
/themes/           # Folder containing theme HTML files
  ├─ manifest.json # Optional metadata file
  ├─ captain-nemo.html
  ├─ hacker-ninja.html
  ├─ hacker-reaper.html
  └─ ...
```

### Example manifest.json

```json
{
  "themes": [
    { "file": "captain-nemo.html", "name": "Captain Nemo", "author": "nemocyberworld" },
    { "file": "dark-matrix.html", "name": "Dark Matrix", "author": "0xleopards" }
  ]
}
```

---

## 🛠️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Open `index.html` in your browser.

   The gallery will automatically load themes from `/themes`.
3. Add your custom theme HTML files to the `/themes` directory.

   Update `manifest.json` if you want to display theme names and authors.

---

## 📥 Adding New Themes

1. Create a new `.html` file inside `/themes`.
2. (Optional) Add metadata in `manifest.json`.
3. Reload the gallery to see your theme in the list.

---

## 📧 Contact

For  **custom portfolio site development** , contact the theme creator:

👉 [nemo14398@mail.com](mailto:nemo14398@mail.com)
