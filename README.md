# PANGANA FLEET — Website README

> *Tulumikizane. Tipange. — We Connect. We Make It Happen.*

---

## Overview

This is the official website for **Pangana Fleet** — Zambia's specialist truck brokerage. The site serves as the primary digital presence for the business, communicating the brand, explaining the service and converting two distinct audiences into active leads:

1. **Logistics companies** that need extra trucks to fulfil contracts
2. **Truck owners** that have idle fleet capacity and want to monetise it

The site is built with the **[Astro](https://astro.build) framework** — a modern, performance-first static site builder that ships zero JavaScript by default, making it fast, lightweight and ideal for a content-driven landing page like this one. It is built on the Pangana Fleet brand identity — deep green, gold and off-white — with plain, direct language rooted in Zambian culture and the Nyanja name that carries the entire business model inside it.

---

## Business Context

**Business Name:** Pangana Fleet
**Type:** Truck Procurement & Brokerage Service
**Location:** Lusaka, Zambia
**Founded:** 2026
**Tagline:** *Tulumikizane. Tipange. — We Connect. We Make It Happen.*

Pangana Fleet is a professional middleman in Zambia's logistics sector. When a company needs more trucks than it owns, Pangana Fleet finds them, vets them and places them under a professionally managed brokerage arrangement. When a truck owner has idle vehicles earning nothing, Pangana Fleet connects them to vetted, paying clients and manages the relationship.

The business brokers **both sides** of every deal — not just one.

---

## Site Purpose

The website has four jobs:

- **Communicate** what Pangana Fleet is and why it exists
- **Convert** two audiences — companies needing trucks and owners with trucks — into leads via WhatsApp, phone or email
- **Build trust** through clear explanation of the process, compliance standards and Zambian identity
- **Establish credibility** as the only professional, structured, dual-side truck brokerage in Zambia

---

## Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | [Astro](https://astro.build) v4+ |
| **Styling** | CSS custom properties (no framework required) |
| **Scripting** | Vanilla JS — Astro ships zero JS by default |
| **Deployment** | Static output — compatible with Netlify, Vercel, Cloudflare Pages |
| **Package Manager** | npm or pnpm |

Astro was chosen for this project because:
- It produces **static HTML by default** — fast load times on Zambian mobile networks
- **Component-based architecture** keeps each page section clean and maintainable
- **Zero client-side JS** unless explicitly added — no bloat for a content-driven site
- Easy to extend with framework components (React, Svelte, Vue) if interactive features are added later

---

## Site Structure

```
/
├── public/
│   ├── favicon.ico             # PF monogram in gold on green
│   ├── hero-bg.jpg             # Hero background — Zambian trucks/logistics yard
│   └── logo.svg                # Pangana Fleet wordmark
├── src/
│   ├── components/
│   │   ├── Nav.astro           # Navigation bar with anchor links and CTA button
│   │   ├── Hero.astro          # Hero section — headline, tagline, dual CTA buttons
│   │   ├── SocialProof.astro   # Trust bar — four stat tiles
│   │   ├── Problem.astro       # The problem section — two-column audience pain points
│   │   ├── HowItWorks.astro    # Three-step process — Match, Vet, Manage
│   │   ├── Services.astro      # Two service cards — companies and truck owners
│   │   ├── WhyUs.astro         # Four differentiator cards
│   │   ├── About.astro         # Brand story and Zambian identity
│   │   ├── Industries.astro    # Five industry tiles
│   │   ├── Contact.astro       # CTA section with WhatsApp, phone and email
│   │   ├── Footer.astro        # Three-column footer with brand mantra
│   │   └── WhatsAppButton.astro # Floating WhatsApp CTA — fixed bottom right
│   ├── layouts/
│   │   └── BaseLayout.astro    # Root layout — head, meta, global styles, font
│   ├── pages/
│   │   └── index.astro         # Main landing page — imports all components
│   └── styles/
│       └── global.css          # CSS custom properties, reset, typography scale
├── astro.config.mjs            # Astro configuration
├── package.json                # Dependencies and scripts
├── README.md                   # This file
└── tsconfig.json               # TypeScript config (optional)
```

---

## Page Sections

The landing page is a single-page layout with nine sections. Each section has a named anchor for direct linking.

### `#hero`
**Purpose:** First impression and immediate audience routing.
**Content:** Brand name, Nyanja tagline, one-line descriptor, two CTA buttons — *I Need Trucks* and *I Have Trucks.*
**Design:** Full-width deep green background. Large bold white headline. Gold italic tagline. Two-button CTA in gold and white-outline.

---

### `#social-proof`
**Purpose:** Immediately establish trust and credibility below the fold.
**Content:** Four short stat tiles — Both Sides Served, 100% Vetted, 8-Step Process, Zambia-Built.
**Design:** Thin full-width bar in off-white with gold accent numbers.

---

### `#problem`
**Purpose:** Qualify both audiences by naming their pain directly.
**Content:** Two-column layout — one column for companies, one for truck owners — each describing their specific problem. Closing statement that positions Pangana Fleet as the solution.
**Design:** Off-white background. Two equal columns. Bold dark green headline. Body text in dark text colour.

---

### `#how-it-works`
**Purpose:** Explain the service simply in three steps.
**Content:** Match → Vet → Manage. Each step has a short headline and one-paragraph description. Closing line reinforces ongoing management vs one-time introduction.
**Design:** Deep green background. White text. Three horizontal cards with gold outlines and step numbers.

---

### `#services`
**Purpose:** Detail the two service offerings for each audience.
**Content:** Two service cards — Fleet Gap Brokerage (for companies) and Fleet Monetisation Brokerage (for truck owners). Each card includes a description, a list of who it serves and a CTA link. Full-width statement bar below.
**Design:** Off-white background. Two deep green cards with gold top borders. Gold CTA links.

---

### `#why-us`
**Purpose:** Differentiate Pangana Fleet from informal competitors.
**Content:** Four differentiators — Dual-Side Brokerage, Compliance First, We Stay In The Deal, Built For Zambia.
**Design:** Deep green background. Four white cards with gold left border accents.

---

### `#about`
**Purpose:** Build brand trust and communicate Zambian identity.
**Content:** Two short paragraphs explaining the business origin and ethos. Name meaning explanation. Nyanja tagline close. Optional 2x2 stat grid on the right side.
**Design:** Light green background left, white right — or full light green. Dark green headings. Gold italic for the Nyanja tagline.

---

### `#industries`
**Purpose:** Show breadth of market coverage.
**Content:** Five industry tiles — Fuel & Petroleum, Mining & Copperbelt, Agricultural Freight, Construction & Infrastructure, Cross-Border Logistics. One closing line about geographic expansion.
**Design:** Off-white background. Five deep green tiles with gold icons and white labels in a horizontal row.

---

### `#contact`
**Purpose:** Convert visitors into leads.
**Content:** Headline, subtext encouraging WhatsApp contact, two CTA buttons, phone number, email, WhatsApp number and Lusaka location.
**Design:** Full-width gold background. White text. Two white-background buttons with gold text.

---

### `footer`
**Purpose:** Close the page and provide navigation and contact reference.
**Content:** Three columns — brand identity, quick links, contact details. Bottom strip with copyright and brand mantra.
**Design:** Deep green background. White text. Gold brand name. Light green italic for the mantra.

---

## Brand & Design System

### Colour Palette

| Variable | Hex | Usage |
|---|---|---|
| `--deep-green` | `#1B4332` | Primary background, headers, dominant brand colour |
| `--gold` | `#C8841A` | Accents, CTA buttons, tagline, highlights |
| `--light-green` | `#D8F3DC` | Secondary backgrounds, table rows, breathing space |
| `--light-gold` | `#FDF3DC` | Quote boxes, warm highlight backgrounds |
| `--off-white` | `#FAFAF8` | Page content backgrounds, neutral sections |
| `--dark-text` | `#1A1A1A` | All body copy |
| `--white` | `#FFFFFF` | Text on dark backgrounds |

### Typography

| Element | Size | Weight | Colour |
|---|---|---|---|
| Brand name / Hero | 64–80px | Bold | White |
| Section headings | 32–40px | Bold | Deep green or white |
| Sub-headings | 22–24px | Bold | Deep green or gold |
| Body copy | 16–18px | Regular | Dark text |
| Labels / Tags | 12–14px | Bold, letter-spaced | Gold |
| Nyanja tagline | 18–22px | Italic | Gold |

**Primary font:** Arial or system sans-serif. Clean, universally available, lets colour and content lead.

### Design Principles

- **Dark anchors, light content** — green backgrounds for hero, section headers and footer. Off-white and light tones for content sections. Alternating rhythm throughout.
- **Gold signals importance** — every gold element draws attention to something that matters. Never decorative.
- **Structure over decoration** — no gratuitous visual elements. Every component serves the content.
- **Zambian warmth** — earthy palette, local language, real imagery. The site must look like it belongs here.

---

## CTA Logic

The site has two primary conversion paths that run in parallel throughout the page:

| Audience | CTA Text | Action |
|---|---|---|
| Companies needing trucks | *I Need Trucks* / *Get trucks now* | Opens WhatsApp chat or contact form |
| Truck owners with idle fleet | *I Have Trucks* / *Put your trucks to work* | Opens WhatsApp chat or contact form |

**WhatsApp is the primary contact channel.** A floating WhatsApp button in gold sits fixed in the bottom-right corner of every page view. All CTA buttons should link to a pre-filled WhatsApp message where possible, given that WhatsApp is the dominant B2B communication channel in Zambia.

---

## Content Tone Guidelines

All copy on the site follows the Pangana Fleet voice:

- **Confident** — state things directly, no hedging
- **Warm** — speak like a trusted Zambian business partner
- **Plain** — short sentences, strong verbs, no unnecessary jargon
- **Local** — reference Zambian realities, use the Nyanja tagline naturally
- **Accountable** — say what the business does and mean it

**Avoid:** corporate buzzwords, passive voice, vague promises, generic logistics language that could apply to any country.

---

## Mobile Considerations

- Two-column layouts collapse to single column below 768px
- Hero CTA buttons stack vertically on mobile
- Industry tiles wrap to a 2x3 grid on tablet, single column scroll on mobile
- Navigation collapses to a hamburger menu on mobile
- Floating WhatsApp button remains visible and accessible on all screen sizes
- Font sizes scale down proportionally — brand name remains prominent at all breakpoints

---

## Key Brand Copy

These lines are fixed and should not be altered without a brand review:

| Element | Copy |
|---|---|
| Brand name | PANGANA FLEET |
| Nyanja tagline | Tulumikizane. Tipange. |
| English tagline | We Connect. We Make It Happen. |
| Alt English tagline | Where Trucks Meet Their Match. |
| Hero descriptor | Zambia's specialist truck brokerage — connecting companies that need trucks with owners who have them. |
| Brand mantra | Solve local. Own logistics. Adapt culturally. Dominate uncontested. Brand proudly African. |
| Purpose statement | We exist so that no Zambian logistics company ever loses a contract because they did not have enough trucks — and no truck owner ever watches their fleet sit idle when there is money to be made. |

---

## Contact Information Placeholders

Replace the following placeholders before going live:

```
[PHONE_NUMBER]      → Pangana Fleet primary phone number
[EMAIL_ADDRESS]     → Pangana Fleet primary email address
[WHATSAPP_NUMBER]   → WhatsApp business number (include country code: +260...)
[PHYSICAL_ADDRESS]  → Lusaka office or registered address
```

---

## Getting Started

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

The dev server runs at `http://localhost:4321` by default.

---

## Notes for Developers

- All section IDs must match the navigation anchor links exactly
- The floating WhatsApp button should use the WhatsApp Business API link format: `https://wa.me/[WHATSAPP_NUMBER]?text=[PRE-FILLED_MESSAGE]`
- Pre-filled WhatsApp messages should differ per CTA button — companies get one message template, truck owners get another
- The two CTA buttons in the hero (`I Need Trucks` / `I Have Trucks`) are the most important conversion elements on the page — they must be immediately visible without scrolling on all screen sizes
- Images used must reflect real Zambian logistics environments — not generic stock photography
- Each page section lives in its own `.astro` component under `src/components/` — edit sections independently without touching the full page
- Global CSS custom properties (colour variables, type scale) are defined in `src/styles/global.css` — change a colour once and it updates everywhere
- Astro's static output means no server required for deployment — drop the `dist/` folder onto any static host
- If adding interactive components (e.g. a contact form), use Astro's `client:load` or `client:visible` directives to hydrate only what needs JS

---

## Deployment

The site builds to a static `dist/` folder via `npm run build`. It can be deployed to any static hosting provider:

| Provider | Deploy Command |
|---|---|
| Netlify | Connect repo — auto-deploys on push |
| Vercel | `vercel --prod` |
| Cloudflare Pages | Connect repo — auto-deploys on push |
| Manual | Upload `dist/` contents to any web server |

No server-side runtime required.

---

*Pangana Fleet — README v1.0 — Astro Framework — 2026 — Lusaka, Zambia*
*Confidential. Internal use only.*

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`             | Starts local dev server at `localhost:4321`      |
| `bun build`           | Build your production site to `./dist/`          |
| `bun preview`         | Preview your build locally, before deploying     |
| `bun astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help` | Get help using the Astro CLI                     |
