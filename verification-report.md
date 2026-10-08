# Verification report

Rendered in headless Chromium 153 (SVG opened directly so SMIL and CSS time could be set).

| Check | hero | about-life | stack | id-dashboard | connect |
| --- | --- | --- | --- | --- | --- |
| Frames at 0, 2, 5, 9, 13 s | pass | pass | pass | pass | pass |
| Animation removed (all animate elements stripped, CSS animation off) | pass | pass | pass | pass | pass |
| Loaded as an img element at 880 px and 390 px | pass | pass | pass | pass | pass |
| prefers-reduced-motion: motion layers hidden, static layer shown | pass | pass | pass | pass | pass |
| Transparent rounded corners (alpha 0), opaque content (alpha 255) | pass | pass | pass | pass | pass |
| Text inside the canvas at every sampled frame (4 px margin) | pass | pass | pass | pass | pass |
| Network requests other than data: URIs | 0 | 0 | 0 | 0 | 0 |
| script, foreignObject, @import, external href | none | none | none | none | none |
| IDs namespaced and unique | pass | pass | pass | pass | pass |
| Smallest text size (px in a 900 px canvas) | 13.8 | 15 | 14 | 14 | 15 |

Orbit check: every orbiting node sat on its ellipse (equation value 1.000) at 0, 3, 7 and 13 s.

Not verifiable here: LinkedIn and the portfolio host are blocked in the build sandbox. github.com/AshwikBire returned 200.
