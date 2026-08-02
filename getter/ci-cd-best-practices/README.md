# Accelerate with Control

CI/CD, Security Scanners & Engineering Best Practices — internal tech talk for the Getter team.

## About

This presentation covers engineering best practices to ship faster with confidence:

- Why CI/CD: acceleration with control
- Automated testing as the safety net (test pyramid)
- CI/CD pipeline best practices (pipeline as code, deterministic builds, caching, environment parity, rollbacks)
- Security scanners in the pipeline (SAST, SCA, secret scanning, container scanning, SBOM)
- Commit best practices (atomic commits, Conventional Commits)
- Merge Request best practices (small MRs, review checklist, merge strategies)
- Measuring impact (DORA metrics, pipeline health)

## How to run

```bash
# from this directory
python3 -m http.server 8899
# open http://localhost:8899
```

Or serve the repository root and navigate to `/getter/ci-cd-best-practices/`.

## Navigation

- `→` / `←` — next / previous slide
- `↓` / `↑` — navigate vertical sections
- `F` — fullscreen
- `Esc` — overview
- `S` — speaker notes

## Print / PDF

Add `?print-pdf` to the URL and use the browser's print dialog.

## Structure

Built with [Reveal.js](https://revealjs.com/) (local copy, no CDN), dark theme (`night`), custom styles in `css/custom.css`.
