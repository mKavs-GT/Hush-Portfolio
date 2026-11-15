# HUSH — Luxury Avant-Garde Bags

A luxury e-commerce web showcase featuring avant-garde aesthetics, interactive product showcases, infinite marquee reviews, and responsive design.

## 🚀 Deploy to Vercel

This repository is pre-configured and 100% deployment ready for [Vercel](https://vercel.com).

### Option 1: Import via Vercel Dashboard (Recommended)
1. Go to [vercel.com/new](https://vercel.com/new).
2. Select and import your GitHub repository (`Hush-Portfolio`).
3. Leave all default build settings intact (Framework Preset: **Other**, Root Directory: `./`).
4. Click **Deploy**. Your site will be live in seconds.

### Option 2: Deploy via Vercel CLI
```bash
# Install Vercel CLI if not already installed
npm i -g vercel

# Deploy to production
vercel --prod
```

## 📁 Project Structure

```
├── index.html        # Home & collections landing page
├── product.html      # Interactive product detail page
├── style.css         # Styling, layout, and responsive media queries
├── images/           # High-resolution bags & futuristic model assets
├── vercel.json       # Clean URLs, caching headers & security rules
└── .gitignore        # Ignores temp files, logs & dependencies
```

## ✨ Features
- **Clean URLs**: Clean routing with `vercel.json` (`/product` -> `product.html`).
- **Optimized Caching**: Long-term asset caching headers configured for images.
- **Interactive Gallery & Swatches**: Thumbnail selector, quantity counter, and color swatches on `product.html`.
- **Carousel Controls**: Smooth sliding product marquee and new arrivals carousel.
- **Responsive Layout**: Designed for mobile, tablet, and desktop viewports.
