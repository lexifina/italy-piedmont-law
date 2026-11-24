<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Italiano](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Piedmont only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 01:22 UTC, Arianna (Consiglio regionale del Piemonte): 59 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Arianna (Consiglio regionale del Piemonte)](https://arianna.cr.piemonte.it/) | `lr/` | daily | 2026-11-24 01:22 UTC | no change | watched: the text service (serviziweb.csi.it) is read through the EU egress: it does not accept connections from the watcher's own address; the Statute is not held (Arianna's robots.txt disallows /leggistatutarie/) |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 00:52](checks/2026-11.md#it-arianna-20261124t005215z) | arianna | 59 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 00:40](checks/2026-11.md#it-arianna-20261124t004015z) | arianna | 44 | 0 | 0 | 0 | 0 (0) | no change `audit-disagrees` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
