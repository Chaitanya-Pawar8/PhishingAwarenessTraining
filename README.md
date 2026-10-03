# Phishing Awareness Training

An interactive, single-page security awareness module, built for
legal purposes only. It teaches people to recognize phishing
emails and fake websites, understand the social engineering tactics
behind them, and test what they've learned with a scored quiz — all in
one self-contained HTML file with no build step, frameworks, or
external dependencies.

**[Open `index.html` in any browser to view it](./index.html)** — or
enable GitHub Pages on this repo to host it as a live link.

---

## What's inside

- **The Anatomy of a Phishing Email** — a fictional but realistic email
  exhibit with 6 clickable red flags (mismatched sender domain,
  manufactured urgency, generic greeting, credential-harvesting request,
  a button that hides its real link, and grammar tells), each explained
  in plain language.
- **Fake Websites** — a walkthrough of how to actually read a URL
  (subdomain vs. real domain), plus a checklist covering HTTPS
  misconceptions, lookalike character swaps, and safer browsing habits.
- **The Social Engineering Playbook** — nine tactics attackers use
  (urgency & fear, authority, curiosity/baiting, familiarity, scarcity,
  pretexting, vishing/smishing, quid pro quo, tailgating), each with a
  one-line real-world-style example.
- **Real-World Case Files** — a chronological look at four widely
  documented, publicly reported phishing-driven incidents: the 2011 RSA
  SecurID breach, the 2013 Target breach, the Evaldas Rimasauskas
  $100M+ BEC scam against Google and Facebook, and the 2020 Twitter
  vishing incident.
- **Defense Checklist** — eight concrete, actionable habits.
- **Scored Interactive Quiz** — 8 questions with immediate per-question
  feedback, a final score, and a retake option.

## Design

The visual language borrows from an investigator's case file rather
than a generic "hacker terminal" or SaaS dashboard — deep ink-navy
sections, amber highlight accents for evidence/callouts, and a serif +
monospace pairing that reads like an incident report. It's meant to
match the actual subject matter: you're learning to spot forgeries, so
the interface treats each example like evidence to be examined.

## Running it

No installation needed — it's one HTML file with inline CSS and vanilla
JavaScript.

```bash
# just open it
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or host it for free with **GitHub Pages**: push this repo, then enable
Pages in Settings → Pages → Deploy from branch → `main` / root. It'll be
live at `https://chaitanya-pawar8.github.io/PhishingAwarenessTraining/`.

## Notes

- The email and bank name used in the walkthrough ("Northwind Bank") are
  entirely fictional — built to demonstrate the pattern without
  impersonating any real company.
- Historical incidents are described from general public reporting and
  widely cited security-training material; figures like the BEC scam
  total are commonly reported as "over $100 million."

---

**Author:** Chaitanya Pawar ([@Chaitanya-Pawar8](https://github.com/Chaitanya-Pawar8))

`#cybersecurity` `#phishing` `#securityawareness`
