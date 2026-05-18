# Savoir+ LMS Website — Roadmap

## Phase 1 — MVP ✅ Complete

- [x] Single-page marketing site (French)
- [x] Navbar with logo
- [x] Hero section with dashboard screenshot
- [x] 12+ features section
- [x] "Pour qui ?" section
- [x] Footer with social media placeholders
- [x] Favicon
- [x] Scroll to top button (all pages)
- [x] Mobile & tablet responsive
- [x] SEO meta tags + Open Graph
- [x] Custom domain `savoirpluslms.com`
- [x] SSL certificate (Azure)
- [x] GitHub CI/CD (auto-deploy on push)
- [x] Email forwarding `contact@savoirpluslms.com` → Gmail (ImprovMX)

---

## Phase 2 — Additional Pages ✅ Complete

- [x] `/contact` — Dedicated contact page with form validation (Web3Forms)
- [x] `/demo` — Demo request page with feature overview and form
- [x] `/a-propos` — À propos page (histoire, mission, vision, valeurs)
- [x] `/tarifs` — Pricing page (3 tiers, tarif sur devis, FAQ, CTA)
- [x] `/blog` — Blog & Actualités with JSON-driven architecture
  - [x] 3 published posts (Gestion académique, Bonnes pratiques LMS, Numérique en RDC)
  - [x] Individual article pages with Lora serif typography and highlight callouts
- [x] `/politique-de-confidentialite` — Full privacy policy
- [x] `/conditions-dutilisation` — Full terms of use
- [x] Navbar consistent across all pages (À propos · Démonstration · Tarifs · Blog · Contact)
- [x] Mobile hamburger menu on all pages
- [x] Footer navigation links on all pages (À propos · Blog · Tarifs · Contact + legal)

---

## Phase 3 — Nice to Have

- [ ] Testimonials section (from early institutions)
- [ ] `og-image.png` — social media preview image (1200×630px)
- [ ] Real social media profile URLs in footer (replace `href="#"`)
- [ ] Update `@savoirpluslms` Twitter handle in SEO meta tags once account is created
- [ ] Google Analytics (Measurement ID needed)
- [ ] Cookie consent banner (GDPR-lite)
- [ ] Multi-language support (French + English)
- [ ] Live chat widget (e.g. Tawk.to — free)

---

## Blog — Content Pipeline

- [x] Pourquoi votre université a besoin d'un LMS en 2026 *(Gestion académique)*
- [x] 5 bonnes pratiques pour réussir l'adoption d'un LMS *(Bonnes pratiques LMS)*
- [x] L'enseignement supérieur en RDC face au défi du numérique *(Numérique en RDC)*
- [ ] Upcoming: Actualités Savoir+
- [ ] Upcoming: Témoignages
- [ ] Upcoming: Guides pratiques

> To publish a new article: add an entry to `posts.json` and drop the HTML file in the `blog/` folder.

---

## Technical Debt / Improvements

- [ ] Replace `href="#"` on social media buttons with real profile URLs
- [ ] Update `@savoirpluslms` Twitter handle in SEO meta tags once account is created
- [ ] Add `og-image.png` to root folder and verify Open Graph preview
- [ ] Consider adding `staticwebapp.config.json` for URL redirects (www → non-www)
