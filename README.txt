Rent Manager v14.2

Project structure:
- frontend/index.html
- backend/server.js
- package.json

Features: device-supported face/fingerprint authentication prompt where available, animated scanning-style lock screen, browser-level lock after login when configured, brightness slider and fingerprint icon setting.

Run: npm install, ensure local MongoDB is running, npm start, then open http://localhost:3000.

No .env file is required; MongoDB URI is configured directly in backend/server.js.
Important: device/browser biometric support varies. The animation is visual only; real verification is performed by the browser/device. This app-level lock is not a replacement for server-side authorization. Test on localhost or HTTPS.
