# Portfolio Redesign – Claude Code Instructions

## Project

Static portfolio site hosted on GitHub Pages.
Live URL: https://harvey-ignacio.github.io/portfolio
Repo: harvey-ignacio/portfolio

## Goal

Full visual redesign using Tailwind CSS with a dark theme.
Keep ALL existing content, copy, project data, images, and
testimonials exactly as-is. Only change design and layout.

## Tech Stack

- Plain HTML + Tailwind CSS via CDN (no build tools)
- Vanilla JS only
- Google Fonts: Plus Jakarta Sans (headings) + Inter (body)

## Design System

- Base background: #0F0F1A (dark navy/black)
- Card/surface: #1A1A2E
- Primary accent: #5B7CF6 (blue)
- Secondary accent: #6EE58A (green)
- Highlight/CTA: #F5C842 (yellow)
- Muted text: #94A3B8
- Body text: #F1F5F9
- Borders: #2A2A3E

## Typography

- Headings: Plus Jakarta Sans, bold, tight letter spacing
- Body: Inter, regular
- Load both from Google Fonts

## Libraries (all via CDN)

- Tailwind CSS: https://cdn.tailwindcss.com
- AOS: https://unpkg.com/aos@2.3.1/dist/aos.css and aos.js
- GSAP: https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js
- Particles.js: https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
- Google Fonts: Plus Jakarta Sans + Inter

## Hero Section

- Full viewport height
- Background: #0F0F1A dark base
- Particles.js background: dark canvas with floating connected dots
  and geometric shapes in #5B7CF6 blue and #6EE58A green
  low opacity (0.4–0.6), slow movement, connected lines in blue
- Particles config: 80 particles, move speed 1.5, line distance 150,
  size 3–5px, on hover: grab effect, on click: push particles
- GSAP entrance animation on page load:
  - Available badge: fade in first (0.3s delay)
  - Headline: slide up + fade in (0.5s delay)
  - Subtext: fade in (0.7s delay)
  - CTA buttons: slide up + fade in (0.9s delay)
  - Stats bar: fade in last (1.1s delay)
- Primary CTA: #5B7CF6 blue with white text
- Secondary CTA: transparent with #5B7CF6 border and white text

## AOS Scroll Animations

- Add data-aos attributes to every section and card
- About section: data-aos="fade-up"
- Service cards: data-aos="fade-up" data-aos-delay="100/200/300"
  (staggered per card)
- Project cards: data-aos="fade-up" with staggered delays
- Experience timeline items: data-aos="fade-right"
- Testimonial cards: data-aos="zoom-in"
- Skills groups: data-aos="fade-up" with staggered delays
- Stats bar items: data-aos="fade-up" with staggered delays
- AOS settings: duration 700, easing ease-in-out, once true

## Featured Work Section

- Background: #1A1A2E
- Full-width prominent section after hero
- Label: "Featured Work" in #6EE58A green
- Feature Boosted Commerce as hero project
- Show: 7+ storefronts, 30–50% Lighthouse improvements,
  custom features (cart drawers, variant selectors), US DTC brands
- Tags: Liquid, Shopify CLI, Replo, Tailwind CSS, JavaScript, Figma → Code
- Embed Tianyao Ma testimonial inside this section
- Use #5B7CF6 blue accent border or split-layout

## Projects Section

- Background: #0F0F1A
- 3-column grid desktop, 1-column mobile
- Cards: #1A1A2E background, #2A2A3E border
- Project image, name, URL, description, tech tags as pills
- Tag pills: #2A2A3E background, #5B7CF6 text
- Hover: subtle blue glow or lift effect
- Fix all wrong alt attributes on WellPath, Aberlite, Bamboo, Charis
- Keep all 11 projects with original image paths (images/\*.jpg)

## Tech Stack Section

- Background: #0F0F1A with subtle grid or dot pattern
- Left side: category label in #6EE58A green, bold heading in white,
  description in muted text
- Right side: pill grid grouped by category
- Category labels: #5B7CF6 blue, uppercase, tracking-wide
- Pill badges: #1A1A2E background, #2A2A3E border, #F1F5F9 text
- Groups:
  Shopify: Liquid, Shopify CLI, Shopify APIs & Webhooks, Replo, Theme Architecture
  Frontend: HTML, CSS, JavaScript, jQuery, Tailwind CSS, Bootstrap
  WordPress: WordPress, WooCommerce, Elementor, Divi, Beaver Builder, PHP
  Full-Stack: Angular, NestJS, MongoDB
  Tools: Git, GitHub, Figma, GitHub Copilot, ChatGPT, Claude

## Nav

- Background: #0F0F1A with subtle border bottom #2A2A3E
- Logo: white text
- Links: #94A3B8 muted, hover #F1F5F9 white
- CTA button: #5B7CF6 blue
- Mobile: hamburger menu

## About Section

- Background: #0F0F1A
- Profile card: #1A1A2E with #2A2A3E border
- Available badge: #6EE58A green

## Services Section

- Background: #1A1A2E
- Cards: #0F0F1A background, #2A2A3E border
- Icon accent: #5B7CF6 blue or #6EE58A green
- Hover: #5B7CF6 border glow

## Testimonials

- Background: #0F0F1A
- Cards: #1A1A2E, stars in #F5C842 yellow
- Quote text: #F1F5F9

## Contact

- Background: #1A1A2E
- Form inputs: #0F0F1A background, #2A2A3E border
- Submit button: #5B7CF6 blue
- Focus state: #5B7CF6 border glow

## Footer

- Background: #0F0F1A
- Border top: #2A2A3E
- Text: #94A3B8 muted

## General Rules

- Keep ALL existing copy exactly as written
- Fully mobile responsive at all breakpoints
- Smooth scroll between sections
- No npm, no build step — CDN only
- Subtle transitions and hover effects throughout
- Particles.js canvas must be position absolute, z-index 0
- All hero content must be position relative, z-index 1
