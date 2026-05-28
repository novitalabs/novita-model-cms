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

Optional structured sections include `overviewTitle`, `overviewBody`, `capabilities`, `lineupSections`, `whyNovitaItems`, `faq`, and `guidanceLinks`.

`lineupSections` supports:

- `title`
- `description`
- `items`
- `modelNames`

`models` can be used to provide collection card records when frontend model config is not available in the current environment. Keep each record structured:

- `name`
- `displayName`
- `description`
- `coverImage`
- `series`
- `tags`
- `infos`
- `link`
- `isNew`
- `isHot`
