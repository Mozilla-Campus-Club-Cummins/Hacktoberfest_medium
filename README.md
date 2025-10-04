# hacktoberfest_medium

A Hacktoberfest-friendly repository for contributing short Medium-style articles, guides, and resources about open source, programming, and tech topics.

This repository is part of a collection of projects from **different domains** so that everyone has a chance to contribute. Make sure to check other repositories in the collection too!

---

## Project idea

The idea is to build a community-driven knowledge hub where contributors can add:

* Short articles (500–1500 words)
* Tutorials and how-to guides
* Open source contribution stories
* Beginner-friendly programming explanations

All content will be in Markdown format, making it easy to edit, review, and publish.

---

## Setup instructions

1. **Fork this repository**
2. **Clone your fork:**

   ```bash
   git clone https://github.com/<your-username>/hacktoberfest_medium.git
   cd hacktoberfest_medium
   ```
3. **Create a new branch:**

   ```bash
   git checkout -b feature/my-article
   ```
4. **Add your article or contribution** in the `articles/` folder.
5. **Commit and push your changes:**

   ```bash
   git add .
   git commit -m "Add: my new article on XYZ"
   git push origin feature/my-article
   ```
6. **Open a Pull Request** with a short description of your contribution.

---

## Contribution guidelines

* Articles must be in Markdown (`.md`).
* Keep them concise and clear (500–1500 words).
* Use proper headings, bullet points, and code blocks.
* Images should go in the `assets/` folder.
* Follow the [Code of Conduct](#code-of-conduct).

### Labels to use on Issues & PRs

* `good first issue` → Beginner-friendly tasks
* `medium` → Intermediate difficulty
* `hard` → Advanced tasks
* `documentation` → For doc-related contributions
* All repositories must be tagged with `hacktoberfest`

---

## Example Issues

Each repository must have at least **3 well-explained issues**. Here are some examples:

### 1. Add an article about "Getting Started with Git & GitHub" (`good first issue`)

**Description:** Write a beginner-friendly article explaining Git basics, commits, branches, and how to contribute to GitHub projects.

### 2. Improve repository structure (`medium`)

**Description:** Organize the repo with better folder naming, update the templates, and improve readability of articles.

### 3. Add advanced tutorial on "Setting up CI/CD with GitHub Actions" (`hard`)

**Description:** Write a detailed guide on GitHub Actions workflows with examples for testing and deployment.

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

This repository is released under the MIT License — see `LICENSE` for details.

---

## Code of conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/). Please be respectful and constructive in all interactions.

---

## Contact

Maintainer: **nehalxx**
For questions, open an issue or reach out via GitHub.

---

### Hacktoberfest note

This repository is tagged with the **Hacktoberfest** topic. All valid contributions will count toward your Hacktoberfest pull requests!

---

### Thank you

Thanks for contributing! 🚀 Every small effort helps the open-source community grow.
