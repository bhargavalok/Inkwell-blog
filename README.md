# Inkwell

A personal editorial blog built from scratch using pure HTML and CSS — no frameworks, no JavaScript, no shortcuts.
Inkwell is a long-form reading platform designed around a single conviction: that good writing deserves a space that feels as considered as the words themselves. The design is slow, intentional, and editorial — built to make you stop, read, and think.

## Why I Built This

Most blog templates are generic. They're built for speed, not for feel. I wanted to understand — at a deep, fundamental level — how a professional publication-quality website is actually constructed. Every layout decision, every hover state, every responsive breakpoint in this project was written by hand with a specific reason behind it.
This is not a template. This is a study in craft.

## What's Inside
- **Sticky glassmorphism navbar** with a CSS-only hamburger menu that animates to a ✕ — no JavaScript
- **Editorial hero section** with staggered CSS entry animations, a radial spotlight glow, and a dot-grid texture
- **Sticky sidebar layout** using `flexbox` + `position: sticky` with a precise `top` offset matching the navbar height
- **Featured article card** with image zoom on hover, blockquote styling, and a structured reading experience
- **Bento-style photo gallery** using CSS Grid with custom `nth-child` placement and hover caption reveals
- **Two-column contact form** with HTML5 validation states, focus glow rings, and SVG icon contact details
- **Newsletter strip + footer** with social icons, column links with slide animations, and a radial glow effect
- **Full responsive design** across 6 breakpoints: 1100px → 900px → 768px → 600px → 480px → 360px
- **Orientation queries** for both phone landscape and tablet landscape
- **`prefers-reduced-motion`** accessibility support
  
## Tech Stack

| Layer | Technology |
|---|---|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS (no frameworks) |
| Fonts | Google Fonts — Playfair Display, Lora, DM Sans |
| Responsive | CSS Media Queries + Orientation Queries |
| Animations | Pure CSS `@keyframes` |
| Interactivity | CSS-only (checkbox hack for hamburger) |

## CSS Concepts Applied

This project was built as a deliberate exercise in mastering real-world CSS patterns:
- `position: sticky` with bounded scroll containers
- `backdrop-filter: blur()` for glassmorphism
- CSS Grid with manual `nth-child` placement for editorial layouts
- `clamp()` for fluid, responsive typography without media queries
- Staggered `animation-delay` for cascade reveal effects
- `::after` pseudo-elements for hover indicators and overlay gradients
- CSS custom properties (`--accent`, `--bg-dark`) for a consistent design system
- The checkbox hack (`input:checked ~ sibling`) for JS-free interactivity
- `align-items: stretch` for synchronized column heights
- `overflow: hidden` + `transform: scale()` for performant image zoom

                                            ## Project Structure
## Pages / Sections

1. **Navbar** — Sticky, glassmorphism, with active state indicator
2. **Hero / Showcase** — Animated entry, stats row, scroll indicator
3. **Body Layout** — Sticky sidebar + divider + main content column
4. **Featured Article** — Full editorial reading experience
5. **Latest Stories** — 2-column card grid with hover effects
6. **Photo Gallery** — Editorial bento grid with caption reveals
7. **Get in Touch** — Two-column contact section with form validation
8. **Footer** — Newsletter strip, social icons, multi-column links

## Responsive Behaviour

| Breakpoint | Behaviour |
|---|---|
| `> 1100px` | Full desktop layout |
| `≤ 1100px` | Tighter gaps, compressed sections |
| `≤ 900px` | Getintouch stacks to single column, newsletter stacks |
| `≤ 768px` | Sidebar moves above content, gallery resets to 2-col |
| `≤ 600px` | Hamburger menu activates, CTAs stack, single-col categories |
| `≤ 480px` | Gallery goes single column, stat pipes hidden |
| `≤ 360px` | Fine-tuned for small Android devices |

## What I Learned

Building Inkwell taught me that professional web design isn't about using the right tools — it's about understanding *why* every line of CSS exists. The difference between `position: sticky` on a parent vs. a child. Why `align-items: stretch` is a prerequisite for sticky sidebars. Why `transition` belongs on the base state, not the hover. Why `transform` beats `top/left` for animations.
These aren't tricks. They're the fundamentals that separate websites that feel crafted from websites that just exist.

## Author

**Alok Bhargav**  
[LinkedIn](https://www.linkedin.com/in/alok-bhargav/) 
[Instagram](https://www.instagram.com/alok_bhargav_/) 
[Twitter/X](https://x.com/Alok_bhargav_)


