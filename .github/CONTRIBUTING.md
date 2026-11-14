# Contributing to ITIL 4 Foundation Study Notes

Thanks for helping keep these notes accurate. They cover the **ITIL 4 Foundation** exam, and PeopleCert updates the exam and its guidance from time to time. ITIL (Version 5) now runs alongside ITIL 4 as well, so it's easy for a detail to drift. Reports from people studying with the notes are the best way to catch that.

> [!IMPORTANT]
> **This repo accepts issues, not pull requests.** Pull requests are turned off because I write every change myself and check it against the official ITIL 4 material, which keeps the notes in one voice and consistent from page to page. If you know exactly how something should read, put your proposed wording in the issue. That's just as helpful.

---

## Contents

- [Ways to Help](#-ways-to-help)
- [Before You Open an Issue](#-before-you-open-an-issue)
- [Opening an Issue](#-opening-an-issue)
- [Out of Scope](#-out-of-scope)
- [What Happens Next](#-what-happens-next)
- [Code of Conduct](#-code-of-conduct)
- [Security](#-security)

## 🙌 Ways to Help

Every report fits one of the six types in the issue template:

| Type | What it covers | For example |
| --- | --- | --- |
| **Content error** | A definition, a table, a callout, a diagram or a flash card is wrong | A guiding principle is given the wrong focus, or a practice's purpose is matched to the wrong practice |
| **Outdated content** | PeopleCert has changed the exam or the ITIL 4 scheme since the page was written | The number of questions or the pass mark has changed, or PeopleCert's plan for retiring ITIL 4 has moved |
| **Exam coverage** | The notes don't match the ITIL 4 Foundation candidate syllabus | A learning outcome the exam tests isn't covered, or the marks shown for a topic don't match the syllabus |
| **Site bug** | Search, navigation, diagrams, a broken link or accessibility | A Mermaid diagram doesn't render, search finds nothing for a term that's on the page, or a link returns 404 |
| **Device issue** | Something looks wrong or doesn't work on a specific device, browser or screen size | A wide table won't scroll sideways on a phone, or the navigation menu won't open on a tablet |
| **Suggestion** | Something could be clearer or easier to study | A topic that would read better as a comparison table, a new flash card, or another exam trap for the cheatsheet |

## 🔎 Before You Open an Issue

- **Search the existing issues**, [open and closed](https://github.com/marcogrimaldi29/itil-4-foundation/issues?q=is%3Aissue). If yours is already there, add a 👍 reaction or a comment with anything new rather than opening a duplicate.
- **Check the exam details.** I first wrote the notes in March 2026, against the ITIL 4 Foundation exam as PeopleCert describes it: 40 multiple-choice questions, 60 minutes, closed book and 65% to pass. PeopleCert doesn't publish a dated list of skills for this exam, so compare the **Exam** section of its [ITIL 4 Foundation page](https://www.peoplecert.org/browse-certifications/it-governance-and-service-management/ITIL-1/itil-4-foundation-2565) and the answer to *"When will ITIL 4 modules be sunsetted?"* in its [ITIL FAQ](https://www.peoplecert.org/help-and-support/faq-itil). If either has changed, say so in the issue.
- **Check the official source.** The official book, *ITIL® Foundation, ITIL 4 Edition*, is what the exam is based on, and a page or section in it usually settles whether something is wrong. ITIL Foundation (Version 5) is a separate exam with its own book, so if a detail reads differently there, check it against the ITIL 4 material before reporting it as an error.
- **One problem per issue.** Separate issues are easier to track, fix and close. Several typos on the same page can go in one issue.
- **For a site bug, hard-refresh first** (Ctrl+F5, or Cmd+Shift+R on a Mac) in case your browser is showing an older copy of the page.

## 📝 Opening an Issue

1. Open a new issue with the [🐞 Report an Issue](https://github.com/marcogrimaldi29/itil-4-foundation/issues/new?template=ISSUE_TEMPLATE.md) template.
2. Give it a title that names the page and the problem, for example *"07 — Seven Practices: priority matrix swaps impact and urgency"* rather than *"Mistake on page"*.
3. Fill in the template's sections. Leave out any that don't apply.

> [!TIP]
> To link straight to a section, click it in the page's **Table of Contents**, or hover over a heading and click the link icon beside it. Then copy the address from your browser.

### What Makes a Report Easy to Fix

- **A link to the exact section**, not just the page
- **The text as the notes have it**, quoted, so it can be found even if the page has moved on
- **An official source** for any content change, such as a page or section of the ITIL 4 Foundation book or a PeopleCert page. A report without one may take longer, because every change has to be checked before it goes in. A short reference is enough, so there's no need to copy long passages from the book
- **For bugs and device issues:** the steps to reproduce it, what you expected and what happened instead, the device, operating system and browser, and a screenshot if it shows the problem
- **Your proposed wording**, if you have it. With pull requests turned off, this is the closest thing to suggesting an edit directly

## 🚫 Out of Scope

To keep the notes accurate and the issue tracker useful, please don't open issues for:

- **Live exam content.** Questions, answers or topics remembered from a real exam break PeopleCert's rules: its [Online Terms of Service](https://www.peoplecert.org/-/media/languagecert/document-library/selt/policies-and-procedures/lemd06-peoplecert-online-terms-of-service.pdf) treat the whole certification process as confidential, and an online proctored exam won't start until you accept a non-disclosure agreement. Issues or comments that include them will be closed and the content removed.
- **Exam booking, results or re-sits.** PeopleCert's [Help & Support FAQ](https://www.peoplecert.org/help-and-support/FAQ) covers rescheduling, results and Take2 re-sits, and how to reach its Customer Service team.
- **Help applying ITIL at work.** For questions about your own service desk, change process or ITSM tool, ask in the [ITIL group of the PeopleCert Community](https://community.peoplecert.org/public/clubs/itil).
- **Anything private.** Issues are public, so leave out your PeopleCert account details, exam voucher codes and anything about your employer's or clients' services, incidents or tools, including in screenshots.
- **Unofficial sources.** Practice-test sites, exam dump sites and AI chat answers aren't accepted as the source for a content change.
- **Promotion.** Links to courses, training providers, products or services, affiliate links and paid placements won't be added.
- **Security vulnerabilities.** Please [report these privately](https://github.com/marcogrimaldi29/itil-4-foundation/security/advisories/new), as described in the [security policy](SECURITY.md), not in a public issue.

## 🔄 What Happens Next

- I maintain the notes on my own, in my spare time, so replies are best effort and there's no fixed response time.
- I check each report against the official ITIL 4 material. If something needs clarifying, I'll ask on the issue, so keep an eye on your GitHub notifications.
- When a fix goes in, I close the issue with a note or a link to the change. The live site updates shortly after.
- If nothing changes, I close the issue with the reason, such as out of scope, can't be verified, or working as intended.
- An issue waiting on a reply may be closed after a while. Comment with the missing details and it can be reopened.

## 🤝 Code of Conduct

By opening, commenting on or reacting to issues here, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Comments that are abusive, spam or share live exam content may be hidden, edited or locked.

## 🔒 Security

Found a security problem with the site or this repo? Please don't report it in a public issue. Use [Report a vulnerability](https://github.com/marcogrimaldi29/itil-4-foundation/security/advisories/new) instead, so only you and I can see it. The [security policy](SECURITY.md) has the details.

---

If the notes helped you, the README's [💚 Support](https://github.com/marcogrimaldi29/itil-4-foundation#-support) section has a couple of ways to show it. Thanks for helping make them better for the next ITIL 4 Foundation candidate.
