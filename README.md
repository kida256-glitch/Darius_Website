# Darius Website

A single-page brand website for Eikon Graphe, focused on premium pencil portrait commissions.

## Project Overview

This project is a static, single-page website built with:
- HTML5
- Embedded CSS
- Embedded vanilla JavaScript

The page presents:
- Brand identity and hero section
- About/story section
- Portfolio gallery
- Commission workflow
- Service offerings
- Community/referral section
- Footer navigation and contact links

## File Structure

- `index.html`: Entire application (markup, styling, and behavior)

## Run Locally

Since this is a static website, you can run it in two simple ways.

### Option 1: Open Directly
Open `index.html` in any modern browser.

### Option 2: Serve With a Local HTTP Server
Using Python:

```bash
python3 -m http.server 5500
```

Then open:

`http://localhost:5500`

## Deployment

This site can be deployed to any static hosting platform:
- GitHub Pages
- Netlify
- Vercel (static)
- Cloudflare Pages

## Customization Guide

Edit `index.html` to update:
- Brand name/title and page metadata
- Color palette (CSS variables under `:root`)
- Section text and call-to-actions
- WhatsApp link and commission contact details
- Gallery/service items

## Accessibility and Responsiveness

The page includes:
- Mobile menu for smaller screens
- Responsive typography with `clamp(...)`
- Structured sections and semantic elements

## Notes

- Google Fonts are loaded via CDN.
- No build step or dependency installation is required.

## License

No license file is currently included. Add a `LICENSE` file if you want to define usage rights.
