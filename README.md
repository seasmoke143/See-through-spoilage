# 🧅 See-Through Spoilage (STS)

A camera-based web app that helps buyers check whether an onion looks fresh or rotten before buying.

## Features
- User manual page that guides the scanning process
- Live camera scan or photo upload
- Image analysis for dark patches, soft-rot browning and mold-like areas
- Clear result: Looks Fresh, Check Carefully or Likely Rotten, with a risk bar
- Runs fully in the browser, no installation needed

## How to run
1. Download `sts-onion-scanner.html`
2. Open it in Chrome, Edge or Brave

If the camera is blocked, run this in the same folder and open the link:

    python3 -m http.server
    http://localhost:8000/sts-onion-scanner.html

## Tech stack
HTML, CSS, JavaScript (optional TensorFlow.js / Teachable Machine model)

## Roadmap
- Train a deep learning model on fresh vs. rotten onion images
- Add NIR (infrared) and depth imaging to detect spoilage under the skin
- Mobile app version

## Disclaimer
This is an early prototype and a visual aid only. If an onion smells bad, feels soft or slimy, or shows mold, don't buy or eat it.
