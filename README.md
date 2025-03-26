# AR Model Viewer

This is a web application that uses Hiro AR to display 3D models in augmented reality. When you scan the Hiro marker with your smartphone's camera, it will display a 3D model in AR.

## Setup

1. Clone this repository
2. Make sure your 3D model is in the correct location: `Modelos 3d/Modelo1/modelo1_green.glb`
3. Deploy to GitHub Pages for HTTPS support

## Usage

1. Open the deployed URL on your smartphone
2. Allow camera access when prompted
3. Point your camera at the Hiro marker
4. The 3D model will appear on top of the marker

## Requirements

- Modern smartphone with camera
- Web browser with WebXR support
- HTTPS connection (provided by GitHub Pages)
- Hiro marker (can be printed or displayed on screen)

## Development

To test locally:
1. Install a local server (e.g., `python -m http.server 8000`)
2. Open `http://localhost:8000` in your browser
3. Note: AR features require HTTPS, so local testing will be limited 