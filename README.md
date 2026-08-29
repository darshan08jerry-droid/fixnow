# FixNow Home Care — Website

Marketing and legal-info website for **FixNow Home Care**, a home appliance repair service (AC, washing machine, refrigerator, RO water purifier, water heater) operating in Coimbatore, Chennai, Madurai, Tirupur, and Erode, Tamil Nadu, India.

Live site: [fixnow.live](https://fixnow.live)

## Pages

| File | Description |
|---|---|
| `index.html` | Main landing page — hero, services, pricing, testimonials, booking popup, and site footer |
| `privacy.html` | Privacy Policy — what data FixNow collects (accounts, bookings, technician location/attendance, face verification) and how it's used |
| `terms.html` | Terms & Conditions governing use of the app, website, and repair services |
| `delete-account.html` | Account & Data Deletion — instructions and quick-action buttons for requesting account/data deletion |

All pages share a single design system (colors, type, spacing) defined via CSS custom properties, and link to each other using relative filenames — keep all four files in the same folder.

## Tech stack

- Plain **HTML, CSS, and vanilla JavaScript** — no build step, no framework, no dependencies to install
- Fonts loaded from Google Fonts (`DM Sans`, `Nunito`)
- Fully static — can be hosted from any static file host (GitHub Pages, Netlify, Vercel, S3, etc.)

## Running locally

No build tools required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder locally, e.g.:
  ```bash
  python3 -m http.server 8000
  ```
  then visit `http://localhost:8000`

## Deploying

Upload/copy all files in this folder (HTML pages + image/media assets) to your static host, keeping the flat folder structure so relative links (`privacy.html`, `terms.html`, `delete-account.html`, `index.html`) keep working.

## Contact

**FixNow Home Care**
Tamil Nadu, India
Email: fixnowcoimbatore@gmail.com
Phone/WhatsApp: +91 80986 06019
