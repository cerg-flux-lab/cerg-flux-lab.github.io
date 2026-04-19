# CERG-FLUX Lab Website

**Fluids, Learning, and Uncertainty in compleX systems**

A research subgroup within the Clean Energy Research Group (CERG), Department of Mechanical & Aeronautical Engineering, EBIT, University of Pretoria.

## Live Site

[https://cerg-flux-lab.github.io](https://cerg-flux-lab.github.io)

## Structure

```
├── index.html                        # Landing page
├── assets/
│   ├── cerg-flux-logo-dark.png       # Full logo (dark variant)
│   └── cerg-flux-icon-dark.png       # Icon-only mark
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

| Element | Value |
|---|---|
| UP Blue | `#003087` (Pantone 287) |
| UP Red | `#86002D` |
| Dark background | `#080b14` |
| Wordmark font | Georgia |
| Labels / mono | JetBrains Mono |
| Body text | DM Sans |

## Contact

**Assoc. Prof. Muaaz Bhamjee** — [muaazbhamjee.github.io](https://muaazbhamjee.github.io)

## Licence

Content © 2026 CERG-FLUX Lab, University of Pretoria. All rights reserved.
