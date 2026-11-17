# Ganicon Electrics (Pty) Ltd
## Corporate Website

**Empowering Today with Technology of Tomorrow.**

Official corporate website for Ganicon Electrics (Pty) Ltd.

### Core capabilities

- Software Development
- Electronics & Engineering
- Metrology & Quality
- Mobility Systems

### Current website release

**V1.1 — Corporate Brand Integration**

The corporate identity combines a gold microchip, live company wordmark, dark navy backgrounds and cyan accents. Chip-only favicons and a horizontal footer identity complete the website branding.

### Technology and files

A static website built with HTML, CSS and JavaScript. No build process, framework, database or package installation is required.

```text
index.html       Page content and structure
styles.css       Branding, responsive layouts and animation
script.js        Navigation, header behaviour and reveal effects
assets/          Gold chip logo and 16, 32 and 192 px icons
README.md        Project identity and maintenance guidance
.gitignore       Files excluded from version control
```

### Local preview

Open `index.html` in a modern browser, or open the folder in Visual Studio Code and use Live Server. Google Fonts requires an internet connection; local fallback fonts remain available.

Check navigation, the mobile menu, logo and favicons, and narrow-screen layout after changes.

### Project portfolio

- **001 — TruDrags V2:** drag-racing timing and data platform.
- **002 — SafeRoute:** managed scholar transport platform.
- **003 — RoadSafe:** road-safety back-office software.

The preserved V1.1 design displays these numbers in shortened form (01, 02 and 03).

### Development workflow

- `main`: stable website source.
- `development`: ongoing website changes, when created.
- Use focused feature branches and review changes before merging into `main`.
- Keep training exercises in a separate project.

Use clear commits describing one meaningful change. Repository publication and website hosting are separate steps; this repository does not itself confirm an active GitHub Pages deployment.

### Known V1.1 limitations

- The contact button still uses `info@example.com`. Replace it with the approved company email before using the site for customer enquiries.
- Company contact and registration details remain to be approved and added.
- Project descriptions and status labels reflect the supplied prototype and need periodic review.
- The chip images are raster assets; a final approved vector version can be introduced later.
- The site has no contact-form backend or customer accounts.

### Repository hygiene

Commit only public website content and approved branding assets. Keep credentials, `.env` files, internal GIMS/QMS documents, controlled registers, CIPC source records, customer data and proprietary project material outside this repository. The ignore file is a convenience, not a substitute for reviewing staged files.

### Ownership

Copyright Ganicon Electrics (Pty) Ltd. All rights reserved. No open-source licence is granted by publication of this repository.
