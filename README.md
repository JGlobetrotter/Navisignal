# Navisignal
Navisignal product ecosystem website of Navisignal Insights LLC built in HTML, hosted via gitpages at (https://navisignal.app).

All Rights Reserved. Licensing requires permission.

## Contains

* Homepage with audience-segmented solutions explorer (Corporate, Humanitarian, Government, AI-Curious)
* Structured decision journey section with use scenarios and output examples
* Free Digital Tools with interactive demos (SMART Logframe, RACI Matrix Generator)
* Waitlist signup and contact section
* Legal pages: Privacy Policy, Terms of Service, Affiliate Disclosure

## Structure

```
/
├── index.html                  Main site (single-page layout)
├── style.css                   All site styles
├── demo-logframe.html          Interactive M&E SMART Logframe tool
├── example-raci.html           RACI Matrix Generator demo
├── privacy.html                Privacy Policy
├── terms.html                  Terms of Service
├── affiliate-disclosure.html   Affiliate Disclosure
├── favicon.svg                 Site icon
├── CNAME                       Custom domain config
├── netlify.toml                Netlify build/deploy config
└── .nojekyll                   Disables Jekyll if mirrored to GitHub Pages
```

## Licensing

All Rights Reserved. Use of any content, code, or assets requires written permission from Navisignal Insights LLC.

## Deployment

The site is a static HTML project with no build step. Pushes to `main` auto-deploy via Netlify using the config in `netlify.toml`.

```toml
[build]
  publish = "."
  command = "echo 'Static site — no build step'"
```

## Tools Featured

| Tool | Audience |
|------|----------|
| SMART Logframe Generator | NGOs, Humanitarian |
| RACI Matrix Generator | Corporate, Humanitarian |
| Sustainability Supplier Readiness Tool | Corporate |
| Supplier / Partner Risk Assessment Tool | Corporate |
| KPI Generator by Sector | Corporate |
| HRDD Responsibility Mapping Tool | Corporate |
| Proposal Compliance Matrix Generator | Corporate, Humanitarian |
| LCA Prep Assistant | Corporate |
| Supplier Sustainability MRV Tool | Corporate |
| Supply Chain Transparency & Governance Tool | Corporate |
| Rights Protector (Grievance Mechanism) | Corporate |
| M&E Indicator Generator by Sector | Humanitarian |
| Proposal Go / No-Go Tool | Humanitarian |
| Custom AI Decision Tool | AI-Curious |
| AI Strategy & Scoping Session | AI-Curious |
