# Savoir+ Marketing Website — Project Starter

## Purpose

A standalone public-facing website that presents Savoir+ LMS to prospective institutions, generates demo requests, and establishes the product's credibility. The LMS app itself remains at its own URL.

---

## Recommended Tech Stack

| Concern | Recommendation | Why |
|---|---|---|
| Framework | **ASP.NET Core Razor Pages** | Stays in the .NET ecosystem you already know; server-side rendered = good SEO |
| Styling | **Tailwind CSS** | No MudBlazor dependency, fast, highly customizable for a marketing aesthetic |
| Hosting | Same Azure subscription | Easy, consistent infra |
| CMS (later) | None for now — static content | Add a headless CMS (e.g. Contentful) when content updates become frequent |

> Alternative: plain HTML + Bootstrap 5 if you want zero framework. Works perfectly for Phase 1.

---

## Information Architecture (Phase 1 — single page)

```
/  (Landing page)
├── Navbar          — Logo · "Se connecter" button
├── Hero            — Headline · subtext · CTA buttons
├── Features        — 6 feature cards
├── Pour qui ?      — Universities · Institutes · Professional schools
├── CTA section     — Demo request (email for now)
└── Footer          — Copyright · Privacy · Terms
```

Future pages to add: `/tarifs`, `/contact`, `/demo`, `/blog`, `/a-propos`

---

## Content — Hero Section

**Headline:**
> Modernisez l'enseignement dans votre institution

**Subtext:**
> Savoir+ LMS est une plateforme complète de gestion de l'apprentissage conçue pour les universités et établissements d'enseignement supérieur en République Démocratique du Congo. Gérez vos cours, vos étudiants et vos résultats académiques depuis une seule interface.

**CTA buttons:**
- Primary: "Demander une démonstration" → `mailto:` or contact form
- Secondary: "Se connecter" → LMS app URL

---

## Content — 6 Feature Cards

| Icon | Title | Description |
|---|---|---|
| 📚 | Cours & Ressources | Organisez vos cours en chapitres avec des ressources multimédias : PDF, vidéos, audio, présentations. |
| ✅ | Évaluations & Quiz | Créez des devoirs, quiz interactifs et grilles de notation pour évaluer vos étudiants efficacement. |
| 🗓️ | Présences | Enregistrez la présence des étudiants par séance et générez des rapports automatiquement. |
| 📅 | Calendrier académique | Planifiez les examens, événements et congés dans un calendrier partagé visible par tous. |
| 🎥 | Sessions en direct | Organisez des cours en ligne avec des sessions vidéo intégrées directement dans la plateforme. |
| 🎓 | Délibérations | Gérez les résultats académiques par promotion et générez les procès-verbaux de délibération. |

---

## Content — "Pour qui ?" Section

- Universités et facultés
- Instituts supérieurs et techniques
- Grandes écoles et centres de formation professionnelle
- Tout établissement souhaitant moderniser sa gestion pédagogique

---

## Design System (match the LMS app)

| Token | Value |
|---|---|
| Primary blue | `#1565C0` |
| Dark blue (hover) | `#0D47A1` |
| Light background | `#F4F6F9` |
| Text | `#1A1A2E` |
| Font | Inter or Roboto (same feel as MudBlazor default) |
| Border radius | 12px on cards |

---

## Phase 1 Scope (MVP)

- [ ] Single-page site, French only
- [ ] Navbar with logo + "Se connecter" link to LMS
- [ ] Hero section
- [ ] 6-feature grid
- [ ] "Pour qui ?" section
- [ ] Footer with copyright
- [ ] Mobile responsive
- [ ] Basic SEO meta tags (title, description, Open Graph)

## Phase 2 (when ready)

- Contact / demo request form
- Pricing page
- Testimonials from early institutions
- Screenshots or short video demo
- Blog / actualités

---

## Project Name

`SavoirPlus.Web` — keeps naming consistent with `SavoirPlus.Client` and `SavoirPlus.API`.
