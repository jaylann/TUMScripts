# 🎓 TUMScripts

A collection of satirical and entertaining Tampermonkey userscripts designed to enhance your TUM (Technische Universität München) browsing experience with humor and whimsy.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-Compatible-green.svg)](https://www.tampermonkey.net/)
[![TUM](https://img.shields.io/badge/TUM-Excellence-blue.svg)](https://www.tum.de/)

## 📋 Table of Contents

- [Overview](#overview)
- [Scripts](#scripts)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 🚀 Scripts

### 🏆 Excellence Reminder
**File:** `Excellence Reminder.js`

Periodically reminds you of TUM's excellence through randomly played audio clips and images. This script ensures you never forget about the institutional greatness surrounding you.

- **Target:** `*://*.tum.de/*`
- **Features:**
  - Random audio reminders at intervals
  - Dynamic image overlays featuring institutional imagery
  - Seamless integration with TUM websites
  - Customizable timing and content

### 📺 Attention Span Extender
**File:** `Attention Span Extender.js`

Uses "sophisticated psychological techniques" to keep your attention focused on TUM pages by embedding curated YouTube videos. Perfect for those moments when you need extra motivation to stay engaged.

- **Target:** `*://*.tum.de/*`
- **Features:**
  - Embedded YouTube videos with autoplay
  - Rotating video selection
  - Fixed positioning for optimal viewing
  - Session-based video progression

### 🏛️ TUM Logo Replacer
**File:** `TUM Logo Replacer.js`

Automatically replaces instances of the word "tum" and "Technische Universität München" with the official TUM logo SVG across all websites you visit.

- **Target:** `*://*/*` (all websites)
- **Features:**
  - Real-time text replacement
  - Scalable SVG logo integration
  - Responsive sizing based on text font size
  - Universal website compatibility

## 📦 Installation

### Prerequisites
- [Tampermonkey](https://www.tampermonkey.net/) browser extension
- A web browser (Chrome, Firefox, Safari, Edge)

### Steps

1. **Install Tampermonkey**
   - Visit [tampermonkey.net](https://www.tampermonkey.net/)
   - Download and install the extension for your browser

2. **Install Scripts**
   - Click on the Tampermonkey extension icon
   - Select "Create a new script"
   - Copy and paste the content from any of the `.js` files in this repository
   - Save the script (Ctrl+S)
   - Repeat for each script you want to install

3. **Alternative Installation**
   - Download the desired `.js` file(s) from this repository
   - Drag and drop the file into your browser
   - Tampermonkey should automatically detect and offer to install the script

## 🎯 Usage

Once installed, the scripts will automatically activate based on their target URLs:

- **Excellence Reminder** and **Attention Span Extender**: Activate when visiting any `*.tum.de` website
- **TUM Logo Replacer**: Activates on all websites

### Configuration

Scripts can be configured through the Tampermonkey dashboard:
1. Click the Tampermonkey icon
2. Select "Dashboard"
3. Find the script you want to configure
4. Click the script name to edit settings

### Disabling Scripts

To temporarily disable a script:
1. Open Tampermonkey dashboard
2. Toggle the script off using the switch next to its name

## 🤝 Contributing

Contributions are welcome! Whether you want to add new scripts, improve existing ones, or enhance documentation:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-script`)
3. Commit your changes (`git commit -m 'Add amazing new script'`)
4. Push to the branch (`git push origin feature/amazing-script`)
5. Open a Pull Request

### Script Guidelines

- Follow Tampermonkey userscript format
- Include proper metadata headers
- Use MIT license
- Test thoroughly before submitting
- Document any new dependencies or requirements

## ⚠️ Disclaimer

These scripts are created for entertainment and educational purposes. Use responsibly and be mindful of:
- University IT policies
- Website terms of service
- Academic integrity guidelines
- Bandwidth and performance considerations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<p align="center">
  Made with ❤️ by <a href="https://lanfermann.dev">Justin Lanfermann</a>
</p>
