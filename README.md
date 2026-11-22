# Hot Days Filter Lab

Live browser test bench for the app's beauty filters (skin smoothing, Hot Days color, even tone, glow, face reshape, makeup).
Single static page: `index.html` (WebGL2 + MediaPipe Face Landmarker). No build step.

- Open on a phone over HTTPS, tap **Start camera**.
- Tweak sliders, then **Adjust → Copy JSON** to export settings for the native (React Native) filter.

Deploys automatically to Vercel on every push to `main`.
