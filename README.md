# Pocket Menu - Browser Extension

**Pocket Menu** is a lightweight, cross-browser extension designed to let users quickly search and check if specific items exist on [SwigMenus](https://swigmenus.com). 

## Features

- ⚡ **Instant Search:** Real-time offline search capabilities to quickly verify menu item availability.
- 🎯 **Smart Matching:** Displays exact matches and provides up to 5 partial match suggestions if an exact match isn't found.
- 🔗 **Direct Integration:** Quick links to seamlessly jump directly to SwigMenus.
- 🌐 **Cross-Browser Support:** Available for Google Chrome, Mozilla Firefox, and Microsoft Edge, natively built using Manifest V3.
- 🔒 **Privacy-Focused:** Performs search locally using bundled data. No tracking, no telemetry.

## Directory Structure

- `/chrome`: Unpacked Chrome extension (Manifest V3)
- `/edge`: Unpacked Edge extension (Manifest V3)
- `/firefox`: Unpacked Firefox extension (Manifest V3 with Firefox specific properties)
- `/cyber-cafe`: "Cyber Café" Premium Browser Theme project files

## Installation (Developer Mode)

### Google Chrome
1. Open Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** using the toggle in the top right corner.
3. Click **Load unpacked**.
4. Select the `/chrome` folder from this repository.

### Microsoft Edge
1. Open Edge and navigate to `edge://extensions/`
2. Enable **Developer mode** in the left sidebar or bottom-left corner.
3. Click **Load unpacked**.
4. Select the `/edge` folder from this repository.

### Mozilla Firefox
1. Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on...**
3. Select the `manifest.json` file inside the `/firefox` folder from this repository.

## Usage

1. Click on the **Pocket Menu** icon in your browser's toolbar to open the popup.
2. Start typing the name of the menu item in the search bar.
3. Press `Enter` or click **Search** to see if the item exists.
4. If there's an exact match, it will be confirmed immediately. If not, potential partial matches will be displayed.
5. Click **View on SwigMenus** to visit the website.

## Tech Stack
- HTML5
- Vanilla CSS
- Vanilla JavaScript
- Manifest V3 (MV3)
