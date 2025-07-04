# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML website for "Miss Ranae's Brilliant Back-to-School Bundles" - a business selling pre-packaged school supply bundles. The site is hosted on GitHub Pages with a custom domain.

## Architecture

- **Single-page application**: The entire site is contained in `index.html`
- **Static hosting**: Deployed via GitHub Pages
- **Custom domain**: Uses `backtoschool.darrellandranae.com` (configured in CNAME)
- **Self-contained styling**: All CSS is inline within the HTML file
- **No build process**: Direct deployment of HTML file

## File Structure

```
/
├── index.html          # Main landing page with embedded CSS
├── CNAME              # GitHub Pages custom domain configuration
└── CLAUDE.md          # This file
```

## Key Features

The website includes:
- Responsive design with mobile-first approach
- Two product bundles (K-5th grade and 6th-12th grade)
- Gradient backgrounds and modern styling
- Call-to-action button linking to Google Forms
- Testimonial section
- Responsive grid layouts

## Common Tasks

Since this is a static site with no build process:

- **Local development**: Open `index.html` directly in browser
- **Deployment**: Changes are automatically deployed via GitHub Pages when pushed to main branch
- **Testing**: Manual testing in browser, no automated test suite
- **Domain**: Custom domain configured through CNAME file

## Content Updates

When updating content:
- All text content is directly in HTML
- Styling is embedded in `<style>` tags within the HTML
- Product information and pricing are hardcoded in the HTML structure
- External link for orders goes to Google Forms

## Hosting Details

- Repository serves as GitHub Pages source
- Main branch is the deployment branch
- Custom domain: `backtoschool.darrellandranae.com`
- No Jekyll or other static site generator used