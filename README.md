# QGIS-LoadShapefile-Plugin
# Load Shapefile Plugin for QGIS

## 📌 Overview

This is a basic QGIS plugin that allows users to **select and load a shapefile (.shp)** into the QGIS interface using a simple graphical interface. It demonstrates core plugin development concepts like custom dialogs, using `QFileDialog`, and loading vector layers with `QgsVectorLayer`.

---

## ✅ Features

- Browse and select a shapefile via a button.
- Automatically load the selected shapefile into the current QGIS project.
- User feedback via success/error messages.

---

## 📁 Folder Contents

- `__init__.py` – Initializes the plugin.
- `mainplugin.py` – Main logic for loading shapefiles.
- `metadata.txt` – Plugin metadata for QGIS.
- `loadshapefileplugin_dialog_base.ui` – GUI layout file created with Qt Designer.
- `resources.qrc` and `resources.py` – Plugin resources (e.g., icons).
- `icon.png` – Icon displayed in QGIS toolbar.

---

## ▶️ Installation

1. Download the plugin folder or ZIP file.
2. In QGIS:
   - Go to **Plugins > Manage and Install Plugins > Install from ZIP**.
   - Browse to your downloaded `loadshapefileplugin.zip`.
3. Activate the plugin in the **Plugin Manager**.
4. You will see a new toolbar icon or menu item to launch the plugin.

---

## 🧑‍💻 Usage

1. Click the plugin icon or menu item.
2. A dialog will open — click the "Browse" button to select a `.shp` file.
3. If valid, the shapefile will be added to your QGIS map canvas.
4. You'll get a confirmation or error message depending on success.

---

## 🛠️ Requirements

- QGIS 3.x
- Python 3
- PyQt5 (comes bundled with QGIS)
- Qt Designer (for editing `.ui` file, optional)

---

## 📄 Author

**Apurwa Chaurasia**  
Ph.D. Researcher, Geomatics  
Indian Institute of Technology Roorkee  
Email: apurwa2776@gmail.com

---

## 📷 Screenshots

_Add screenshots of the plugin interface and loaded shapefile here._
![image](https://github.com/user-attachments/assets/f7a5021c-5e75-4f7b-a9a1-3e5f1edc3cf3)
![image](https://github.com/user-attachments/assets/46cd58d0-be1b-4add-82d4-dc10da54bdca)


---

## 📘 License

This plugin is provided for educational purposes. Feel free to reuse and modify it.

