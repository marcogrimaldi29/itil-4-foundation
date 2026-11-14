# Security Policy

ITIL 4 Foundation Study Notes is a static site built with Jekyll and the Just the Docs theme, and published to GitHub Pages. It has no accounts and no sign-in, search runs entirely in your browser, and the site doesn't store anything in your browser: no cookies and no local storage. Diagrams are drawn by Mermaid, loaded from the jsDelivr CDN, and analytics are cookieless, through [Umami](https://umami.is/). The attack surface is small, but security reports are still welcome, and I'd rather hear about a problem privately before it's public.

---

## 🛡️ Supported Versions

There are no releases. Only what's live is maintained.

| Version | Supported |
| --- | --- |
| The live site at [marcogrimaldi29.com/itil-4-foundation](https://marcogrimaldi29.com/itil-4-foundation/) and the `main` branch | ✅ |
| Older commits, forks and copies hosted elsewhere | ❌ |

## 📮 Reporting a Vulnerability

**Please don't open a public issue or comment.** Instead, report it privately through GitHub: open the repo's **Security** tab and choose **Report a vulnerability**, or go straight to the [private report form](https://github.com/marcogrimaldi29/itil-4-foundation/security/advisories/new). Only you and I can see the report, and we can discuss and fix the problem there before anything is made public.

It helps to include:

- The affected URL or file in this repo
- What the problem is and what someone could do with it
- The steps to reproduce it, or a short proof of concept

Please don't include real secrets, credentials or anyone else's personal data in the report, and don't test against anything that isn't yours.

If you can't use GitHub, send me a private message on [LinkedIn](https://www.linkedin.com/in/marco-grimaldi29/) instead, starting it with **"Security: ITIL 4 Foundation Study Notes"** so it's easy to spot.

## 🎯 Scope

**In scope:**

- The published site, including its pages, scripts and assets
- This repository's source code and its GitHub Actions workflow
- A dependency version used here that has a known vulnerability, including the Ruby gems in the `Gemfile` and the Mermaid version the site loads

**Out of scope:**

- **PeopleCert's websites, exam platform or other services.** Report these through [PeopleCert's vulnerability disclosure program](https://app.intigriti.com/programs/peoplecert/peoplecert/detail) on Intigriti.
- **A vulnerability in Jekyll, Just the Docs, Mermaid, Lunr or another dependency itself.** Report it to that project. If this repo uses an affected version, let me know as well.
- **HTTP response headers set by GitHub Pages.** The repo can't change them.
- **Automated scanner output** with no demonstrated impact on this site.
- **Weak security advice in the notes**, such as a summary of the information security management practice that gets it wrong. That's a content issue, so it's welcome as a public issue — see the [contributing guide](CONTRIBUTING.md).

## ⏱️ What to Expect

I maintain this repo on my own, so responses are best effort. I'll confirm I've received your report, keep you posted in the private report while I look into it, and let you know when it's fixed. If you'd like to be credited, say so and I'll credit you in the security advisory or the fix.

Dependabot alerts and security updates are turned on for this repo, so known vulnerabilities in its dependencies are usually flagged and patched without a report.
