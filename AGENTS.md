# AGENTS.md

## Purpose

This repository is a profile repository. The primary goal is to keep `README.md` aligned with `profile.json`.

## Source Of Truth

- Use `profile.json` as the authoritative source for personal and professional information.
- Keep `README.md` concise and human-readable; avoid dumping raw JSON.

## Repository Structure

- `profile.json`: Structured profile data (primary input).
- `README.md`: Public profile page (derived from `profile.json`).
- `.github/workflows/snake.yml`: GitHub Actions workflow for snake generation.
- `output/*`: Generated snake assets.
- `github-contribution-grid-snake*.gif`: Generated/derived media assets.

## Editing Rules

- Update `README.md` whenever `profile.json` changes.
- Prefer preserving existing section order unless a structural change is intentional.
- Do not add personal data that is not present in `profile.json`.
- Keep Markdown ASCII-friendly and portable.

## Workflow Notes

- The snake assets are generated artifacts; avoid manual edits to generated SVG/GIF files.
- If you change contribution snake settings, update `.github/workflows/snake.yml` and verify asset paths used in `README.md`.
- If GitHub username changes, update workflow config and README references together.

## Recommended Update Flow

1. Read `profile.json`.
2. Refresh summary, experience, skills, certifications, and contact sections in `README.md`.
3. Verify links and dates in `README.md`.
4. Validate the diff for accidental removals.
