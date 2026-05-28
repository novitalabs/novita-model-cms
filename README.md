# Novita Model CMS

Structured public CMS content for Novita model collection pages.

## Files

- `collections/kling.json`
- `collections/wan.json`

Each collection file is read by `novita-home` as JSON. Keep field names camelCase and aligned with the frontend schema.

## Required Fields

- `seriesSlug`
- `heroTitle`
- `heroDescription`

Optional structured sections include `capabilities`, `lineupSections`, `whyNovitaItems`, `faq`, and `guidanceLinks`.
