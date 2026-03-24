# Drew Peterson — Personal Landing Page

## Overview

A static personal professional landing page for Drew Peterson, a dual B.B.A. candidate (Finance and Business Analytics & Information Systems) at the University of Iowa, targeting Financial Analyst roles at commercial real estate firms in the Midwest.

## Project Structure

```
/
├── index.html          # Main HTML file (single page)
├── css/
│   └── stylesheet.css  # All styles (vanilla CSS3, no frameworks)
├── js/
│   └── scripts.js      # Reserved for future enhancements
├── images/
│   └── headshot.png    # Professional headshot
├── PRD                 # Product Requirements Document
├── standards           # Design & technical standards
```

## Tech Stack

- **HTML5** — semantic elements throughout
- **CSS3** — vanilla CSS, no frameworks
- **No JavaScript** required (scripts.js is a placeholder)
- **No backend** — pure static site

## Dev Server

Served with Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a **static** deployment with `publicDir: "."`.

## Design Standards

- Color palette: `#F8F9FA` (bg), `#212529` (text), `#1B3A6B` (accent navy), `#E9ECEF` (secondary bg)
- Font: Inter (Google Fonts)
- Max content width: 800px
- Fully responsive from 320px+
- WCAG 2.2 Level AA accessibility

## Sections

1. **Navigation** — sticky top bar with anchor links
2. **Hero** — headshot, name, tagline
3. **About** — academic status, majors, graduation, career interest
4. **Skills** — Excel, PowerBI, Python, SQL (pill badges)
5. **Projects** — 3 placeholder project cards (2-column on desktop)
6. **Experience** — Watts Group (2025), Flummerfelt Homes (2024)
7. **Contact** — LinkedIn, GitHub, email
