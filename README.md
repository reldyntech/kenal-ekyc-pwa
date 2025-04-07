# eKYC PWA

A simple Progressive Web App (PWA) for MyKad and Passport verification using the Kenal.io API.

## 🔥 Features

- Toggle between **MyKad** and **Passport** verification
- Clean, mobile-friendly UI using Bootstrap 5
- Branding with primary color `#ee0979`
- Fully installable PWA with offline support
- Auto-redirect to verification flow from API response

## 📦 Folder Structure

```
.
├── index.html
├── manifest.json
├── service-worker.js
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## 🚀 Live Demo

> You can host this PWA using GitHub Pages, Netlify, Vercel, or any static hosting platform.

### ✅ Deploy to GitHub Pages

1. Push this project to a **public GitHub repository**.
2. Go to **Settings > Pages**.
3. Under "Source", choose `main` branch and `/ (root)` folder.
4. Save and wait for the deployment URL.

> Example: `https://your-username.github.io/ekyc-pwa`

---

## 📱 Install as App

1. Open the app in a mobile browser (e.g. Chrome).
2. Tap **“Add to Home Screen”**.
3. Launch it like a native app!

---

## 🔐 API Key

> Replace the sample API key with your own in `index.html`:

```js
'x-api-key': 'YOUR_API_KEY_HERE'
```

---

## 🛡️ License

This project is open source and available under the [MIT License](LICENSE).
