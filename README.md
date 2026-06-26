# IRONMODE - Home Fitness Landing Page

A production-ready, dark-themed landing page for a home fitness app. Built with React, Tailwind CSS, and Framer Motion.

**Live:** https://ironmode-landing.netlify.app/

## Tech Stack

- React 18
- Vite 5
- Tailwind CSS 3
- Framer Motion 11
- Lucide React (icons)

## Quick Start

### Prerequisites

- Node.js 18+ installed
- npm or yarn

### Setup

```bash
# Clone the repo
git clone https://github.com/your-username/ironmode-landing.git
cd ironmode-landing

# Install dependencies
npm install

# Start dev server
npm run dev
```

Open http://localhost:5173 in your browser.

### Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |

## Project Structure

```
ironmode-landing/
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── netlify.toml
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── index.css
    ├── hooks/
    │   └── useCountUp.js
    └── components/
        ├── Navbar.jsx
        ├── Hero.jsx
        ├── Stats.jsx
        ├── Features.jsx
        ├── Programs.jsx
        ├── Testimonials.jsx
        ├── Pricing.jsx
        ├── CTA.jsx
        └── Footer.jsx
```

## Sections

| Section | Description |
|---------|-------------|
| **Navbar** | Fixed top nav, transparent on load, border on scroll |
| **Hero** | Full-screen hero with animated SVG dumbbell, noise texture |
| **Stats** | Animated count-up numbers (12K+ members, 500+ workouts, etc.) |
| **Features** | Asymmetric grid with 3 feature cards + mini SVG chart |
| **Programs** | 3 program tiers (Beginner / Intermediate / Advanced) |
| **Testimonials** | Before/after transformation cards |
| **Pricing** | Free vs Pro comparison |
| **CTA** | Final call-to-action with watermark background |
| **Footer** | Logo, nav links, copyright |

## Customization

### Colors

Edit `tailwind.config.js` to change the color palette:

```js
colors: {
  bg: { primary: '#080808', card: '#0F0F0F', elevated: '#1A1A1A' },
  accent: { DEFAULT: '#FF3D00', dim: '#CC3100', muted: 'rgba(255,61,0,0.12)' },
}
```

### Content

All text content is directly in the component files. Edit the relevant component to change copy:

- `src/components/Programs.jsx` - Program names, features, durations
- `src/components/Testimonials.jsx` - Quotes, names, before/after stats
- `src/components/Pricing.jsx` - Prices, features, plan names
- `src/components/Features.jsx` - Feature descriptions
- `src/components/Hero.jsx` - Headlines, body text, mini stats

### Fonts

Google Fonts are loaded in `index.html`. Default fonts:
- **Barlow Condensed** (400, 700, 900) - Headlines
- **Inter** (400, 500, 600) - Body text

## Deployment

### Netlify

The `netlify.toml` is pre-configured. Just connect your GitHub repo to Netlify.

### Manual

```bash
npm run build
# Upload the dist/ folder to any static host
```

## License

MIT

---

Built with collaboration by [haideralio73](https://github.com/haideralio73) and [naumanshah1710-crypto](https://github.com/naumanshah1710-crypto)
