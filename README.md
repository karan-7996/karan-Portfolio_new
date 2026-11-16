[README (1).md](https://github.com/user-attachments/files/34903035/README.1.md)
# Karansinh Padhiyar --- Developer Portfolio

A responsive, motion-led developer portfolio adapted from the Haldoren
"Laptop Dive" concept. The experience presents Karansinh Padhiyar's
profile, selected projects, contact details, and downloadable résumé
through a cinematic laptop-focused interface.

## Overview

-   **Hero:** Full-screen studio scene with a prominent name treatment,
    developer tagline, portrait, and hanging profile card.
-   **Laptop transition:** Scroll, touch, keyboard, and navigation
    interactions move the scene into the portfolio showcase.
-   **Project showcase:** Case-study previews for ERP Modules,
    E-commerce App, Ronspot SaaS, and Hotel Booking.
-   **Profile card:** Highlights full-stack experience and contact
    information.
-   **Contact panel:** Provides phone, email, LinkedIn, and
    location/availability details, with copy actions.
-   **Résumé:** Opens the full profile/resume content and provides a PDF
    download.
-   **Responsive layout:** Desktop and mobile layouts, with
    reduced-motion support.

## Project details

  -----------------------------------------------------------------------
  Area                                Details
  ----------------------------------- -----------------------------------
  Name                                Karansinh Padhiyar

  Role                                Full-Stack Developer

  Experience positioning              5+ years of full-stack development

  Core technologies                   PHP, Laravel, React.js, JavaScript,
                                      MySQL, REST APIs

  Additional focus                    Python, AI tools, workflow
                                      automation

  Location                            Gujarat, India
  -----------------------------------------------------------------------

## Featured projects

### ERP Modules

**Pirotan Technolabs · Laravel 11 / Filament · 2026**

Internal ERP workflows covering HR processes, inventory, role-based
access control, and audit trails. The project presentation highlights
MySQL query optimisation and an approximately 40% reduction in query
latency.

### E-commerce App

**Alendei / Aarya SoftEx · Laravel / React.js · 2025**

Responsive e-commerce experience featuring product catalogues, cart
integrations, and secure payment-gateway checkout.

### Ronspot SaaS

**Krayons Technology · Laravel / AG-Grid · 2025**

Workplace and resource-allocation SaaS interface with allocation views,
AG-Grid reporting, Livewire dashboards, and bug-fixing work.

### Hotel Booking

**INNsight Hospitality · Laravel / QR Tracking · 2022**

Hospitality reservation and inventory workflow, including QR-code-based
inventory scanning for a multi-property hotel environment.

## Running locally

This repository contains the portfolio page in `index.html`, with its
styles and interaction logic inline.

1.  Clone or download the repository.
2.  Make sure the referenced assets are present in the expected
    `assets/aistudio/` directory.
3.  Open `index.html` in a modern browser.

For a local web server, you can use Python:

``` bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

If the project is being maintained through the supplied Vite-based
workspace, use that workspace's existing development and build scripts.

## Asset paths

The customised page references these local assets:

``` text
assets/
└── aistudio/
    ├── ChatGPT_Image_Sep_13__2026__04_41_04_PM_77de4dc5.png
    └── Karansinh_Padhiyar_Resume__2__742917ad.pdf
```

Keep the filenames and relative paths in sync with the references in
`index.html`. If you replace either file, update the corresponding path
in the HTML.

## Customisation

-   Update the hero name, tagline, and profile-card content in
    `index.html`.
-   Update project titles, descriptions, organisations, and preview
    media in the case data.
-   Update contact links and availability information in the contact
    panel.
-   Replace the résumé PDF in `assets/aistudio/` and update its path if
    the filename changes.
-   Keep image and video assets appropriately sized for smooth loading.

## Accessibility and motion

The interface includes keyboard navigation and a reduced-motion path
using the browser's `prefers-reduced-motion` setting. Test wheel, touch,
keyboard, and button navigation after changing transition logic.

## Verification

The customised portfolio was reported as passing:

-   Vite production build
-   TypeScript check (`tsc --noEmit`)

Run the project's own build and type-check scripts again after making
changes. The exact commands depend on the scripts configured in the
workspace's `package.json`.

## Notes

-   Contact information and résumé content should be checked for
    accuracy before publishing.
-   Ensure you have permission to publish the portrait, résumé, project
    descriptions, and any third-party preview media.
-   Do not commit private credentials, API keys, or personal documents
    that are not intended for public access.
