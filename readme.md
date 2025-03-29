# 🔍 QR Code Generator

A simple web app that generates QR codes from any text or URL. Built with vanilla HTML, CSS, and JavaScript - no libraries or frameworks needed.


## Features
- Instantly converts text/URLs to QR codes
- Clean, responsive design that works on mobile
- Visual feedback during generation
- Auto-resizes for different screens
- One-click copy functionality (just scan the QR code)

## How to Use
1. Type or paste any text/URL in the input box
2. Click "Generate QR Code"
3. Scan the QR code with your phone's camera
4. To generate another, just enter new text and click again

## Files Breakdown
- `index.html` - The basic page structure
- `style.css` - All styling with smooth animations
- `app.js` - The logic that generates QR codes

## Why I Built This
I wanted a simple QR generator that:
- Doesn't track user data
- Works offline after first load
- Has zero dependencies
- Is lightweight (under 20KB total)

## Customization Tips
Want to make it your own? Try:
- Changing colors in the CSS variables
- Adding a download button for the QR code
- Implementing dark mode
- Adding size options for the QR code

## Quick Setup (2 ways)

1. **One-click Download**  
   - Click "Code" button (green) above → "Download ZIP"
   - Extract and open `index.html` in any browser

2. **Git Clone** *(for developers)*  
   ```bash
   git clone https://github.com/your-username/qr-code-generator.git
   cd qr-code-generator
   open index.html

## Found a Bug?
Feel free to open an issue or just fork and fix it yourself - this is meant to be hacked on!

---

*Note: Uses the free API from [QRServer](https://goqr.me/api/) for actual QR generation.*


