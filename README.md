# NCO2 - Negative Carbon Solutions

A modern, glassmorphism-styled website for NCO2 featuring an interactive reforestation calculator.

![NCO2 Preview](https://img.shields.io/badge/NCO2-Negative%20Carbon%20Solutions-152F45?style=for-the-badge&labelColor=e6990b)

## 🌳 Features

- **Interactive Reforestation Calculator** - Estimate CO₂ offset by number of trees or area (km²)
- **Glassmorphism 2.0 Design** - Modern frosted glass aesthetic with animated backgrounds
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- **Embedded Video** - YouTube integration for "Where Technology Meets Nature"
- **Smooth Animations** - Scroll-triggered animations and micro-interactions

## 🎨 Brand Colors

| Color | Hex Code | Usage |
|-------|----------|-------|
| NCO2 Blue | `#152F45` | Primary background, dark tones |
| NCO2 Orange | `#e6990b` | Accent color, CTAs, highlights |
| NCO2 Gray | `#999999` | Secondary text, muted elements |
| White | `#ffffff` | Primary text, glass borders |

## 🧮 Calculator Logic

The reforestation calculator uses science-based estimates:

- **Trees to CO₂**: `(number of trees × 22kg) / 1000 = tonnes CO₂/year`
- **Area to CO₂**: `km² × 400 trees × 22kg / 1000 = tonnes CO₂/year`

Based on:
- Average tree CO₂ absorption: **22kg per year** (USDA estimate)
- Average tree density: **~400 trees per km²** (mixed forest)

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `index.html` in your browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

### Option 3: Deploy to GitHub Pages
1. Push this repo to GitHub
2. Go to Settings → Pages
3. Select "Deploy from a branch" → `main` → `/ (root)`
4. Your site will be live at `https://yourusername.github.io/nco2-website/`

## 📁 Project Structure

```
nco2-website/
├── index.html      # Main website file (all-in-one HTML/CSS/JS)
├── README.md       # This file
├── LICENSE         # MIT License
└── .gitignore      # Git ignore rules
```

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** - No dependencies
- **Google Fonts** - Plus Jakarta Sans

## 📱 Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📄 License

MIT License - feel free to use this for your own projects.

## 🔗 Links

- [NCO2 Website](https://ncotwo.com)
- [YouTube: Where Technology Meets Nature](https://www.youtube.com/watch?v=qStpetnz75Y)

---

Built with 💚 for a carbon-negative future.
