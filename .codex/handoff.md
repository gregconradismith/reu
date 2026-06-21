# Codex Handoff

Date: 2026-06-21

Repo: `reu`

Branch: `main`

Current Git status after the 2026-06-21 migration readiness fetch and before this handoff edit:

```bash
## main...origin/main
```

## Repository Role

This repository is a GitHub template for undergraduate research students. It is
intended to help students organize profiles, CVs, project code, papers,
presentations, datasets, references, and dated research notes.

## High-Value Context

- Read `AGENTS.md` before editing.
- `STUDENT_GUIDE.md` is the primary student-facing orientation.
- `docs/github-template-setup.md` explains how to enable and use the GitHub
  template flow.
- `profile/` is for student profile materials.
- `projects/` is for research work products and notes.
- `templates/` contains reusable Markdown templates.
- The repository should stay broadly reusable rather than becoming tied to one
  student's specific project.

## Useful Commands

Check status:

```bash
git status --short --branch
```

Check whitespace in a scoped diff:

```bash
git diff --check
```

## Migration Readiness Snapshot

- Checked on 2026-06-21 before moving computers.
- Non-interactive `git fetch --all --prune` completed successfully.
- Root `README.md` points to `.codex/handoff.md` when a root README exists.

Pre-edit Git state after fetch:

```bash
## main...origin/main
```

## Notes For The Next Codex

- Keep wording student-facing, concrete, and mentor-safe.
- Do not add private student information, restricted datasets, credentials,
  unpublished sensitive material, or copyrighted PDFs without explicit
  direction.
- Prefer small Markdown/documentation improvements and reusable templates.
- After adding or updating `AGENTS.md` / `.codex/handoff.md`, commit the scoped
  change and push it to `main`.
