SnapShrink Pro | Client-Side Image Compressor

A high-performance, browser-based image compression tool that prioritizes user privacy and speed. SnapShrink processes images entirely in the browser using the HTML5 Canvas API, meaning no files are ever uploaded to a server.

🔗 Live Demo

⚡ Features

100% Client-Side: Image processing happens locally. Zero latency, maximum privacy.

Format Conversion: Convert bulky JPEGs/PNGs to modern WebP format for 30%+ size reduction.

Smart Resizing: Automatically resize high-resolution images to web-friendly dimensions.

Visual Comparison: Real-time "Before vs. After" slider to inspect quality loss.

Drag & Drop UI: Clean, minimalist interface with immediate feedback.

🛠️ Technical Implementation

This project was built with Vanilla JavaScript (No frameworks/dependencies) to ensure maximum performance and lightweight load times.

Core Logic

File Reading: Uses FileReader to load the user's image into memory as a Base64 string.

Canvas Rendering: The image is drawn onto an HTML5 <canvas> element.

Resizing: Resolution is calculated based on the aspect ratio to fit the "Max Width" constraint.

Compression: Uses the canvas.toBlob(callback, mimeType, quality) method to re-encode the image stream with specific compression algorithms (e.g., lossy WebP or JPEG).

🚀 How to Run Locally

Since this is a static application, no Node.js or Python server is required.

Clone the repository

git clone [https://github.com/yourusername/snapshrink-pro.git](https://github.com/yourusername/snapshrink-pro.git)
