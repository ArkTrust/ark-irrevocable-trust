# Ark Irrevocable Trust

Public home for the **Ark Irrevocable Trust** and its companion **Ark Foundation** (acting trustee).  
This repo contains:

1. Legal agreements and policies  
2. A simple static website (deployable to GitHub Pages)  
3. Public metrics schema + example data for transparency widgets  

> Status: MVP scaffold — September 2025.

---

## Quick Start

1. Clone this repo or download the files.
2. Enable **GitHub Pages** (via GitHub Actions). The included workflow deploys `/site` automatically on push to `main`.
3. Edit the legal docs in `/agreements` and policies in `/policies`.
4. Update `/public/data/metrics.json` regularly (or automate via brokerage/API).

---

## Repo Layout
```
/agreements # Trust deed + Trust ↔ Foundation agreement (drafts)
/policies # Investment, distribution, governance policies (modifiable by Foundation within trust limits)
/public/data # Public metrics JSON served by the website
/site # Static site (no framework) that reads metrics.json and renders counters
/tools # Example scripts and docs helpers
/.github/workflows # CI for GitHub Pages deployment
```

---

## Contribution Principles

- **Immovable core in the Trust Deed.** Foundation policy files may evolve, but the deed defines immutable constraints.  
- **Transparency.** All changes via pull requests. Use signed commits when possible.  
- **Plain language first.** Legal sections should have plain-language summaries.  
- **Open license.** Repo is MIT licensed; legal text © Ark Irrevocable Trust, shared for public review (see LICENSE).  

---

## Roadmap (MVP)

- [ ] Fill in Trust–Foundation Agreement sections.  
- [ ] Publish initial Trust Deed draft for public comment.  
- [ ] Hook `/public/data/metrics.json` to brokerage/API (or manual updates) and verify counters.  
- [ ] Add donation links and FAQ.  
- [ ] Add language/localization support.  
