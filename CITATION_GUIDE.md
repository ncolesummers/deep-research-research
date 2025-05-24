# 📝 APA-7 Citation Guide (Markdown Edition)

> **Purpose:** Ensure every deep-research report uses consistent, post-Feb 2025 sources with clear, verifiable citations.

---

## 1. Inline (Parenthetical) Citations

| Use-Case              | Format Example                                                  | Notes                                     |
| --------------------- | --------------------------------------------------------------- | ----------------------------------------- |
| Single author         | `(Smith, 2025)`                                                 | Author surname + year.                    |
| Two authors           | `(Smith & Lee, 2025)`                                           | Use ampersand in parentheses.             |
| 3–5 authors           | `(Smith et al., 2025)`                                          | “et al.” after first author.              |
| Direct quote          | `(Smith, 2025, p. 12)`                                          | Include page or paragraph number.         |
| Multiple sources      | `(Smith, 2025; Lee, 2026)`                                      | Semicolon-separated, alphabetical.        |
| Organization/Gov site | `(National Institute of Standards and Technology [NIST], 2025)` | Spell out on first use, abbreviate later. |

### Markdown Tip

Place inline citations **outside** code blocks and headings to avoid styling issues.

---

## 2. Reference List (End of Document)

> Add a level-2 heading `## References` at the bottom of each report.

### 2.1 Common Formats

| Source Type             | Reference Entry Template                                                                                      |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| Journal Article         | `Author, A. A., & Author, B. B. (2025). Title of article. *Journal Name, 12*(3), 45–67. https://doi.org/xxxx` |
| Conference Paper        | `Author, A. A. (2025). Title of paper. In *Proceedings of the ABC Conference* (pp. 123–130). Publisher. URL`  |
| Web Page / Blog         | `Author, A. A. (2025, March 7). Title of page. *Site Name*. https://url`                                      |
| GitHub Repo             | `Owner. (2025). *Repo name* (Version tag, if relevant) [Source code]. GitHub. https://github.com/owner/repo`  |
| Government / Org Report | `Organization Name. (2025). *Title of report* (Report No. 123). Publisher. URL`                               |

### 2.2 Formatting Rules

- **Hanging indent** (not rendered in plain Markdown—OK to leave flush-left).
- List in **alphabetical order** by first author or organization.
- Use italics (`*...*`) for book, journal, and repo names in Markdown.

---

## 3. Recency Guardrails

1. **Primary sources must be ≥ March 2025.**
2. If an older source is required for context, prefix with `Pre-Feb 2025 (context only).`

```markdown
Pre-Feb 2025 (context only) – Smith, J. J. (2023). Title...
```
