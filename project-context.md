# KOR-0049 marketing site context

- Service: 산업안전산업기사 필기·실기
- Service ID: KOR-0049
- Android package / iOS bundle: `app.mcyj.examprep.kor0049`
- Scope: currently released app marketing site for GitHub Pages
- Locales: Korean primary, English support
- Design: charcoal and safety-orange permit-to-work / inspection-board visual system
- Typography: preserve Korean word units with global `word-break: keep-all`
- Store badges: App Store and Google Play controls use identical 194 × 75 frames
- Public store links: Google Play and App Store live listings only
- Source app is read-only; website work is isolated in this repository.

## Verification log

- 2026-09-19: Initialized the isolated marketing-site project.
- 2026-09-19: Built 34 indexable routes and 36 HTML files across Korean and English.
- 2026-09-19: `npm test` verified metadata, internal links, official exam facts, both released Store identities, global `word-break: keep-all`, and equal 194 × 75 marketplace badge frames.
- 2026-09-19: Local HTTP QA passed for all 34 sitemap routes, static assets, and the custom 404 page.
- 2026-09-19: Created public repository `MCYJ/kor-0049-web`, enabled workflow-based GitHub Pages, and completed deployment run `35375904094`.
- 2026-09-19: Production QA passed for all 34 routes, static assets, custom 404, App Store ID `6807105044`, Google Play package `app.mcyj.examprep.kor0049`, keep-all CSS, and equal Store badge frames.
- Production: https://mcyj.github.io/kor-0049-web/ko/
