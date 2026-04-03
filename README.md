# Civil At Hand – World-Class Civil Engineering Website

> A premium, production-ready civil engineering services website. Zero dependencies. Deploy in 60 seconds.

---

## 🚀 Live Preview
Open `index.html` in any browser — works instantly, no build step required.

---

## ✅ All Features Included

| Feature | Details |
|---|---|
| 🌐 Hero Section | Animated tagline, stats counter, live project tracker visual |
| 🏗️ 8 Service Pages | AutoCAD, Structural, Estimation, Planning, Surveying, 3D, Water Tank, STP |
| 📝 Work Request System | Full form with file upload, validation, and success confirmation |
| 👤 Auth UI | Sign In / Sign Up with simulated dashboard |
| 📊 Project Dashboard | Status tracking for active, in-review, and completed requests |
| 💬 Live Chat Widget | Quick replies, custom chat bot responses |
| 🟢 WhatsApp Button | Floating button linking to WhatsApp |
| 📁 Portfolio | 6 projects with category filter (All/Structural/Water/Planning) |
| ⭐ Testimonials | 3 client reviews with 5-star ratings |
| 📚 Knowledge Hub | 6 full-length blog articles about civil engineering |
| 📞 Contact Page | Map embed, contact info, quick message form |
| 🌙 Dark/Light Mode | Persistent theme preference |
| 📱 Fully Responsive | Mobile-first, works on all screen sizes |
| 🎬 Animations | Scroll reveal, counters, hover effects, loading screen |
| 🔍 SEO Optimized | Meta tags, semantic HTML, structured content |

---

## 🗂️ Project Structure

```
civil-at-hand/
└── index.html      ← Complete website (single file, zero dependencies)
```

---

## ⚡ Deployment Options

### Option 1: Netlify Drop (30 seconds, recommended)
1. Visit [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `civil-at-hand` folder onto the page
3. Live immediately at a `.netlify.app` URL

### Option 2: GitHub Pages
1. Create new repo on GitHub
2. Upload `index.html`
3. Settings → Pages → Deploy from `main` branch

### Option 3: Vercel
```bash
npx vercel
```

### Option 4: Local Preview
```bash
# Just open index.html in browser, OR:
npx serve .
```

---

## 🎨 Customization

### Business Details — Search & Replace in index.html:
- `Civil At Hand` → Your company name
- `+91 98765 43210` → Your phone
- `info@civilathand.com` → Your email
- `42 Engineering Hub, Sector 5, Mumbai` → Your address
- `919876543210` → Your WhatsApp number (in wa.me links)

### Brand Colors (CSS variables at top of `<style>`):
```css
--accent: #1a4fd6;   /* Main blue */
--gold: #c49a3c;     /* Accent gold */
```

### Connect Real Form Backend (Formspree — free):
In the `submitRequest()` function, add:
```javascript
await fetch('https://formspree.io/f/YOUR_ID', {
  method: 'POST',
  headers: {'Content-Type': 'application/json'},
  body: JSON.stringify({name, phone, email, service, desc})
});
```

---

## 🔌 Recommended Free Integrations
- **Formspree** — form → email notifications
- **Crisp.chat** — real live chat
- **Google Maps Embed** — real location map
- **Cloudflare Pages** — free hosting with CDN

---

*© 2024 Civil At Hand. Production-ready. Deploy today.*
