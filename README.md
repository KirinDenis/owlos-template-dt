# owlos-template-dt

A modern, light-themed **dental clinic website template** — single page, mobile-friendly,
100% self-contained, GDPR compliant out of the box.

> **Template demo** — replace all placeholder content (clinic name, doctors, phone, address,
> photos, prices) before deploying as a real website.

---

## Features

- **Single page** — Hero, Services, Technology, Doctors, Gallery, Reviews, Booking, Contact
- **Light medical design** — mint/teal accent (#00b89a), clean Inter typography
- **Interactive 3D** — rotating tooth model + 4-step treatment viewer (Three.js, self-hosted)
- **Self-hosted fonts** — Inter loaded from `/fonts/` (woff2); zero requests to Google Fonts or any external CDN
- **Self-hosted Three.js** — library in `/js/three.min.js`; zero requests to unpkg or any CDN
- **No analytics, no tracking** — zero external HTTP requests at page load
- **Demo disclaimer banner** — fixed-position notice with localStorage dismissal;
  remove the banner block before going live
- **MIT License** — use freely, replace `[Your Company Name]` in `LICENSE`

---

## Quick Start

1. Download or clone this repository
2. Open `index.html` in your browser — no build step required
3. Replace placeholder content:
   - Clinic name `Dentária Trenčín` → your clinic name (search & replace)
   - Phone, email, address (search for `+421 911 000 000` / `objednanie@dentaria.tn`)
   - Doctor names, bios, and photos — replace `images/placeholder.svg` with real photos
   - Gallery photos — replace `images/placeholder.svg` with actual clinic photos
   - Replace `© 2026 Your Company Name` in the footer
   - Remove the `<!-- Demo disclaimer -->` block (or dismiss it once — uses `localStorage`)
4. Deploy: upload all files to any static web host

---

## Browser Support

Chrome 90+, Firefox 88+, Safari 14+, Edge 90+.
Three.js WebGL rendering requires a GPU — not supported in very old browsers.

---

## GDPR Notice

This template is designed for use in the EU/EEA and follows GDPR best practices:

- **Fonts** — fully self-hosted (woff2 in `/fonts/`); no Google Fonts CDN requests
- **Three.js** — fully self-hosted (`/js/three.min.js`); no unpkg or CDN requests
- **No analytics** — no Google Analytics, Matomo, Hotjar, or similar scripts included
- **No tracking pixels** — no Facebook Pixel or third-party pixels
- **No contact form backend** — the booking form does not submit data anywhere
  in demo mode; connect your own backend or form service (e.g. Netlify Forms)

---

## Disclaimer

This is a **template** — a starting point for a real website. The clinic name, doctor names,
phone numbers, addresses, and photos are fictional placeholders. owlos.sk provides
this template as-is, with no warranty. The licensee is responsible for all content,
legal compliance, and data protection obligations of the deployed website.

**Medical disclaimer:** this template does not constitute medical advice.
Remove or replace all medical content placeholders with accurate, approved information.

---

## License

MIT License — see [LICENSE](LICENSE).


---

## Third-Party Credits

| Asset | License | Source |
|---|---|---|
| Three.js r160 | MIT | mrdoob / three.js |
| Inter | SIL Open Font License 1.1 | Rasmus Andersson |

---

Designed with ♥ by [owlos.sk](https://owlos.sk)
