# CERG-FLUX Lab Website

**Fluids, Learning, and Uncertainty in compleX systems**

A research subgroup within the Clean Energy Research Group (CERG), Department of Mechanical & Aeronautical Engineering, EBIT, University of Pretoria.

## Live Site

[https://cerg-flux-lab.github.io](https://cerg-flux-lab.github.io)

## Structure

```
├── index.html                        # Landing page
├── assets/
│   ├── cerg-flux-logo-light.{svg,png}  # Full logo — for white/light backgrounds
│   ├── cerg-flux-icon-light.{svg,png}  # Icon-only mark — for white/light backgrounds
│   └── up-ebit-faculty-lockup.png      # Official UP/EBIT Faculty lock-up (see below)
├── .gitignore
└── README.md                         # This file
```

## Updating the Site

The site is a single static HTML file deployed via GitHub Pages. To update:

1. Clone this repo
2. Edit `index.html` directly
3. Commit and push to `main` — GitHub Pages deploys automatically

### Adding a New Member

Find the relevant section in `index.html` (PhD Students, MEng Students, Postdoctoral Research Fellows, or Collaborators) and add a card:

```html
<div class="member-card">
  <div class="name">Full Name</div>
  <div class="degree">PhD · UP</div>
  <div class="topic">One-line research topic</div>
</div>
```

Replace any `member-placeholder` div when populating a section for the first time.

### Adding a New Infrastructure Card

```html
<div class="infra-card">
  <h4>Resource Name</h4>
  <p>Short description. <a href="https://example.com" target="_blank" rel="noopener">Link</a></p>
</div>
```

## Brand

Colours follow the UP / EBIT internal marketing guidelines. The site sits on a white
background, per the guideline that the UP logo appears on white only. UP Blue is
dominant; EBIT teal is the faculty colour and carries the section accents and calls
to action; UP Red and UP Ochre are the categorical accents.

| Element | Brand value | Notes |
|---|---|---|
| UP Blue (Pantone 287) | `#005BAA` | Links, headings accents, flow-field artwork |
| EBIT Teal (Pantone 322) | `#007B7C` | Section accents, CTAs (`#00595A` on hover) |
| UP Red (Pantone 186) | `#D71C33` | HEP pillar, postdoc badge, logo vortices |
| UP Ochre (Pantone 132) | `#C48B3B` | SciML pillar, PhD badge; text uses `#8F6222` |
| UP Cool Grey (dark / medium / light) | `#5C5C61` / `#A1A59B` / `#D7D2D1` | Self-funded badge |

Ochre is too pale to read as text on white, so `--up-ochre-deep` (`#8F6222`) is used
wherever it carries type.

| Element | Value |
|---|---|
| Background (primary / secondary / card) | `#FFFFFF` / `#F6F9FC` / `#EEF3F8` |
| Text (primary / secondary / muted) | `#0E1A26` / `#44586B` / `#5C7288` |
| Border | `#DDE5ED` |
| Wordmark font | Georgia |
| Labels / mono | JetBrains Mono |
| Body text | DM Sans |

## UP / EBIT Faculty lock-up

`assets/up-ebit-faculty-lockup.png` is the official Faculty lock-up — UP crest, the
Faculty name in all three official UP languages, and the "Make today matter" block
with the University URL. It is extracted at 1200 dpi from the vector artwork in
*Internal branding guidelines fin.pdf* (page 7, "Non-clickable digital applications").

Placement follows the guidelines:

- Entities under EBIT use the **Faculty lock-up**, not the crest on its own, and not a
  standalone sub-logo. The crest is therefore *not* composed into the CERG-FLUX mark;
  the lock-up stands as its own element in the page footer.
- It sits on **white only**, with clear space around it kept free of other marks
  (~1/3 of the lock-up height).
- It renders ~204 px tall, clearing the 200 px minimum height for digital applications
  carrying the URL.
- It links back to `up.ac.za/ebit`, as required of all sub-sites.

For print, or if a scalable asset is needed, request the vector (EPS/AI/SVG) from EBIT
Marketing rather than scaling this raster up.

## Contact

**Assoc. Prof. Muaaz Bhamjee** — [muaazbhamjee.github.io](https://muaazbhamjee.github.io)

## Licence

Content © 2026 CERG-FLUX Lab, University of Pretoria. All rights reserved.
