# Paul's Internship in Numbers

A farewell dashboard for Paul, intern BI Consultant at Cadran Analytics,
5 January – 28 August 2026. Built in the dashboard style he designed himself.

`index.html` is a single self-contained page: the photo and logo are embedded
as data URIs, and the only external request is Google Fonts. No build step.

## Publishing

Hosted with GitHub Pages from the `main` branch, root folder.
Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`.

## Editing the content

Everything lives in clearly marked arrays near the top of the `<script>` block
at the bottom of `index.html`:

| What | Array |
|---|---|
| Months, working days, coffee estimate | `MONTHS` |
| Projects, their run of months, tool, client | `PROJECTS` |
| The reusable templates | `TEMPLATES` |
| Skill scores, week one vs last day | `SKILLS` |
| Timeline entries | `MILESTONES` |
| The three documented strengths | `STRENGTHS` |
| Quotes that have arrived | `QUOTES` |
| Placeholder tiles for quotes still to come | `PENDING_QUOTES` |

Quote order: Pim first, Daniël second, everyone else in order of submission.
