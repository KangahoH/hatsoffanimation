# Hats Off Animation — Website

> "...the drawing folk. From Kampala to the world one frame at a time."

## 🚀 Deployment to Hostinger

This is a **single-file static website** — no build step, no Node.js, no dependencies to install.

### Deploy via Hostinger hPanel

1. Log into your **Hostinger hPanel**
2. Navigate to **File Manager** under your hosting account
3. Open the `public_html` folder
4. Upload `index.html` directly into `public_html`
5. Your site is live ✅

### Deploy via FTP

1. Use FileZilla or any FTP client
2. Connect with your Hostinger FTP credentials (found in hPanel → FTP Accounts)
3. Upload `index.html` to the `/public_html/` directory
4. Done ✅

### Deploy via GitHub + Hostinger Git

1. Push this repo to GitHub
2. In hPanel, go to **Git** section
3. Connect your GitHub repo and set the branch to `main`
4. Set the deployment path to `public_html`
5. Click Deploy ✅

---

## 📁 File Structure

```
hatsoff-website/
├── index.html       ← The entire website (self-contained)
└── README.md        ← This file
```

## 🎨 Brand Colors

| Name         | Hex       |
|-------------|-----------|
| Oxford Blue  | `#051223` |
| Deep Saffron | `#FCAF45` |
| Off-White    | `#F5F5F5` |
| Pure Black   | `#000000` |

## 📌 Font

**Montserrat** — loaded via Google Fonts CDN (no install needed)

## ✏️ To Customise

- **Contact form**: Replace the `handleSubmit()` function with a real backend integration (Formspree, Netlify Forms, EmailJS, etc.)
- **Logo**: Replace the inline SVG with your actual logo image
- **Social links**: Update the LinkedIn and YouTube URLs in the footer
- **Analytics**: Add your Google Analytics / Umami script before `</body>`

## 📞 Contact Details (already in site)

- Phone: +256 200 911 416
- WhatsApp: +256 792 871 657
- Email: info@hatsoffanimation.com
- Address: Plot 363, Dr. Lukwiya Road, Balintuma A, Nakawa Division, Kampala, Uganda

---

© Hats Off Animation Limited. All rights reserved.
