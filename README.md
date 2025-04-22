# `jobear.dev` articles (en)

This repository serves as the centralized collection of all articles published on [jobear.dev](https://jobear.dev). Each article is written in *MDX* (*Markdown* + *JSX*) format, allowing rich content and interactive components to be seamlessly integrated into the writing.

This repo is designed to be used as a *git submodule* within the main `jobear.dev` repository (currently private), which can provide article content and associated assets in an organized format.

---

## Repository Structure

Each article is stored in its own dedicated folder with the following naming convention:

`yyyy-mm-dd-article-title`

A typical article folder contains:

- `index.mdx`: The article content
- Any images, videos, or files used within the article

Example:
```
2025-04-22-migrating-xctest-tests-to-swift-testing/
├── index.mdx
├── screenshot1.png
└── screenshot2.png
```

---

## Workflow

This repository is **not** meant to be used standalone. Instead, it is included in the main `jobear.dev` repo as a *submodule*, and article updates or additions are reflected on the site when the main repo is updated.

- At the moment, only @jobearrr can update the main site and deploy new versions.
- Article submissions are welcome via Pull Requests to this repository.
- The articles are pulled in during the site build process to populate its content

This setup allows for easier article management, collaboration, and versioning.

---

## Contributing Articles

Want to publish your article on [jobear.dev](https://jobear.dev)? Here's how:

1. Fork this repository.
2. Create a folder with the format: `yyyy-mm-dd-your-article-title/`
3. Add your `index.mdx` file and any associated assets (images, code snippets, etc.)
4. Open a Pull Request with your contribution.

> Make sure to include your name at the top of the `index.mdx`!

Example:
```mdx
---
title: My Article Title
author: Jane Doe
date: 2025-04-22
---
```

Submitted articles are reviewed and, if approved, pulled into the main site during the next site update.

## Licensing
- Each article is copyrighted by its individual author.
- Do not reuse or redistribute content without the author's permission.
- Attribution is required if you quote or reference articles elsewhere.
