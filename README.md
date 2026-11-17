# Ganicon Electrics (Pty) Ltd — Website V1.1

This is the first coded website foundation for Ganicon Electrics (Pty) Ltd.

## Technology

- HTML5 — page structure and semantic content
- CSS3 — visual design, responsive layout and animation
- JavaScript — navigation, scroll behaviour and reveal effects

No framework is required for V1. This is intentional: it keeps the code easy to learn, inspect and modify.

## Project structure

```text
ganicon-electrics-website-v1/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── README.md
```

## How to run it

1. Extract the ZIP file.
2. Open the folder in Visual Studio Code.
3. Open `index.html` directly in a browser, or use the VS Code **Live Server** extension.
4. Edit a file, save it, and refresh the browser.

## Important placeholders

Before publishing, replace:

- The temporary `G` brand mark with the approved Ganicon logo.
- The temporary colour system with colours sampled from the approved logo/letterhead if necessary.
- `info@example.com` with the official Ganicon email address.
- Any approved company registration/contact information you want displayed.
- Any project status descriptions that have changed.

## Recommended next development stages

### V1.1 — Brand integration
Add the approved logo, letterhead colours, favicon and final company contact details.

### V1.2 — Content architecture
Create dedicated pages for:
- About Ganicon
- Software Development
- Electronics & Engineering
- Metrology & Quality
- Mobility Services
- TruDrags V2
- SafeRoute
- RoadSafe
- Integrated Management System / Quality
- Contact

### V1.3 — Technical production readiness
Add:
- SEO metadata and social preview cards
- Privacy notice and POPIA-aligned website privacy content
- Cookie handling only if tracking/cookies are introduced
- Production contact form with server-side validation
- Analytics only after deciding what data Ganicon actually needs
- Security headers and deployment configuration

### V2 — Web application foundation
When the website starts needing authenticated dashboards, databases or customer portals, migrate selected functionality to an application architecture rather than turning the marketing site into one large script.

A good future stack for Ganicon could be:
- Front end: HTML/CSS/JavaScript first, then React or Next.js when justified
- API/backend: Python + FastAPI
- Database: PostgreSQL
- Authentication: standards-based authentication through a reputable provider or carefully managed first-party implementation
- Deployment: a modern managed hosting platform initially, with infrastructure formalised as requirements grow


## V1.1 Corporate Brand Integration

This revision introduces the first approved visual identity direction:

- Gold microchip mark replaces the temporary G symbol.
- Company wordmark remains live HTML text for accessibility and responsive control.
- Gold is used as the corporate brand accent.
- Cyan remains the digital/signal/interactive accent.
- The corporate slogan is displayed separately from the primary logo.
- Chip-only favicon files are included at 16 px, 32 px and 192 px.
- The footer uses a horizontal chip + live wordmark lockup and the corporate slogan.
- A restrained cyan/gold hover/load treatment demonstrates the future animated digital logo idea.

The chip asset in this prototype was derived from the supplied raster logo. For production branding, replace it with the final approved vector SVG when available.
