<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Español](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Valencian Community only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 15:21 UTC, BOE consolidated legislation, autonomous communities (open data): 25 addresses read; 0 added, 0 changed, 0 removed; the check failed; 12 not published, 0 of them with no reason. Flags: `publish-lag`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [BOE consolidated legislation, autonomous communities (open data)](https://www.boe.es/datosabiertos/api/api.php) | `estatuto-de-autonomia/`, `ley-*/`, `decreto-ley-*/`, `decreto-legislativo-*/`, `…` | daily | 2026-11-23 14:04 UTC | the check failed | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 15:20](checks/2026-11.md#es-boe-autonomico-20261124t152044z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 14:29](checks/2026-11.md#es-boe-autonomico-20261124t142939z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 13:06](checks/2026-11.md#es-boe-autonomico-20261124t130611z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 11:24](checks/2026-11.md#es-boe-autonomico-20261124t112427z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 10:21](checks/2026-11.md#es-boe-autonomico-20261124t102101z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 09:19](checks/2026-11.md#es-boe-autonomico-20261124t091935z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 08:19](checks/2026-11.md#es-boe-autonomico-20261124t081943z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-24 07:28](checks/2026-11.md#es-boe-autonomico-20261124t072828z) | boe-autonomico | 25 | 0 | 0 | 0 | 12 (0) | the check failed `publish-lag` | — |
| [2026-11-23 14:04](checks/2026-11.md#es-boe-autonomico-20261123t140408z) | boe-autonomico | 24 | 0 | 0 | 0 | 12 (0) | no change `publish-lag` | — |
| [2026-11-23 01:08](checks/2026-11.md#es-boe-autonomico-20261123t010832z) | boe-autonomico | 10 | 0 | 0 | 0 | 12 (0) | no change `publish-lag` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
