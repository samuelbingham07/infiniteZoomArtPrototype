Infinite Zoom Shader Prototype

This is a tiny WebGL prototype that renders a continuous Mandelbrot-style zoom in a fragment shader.

Files:
- `index.html` — single-file prototype. Open in a browser (served from a local web server) to view.

How to run (macOS / zsh):

Run a local static server from the project root and open http://localhost:8000 in a browser:

```bash
cd /Users/samuelbingham07/Desktop/infiniteZoomArtPrototype
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

Notes:
- Click the canvas to pause/resume the animation.
- Tweak `iTime` speed or palette in the fragment shader inside `index.html` to change the zoom speed and colors.
- For a seamless, endlessly looping zoom consider switching to a periodic zoom function or designing the pan/zoom to return to start after N seconds.