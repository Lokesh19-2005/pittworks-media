# Pittworks Media — Image Assets Guide

This document explains the placeholder images and dimensions required for each slot on the site.

## Service Section Images (`service-*.webp`)

These appear in the alternating service rows. Replace with actual project/service imagery.

| File | Slot | Aspect Ratio | Recommended Size |
|------|------|-------------|-----------------|
| `service-brand-strategy.webp` | Brand Strategy | 4:3 | 800×600 px |
| `service-video-production.webp` | Video Production | 4:3 | 800×600 px |
| `service-commercial-shoots.webp` | Commercial Shoots | 4:3 | 800×600 px |
| `service-restaurant-branding.webp` | Restaurant Branding | 4:3 | 800×600 px |
| `service-social-media.webp` | Social Media Marketing | 4:3 | 800×600 px |
| `service-graphic-design.webp` | Graphic & Packaging Design | 4:3 | 800×600 px |
| `service-campaigns.webp` | Creative Campaigns & Corporate Films | 4:3 | 800×600 px |
| `service-digital-marketing.webp` | Digital & Performance Marketing | 4:3 | 800×600 px |

## Portfolio Images (`portfolio-*.webp`)

These appear in the portfolio grid cards as hero images.

| File | Slot | Aspect Ratio | Recommended Size |
|------|------|-------------|-----------------|
| `portfolio-forge.webp` | Forge & Co — Rebrand Launch | 16:10 | 960×600 px |
| `portfolio-haven.webp` | Haven Hotels — Seasonal Campaign | 16:10 | 960×600 px |
| `portfolio-meridian.webp` | Meridian — Full Identity System | 16:10 | 960×600 px |
| `portfolio-studio-nine.webp` | Studio Nine — Content Engine | 16:10 | 960×600 px |

## Instagram Grid (`insta-*.webp`)

Square tiles for the Instagram feed section.

| File | Slot | Aspect Ratio | Recommended Size |
|------|------|-------------|-----------------|
| `insta-1.webp` | Feed tile 1 | 1:1 | 600×600 px |
| `insta-2.webp` | Feed tile 2 | 1:1 | 600×600 px |
| `insta-3.webp` | Feed tile 3 | 1:1 | 600×600 px |
| `insta-4.webp` | Feed tile 4 | 1:1 | 600×600 px |
| `insta-5.webp` | Feed tile 5 | 1:1 | 600×600 px |
| `insta-6.webp` | Feed tile 6 | 1:1 | 600×600 px |

## Social Share / OG Image (`og-image.jpg`)

Used for Open Graph / Twitter Card previews when the site is shared on social media.

| File | Purpose | Aspect Ratio | Recommended Size |
|------|---------|-------------|-----------------|
| `og-image.jpg` | Social share preview | ~1.91:1 | 1200×630 px |

## Favicon Set (`/assets/icons/`)

| File | Purpose | Size |
|------|---------|------|
| `favicon-16x16.png` | Browser tab icon (small) | 16×16 px |
| `favicon-32x32.png` | Browser tab icon (standard) | 32×32 px |
| `apple-touch-icon.png` | iOS home screen icon | 180×180 px |

## Logo (`logo.webp` + `logo.jpeg` fallback)

| File | Purpose | Notes |
|------|---------|-------|
| `logo.webp` | Optimized logo (primary) | Compressed WebP version |
| `logo.jpeg` | Fallback for older browsers | Keep original as fallback |

---

## How to Replace

1. Prepare images at the recommended sizes above.
2. Export as WebP (quality 80–85) for web performance. Keep a JPEG fallback if needed.
3. Name them exactly as listed above and drop into `/assets/images/`.
4. The HTML uses `<picture>` with WebP source and JPEG/PNG fallback where applicable.
5. Update `alt` attributes in `index.html` if the image content differs from placeholders.
