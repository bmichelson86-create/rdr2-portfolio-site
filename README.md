# 🤠 Red Dead Redemption 2 - Portfolio Showcase

An interactive, cinematic portfolio website inspired by Red Dead Redemption 2, featuring advanced animations, custom cursor effects, and a stunning mask reveal landing page.

![RDR2 Portfolio Banner](Hero-image.png)

## 🌟 Live Demo

**[View Live Site](https://YOUR-USERNAME.github.io/rdr2-portfolio-site/)**

## ✨ Features

### 🎭 Interactive Mask Reveal Landing Page
- Custom spotlight effect that follows your cursor
- Smooth clip-path animation revealing the hero image
- Click-to-zoom transition with video integration
- Custom cursor with visual feedback

### 🎬 Advanced Animations
- **GSAP ScrollTrigger** - Scroll-based animations throughout
- **Horizontal Scrolling** - Unique location showcase with parallax effects
- **Pin Sections** - Character reveals with layered image animations
- **Smooth Transitions** - Page-to-page navigation with video overlays

### 📱 Fully Responsive
- Mobile-optimized layouts for all 7 pages
- Touch-friendly navigation and interactions
- Adaptive video/image sizing
- Conditional animations (disabled on mobile for performance)

### 🎨 Pages Included
1. **Landing Page** - Interactive mask reveal with custom cursor
2. **Home** - Hero video with smooth image-to-video transition
3. **Characters** - Scroll-triggered character reveals with parallax
4. **Weapons** - Interactive weapon categories with video backgrounds
5. **Story** - Chapter cards with lightbox image viewer
6. **Gallery** - Video clips with text overlays
7. **About** - Game statistics and development info
8. **Locations** - Horizontal scroll gallery with location panels

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6+)** - Modern vanilla JS
- **GSAP 3.12.5** - Professional-grade animations
- **ScrollTrigger** - Scroll-based animation library

## 🎯 Key Technical Features

### Advanced CSS
- `clip-path` animations for mask reveal
- `object-fit` for responsive media
- CSS Grid & Flexbox layouts
- Custom cursor with `mix-blend-mode`
- Glassmorphism effects
- Smooth gradients and transitions

### JavaScript Highlights
- Custom cursor tracking with smooth easing
- Intersection Observer for scroll animations
- Video playback control and transitions
- Conditional rendering for mobile devices
- GSAP timeline orchestration

### Performance Optimizations
- Lazy loading for videos
- Conditional animations based on viewport
- Optimized scroll listeners
- Efficient DOM manipulation

## 📂 Project Structure

```
rdr2-portfolio-site/
├── index.html              # Landing page (mask reveal)
├── home.html               # Main homepage
├── characters.html         # Character showcase
├── weapons.html            # Weapons gallery
├── story.html              # Story chapters
├── gallery.html            # Video gallery
├── about.html              # About the game
├── locations.html          # Locations showcase
├── Hero-image.png          # Main hero image
├── home-video.mp4          # Hero video
├── camp1-6.png             # Chapter images
└── [weapon videos]         # Background videos
```

## 🚀 Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/rdr2-portfolio-site.git
   cd rdr2-portfolio-site
   ```

2. **Open with a local server**
   
   Using Python:
   ```bash
   python -m http.server 8000
   ```
   
   Using Node.js:
   ```bash
   npx serve
   ```
   
   Or use VS Code Live Server extension

3. **Visit in browser**
   ```
   http://localhost:8000
   ```

> **Note:** A local server is required for proper video playback and CORS policies.

## 🎨 Design Highlights

### Color Palette
- **Primary Red:** `#EA2424` - Bold, attention-grabbing
- **Gold Accent:** `#d4a574` - Western, vintage feel
- **Dark Background:** `#000000` - Dramatic contrast

### Typography
- **Chinese Rocks** - Display font for headers
- **Impact/Arial Black** - Fallback fonts
- Letter-spacing for Western aesthetic

### Visual Effects
- Smooth scroll animations
- Hover state transitions
- Video background overlays
- Custom cursor interactions
- Mask reveal spotlight

## 📸 Screenshots

### Landing Page
![Mask Reveal Landing](screenshots/landing.png)

### Home Page
![Hero Section](screenshots/home.png)

### Characters Page
![Character Showcase](screenshots/characters.png)

### Weapons Page
![Weapons Gallery](screenshots/weapons.png)

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (limited support)

## 📱 Mobile Support

Fully responsive design tested on:
- iPhone SE (375px)
- iPhone 12 Pro (390px)
- iPad (768px)
- Desktop (1920px+)

## 🔧 Future Enhancements

- [ ] Add preloader for assets
- [ ] Implement lazy loading for images
- [ ] Add sound effects on interactions
- [ ] Create admin panel for content updates
- [ ] Add analytics tracking
- [ ] Optimize video file sizes
- [ ] Add WebP image format support

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)
- Portfolio: [yourportfolio.com](https://yourportfolio.com)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Red Dead Redemption 2 by Rockstar Games (theme inspiration)
- GSAP by GreenSock (animation library)
- Unsplash (placeholder images for locations page)

---

⭐ **Star this repo if you found it helpful!**

Made with ❤️ and lots of ☕
