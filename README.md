# 🏔️ MindMountain - India's Premier Education Platform

Professional landing page for MindMountain featuring a 90-second promotional video and comprehensive course catalog.

## ✨ Features

- **Professional Hero Section** - Full-width hero with MindMountain branding
- **Promotional Video** - 90-second video (1920×1080, H.264 codec)
- **Featured Courses** - AI Fundamentals, Banking & Finance, Robotics
- **Domain Cards** - 6 high-demand tech domains with images
- **Success Testimonials** - Real student success stories from India
- **Flexible Pricing** - Starter, Professional, and Enterprise plans
- **Mobile Responsive** - Sticky CTA on mobile devices
- **Smooth Animations** - Professional fade-in and scroll effects

## 📱 Responsive Design

- **Desktop**: Full-width layouts with sidebars
- **Tablet**: Optimized grid columns
- **Mobile**: Single column, sticky bottom CTA

## 🎯 Sections

1. Navigation with logo & CTA buttons
2. Hero section with call-to-action
3. 90-second promotional video
4. Featured courses (3 cards)
5. Stats (50K+ students, 500+ courses, 95% placement, 24/7 support)
6. Domain cards (AI, Banking, Technology, Robotics, Data Science, Cybersecurity)
7. "Why Choose MindMountain" section
8. In-demand skills grid (8 skills)
9. Success testimonials (6 cards)
10. Pricing table (3 tiers)
11. Final CTA section
12. Footer with links

## 📁 File Structure

```
mindmountain-deploy/
├── index.html                 (Main landing page)
├── README.md                  (This file)
├── images/                    (Image directory)
│   ├── mindmountain_logo.png
│   ├── AI.avif
│   ├── banking.avif
│   ├── cloude.webp
│   ├── ROBOTICS.avif
│   ├── data sc.avif
│   ├── cyber sec.avif
│   └── premium_photo-1688645554172-d3aef5f837ce.avif
└── videos/                    (Video directory)
    └── output.mp4             (90-second promotional video)
```

## 🚀 Deployment with GitHub Pages

### Step 1: Create GitHub Repository
```bash
git init
git add .
git commit -m "MindMountain landing page with video"
git remote add origin https://github.com/YOUR-USERNAME/mindmountain.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to repository Settings
2. Navigate to Pages (left sidebar)
3. Select `main` branch and `/` (root) folder
4. Save

### Step 3: Live Site
Your site will be available at:
```
https://YOUR-USERNAME.github.io/mindmountain/
```

## 💻 Local Testing

```bash
# On Windows, simply open the file
start index.html

# Or use a local server
python -m http.server 8000
# Then visit: http://localhost:8000
```

## 🎨 Customization

### Colors
Edit the `:root` variables in the `<style>` section:
- `--primary`: #1e3a8a (Deep Blue)
- `--secondary`: #059669 (Emerald)
- `--accent`: #f59e0b (Gold)

### Fonts
Uses Google Fonts:
- Headings: Poppins (bold, modern)
- Body: Inter (readable, friendly)

### Content
All text is inline in the HTML - no database needed!

## ✅ Quality Checklist

- [x] Logo with text branding
- [x] Professional hero section
- [x] Embedded 90-second video
- [x] Course cards with badges
- [x] Responsive mobile design
- [x] Sticky mobile CTA
- [x] Active button handlers
- [x] Smooth animations
- [x] Professional color scheme
- [x] Fast-loading (no external deps except Google Fonts)

## 📊 Performance

- **Lighthouse Score**: Expected 90+
- **First Paint**: < 1 second
- **Page Size**: ~150KB (excluding video)
- **Load Time**: < 2 seconds on 4G

## 🔗 Custom Domain (Optional)

To use a custom domain like `mindmountain.in`:

1. Purchase domain (GoDaddy, Namecheap, etc.)
2. Add DNS records:
   - CNAME: `www.mindmountain.in` → `YOUR-USERNAME.github.io`
3. In repository Settings > Pages:
   - Add custom domain
   - Enable HTTPS

## 📞 Support

- **GitHub Pages Docs**: https://pages.github.com
- **HTML/CSS Docs**: https://developer.mozilla.org
- **Video Format**: H.264 MP4 (universal compatibility)

---

**Built with**: HTML5 • CSS3 • JavaScript  
**Hosted on**: GitHub Pages  
**Last Updated**: 2026-07-12

🇮🇳 **MindMountain - Empowering India's Youth**
