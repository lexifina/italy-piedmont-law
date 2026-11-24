<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Watching the sources: what is watched for Piedmont

[Italiano](WATCHING.md)

How global-law watches every country's sources: [global-law WATCHING.md](https://github.com/lexifina/global-law/blob/main/WATCHING.md). This page is the same for Piedmont only: every official source this repository takes text from, what is read on it, how often and when it was last read. Every read and what came of it: [monitoring/](monitoring/README.en.md).

| Source | What is read | Folders | How often | Last read | State |
| --- | --- | --- | --- | --- | --- |
| [Arianna (Consiglio regionale del Piemonte)](https://arianna.cr.piemonte.it/) | the open dataset of the regional laws in force (Regione Piemonte, one CSV), and the text in force of each new law and of a thirtieth of the held laws a day (normacat text service) | `lr/` | daily | 2026-11-24 00:52 UTC | watched: the text service (serviziweb.csi.it) is read through the EU egress: it does not accept connections from the watcher's own address; the Statute is not held (Arianna's robots.txt disallows /leggistatutarie/) |

Sources are read within their robots.txt and terms, with pauses between requests.
