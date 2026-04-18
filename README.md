# Muhammad Hamza — Portfolio Website

## 🚀 How to Deploy on Vercel

### Method 1: Drag & Drop (Easiest)
1. Go to https://vercel.com → Sign up / Log in
2. Click "Add New Project" → "Deploy from template" → or just drag your folder
3. Drop the entire portfolio folder onto Vercel's deploy page
4. Done! Your site is live in ~60 seconds.

### Method 2: Via GitHub (Recommended for auto-updates)
1. Create a new repo on GitHub (e.g., `hamza-portfolio`)
2. Upload these files: `index.html`, `vercel.json`, your photo, your CV PDF
3. Go to https://vercel.com → "Add New Project"
4. Import your GitHub repo → Click "Deploy"
5. Every push to GitHub auto-deploys!

---

## 📁 File Structure
```
portfolio/
├── index.html          ← Main portfolio file
├── vercel.json         ← Vercel config
├── your-photo.jpg      ← ADD YOUR PHOTO HERE
└── Muhammad-Hamza-CV.pdf ← ADD YOUR CV HERE
```

---

## ✏️ What to Customize

### 1. Add Your Photo
- Add your photo as `your-photo.jpg` in the same folder
- In `index.html`, find the `hero-photo-placeholder` div and replace with:
```html
<img src="your-photo.jpg" alt="Muhammad Hamza" />
```

### 2. Add Your CV
- Add your CV as `Muhammad-Hamza-CV.pdf` in the same folder
- The download button is already linked to it!

### 3. Update Certificates
- Find the `#certificates` section in `index.html`
- Update the cert names, issuers, and add links if available

### 4. Custom Domain (Optional)
- In Vercel dashboard → Your Project → Settings → Domains
- Add your custom domain (e.g., `hamza.dev`)

---

## 🎨 Features
- ✅ Animated particle network background
- ✅ Custom cursor with magnetic effect
- ✅ Glitch effect on name
- ✅ Typewriter role animation
- ✅ Scroll-reveal animations
- ✅ Animated counter stats
- ✅ Floating skill badges
- ✅ All links clickable (GitHub, LinkedIn, Docker Hub, Email, Phone)
- ✅ CV download button
- ✅ Fully responsive (mobile-friendly)
- ✅ Dark cyberpunk aesthetic

---

Built with HTML, CSS & Vanilla JavaScript — No frameworks needed!
