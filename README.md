# 365digital Client Assets

Shared working library for client logos, photos, screenshots, notes, and agent handoffs.

Use this repo as the staging place for raw and approved assets. Final production/demo sites should still copy approved assets into their own `public/images` folders when possible.

## Folder Pattern

```text
clients/
  client-name/
    notes.md
    logos/
    photos/
    screenshots/
    documents/
```

## Handoff Rules

- Keep file names simple: lowercase, hyphenated, and descriptive.
- Put raw uploads in the client folder first.
- Mark approved assets in `notes.md`.
- Add source URLs and usage rights when known.
- Do not overwrite original files; add a new version suffix like `-v2`.

## Recommended Flow

1. Add raw client assets here.
2. Update the client `notes.md` with context and usage notes.
3. Let agents reference this folder for demos and edits.
4. Copy final approved website assets into the actual site repo.
