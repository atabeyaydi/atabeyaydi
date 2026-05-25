# CLAUDE.md

## Repository Overview

This is a **GitHub profile README repository** (`atabeyaydi/atabeyaydi`). The repository name matches the GitHub username, which causes GitHub to automatically render `README.md` as the profile page at `https://github.com/atabeyaydi`.

The repo contains a single meaningful file: `README.md`.

## File Structure

```
atabeyaydi/
└── README.md   # GitHub profile page — the only content file
```

## README Structure & Conventions

The README follows this section order:

1. **Header block** — centered `<div>`, name/title line, LinkedIn + Stack Overflow badge links
2. **About Me** — bullet list of disciplines (EE, software, cybersecurity, AI, data, open source)
3. **Expertise & Technical Focus** — prose summary + nested bullet points per domain
4. **Tech Stack & Tools** — `![Badge](shields.io)` inline images grouped by category:
   - Languages
   - AI / Data / Analytics
   - Cybersecurity
   - DevOps / Cloud / Tools
5. **My Stats** — centered `<div>` with three `github-readme-streak-stats` / `github-readme-stats` image embeds
6. **Key Focus Areas** — Markdown table (Domain | Focus) with emoji prefixes
7. **Footer quote** — centered italic closing quote

### Badge Style

All badges use **shields.io** with the `flat-square` style and white logo text:

```markdown
![Label](https://img.shields.io/badge/Label-COLOR?style=flat-square&logo=logo-slug&logoColor=white)
```

Social/profile badges at the top use `for-the-badge` style instead.

### Stats Widgets

Three widgets are embedded (all scoped to `username=atabeyaydi`):
- `github-readme-streak-stats.herokuapp.com` — contribution streak
- `github-readme-stats.vercel.app/api/top-langs` — language breakdown (compact layout)
- `github-readme-stats.vercel.app/api` — general GitHub stats

All use `bg_color=ffffff&hide_border=true` for a clean white look.

## Development Workflow

- **Default branch:** `main` — direct edits or PRs both land here
- **Feature branches:** `claude/<description>` naming convention (e.g. `claude/claude-md-docs-BaQBp`)
- **Commit style:** plain imperative sentences, e.g. `Update README.md` or `Add stats section to README`
- Changes are usually small, targeted edits to `README.md` with no build steps

## What AI Assistants Should Know

- There is no build system, no tests, no CI pipeline, and no package manager. The repository is purely Markdown + HTML.
- The only deployable artifact is `README.md` — changes take effect immediately on the GitHub profile page after pushing to `main`.
- Preserve the existing section order and visual style (centered headers, shield badges, emoji bullets) unless explicitly asked to redesign.
- When adding technologies to the Tech Stack section, match the existing badge format exactly and insert them into the correct category group.
- Avoid adding sections the owner hasn't established (e.g. a pinned projects section doesn't currently exist — don't add one unless asked).
- The profile represents a multidisciplinary engineer: Electrical-Electronics Engineering, backend software (.NET/Java), cybersecurity, AI/ML (Azure ML, scikit-learn, CNNs/LSTMs), and data analytics. Keep any generated content consistent with these domains.

## Owner Profile Summary

**Atabey Aydi** — Electrical-Electronics Engineer with expertise spanning:
- Backend: .NET Web API, Entity Framework Core, MSSQL, JWT
- Embedded: Verilog HDL, C/C++ for microcontrollers
- AI/ML: CNN, LSTM, Azure ML Studio, Python pipelines
- Security: Kali Linux, Wireshark, OWASP practices
- Cloud/DevOps: Azure, Docker, Git, Linux
