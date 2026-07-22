# Contributing

## Scope

This repository combines manuscript content, research evidence, and implementation proposals. Contributions should keep these layers distinct:

- **Manifesto Chapters**: reader-facing narrative
- **Research Papers**: source-backed analysis
- **Proposals**: concrete policy or legal implementation drafts

## Content Standards

1. Use the structure in `STYLE_GUIDE.md` for chapters and proposals.
2. Distinguish fact, analysis, and recommendation clearly.
3. Add citations for factual claims.
4. Keep filenames descriptive and stable.

## Recommended Process

1. Add or update the item in `PROJECT_REQUIREMENTS_SPECIFICATION.md`.
2. Draft content in the appropriate directory.
3. Put the assigned ID, status, dependencies, and open-work IDs at the top of
   the working document.
4. Add an entry in `CHANGELOG.md` under `Unreleased`.
5. Commit with a clear message that describes the content change.

## Pull Request Checklist

- [ ] Content is in the correct top-level folder.
- [ ] Its identifier is registered and has not already been used.
- [ ] Claims are source-backed or explicitly marked as opinion.
- [ ] Dependencies are recorded both in the working document and specification.
- [ ] Related status and work items were updated in the specification.
- [ ] `CHANGELOG.md` was updated.
