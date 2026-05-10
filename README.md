# Vijay Kumar — Portfolio

A dark-themed personal portfolio website. Pure HTML + CSS + JavaScript. No build step needed.

---

## 📁 File Structure

```
vijay-portfolio/
├── index.html      ← Main page (all sections)
├── style.css       ← All styles
├── script.js       ← Scroll animations, mobile menu, smooth scroll
├── resume.pdf      ← Add your actual CV here
└── README.md       ← This file
```

---

## 🚀 How to Run Locally

**Option 1 — Just open in browser:**
Double-click `index.html` — works instantly, no server needed.

**Option 2 — Live Server (recommended for development):**
1. Install VS Code
2. Install the "Live Server" extension
3. Right-click `index.html` → "Open with Live Server"

---

## ✏️ How to Customize

### Change your name / bio
Open `index.html` and search for "Vijay Kumar" — update any text directly.

### Add a real GitHub link
Find all `href="https://github.com/"` and replace with your actual GitHub URL.

### Add LinkedIn
Find `href="https://linkedin.com/"` and replace with your LinkedIn profile URL.

### Add your resume PDF
Drop your CV as `resume.pdf` in the same folder. The "Download CV" button links to it.

### Add a real profile photo
In `index.html`, find the `.avatar-initials` div and replace it with:
```html
<img src="photo.jpg" alt="Vijay Kumar" style="width:100%;height:100%;border-radius:50%;object-fit:cover;" />
```

### Add the Tic-Tac-Toe GitHub link
Find the project card with "Python Tic-Tac-Toe" and change:
```html
<a href="https://github.com/" target="_blank" class="plink">
```
to your actual GitHub repo URL.

---

## 🌐 Deploy for Free

### Vercel (Recommended — same as the portfolio you shared)
1. Go to https://vercel.com
2. Sign in with GitHub
3. Push your folder to a GitHub repo
4. Import the repo on Vercel → Deploy
5. You'll get a free `.vercel.app` domain

### Netlify (Alternative)
1. Go to https://netlify.com
2. Drag & drop your project folder onto the Netlify dashboard
3. Done — instant live URL

### GitHub Pages
1. Push to GitHub
2. Go to repo Settings → Pages → Source: main branch
3. Live at `yourusername.github.io/repo-name`

---

## 🎨 Theme Colors

All colors are in CSS variables at the top of `style.css`:
- `--accent` → Purple (#6c63ff) — change to any color you like
- `--bg` → Dark background
- `--text-muted` → Secondary text

To change the accent color (e.g., to teal), update:
```css
--accent: #00c9a7;
--accent-light: #5dcaa5;
--accent-glow: rgba(0,201,167,0.25);
```

---

## 📞 Contact Info in Portfolio

- Email: vijaykumar.soomro@gmail.com
- LUMS: 28100445@lums.edu.pk
- WhatsApp: +92 315 3418920

Update these in `index.html` if anything changes.
