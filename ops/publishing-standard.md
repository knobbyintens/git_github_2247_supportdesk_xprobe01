# Publishing standard - release 2026.11

Each published bundle lives in its own folder under `packages/` on the release branch.

Required files per package:

- `README.md` - a verbatim copy of the bundle's `overview.md` from the draft source.
- `content.md` - a verbatim copy of the bundle's `content.md` from the draft source.
- `metadata.json` - a JSON object with these keys:
  - `slug` - the bundle slug used in the catalog
  - `title` - the bundle title
  - `track` - the bundle track
  - `owner_email` - the bundle owner's email address
  - `release` - the release identifier, `2026.11`

Publishing is copy-only. Do not rewrite, summarise, re-order or generate content.
A bundle whose draft source is incomplete cannot be published.
