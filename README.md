# Post-Coast-to-Coast

# Interactive Post-Game Animation

## Overview
This is an interactive web-based animation created using Adobe Animate CC and CreateJS. The application provides a dynamic, responsive visual experience designed to run in a web browser.

## Technology Stack
- **Development Tool**: Adobe Animate CC
- **Animation Framework**: CreateJS (version 1.0.0)
- **Rendering**: HTML5 Canvas
- **Responsive Design**: Adaptive scaling for various screen sizes

## Features
- Full-screen animation with responsive design
- Dynamic asset loading
- Cross-browser compatibility
- Sound integration

## Technical Specifications
- **Canvas Size**: 1920x1080 pixels
- **Background Color**: Dark gray (RGB: 47, 47, 47)
- **Frame Rate**: Dynamically set by the composition
- **Responsive**: Supports high-DPI screens

## Setup and Installation
1. Ensure you have the following files in the same directory:
   - `index.html`
   - `intAniPostGame.js`
   - Any additional asset files referenced in the manifest

2. No additional dependencies are required beyond the CreateJS library loaded from the CDN.

3. Open `index.html` in a modern web browser to run the animation.

## Key Components
- `init()`: Initializes the animation and sets up asset loading
- `handleComplete()`: Handles asset loading completion and starts the animation
- `playSound()`: Manages sound playback for the animation

## Browser Compatibility
Tested on:
- Chrome
- Firefox
- Safari
- Edge

## Deployment Notes
- The animation uses a CDN-hosted CreateJS library
- Ensure stable internet connection for library loading
- Recommended to host on a server that supports HTTPS

## Customization
To modify the animation:
1. Edit the source file in Adobe Animate CC
2. Export the updated JavaScript and assets
3. Replace the existing `intAniPostGame.js` file

## Troubleshooting
- If the animation doesn't load, check browser console for errors
- Verify all required JavaScript and asset files are present
- Ensure you're using a modern, updated web browser

## Credits
Created with Adobe Animate CC
Animation framework powered by CreateJS

## Contact
Nick Murawski
Nickmski30@gmail.com
