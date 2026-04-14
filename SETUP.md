# AffiliateAI Studio — Setup & Hosting Guide

## Files in this folder
```
affiliateai-studio/
├── index.html      ← Main app (open this in any browser)
├── manifest.json   ← PWA install config
├── icon.svg        ← App icon
└── SETUP.md        ← This guide
```

---

## Option 1: Run Locally (Instant, No Setup)
Just double-click `index.html` to open in Chrome or Edge.
> ⚠️ Service worker and install feature require HTTPS — use options below for full PWA.

---

## Option 2: Host Free on GitHub Pages (Recommended)
Full PWA with Android/iOS install support.

1. Create a free account at **github.com**
2. Click **New Repository** → name it `affiliateai-studio` → Public → Create
3. Upload all 3 files (index.html, manifest.json, icon.svg)
4. Go to **Settings → Pages → Source: main branch → Save**
5. Your app is live at: `https://YOUR-USERNAME.github.io/affiliateai-studio`

---

## Option 3: Host Free on Netlify (Drag & Drop)
1. Go to **netlify.com** → Sign up free
2. Drag the entire `affiliateai-studio` folder onto the Netlify dashboard
3. Done — you get a free HTTPS URL like `https://app-name.netlify.app`

---

## Option 4: Host Free on Vercel
1. **vercel.com** → Sign up with GitHub
2. Import your GitHub repo → Deploy
3. Get a free HTTPS URL automatically

---

## Install as Android App
1. Open your hosted URL in **Chrome for Android**
2. Tap the **⋮ menu** → "Add to Home Screen" or "Install App"
3. App appears on your home screen — works offline!

## Install as iOS App
1. Open your hosted URL in **Safari on iPhone/iPad**
2. Tap the **Share button ⬆️** at the bottom
3. Tap **"Add to Home Screen"**
4. Tap **"Add"** — app icon appears on your home screen

---

## Affiliate Platforms Supported
| Platform | Country | API |
|----------|---------|-----|
| Amazon India | 🇮🇳 | PA API (needs 3 sales) |
| Amazon US | 🇺🇸 | PA API (needs 3 sales) |
| Flipkart | 🇮🇳 | Affiliate Portal |
| JioMart | 🇮🇳 | Manual links |
| Myntra | 🇮🇳 | Via EarnKaro / Admitad |
| Nykaa | 🇮🇳 | Nykaa Affiliate Portal |
| Meesho | 🇮🇳 | Meesho Affiliate |
| Snapdeal | 🇮🇳 | Via CJ Affiliate |
| Tata CLiQ | 🇮🇳 | Tata CLiQ Affiliate |

---

## Social Platforms
| Platform | Method | What's Automated |
|----------|--------|-----------------|
| Facebook Reels | Direct API | ✅ Auto-posts video + caption |
| YouTube Shorts | Direct API | ✅ Auto-uploads with title & tags |
| Instagram Reels | Download + paste | ✅ Video download + caption copied |

---

## Getting Your Credentials

### Amazon PA API
- Go to affiliate-program.amazon.in (India) or affiliate-program.amazon.com (US)
- Dashboard → Tools → Product Advertising API
- ⚠️ Requires 3 qualifying sales first

### Flipkart Affiliate
- affiliate.flipkart.com → Sign up → My Account → Tracking ID

### Meta (Facebook + Instagram)
- business.facebook.com → Settings → Page Access Token
- Generate a Long-Lived Token (doesn't expire)

### YouTube
- developers.google.com/oauthplayground
- Select "YouTube Data API v3" → Authorize → Exchange for Access Token
- ⚠️ Tokens expire in 1 hour — refresh when needed

---

## Legal Requirements (Important!)
- Always include **#ad** and **#affiliate** in every post
- Add disclosure in your bio: "This page contains affiliate links"
- Amazon requires you to state "As an Amazon Associate I earn from qualifying purchases"
- For India: Follow ASA/ASCI guidelines on influencer disclosures
