# AR Drawing Projector

A simple **web-based augmented reality tool** that lets you overlay, move, scale, and filter an image using your device’s camera — perfect for tracing or projecting artwork.
Designed to work on mobile with pinch/drag gestures and minimal UI controls.

---

## Features

* 📷 **Live camera feed** (uses your device’s back camera)
* 🖼 **Upload an image overlay** and position it anywhere
* ✋ **Move** with drag
* 🔍 **Pinch to zoom** and rotate
* 🎚 **Adjust opacity** for better blending with the real world
* 🎨 **Optional grayscale filter** for higher contrast tracing
* 🔒 **Lock controls** to avoid accidental changes
* 📑 **Hide/Show UI** for a distraction-free view
* 📱 **Mobile-friendly** (touch gestures + responsive UI)
* ⏳ **Wake Lock API** to keep your screen awake while working

---

## Controls

| Control / Gesture          | Action                                          |
| -------------------------- | ----------------------------------------------- |
| **Upload Image** button    | Choose an image from your device to overlay     |
| **Opacity** slider         | Adjust overlay transparency (0–100%)            |
| **Filter** button          | Toggle grayscale + contrast filter              |
| **Lock** button            | Lock/unlock image position, scale, and rotation |
| **Hide UI** button         | Show/hide bottom controls panel                 |
| **Drag image**             | Move overlay position                           |
| **Pinch with two fingers** | Scale overlay size                              |
| **Twist with two fingers** | Rotate overlay                                  |
| **Reset** button           | Remove image and reset settings                 |

---

## How to Use

1. **Open** the app in a browser that supports `getUserMedia` and `wakeLock` (e.g., Chrome on Android).
2. **Grant camera permission** when prompted.
3. Tap **Upload Image** to choose your reference image.
4. **Move, zoom, rotate, and adjust opacity** as needed.
5. Use **Lock** to freeze the overlay or **Hide UI** for a full-screen view.

---

## Requirements

* A device with a camera (preferably with a rear-facing camera)
* A modern browser (Chrome, Edge, Firefox — Safari has partial support)
* HTTPS connection (required for camera access)
