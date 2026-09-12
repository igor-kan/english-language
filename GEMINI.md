---
alwaysApply: true
always_on: true
trigger: always_on
description: English Language and Mastery Quarto Website Guidelines
---

# English Language & Mastery Website Guidelines

### Scope & Content Boundaries
* This repository (`english-language`) is dedicated strictly to the **study, mechanics, and mastery of the English language**.
* Topics include: English grammar, syntax, morphology, vocabulary, Latin/Greek roots, rhetoric, effective communication, negotiation, dialectic, and debate.
* **DO NOT store university course materials or unrelated technical CS articles here.**

### Git Dual Remotes (MANDATORY)
* `origin`: `https://github.com/igor-kan/english-language.git` (Public GitHub Pages deployment)
* `private`: `https://github.com/igor-kan/english-language-drafts.git` (Private companion repo for drafts and backups)
* **Always push to both**:
  ```bash
  git push origin main && git push private main
  ```

### Drafts vs. Published
* "Publish" = ensure `draft: true` is not present (or set to `draft: false`).
* "Unpublish" / "Draft" = set `draft: true` in the frontmatter.
* When `draft: true` is enabled, Quarto will NOT render or index the article on the public website.

### UI & Styling Standards
* Adhere strictly to the Notion.so minimalist aesthetic in light and dark mode.
* Footer must display: `© 2026 Igor Kan`.
