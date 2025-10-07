# Oopi Website

A modern, Y2K-inspired website for the Oopi iOS app - transforming photos into beautiful artistic styles.

## 🎨 Design Features

- **Y2K Aesthetic**: Bold fonts, neon green accents (#39FF14), dark theme
- **Modern & Clean**: Beautiful UI with smooth animations
- **Fully Responsive**: Works perfectly on all devices
- **Fast Performance**: Static site built with Vite

## 🚀 Tech Stack

- **Vite**: Lightning-fast build tool and dev server
- **Vanilla JavaScript**: No framework overhead
- **CSS3**: Modern styling with animations
- **Netlify Ready**: Optimized for Netlify deployment

## 📁 Project Structure

```
oopi_web/
├── index.html          # Homepage
├── features.html       # Features page
├── gallery.html        # Gallery showcase
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── support.html        # Support & FAQ
├── style.css           # Main stylesheet
├── main.js            # JavaScript for interactions
├── package.json       # Dependencies
├── vite.config.js     # Vite configuration
└── netlify.toml       # Netlify configuration
```

## 🛠️ Setup & Development

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

## 🌐 Deployment to Netlify

### Option 1: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

### Option 2: Netlify Dashboard
1. Push your code to GitHub
2. Connect repository to Netlify
3. Build settings are already configured in `netlify.toml`
4. Deploy!

### Build Settings (already configured)
- **Build command**: `npm run build`
- **Publish directory**: `dist`

## 📝 Customization

### Colors
Edit CSS variables in `style.css`:
```css
:root {
  --neon-green: #39FF14;
  --dark-bg: #0a0a0a;
  --dark-purple: #1a0f2e;
}
```

### Content
- Replace placeholder images with real screenshots
- Update email addresses in Privacy and Support pages
- Add your App Store link in the "Download" buttons
- Update company/developer name in legal pages

### Fonts
Currently using:
- **Space Grotesk**: Headings (modern, geometric sans-serif)
- **Bebas Neue**: Buttons
- **Inter**: Body text

Change fonts by editing the Google Fonts import in `style.css`.

## 🎯 To-Do Before Launch

- [x] ~~Replace placeholder images with real app screenshots~~ ✅ Done! Using real images from Assets folder
- [ ] Add actual App Store download link
- [ ] Update support email address
- [ ] Complete company/developer information in legal pages
- [ ] Add favicon
- [ ] Test on multiple devices
- [ ] Set up analytics (optional)
- [ ] Test contact form functionality

## 🎨 Gallery Features

The gallery now features **real before/after images** with an interactive hover effect:
- **23 diverse styles** showcased in the gallery page
- **6 featured styles** on the homepage
- **Hover to reveal** - see the original photo by hovering over any transformed image
- Beautiful labels showing "AFTER" that change on hover
- Style names displayed on each image
- Smooth fade transitions between before/after states

## 📱 Pages Included

1. **Homepage** - Hero, features, gallery preview, how it works, CTA
2. **Features** - Detailed feature breakdown with categories
3. **Gallery** - Showcase of photo transformations by style
4. **Privacy Policy** - Comprehensive privacy policy
5. **Terms of Service** - Legal terms and conditions
6. **Support** - FAQ, contact form, help resources

## 🎨 Design Philosophy

The website embodies a modern Y2K aesthetic with:
- Dark backgrounds for visual impact
- Neon green (#39FF14) as the primary accent
- Bold, chunky typography
- Glowing effects and smooth animations
- Clean, uncluttered layouts
- Mobile-first responsive design

## 📄 License

All rights reserved © 2025 Oopi

---

Built with ❤️ for Oopi

