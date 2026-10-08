# Notices and sources

## Fonts (embedded as base64 WOFF2, Latin subset)
| Font | Use | Source | License |
| --- | --- | --- | --- |
| Unbounded 800 | Display type | Fontsource package `@fontsource/unbounded` (Unbounded by NaN) | SIL Open Font License 1.1, see `LICENSES/Unbounded-OFL.txt` |
| JetBrains Mono 500 and 700 | Body and labels | Fontsource package `@fontsource/jetbrains-mono` (JetBrains Mono by JetBrains) | SIL Open Font License 1.1, see `LICENSES/JetBrainsMono-OFL.txt` |

The OFL permits embedding and subsetting. Subsetting kept Basic Latin only (U+0020 to U+007E).

## Brand icons (Simple Icons, CC0 icon data)
Icon paths come from the `simple-icons` npm package. Power BI, LinkedIn, Microsoft SQL Server and Microsoft Azure were removed from the current release, so the pinned release 11.14.0 was used for them. LangChain is from 14.15.0.

| Icon | Release | Where used |
| --- | --- | --- |
| Power BI, Python, Microsoft SQL Server (labelled T-SQL), pandas, NumPy, Microsoft Azure, Databricks, Apache Spark, GitHub | simple-icons 11.14.0 | stack orbits, hero chip, connect card |
| LangChain | simple-icons 14.15.0 | stack orbits |
| LinkedIn | simple-icons 11.14.0 | connect card |

Trademarks and logos belong to their owners. They appear only to name the tools used.

## Marks not shown
Microsoft Fabric, TIBCO and Precisely/Trillium are not in Simple Icons, and the official files could not be downloaded in the build environment. They appear as text chips only. Swap in the official marks yourself if you want them.

## Other
- The globe on the portfolio card is hand-drawn geometry, not a brand mark.
- The portrait is your own photo, embedded as a JPEG crop. JPEG has no alpha channel, so the rounded corners come from a clip path.
