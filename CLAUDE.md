# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a prompt-driven deep research playbook focused on evidence-backed prompt engineering research across four disciplines: Software Engineering, UI/UX Design, Technical Product Management, and Academic Research. The repo uses a structured approach to compare prompting patterns, run controlled experiments, and publish repeatable findings.

## Key Commands

### Quality Assurance
```bash
# Run markdown linting (required before commits)
markdownlint "**/*.md"

# Check for broken links
lychee --verbose --no-progress "**/*.md"
```

### Git Workflow
- Main branch: `main`
- CI runs automatically on pushes to main and PRs that modify .md files
- Use provided PR template for self-evaluation

## Project Structure and Workflow

### Core Files
- `PROMPT_TEMPLATE.md` - Template for discipline reports (copy to `discipline_reports/` and rename)
- `EVALUATION_CRITERIA.md` - 5-point scoring rubric for all reports
- `CITATION_GUIDE.md` - APA-7 citation standards and recency requirements
- `assets/prompt_log.yaml` - Log template for prompt/response pairs and reproducibility

### Research Process
1. **Phase 1**: Deep-dive research per discipline using `PROMPT_TEMPLATE.md`
2. **Phase 2**: Cross-discipline synthesis in `synthesis/` folder
3. **Phase 3**: Gap-filling with focused mini-research
4. **Phase 4**: Final playbook packaging

### Quality Standards
- Word limit: ≤2,500 words per report
- Citation requirements: 100% primary sources ≥March 2025
- Verification: Spot-check ≥10% of references
- Target: ≥3 novel insights per prompting pattern
- All sources must use APA-7 inline citation format

### File Organization
- `discipline_reports/` - Individual discipline deep-dive reports
- `synthesis/` - Cross-discipline summaries and comparisons
- `assets/` - Supporting materials, prompt logs, datasets
- `.github/` - Issue templates, PR template, CI workflow

## Important Constraints

- All primary sources must be from March 2025 or later
- Older sources must be tagged "Pre-Feb 2025 (context only)"
- Reports must follow the structured template format exactly
- Every experiment must be logged in `prompt_log.yaml`
- CI checks markdown style and link integrity automatically