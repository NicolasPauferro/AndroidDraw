<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" alt="AndroidDraw" srcset="https://apolloeducacao.com/androiddraw.png" />
    <img alt="AndroidDraw" src="https://apolloeducacao.com/androiddraw.png" />
  </picture>
</div>

<div align="center">
  <h2>
    AndroidDraw: An open source virtual hand-drawn style whiteboard optimized for Android </br>
  <br />
  </h2>
</div>

<br />

## 📱 About AndroidDraw

**AndroidDraw** is a specialized fork of the popular [Excalidraw](https://excalidraw.com/) project, engineered specifically to deliver a native, highly-optimized whiteboard experience on Android devices. 

By leveraging **Capacitor**, AndroidDraw packages the powerful Excalidraw web engine into a seamless native Android application, bringing tailored UI refinements and advanced hardware integrations that make mobile drawing and diagramming feel natural and fluid.

---

## ✨ Android-Specific Features

AndroidDraw introduces several key enhancements over the upstream project to ensure a premium mobile experience:

- 📱 **Mobile-Optimized UI Layout:** The interface has been rigorously refined for smaller touch screens.
  - **Togglable Settings Palette:** Tool settings (like color and stroke width) are hidden behind a sleek top-right toggle button, maximizing your canvas real estate and keeping the UI clean.
  - **Distraction-Free Canvas:** Unnecessary hint texts and floating tutorial elements have been removed for a truly immersive drawing session.
  - **Z-Index & Layout Fixes:** Guaranteed proper rendering of toolbars and menus without overlapping components, even on compact smartphone displays.
- 🚀 **Native Android Wrapper:** Built with Capacitor (`@capacitor/android`), providing a reliable, full-screen, installable Android APK experience out of the box.

---

## 🎨 Core Excalidraw Features Inherited

Because AndroidDraw is built on the shoulders of giants, it retains all the beloved features of the original Excalidraw engine:

- 💯&nbsp;Free & open-source.
- 🎨&nbsp;Infinite, canvas-based whiteboard.
- ✍️&nbsp;Hand-drawn like, sketchy style.
- 🌓&nbsp;Dark mode support.
- 📷&nbsp;Image insertion and manipulation.
- 😀&nbsp;Shape libraries support.
- 🌐&nbsp;Localization (i18n) support.
- 🖼️&nbsp;Export to PNG, SVG & clipboard.
- 💾&nbsp;Open format - export drawings as an `.excalidraw` json file.
- ⚒️&nbsp;Wide range of tools - rectangle, circle, diamond, arrow, line, free-draw, text...
- ➡️&nbsp;Arrow-binding & labeled arrows.
- 🔙&nbsp;Undo / Redo capabilities.
- 🔍&nbsp;Smooth zoom and panning.

---
## Installing

If you just wanna to install the apk file to use it in your device, you can just download it by cliking on "releases" on the right side of the page

When you click in "AndroidDraw 1.0" it will open a new tab, download the apk file and ran it on your mobile device.


## 🚀 Building for Android

To build and run AndroidDraw on your local Android device or emulator:

1. **Install Dependencies:**
   ```bash
   npm install
   ```
2. **Build the Web Application:**
   ```bash
   npm run build
   ```
3. **Sync with Capacitor:**
   ```bash
   npx cap sync android
   ```
4. **Compile and Run onto Device/Emulator:**
   ```bash
   npx cap run android
   ```
   *(Ensure you have Android Studio installed and an Android device connected with USB Debugging enabled, or a virtual device running).*

---

## 📄 License & Credits

AndroidDraw is built upon [Excalidraw](https://github.com/excalidraw/excalidraw), which is released under the **MIT license**. 

For upstream contributions or standard web features, please refer to the original Excalidraw repository. For Android-specific issues or S-Pen integrations, feel free to open an issue or PR here.
