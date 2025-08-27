# 🖼️ Ian's Universal Image Resizer & Optimizer v1.0

**Tired of upload limits, bloated image files, and sketchy online converters?**
Say hello to your new best friend for image resizing, compression, and optimization – all in one lightning-fast, browser-based tool.

No installation. No tracking. No file uploads to a server.
**All operations are performed locally on your browser using AI-driven smart optimization.**

---

## 🚀 Features

* ✅ **Resize** images to a maximum dimension of **500px** while preserving format and quality
* ✅ **Compress** images to approximately **50kB** using intelligent resolution and quality scaling
* ✅ **Optimize** using **both resize & compress** for ultra-efficient results
* ✅ **Preserve original filenames**
* ✅ **Supports up to 50 images** per session
* ✅ **Drag-and-drop interface** — super intuitive and snappy
* ✅ **No internet required** after initial load (purely client-side)

---

## 🧰 Supported File Types

**Input Formats:**

* PNG, JPG, JPEG, WEBP, GIF, BMP

**Output Formats:**

* PNG (resize-only)
* JPEG (compress or optimize)

---

## 📝 Instructions

1. Open `photoResizerOptimiser.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. **Upload** up to 50 images via drag-and-drop or file picker
3. Choose one of three modes:

   * 🔹 **Resize Only**: Scales images to 500px max (no compression)
   * 🔸 **Compress Only**: Keeps size but compresses to \~50kB (JPEG)
   * 🟢 **Resize & Compress**: Best of both worlds
4. Download your images individually or bundled as a ZIP

---

## 📦 How It Works

This tool uses HTML5 `<canvas>` and modern JavaScript to:

* Dynamically resize images while maintaining aspect ratio
* Analyze each image to determine the best compression ratio without noticeable quality loss
* Batch process all selected files and display individual stats
* Provide per-image download links and a ZIP option for bulk download

All logic runs locally in your browser. Your files **never leave your device**.

---

## 📊 Sample Output Stats

| Mode              | Avg File Size | Compression Ratio | Output Format |
| ----------------- | ------------- | ----------------- | ------------- |
| Resize Only       | \~150kB       | Varies            | PNG/JPEG/WEBP |
| Compress Only     | \~50kB        | \~85%+            | JPEG          |
| Resize & Compress | \~45kB        | \~90%+            | JPEG          |

---

## 🔒 100% Private & Secure

This tool works entirely offline after initial load.
✅ No cloud processing
✅ No third-party API calls
✅ No data collection

Use it confidently for sensitive or personal images.

---

## 🛠️ Installation (Optional)

Want to host it locally or share with your team?

1. Clone or download this repository
2. Open `photoResizerOptimiser.html` in a browser
3. Done!

---

## 💡 Use Cases

* ✅ Compressing images before email attachments
* ✅ Optimizing photos for web/blog use
* ✅ Resizing content for mobile apps
* ✅ Avoiding premium/paywalled tools
* ✅ Keeping image backups small and efficient

---

## 🙌 Contribute or Customize

This is a clean, open-source HTML+JS project.
Feel free to fork, extend, or adapt it for your own use case.

You can easily:

* Change default resize dimensions
* Adjust compression targets
* Customize styles or UI
* Add more formats

---

## 📄 License

MIT License – Free for personal and commercial use.
No attribution required, but always appreciated!

---

## 🧠 Created By

**Ian's Image Toolkit** – simple tools for powerful image control.

---
