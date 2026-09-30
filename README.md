# BabyRoo public catalogues

This repository contains developer-maintained editorial catalogues only. Users do not edit them through BabyRoo, and no personal plans, budgets, immunisation records, backups or signing files belong here.

| Country | File |
| --- | --- |
| Australia | `catalogue.json` |
| United Kingdom | `catalogue-GB.json` |
| United States | `catalogue-US.json` |
| India | `catalogue-IN.json` |
| Singapore | `catalogue-SG.json` |
| Malaysia | `catalogue-MY.json` |

Update-capable app versions include an offline copy and can check the selected country's public file when online checks are enabled. The older `0.3.0-preview.1` packages need an app upgrade before they can fetch the five new country files. To update one country afterward, edit only that file, increment its integer `revision`, preserve all existing item IDs, validate the JSON and official source links, and test Android and iOS before publishing. Keep `schemaVersion` at `1`; a schema or behaviour change requires an app update. The Australian file and URL must remain compatible with older app versions.

All six catalogues include optional baby shower/welcome-gathering and first through fifth birthday entries; no event, gifts or purchase are required. The five international files are preview editorial content, not clinically approved personalised medical schedules. The apps now package machine-drafted translations for seven non-English languages, but qualified local clinical/editorial and fluent-language review remain pending before public international release.
