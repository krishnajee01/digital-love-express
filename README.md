# 💗 Love Proposal — Setup & Deploy Guide

## ✨ Quick Start

### 1. Add Your Music Link
Open `index.html` and find this line (~line 215):
```html
<a href="YOUR_MUSIC_LINK_HERE" target="_blank">
```
Replace `YOUR_MUSIC_LINK_HERE` with your song (Spotify, YouTube, etc.)

---

### 2. Add Your Photos
Photos are added **live in the browser** — just tap any photo frame when you open the site!
- 5 photo slots: 4 individual + 1 wide "couple" frame
- Accepts any image from your phone/computer
- Tap → pick from gallery → done ✨

If you want to **pre-embed** photos before sharing, replace the `src=""` of each `<img>` tag:
```html
<img id="img1" src="YOUR_PHOTO_URL_HERE" alt="Photo 1"/>
```
Then remove the `display:none` from that img and add class `has-photo` to its parent div.

---

### 3. Personalise the Text
- **Her name** — search for "My dearest," in the letter scene and add her name
- **Story bubbles** — Scene 2 has the bear/bunny dialogue, edit freely
- **Proposal question** — Scene 5 has "Will you be mine?" — change it!

---

## 🚀 Deploy on Vercel

### Option A — Drag & Drop (Easiest)
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **Add New → Project**
3. Drag the folder containing `index.html` + `vercel.json`
4. Click **Deploy** → you get a live link in ~30 seconds!

### Option B — Vercel CLI
```bash
npm i -g vercel
cd love-proposal/
vercel
```
Follow prompts → get your live URL 🎉

---

## 🎨 Colour Customisation
All colours are CSS variables at the top of `index.html`:
```css
--rose:      #FF6B9D;   /* main pink */
--blush:     #FFB6C8;   /* soft pink */
--lavender:  #D4A8E8;   /* purple */
--lilac:     #C9B1FF;   /* light purple */
```

## 📱 Mobile Notes
- Fully responsive, tested down to 360px wide
- Touch sparkles: tap anywhere for ✨ effects
- Scroll-reveal animations on all sections

---

Made with 💗 — go get your person! 🐻🐰
