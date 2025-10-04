# hacktoberfest_medium

A small repository to collect contributions for Hacktoberfest — focused on short Medium-style articles, guides, and resources about open source, programming, and tech topics.

---

## Table of contents

* [About](#about)
* [What you'll find here](#what-youll-find-here)
* [Getting started](#getting-started)
* [How to contribute (Hacktoberfest-friendly)](#how-to-contribute-hacktoberfest-friendly)
* [Content guidelines](#content-guidelines)
* [Repository structure](#repository-structure)
* [License](#license)
* [Code of conduct](#code-of-conduct)
* [Contact](#contact)

---

## About

This repository is a community collection of short, readable articles and guides suitable for publishing on Medium (or similar platforms). The goal is to provide clear, beginner-friendly writeups about programming concepts, tools, and friendly open-source guides — and to make it easy to contribute during Hacktoberfest.

Contributions can be new articles, improvements to existing articles, formatting fixes, or adding images/examples where appropriate.

---

## What you'll find here

* `articles/` — Markdown files containing individual articles or tutorials.
* `templates/` — Contributor templates (article template, pull request template).
* `assets/` — Images or diagrams used by articles.
* `README.md` — This file.

---

## Getting started

1. Fork this repository.
2. Clone your fork:

```bash
git clone https://github.com/<your-username>/hacktoberfest_medium.git
cd hacktoberfest_medium
```

3. Create a new branch for your work:

```bash
git checkout -b feature/my-article
```

4. Add a new Markdown file under `articles/` or make improvements to an existing file.
5. Commit your changes and push the branch:

```bash
git add .
git commit -m "Add: short description of your article"
git push origin feature/my-article
```

6. Open a Pull Request against the main repository. Describe what you changed and why.

---

## How to contribute (Hacktoberfest-friendly)

To make sure your contribution counts for Hacktoberfest and is helpful to maintainers:

* Make sure your PR contains meaningful changes (no trivial or auto-generated edits).
* Follow the content guidelines below.
* Add a short description in the PR explaining the article's scope and audience.
* If you're submitting multiple PRs, vary the topics and ensure each PR is standalone.

Helpful labels you can add to your PR (if you have permissions): `hacktoberfest`, `good first issue`, `documentation`.

---

## Content guidelines

When writing or editing an article, follow these simple rules:

* Use Markdown (`.md`).
* Keep articles between 500–1500 words for short-form content.
* Use headings, lists, and code blocks to improve readability.
* Include a short summary / TL;DR at the top.
* Add references and links for external resources.
* If you include images, place them in `assets/` and reference them with relative paths.
* Make sure code samples are copy-paste runnable when reasonable.

Suggested article template (see `templates/article-template.md`):

```md
# Title

**TL;DR:** One-sentence summary.

## Introduction

Why this matters.

## Body

Step-by-step explanation, code samples, examples.

## Conclusion

Key takeaways and next steps.

## References

Links to resources.
```

---

## Repository structure

```
hacktoberfest_medium/
├── articles/           # Markdown articles
├── assets/             # Images and diagrams
├── templates/          # Contributor and article templates
├── .github/            # Issue and PR templates (optional)
└── README.md
```

---

## License

This repository is released under the MIT License — see `LICENSE` for details. If you prefer a different license for your contribution, mention it in your PR.

---

## Code of conduct

Be respectful and constructive. This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) — please be kind and assume good intent.

---

## Contact

Created and maintained by **nehalxx**. If you have questions, open an issue or reach out via GitHub.

---

### Thank you

Thanks for wanting to contribute — small improvements add up. Happy Hacktoberfest! 🎉
