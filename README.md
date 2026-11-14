# CREOVIA

**Create. Connect. Earn.**

CREOVIA is a mobile-first creator collaboration platform concept for **content creators, brands/businesses, and agencies**. It brings creator discovery, brand campaigns, creator tools, and agency workflows into one workspace.

## Current prototype

This repository contains an early frontend prototype built with plain HTML, CSS, and JavaScript.

### Included
- Role selection: Content Creator, Brand / Business, and Agency
- Demo account creation and profile onboarding
- Responsive dashboard with Overview, Campaigns, Creator Tools, and My Profile sections
- Planned feature previews for AI Content Studio, Instagram Auto-DM, media kits, account health, invoices, analytics, creator camera, and agency roster
- Web app manifest for future PWA setup

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For best results, serve the folder through a local development server or static hosting rather than opening the file directly.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for GitHub Pages to publish the site.

## Important: prototype limitations

This is a **frontend demonstration**, not a production-ready service.

- Demo sign-up data is stored in browser `localStorage`. It is not secure authentication and must not be used with real passwords or sensitive personal data.
- Google sign-in, phone OTP, database, backend APIs, payments, and a private admin system are not connected.
- Instagram connection and Auto-DM are placeholders. A real integration must use Meta's official OAuth and approved APIs/permissions. Never ask users for their Instagram password.
- AI generation, live campaign listings, analytics, invoicing, and creator recording workflows still require implementation and appropriate services.
- Do not enter real personal, business, or payment information into this demo.

## Suggested production roadmap

1. Add a secure backend, database, and authentication (Google and phone OTP through trusted providers).
2. Add role-based access and a protected admin dashboard.
3. Implement Meta OAuth and approved Instagram integrations.
4. Build campaign management, creator discovery, and agency roster workflows.
5. Add AI tools, analytics, invoices, privacy controls, testing, and deployment monitoring.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web App Manifest

## Project status

**Early prototype — integrations and production backend are not yet live.**

© 2026 CREOVIA
