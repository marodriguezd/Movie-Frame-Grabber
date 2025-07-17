# Movie Frame Grabber 🎬

A simple, powerful, browser-based tool to extract frames from video files at a specified interval and download them as a ZIP archive. Everything is processed locally in your browser for maximum privacy and speed.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

### ✨ [Live Demo Here](https://marodriguezd.github.io/Movie-Frame-Grabber/)

![Movie Frame Grabber Screenshot](https://raw.githubusercontent.com/marodriguezd/Movie-Frame-Grabber/main/demo-screenshot.png)

## 🚀 Features

- **Entirely Browser-Based:** No software to install and no video data is ever uploaded to a server.
- **Drag & Drop:** Modern and easy-to-use drag-and-drop interface for video files.
- **Customizable Extraction:**
    - Set the time **interval** (in seconds) between frame captures.
    - Control the output **JPEG quality** to balance file size and clarity.
- **ZIP Package Download:** All extracted frames are automatically bundled into a single `.zip` file for convenient download.
- **Wide Format Support:** Works with common web video formats (`.mp4`, `.mov`, `.webm`, `.avi`, `.mkv`).
- **Responsive Design:** Looks and works great on both desktop and mobile devices.

## 🛠️ Technology Stack

- **HTML5:** For the core structure.
- **CSS3:** For modern styling, gradients, and a responsive layout.
- **Vanilla JavaScript:** For all the logic, from UI interactions to frame processing.
- **JSZip:** A JavaScript library used to create the `.zip` file in the browser.

## 💻 How to Use (Locally)

1. Clone this repository:
   ```bash
   git clone https://github.com/marodriguezd/Movie-Frame-Grabber.git