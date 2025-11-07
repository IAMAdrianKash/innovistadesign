# Innovista Design Studio

A stunning, conversion-focused web agency website built with Astro.js following modern web design principles.

## Design Principles

This website is built following proven web design principles that prioritize conversions and user experience:

### Visual Hierarchy
- Uses strategic sizing and positioning instead of outdated F-pattern layouts
- Most important elements (H1s, CTAs) are biggest and boldest
- Progressive reduction in prominence for less critical elements

### High-Contrast CTAs
- All buttons have solid backgrounds (no ghost buttons)
- Primary CTAs use high-contrast accent colors
- Clear visual distinction between different button variants

### Color Strategy (60-30-10 Rule)
- **60% Dominant Colors**: Blacks, whites, grays for neutral foundation
- **30% Brand Colors**: Indigo and purple for professional, creative feel
- **10% Accent Colors**: Amber for attention-grabbing CTAs

### Typography Hierarchy
- **H1s**: Largest, most prominent - describes the entire page
- **H2s**: Subheadings that divide content and guide attention
- **Paragraph text**: Simple, readable fonts that prioritize clarity

### Conversion-Focused Design
- **Clarity**: Crystal clear who we are and what users should do
- **Scannability**: Designed for how users actually read (scanning, not reading)
- **Motivation**: Speaks to emotional drivers and user needs
- **Reduced Friction**: Easy to find information and take action

## Tech Stack

- **Astro.js**: Modern static site generator
- **TypeScript**: Type-safe development
- **CSS**: Custom properties and modern CSS features
- **No JavaScript Framework**: Blazing fast, zero-JS by default

## Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Button.astro       # High-contrast button component
│   │   ├── Card.astro          # Reusable card component
│   │   └── Section.astro       # Section wrapper with variants
│   ├── layouts/
│   │   └── BaseLayout.astro    # Main layout with header/footer
│   ├── pages/
│   │   └── index.astro         # Homepage
│   └── styles/
│       └── global.css          # Global styles and CSS variables
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Features

### Components

#### Button Component
- Multiple variants: primary, secondary, accent
- Multiple sizes: sm, md, lg
- Solid backgrounds with high contrast
- Smooth hover effects and transitions
- Accessible focus states

#### Section Component
- Background options: white, gray, dark, gradient
- Responsive padding options
- Consistent container width

#### Card Component
- Flexible content areas
- Icon support with gradient backgrounds
- Hover effects for interactive cards

### Sections

1. **Hero Section**
   - Strong visual hierarchy with large H1
   - Clear value proposition
   - Multiple CTAs with different priorities
   - Social proof elements
   - Animated shapes for visual interest

2. **Value Proposition**
   - Statistics with impressive numbers
   - Social proof and credibility markers

3. **Services Section**
   - Grid layout with service cards
   - Clear descriptions and CTAs
   - Icons for quick visual recognition

4. **Portfolio/Work Section**
   - Featured projects with results
   - Visual previews with gradient placeholders
   - Tags for categorization

5. **Process Section**
   - Step-by-step methodology
   - Numbered steps for clarity
   - Builds trust and reduces uncertainty

6. **Contact/CTA Section**
   - High-contrast gradient background
   - Prominent CTA button
   - Multiple contact options

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Development

The project uses Astro's file-based routing. Pages are created in `src/pages/`.

### Commands

| Command           | Action                                       |
|:-----------------|:---------------------------------------------|
| `npm run dev`    | Starts local dev server at `localhost:4321`  |
| `npm run build`  | Build your production site to `./dist/`      |
| `npm run preview`| Preview your build locally, before deploying |

## Customization

### Colors

Edit CSS variables in `src/styles/global.css`:

```css
:root {
  --color-brand-primary: #6366f1;
  --color-brand-secondary: #8b5cf6;
  --color-accent-primary: #f59e0b;
  /* ... */
}
```

### Typography

Fonts can be customized in the global.css file:

```css
:root {
  --font-display: your-font-here;
  --font-body: your-font-here;
}
```

### Content

Edit the content in `src/pages/index.astro` to customize:
- Headlines and copy
- Service offerings
- Portfolio items
- Process steps

## Performance

- Zero JavaScript by default
- Optimized CSS with modern features
- Fast page loads
- SEO-friendly HTML structure
- Accessible markup

## Accessibility

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Focus visible states
- High contrast ratios for readability

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for all screen sizes
- Graceful degradation for older browsers

## License

MIT License - feel free to use this for your own projects!

## Credits

Built with:
- [Astro](https://astro.build/)
- Design principles from modern conversion-focused web design

---

**Innovista Design Studio** - Design That Converts
