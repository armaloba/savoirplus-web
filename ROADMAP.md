# Savoir+ LMS Website — Roadmap

## Phase 1 — MVP ✅ Complete

- [x] Single-page marketing site (French)
- [x] Navbar with logo
- [x] Hero section with dashboard screenshot
- [x] 12+ features section
- [x] "Pour qui ?" section
- [x] Contact / demo request form (Web3Forms)
- [x] Footer with social media placeholders
- [x] Favicon
- [x] Scroll to top button
- [x] Mobile & tablet responsive
- [x] SEO meta tags + Open Graph
- [x] Custom domain `savoirpluslms.com`
- [x] SSL certificate (Azure)
- [x] GitHub CI/CD (auto-deploy on push)
- [x] Email forwarding `contact@savoirpluslms.com` → Gmail (ImprovMX)

---

## Phase 2 — Upcoming Pages

### `/a-propos` — À propos
- Story behind Savoir+ LMS
- Mission and vision
- Team / founding members
- Why we built it (problem we're solving for DRC institutions)

### `/tarifs` — Tarifs
- Pricing plans (per institution size or per module)
- Free trial / demo CTA
- FAQ section (billing, contracts, support)

### `/contact` — Contact
- Dedicated contact page (not just the form at the bottom of the homepage)
- Office location / address (when available)
- Phone number (when available)
- Contact form (reuse the existing one)
- Map embed (optional)

### `/demo` — Démonstration
- Dedicated demo request page
- Embedded video demo or screenshot walkthrough
- Demo request form
- What to expect after requesting a demo

### `/blog` — Actualités
- Articles about edtech in DRC
- Product updates and new feature announcements
- Tips for institutions using LMS platforms

---

## Phase 3 — Nice to Have

- [ ] Testimonials section (from early institutions)
- [ ] `og-image.png` — social media preview image (1200x630px)
- [ ] Social media profile URLs in footer
- [ ] Professional email `contact@savoirpluslms.com` via Microsoft 365
- [ ] Analytics (Microsoft Clarity or Google Analytics)
- [ ] Cookie consent banner (GDPR-lite)
- [ ] Multi-language support (French + English)
- [ ] Live chat widget (e.g. Tawk.to — free)

---

## Footer Pages — Pending Build

### `/politique-de-confidentialite` — Politique de confidentialité
- Currently an empty placeholder page
- Needs full privacy policy content covering:
  - Data collected (form submissions, name, email, institution)
  - How data is used and stored
  - Third-party services (Web3Forms, Azure)
  - User rights and contact for data requests

### `/conditions-dutilisation` — Conditions d'utilisation
- Currently an empty placeholder page
- Needs full terms of use content covering:
  - Acceptance of terms
  - Use of the website and services
  - Intellectual property
  - Limitation of liability
  - Governing law (DRC)

---

## Technical Debt / Improvements

- [ ] Replace `href="#"` on social media buttons with real profile URLs
- [ ] Update `@savoirpluslms` Twitter handle in SEO meta tags once account is created
- [ ] Add `og-image.png` to root folder and verify Open Graph preview
- [ ] Consider adding `staticwebapp.config.json` for URL redirects (www → non-www)
