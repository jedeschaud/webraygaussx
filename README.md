# WebRaygaussX: Remote GPU 3D Viewer with Gaussian-based ray marching

This project is a **browser-based interactive 3D viewer** where the rendering is computed remotely on a **high-performance GPU server** (RTX 5090) using RayGaussX rendering, and the results are streamed back to the client in real time via **WebSockets**.

The browser provides an **interactive camera control system** (orbit, pan, zoom, reset) similar to Three.js `OrbitControls`, while the heavy rendering work happens on the remote machine.  

This allows for **photorealistic rendering** even on low-power client devices.
