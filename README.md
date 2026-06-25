# La Tabernita de Manu

> Landing page for a traditional Castilian restaurant in Ciudad Rodrigo, Spain.

**Live demo → [iulian640.github.io/tabernita-manu](https://iulian640.github.io/tabernita-manu)**

---

## About the project

A real client project — La Tabernita de Manu is a seasonal restaurant in the Plaza Mayor of Ciudad Rodrigo (Salamanca) known for its traditional Castilian cuisine: carrilleras, entrecot and pulpo.

The client had a strong Google Maps presence but no website. The goal was to design a landing page that works as a conversion layer on top of that existing visibility — turning curious visitors into actual reservations.

## Process

**Brand discovery first.** Before writing a line of CSS, I ran a structured brand interview to understand the restaurant's positioning, audience, and competitive context. Key insight: the main competitor leans heavily into a traditional bullfighting aesthetic — La Tabernita needed to communicate the same Castilian heritage with a warmer, more refined tone.

**Design system second.** From the brand brief I built a set of design tokens: a warm dark palette (`#16100A` instead of cold black), Cormorant Garamond for display text, DM Sans for body, and a gold accent system rooted in the restaurant's character.

**Then the interface.** Single HTML file, no framework, no build step — intentional. The client needed something they could open on any device without setup.

## What's in it

- Floating pill nav with entrance animation
- Hero with Ken Burns effect and staggered content entrance
- Info strip, about section, menu cards, CTA and footer
- Scroll reveal via `IntersectionObserver`
- Card hover with gold glow and image zoom
- Fully responsive (mobile / tablet / desktop)
- `prefers-reduced-motion` support
- Real contact data: phone + Google Maps link

## Stack

| | |
|---|---|
| HTML / CSS / JS | Vanilla — no framework |
| Fonts | Cormorant Garamond + DM Sans (Google Fonts) |
| Hosting | GitHub Pages |

## Design decisions

- **Warm black `#16100A`** over cold black: a small shift that makes the whole page feel more inviting
- **DM Sans over Plus Jakarta Sans**: more humanist, less tech-product
- **Ornamental logo `——◆——`**: references the typographic tradition of Spanish restaurant menus without relying on imagery
- **3 menu cards instead of 4**: more space per dish communicates quality over quantity
- **CTA = phone call**: the restaurant takes reservations by phone, so every CTA points directly to `tel:`

---

Built as part of my fullstack bootcamp portfolio · June 2026
