CINE.LAB - Disposable Camera Emulator

CINE.LAB is a browser-based tool that instantly converts digital photos into authentic-looking disposable camera scans. It runs entirely in your browser using HTML5 Canvas, ensuring your photos remain private and are never uploaded to a server.

🔗 Live Demo (Click to try)

📸 Features

Authentic Film Look: Custom color grading engine tuned to mimic 35mm disposable film stocks (Fujifilm/Kodak style).

Lifted shadows (matte black look)

Warm highlights with greenish-teal shadow tints

Soft "Bloom" / Haze effect for that cheap plastic lens vibe

Heavy organic grain simulation

Batch Processing: Drag and drop 1 or 100+ images at once. The engine processes them sequentially without freezing your browser.

Privacy First: All processing happens locally on your device. No data is sent to the cloud.

Bulk Download: Automatically zips multiple processed images into a single file for easy download.

No Watermarks: Clean, high-quality output.

🚀 How to Use

Open the Live Website.

Drag & Drop your photos (JPG, PNG, or WEBP) into the upload area.

Wait for the "Developing" animation to finish.

Click Download to save your photos (saves as a .zip if you uploaded multiple files).

🛠️ Tech Stack

HTML5 Canvas: For pixel-level image manipulation and filtering.

Tailwind CSS: For the retro-modern dark UI.

JSZip: For bundling multiple images into a ZIP file in the browser.

Single-File Architecture: The entire app lives in one index.html file, making it easy to host or run offline.

💻 Running Locally

You can run this app offline on your computer:

Download the index.html file from this repository.

Double-click it to open in Chrome, Safari, or Edge.

That's it! No servers or installation required.

Created by Gurungsa