---
"@apollo/client": patch
---

Honor `@nonreactive` across a `@defer` query's final chunk so deferred fields landing no longer trigger a re-render.
