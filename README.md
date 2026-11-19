# Metadata Cleaner — Landing Page (`metadata_clear_frontend`)

Clean, modern, high-conversion landing page for **Metadata Cleaner** (AI Metadata & Document Privacy Sanitizer), designed with a clean, light aesthetic inspired by the **Habitly** / Appstick mobile app landing page architecture.

## Structure & Pages

- **`index.html`**: Clean main landing page featuring:
  - Sticky navigation header with mobile drawer toggle
  - Hero section with on-device privacy badge, store download buttons (Google Play & App Store), trust points, and real mobile UI phone frame
  - Metadata Inspector / Before & After leak comparison
  - Core capabilities feature cards (Scanner, Lossless, Offline, Batch, AI Prompts, Non-destructive)
  - 3-step workflow & supported format pills (JPG, PNG, WEBP, PDF, DOCX)
  - Mobile screens preview & built-in privacy tools
  - Sanitization modes comparison (Wipe Mode vs Ghost Masking)
  - Zero-telemetry on-device privacy guarantee
  - Interactive FAQ accordion
  - High-converting download CTA banner
  - Appstick-standard 4-column footer
- **`privacy.html`**: Dedicated Privacy Policy page with sticky Table of Contents, 100% on-device file processing guarantee, data safety, and Appstick contact info.
- **`terms.html`**: Dedicated Terms & Conditions page with sticky Table of Contents, acceptable use policy, offline processing disclaimers, intellectual property ownership, and liability terms.
- **`delete-account.html`**: Dedicated Account Deletion page with step-by-step instructions (in-app and via email) meeting Google Play Store Data Safety compliance.
- **`styles.css`**: Clean, lightweight, responsive CSS with CSS variables, modern typography, card hover states, and mobile breakpoints.
- **`script.js`**: Vanilla JS for sticky header, mobile drawer toggle, FAQ accordion, scrollspy, and legal TOC.
- **`assets/`**: Logos, screenshots, and SVGs (Google Play and App Store icons).

## Local Preview

Open `index.html` directly in any web browser, or serve with a local server:

```bash
cd metadata_clear_frontend
python -m http.server 8080
```

Then visit `http://localhost:8080`.
