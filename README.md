# Image Editor 🎨🖼️

A simple and interactive browser-based image editor built with **HTML, CSS, and JavaScript** using the **Canvas API**.
Users can upload images, apply filters in real-time, use preset effects, reset edits, and download the edited image instantly.

---

## 🚀 Features

* 📤 Upload images from your device
* 🎚️ Real-time filter adjustments
* 🎨 Multiple image filters:

  * Brightness
  * Contrast
  * Saturation
  * Hue Rotation
  * Blur
  * Grayscale
  * Sepia
  * Opacity
  * Invert
    
* ✨ Preset effects:
  * Normal
  * Drama
  * Vintage
  * Old School
  * Cinematic
  * Cool
  * Warm
  * Faded
  * Noir
  * Dreamy
* 🔄 Reset all filters
* 💾 Download edited image
* ⚡ Instant preview using HTML5 Canvas

---

## 📸 Preview

Add a screenshot or GIF here.

```md
![Preview](./preview.png)
```

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Canvas API

---

## 📂 Project Structure

```bash
image-editor/
│
├── index.html
├── style.css
├── script.js
├── preview.png
└── README.md
```

---

## ⚙️ Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/TanviLokhande06/Image-Editor.git
```

### 2. Open the project folder

```bash
cd Image Editor
```

### 3. Run the project

Simply open `index.html` in your browser.

---

## 🎛️ Available Filters

| Filter       | Range      |
| ------------ | ---------- |
| Brightness   | 0 - 200%   |
| Contrast     | 0 - 200%   |
| Saturation   | 0 - 200%   |
| Hue Rotation | 0 - 360deg |
| Blur         | 0 - 20px   |
| Grayscale    | 0 - 100%   |
| Sepia        | 0 - 100%   |
| Opacity      | 0 - 100%   |
| Invert       | 0 - 100%   |

---

## 🧠 How It Works

The app uses the HTML5 Canvas API and dynamically applies CSS-like filters using:

```javascript
canvasCtx.filter = `
brightness(...)
contrast(...)
saturate(...)
hue-rotate(...)
blur(...)
grayscale(...)
sepia(...)
opacity(...)
invert(...)
`;
```

Every time a slider changes, the image is redrawn on the canvas with updated filters.

---

## 📥 Download Feature

Edited images are exported using:

```javascript
imageCanvas.toDataURL()
```

This allows users to save the final image as a PNG file.

---

## 🌟 Future Improvements

* Crop tool
* Rotate & flip image
* Drag-and-drop upload
* Mobile responsiveness
* Undo/Redo support
* Custom preset saving
* Dark mode UI

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Made with ❤️ by **Tanvi Lokhande**
