# 🖼️ Image Resizer Tool

A simple Python script to **resize and convert images in batch** using [Pillow](https://pillow.readthedocs.io/).

## 🚀 Features
- Resize all images in a folder
- Supports multiple formats: `.jpg`, `.jpeg`, `.png`, `.bmp`, `.gif`
- Saves resized images into an output folder
- Automates repetitive image processing tasks

## 🛠️ Tools Used
- **Python**
- **Pillow (PIL)**

## 📂 Project Structure
📁 project/
┣ 📂 images/ # Input images (add your original images here)
┣ 📂 resized/ # Output resized images (auto-created)
┣ 📄 image_resizer.py
┗ 📄 README.md


## ▶️ How to Run
1. Install Pillow (if not installed):
   ```bash
   pip install pillow
   Put all your images inside the images/ folder.

Run the script:

   python image_resizer.py
   Resized images will be saved inside the resized/ folder.

   Example

Original image: 800x600

After resizing: 300x300
Outcome: Automates batch image resizing and conversion.

