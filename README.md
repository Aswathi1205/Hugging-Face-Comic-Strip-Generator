# 📚 Comic Strip Generator

## 🎯 Project Overview

This is a Python-based **Comic Strip Generator** that creates comic panels from predefined stories.
The system allows you to:

* Select storylines
* Choose character emotions per panel
* Pick different backgrounds per panel
* Automatically wrap text inside speech bubbles
* Generate comics in a horizontal or vertical layout

> ✅ Easy to use, visually appealing, and fully customizable.

---

## 🚀 Features

✔️ Number-based character selection (user-friendly)

✔️ Dialogues preview while selecting characters

✔️ Multiple backgrounds selection per panel

✔️ Automatic text wrapping inside speech bubbles

✔️ Rounded speech bubbles with speech tails

✔️ Layout selection: Horizontal (1x4) or Vertical (4x1)

✔️ Comic strip auto-saved as PNG

---

## 🛠️ Requirements

* Python 3.8+
* Libraries:

  * `Pillow`
  * `matplotlib`
  * `textwrap` (Python built-in)

### Install Dependencies:

```bash
pip install pillow matplotlib
```

---

## 📂 Project Structure

```text
comic_generator.py           # Main Python script (can also run in Google Colab)
My Drive/
└── comic_assets/            # Folder in Google Drive containing images
    ├── hero_action.png
    ├── hero_happy.png
    ├── villan_cute.png
    ├── villian_classic.png
    ├── forest_glade.jpg
    ├── city_day.png
    └── forest_path.png
```

---

## 📸 Sample Outputs

* Horizontal comic strip: `comic_strip_horizontal.png`
* Vertical comic strip: `comic_strip_vertical.png`

---

## 📝 How to Run in Google Colab

### ✅ Step 1: Mount Google Drive

At the top of your Colab notebook, add:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Follow the authorization link and mount your drive.

---

### ✅ Step 2: Use Provided Image Assets

📁 **Google Drive Assets Folder:**
[Comic Assets Folder](https://drive.google.com/drive/folders/1i5Sn0xI_NTUqNG729hEDux4AH4Sf-xBi?usp=sharing)

Please **download these assets** and upload them to your own Google Drive folder:

```
/content/drive/My Drive/comic_assets/
```

Or you can directly use the paths if the assets are in your own Drive.

---

### ✅ Example Image Paths:

```text
/content/drive/My Drive/comic_assets/hero_action.png
/content/drive/My Drive/comic_assets/villan_cute.png
/content/drive/My Drive/comic_assets/forest_glade.jpg
```

Update these paths in your Python code where images are loaded.

---

### ✅ Step 3: Run the Script

Follow on-screen prompts to:

* Select story
* Choose comic layout (horizontal/vertical)
* Select backgrounds
* Select character emotions per panel

The comic will be displayed and saved automatically as:

* `comic_strip_horizontal.png` or
* `comic_strip_vertical.png`

---

## ☁️ Google Drive Tips

* Store all comic assets in **one organized folder.**
* Always use the correct Drive path format:

  ```text
  /content/drive/My Drive/comic_assets/filename.png
  ```
* Make sure the image names match what the code expects.

---

## 🎮 Future Improvements

* 🎨 Custom font support for speech bubbles
* 🔁 Auto-resizing speech bubbles based on text size
* 🎬 Export comic as GIF or PDF
* 🔊 Add sound effect text like "POW!" or "ZAP!"
* 🌐 Web comic scrollable format (web deployment)

---

## ✨ Credits

* **Developed by:** Aswathi V
* **Image Resources:** Provided by the user via Google Drive
* **Assets Folder:** [Comic Assets on Google Drive](https://drive.google.com/drive/folders/1i5Sn0xI_NTUqNG729hEDux4AH4Sf-xBi?usp=sharing)

---
