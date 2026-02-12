# Travlla - Premium Travel Application (Refactored)

A modern, high-performance travel agency landing page built with a focus on premium aesthetics and robust architecture. This project has undergone a significant refactor to improve maintainability, visual consistency, and performance.

## 🚀 Key Dev Updates

### 1. Architectural Refactoring & Project Cleanup
- **Directory Restructuring**: Consolidated a cluttered root directory into a standard `assets/` architecture (`assets/images/`, `assets/css/`, `assets/js/`).
- **Orphan File Removal**: Cleaned up over 100+ redundant asset files, cache downloads, and legacy "CleanVersion" backups to ensure a lean production-ready codebase.
- **Path Integrity**: Standardized all asset referencing in `index.html` to maintain stability across different environments.

### 2. Carousel System Optimization (Owl Carousel & Swiper)
- **DOM Stability Fix**: Resolved critical issues where JavaScript-cloned elements were breaking the layout hierarchy.
- **Improved Rendering**: Removed pre-calculated inline styles from the source HTML, allowing the carousel engines to initialize cleanly without "jumps."
- **CSS Fallbacks**: Implemented Flexbox-based layout fallbacks to prevent vertical stacking during high latent loading or if JS is disabled.

### 3. Visual & Aesthetic Enhancements
- **Typography Restoration**: Properly integrated and mapped premium Google Fonts (`Afacad`, `Figtree`, `Kaushan Script`) for a consistent design system.
- **Brand Presentation**: Refined the 'Brands Trust Us' section with 80% opacity layering and micro-interactions for a more sophisticated look.
- **Global Assets**: Restored site FavIcons and Logos from fragmented temporary paths to persistent local storage.

## 🛠 Tech Stack & Integration
- **Core**: HTML5, CSS3, Vanilla JS
- **UI Framework**: Bootstrap 5 (Grid & Components)
- **Motion**: GSAP (GreenSock) for high-end cursor and parallax animations.
- **Engines**: 
  - `Owl Carousel 2` for standard sliders.
  - `Swiper.js` for premium touch-enabled tour carousels.
  - `Magnific Popup` for video and gallery lightbox integration.

## 📂 Project Structure
```text
.
├── index.html           # Main entry point (fully refactored)
└── assets/              # Consolidated production assets
    ├── css/             # Minified & custom stylesheets
    ├── images/          # Optimized production media
    └── js/              # Plugin initialization & custom logic
```

---
*Developed with a focus on premium user experience and clean code standards.*
