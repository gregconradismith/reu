# Agent Instructions

This repository is a template for undergraduate research students to organize
research profiles, CVs, project files, code, papers, presentations, references,
and research notes.

Main files and folders:

- `README.md` describes the template and related lab resources.
- `STUDENT_GUIDE.md` is the student-facing orientation.
- `docs/github-template-setup.md` explains how to mark and use the repository
  as a GitHub template.
- `profile/` holds student profile, CV, picture, and statement materials.
- `projects/` holds project code, data, papers, presentations, and research
  notes.
- `references/` holds reference-related guidance.
- `templates/` contains reusable note, paper-summary, proposal, and weekly
  research-note templates.

Keep the repo student-facing and template-friendly. Prefer clear folder-level
instructions, reusable examples, and small Markdown templates over
project-specific assumptions.

Be careful with privacy and research sensitivity. Students should check with a
mentor before committing unpublished manuscripts, private or restricted
datasets, copyrighted PDFs, personal information, or large raw data files.

Useful lightweight checks:

```bash
git status --short --branch
git diff --check
```

Do not commit local noise such as `.DS_Store`, Python caches, virtual
environments, notebook checkpoints, generated build output, or editor temporary
files.
