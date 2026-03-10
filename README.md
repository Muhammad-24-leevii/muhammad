# OM PORTFOLIO — Personal Portfolio Website

A professional, fully animated dark-theme portfolio landing page for **OLAAJE MUHAMMAD** — Freelance Web Developer & UI/UX Designer.

---

## 📁 Project Structure

```
portfolio/
├── index.html       # Main HTML structure
├── style.css        # All styles, animations & responsive design
└── README.md        # Project documentation
```

---

## 🚀 Features

### ✨ Visual Effects
- Custom glowing cursor with animated trailing ring
- Rotating orbit ring decorations in the hero section
- Floating radial background glows that breathe and move
- Subtle CSS grid line texture overlay
- Noise grain layer for depth and atmosphere

### 🔥 Buttons
- All buttons have a multi-layer `box-shadow` glow effect
- `translateY` lift + scale on hover
- Shimmer sweep animation on primary CTA buttons
- Outline buttons pulse green on hover
- All "Get It Now" buttons link to an external URL (see customization below)

### 🌀 Animations
- Glitch text effect on the hero name
- Infinite scrolling skills marquee
- Scroll-triggered reveal animations on every section
- Animated stat counters (3+, 50+, 100%)
- Staggered entrance delays on cards

### 📬 Contact Form
- Input fields glow green with a halo on focus
- Labels shift to accent color when active
- Contact links slide right with a colored left-border reveal on hover
- Submit button has shimmer sweep + loading → success state animation

### 📐 Layout & Sections
- Sticky frosted-glass navbar with animated underline links
- **Hero** — intro, tech tags, stat grid card
- **About** — bio, service feature cards
- **Skills** — infinite auto-scrolling marquee
- **Services** — 4 package cards (Portfolio Website, Portfolio Design, Blog Website, Blog Design)
- **Projects** — alternating layout with browser mockups
- **Contact** — contact links + full message form
- **Footer** — nav links, social platform links

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, animations, layout |
| Vanilla JavaScript | Cursor, scroll reveal, counters, form |
| Google Fonts | Syne (headings) + DM Sans (body) |

No frameworks, no build tools, no dependencies — runs entirely in the browser.

---

## ⚙️ How to Use

1. Download both `index.html` and `style.css`
2. Place them in the **same folder**
3. Open `index.html` in any modern browser

> ⚠️ Both files must be in the same directory for the CSS to load correctly.

---

## ✏️ Customization Guide

### Change Your Name
In `index.html`, find and replace `Lian` / `Leandro Bernol` with your own name.

### Update Contact Info
Find the contact links section and replace the placeholder URLs and email:
```html
<a href="mailto:your@email.com" class="contact-link">
<a href="https://fiverr.com/YOUR-USERNAME" class="contact-link">
<a href="https://upwork.com/YOUR-USERNAME" class="contact-link">
```

### "Get It Now" Buttons — Link to LinkedIn or Any URL
Find each Get It Now button in the Services section and replace `href`:
```html
<!-- Before -->
<a href="#contact" class="btn btn-primary">Get It Now</a>

<!-- After -->
<a href="https://www.linkedin.com/in/YOUR-USERNAME" target="_blank" class="btn btn-primary">Get It Now</a>
```
There are **4 buttons** (one per service card) — update each one.

### Change Accent Color
In `style.css`, find the `:root` block at the top and update:
```css
:root {
  --accent: #00ffb3;   /* Main green glow color */
  --accent2: #00e5ff;  /* Secondary cyan glow color */
}
```

### Add More Projects
Copy an existing `.project-item` block in `index.html` and update the number, title, description, and tech tags.

---

## 📱 Responsive Design

The layout adapts for screens under `900px`:
- Single column hero, about, and contact sections
- Stacked service package cards
- Stacked project items (no alternating direction)
- Adjusted font sizes and spacing

---

## 🌐 Deployment

This is a pure static site — you can host it anywhere:

- **GitHub Pages** — push to a repo and enable Pages in settings
- **Netlify** — drag and drop the folder into netlify.com/drop
- **Vercel** — connect your GitHub repo
- **Any web host** — upload both files via FTP/cPanel

---

## 📄 License

This project is personal portfolio work by **OLAAJE MUHAMMAD**. Feel free to use as a template with credit.
