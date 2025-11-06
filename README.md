# PowerUp Enterprise Landing Page

A professional, minimal landing page designed with a $1B company aesthetic.

## Design Features

- **Orange Primary Color** - Bold, confident brand presence
- **Dark/Black Accents** - Sophisticated, professional look
- **Minimal Design** - Clean, powerful aesthetic like Stripe, Notion, and Figma
- **Professional Typography** - Inter font family with proper hierarchy
- **Subtle 3D Background** - Non-intrusive geometric elements
- **Responsive Design** - Works seamlessly across all devices

## Live Site

Visit the live site at: https://testerleon.github.io/powerup-enterprise-landing

## Technology Stack

- HTML5 / CSS3
- Three.js (for subtle background effects)
- Supabase integration (for form submissions)
- Vanilla JavaScript

## Setup

To enable GitHub Pages:
1. Go to repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click Save

The site will be published at: `https://testerleon.github.io/powerup-enterprise-landing`

## Supabase Configuration

To enable form submissions, update the following variables in `index.html`:
- `SUPABASE_URL` - Your Supabase project URL
- `SUPABASE_ANON_KEY` - Your Supabase anonymous key

Create a table named `waitlist` with the following schema:
- full_name (text)
- email (text)
- company (text)
- company_size (text)
- submitted_at (timestamp)

---

© 2025 PowerUp. Enterprise Performance Platform.
