# Bellagio Fountains Screensaver

[![Status: Live](https://img.shields.io/badge/Status-Live-success)](https://us41242.github.io/pages/)

A dark screensaver featuring a continuous night loop of the Bellagio Fountains in Las Vegas.

Designed primarily for Android TV boxes in hotel environments, this web-based screensaver displays the current date and time over a subtle, high-quality video background.

## Live Demo
[Click here to view the screensaver](https://us41242.github.io/pages/)

---

## Features

* **Seamless Loop**: High-quality night footage of the iconic Bellagio Fountains.
* **Dual Time Display**:
    * **Header**: Standard Date & Time displayed at the top.
    * **Ticker**: Large, scrolling Date & Time at the bottom for visibility from a distance.
* **Dark Mode**: Optimized for low-light environments (suitable for sleeping rooms).
* **Lightweight**: Built with a single HTML file containing all logic and styling.

---

## How to Use

### On Android TV
This project is designed to work with the **Dashboard Screen Saver** app (or any web-based screensaver app).

1.  Install **Dashboard Screen Saver** on your Android TV device.
2.  Open the settings and locate the option to set a **URL source**.
3.  Enter the following URL:
    ```
    [https://us41242.github.io/pages/](https://us41242.github.io/pages/)
    ```
4.  Set the inactivity timeout as desired.

### On Desktop / Browser
The [WebViewScreenSaver](https://github.com/liquidx/webviewscreensaver) works perfectly for use on a computer as well.
---

## File Structure

| File | Description |
| :--- | :--- |
| `index.html` | The core application. Contains the HTML structure, CSS for the dark overlay, and JavaScript for the real-time clock. |
| `video.mov` | The looped video file of the Bellagio fountains. |
| `black.png` | Used as a semi-transparent overlay to darken the video and improve text readability. |

---

## Customization

To use your own video:
1.  **Fork** this repository.
2.  Replace `video.mov` with your own video file (ensure it keeps the same name or update `index.html` to match).
3.  Commit your changes, and GitHub Pages will update automatically.

---

## License
This project is open source. Feel free to use it for your personal setup.
