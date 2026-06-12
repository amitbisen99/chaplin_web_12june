# The Hindu Chaplain - Website PRD

## Original Problem Statement
"Work on the code given in the selected git repo only. Don't use any other repo or code. Create a separate testimonial page."

## Architecture
- Static multi-page HTML site
- Shared `styles.css` (Saffron/Gold/Cream/White theme, Cormorant Garamond + Manrope fonts)
- Pages: index, about, sacred-passage, empathy, matters, testimonials, contact, help

## Core Requirements (static)
- Maintain consistent navigation, footer, and visual language across all pages
- Existing testimonial-card styles in `styles.css` are the canonical look

## What's been implemented
- 2026-01-12: Created `/app/testimonials.html` as a dedicated page
  - Hero header (saffron overline + serif headline)
  - 6 community testimonial cards in responsive grid (reuses `.testimonial-card`)
  - YouTube video testimonial section
  - "Share Your Story" CTA linking to contact page
  - Footer with Testimonials link added
- Added `Testimonials` nav link with `data-testid="nav-testimonials"` to header on every existing page (index, about, sacred-passage, empathy, matters, contact, help)
- Verified rendering via local screenshot

## Backlog / Future ideas
- P2: Convert testimonials list to dynamic data (JSON file or backend API)
- P2: Replace placeholder YouTube video with the real testimonial video
- P2: Add submission form (or visitor form → moderation)
