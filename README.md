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

## Repository structure

```
hacktoberfest_medium/
├── articles/           # Markdown articles
├── assets/             # Images and diagrams
├── templates/          # Contributor and article templates
├── .github/            # Issue and PR templates (optional)
└── README.md
```

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

Thanks for contributing! Every small effort helps the open-source community grow.
