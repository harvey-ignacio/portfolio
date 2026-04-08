# Portfolio Redesign – Claude Code Instructions

## Project

Static portfolio site hosted on GitHub Pages.
Live URL: https://harvey-ignacio.github.io/portfolio
Repo: harvey-ignacio/portfolio

## Goal

Full visual redesign using Tailwind CSS. Keep ALL existing content,
copy, project data, images, and testimonials exactly as-is.
Only change the design, layout, and markup structure.

## Tech Stack

- Plain HTML + Tailwind CSS via CDN (no build tools, keep it simple for GitHub Pages)
- Vanilla JS only
- Google Fonts: Plus Jakarta Sans (headings) + Inter (body)

## Design System

- Base background: #F9F7F4 (warm off-white)
- Card/surface: #FFFFFF
- Primary accent: #4F46E5 (indigo)
- Muted text: #64748B
- Dark text: #0F172A
- Border: #E2E8F0

## Typography

- Headings: Plus Jakarta Sans, bold, tight letter spacing
- Body: Inter, regular
- Load both from Google Fonts

## Hero Section

- Full viewport height
- Animated background: subtle floating geometric shapes (triangles,
  hexagons, or circles) using pure CSS keyframe animations only
- Shapes should be low opacity (0.04–0.08), indigo or slate toned
- NO canvas, NO JS animation libraries
- Hero text layered above the animation with z-index
- Include: name, title, tagline, two CTA buttons (See My Work / Get In Touch)
- Stats bar below hero text: 6+ Years, 17+ Projects, 11+ Stores, 100% Remote

## Featured Project Section (NEW - add between hero and projects grid)

- Full-width prominent card or section
- Headline: "Featured Work"
- Project: Boosted Commerce Shopify Storefronts (2023–2026)
- Show: 7+ storefronts maintained, 30–50% Lighthouse score improvements,
  custom features built (cart drawers, variant selectors), US DTC brands
- Tags: Liquid, Shopify CLI, Replo, Tailwind CSS, Figma → Code, JavaScript
- Testimonial from Tianyao Ma embedded in this section
- Visually distinct from the regular project grid — use an accent border,
  larger layout, or split card treatment

## Projects Section

- Rename to "Selected Work"
- Masonry or 3-column grid on desktop, 1-column on mobile
- Each card: project image, name, URL, short description, tech tags
- Hover: subtle lift shadow effect
- Keep all 11 existing projects with their current descriptions and images

## Skills Section

- Group by category with clear labels:
  - Shopify: Liquid, Shopify Theme Architecture, Shopify CLI, Shopify APIs & Webhooks, Replo
  - Frontend: HTML, CSS, JavaScript, jQuery, Tailwind CSS, Bootstrap
  - WordPress: Elementor, Divi, Beaver Builder, WooCommerce, PHP
  - Full-Stack: Angular, NestJS, MongoDB
  - Tools: Git, GitHub, Figma, GitHub Copilot, ChatGPT, Claude
- Use pill/badge style tags, grouped under category labels

## Experience Section

- Keep all 3 roles (Boosted Commerce, Strongwill IT, NOW Outsourcing)
- Timeline style layout

## Testimonials

- Keep all 3 testimonials
- Card style with star rating, quote, name, title

## Mobile

- Fully responsive at all breakpoints
- Mobile nav: hamburger menu
- Hero animation should be toned down on mobile (fewer shapes)

## Constraints

- Do NOT remove or rewrite any existing copy
- Do NOT invent or add any skills or projects not already listed
- No dark mode, no dark backgrounds anywhere
- Keep all image paths as-is (portfolio/images/\*)
- No npm, no build step — CDN only
- Fast loading — inline only what's necessary
