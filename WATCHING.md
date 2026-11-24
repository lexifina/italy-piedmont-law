<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Sorveglianza delle fonti: che cosa si sorveglia per Piemonte

[English](WATCHING.en.md)

Come global-law sorveglia le fonti di ogni paese: [global-law WATCHING.md](https://github.com/lexifina/global-law/blob/main/WATCHING.md). Questa pagina fa lo stesso per Piemonte soltanto: ogni fonte ufficiale da cui questo repository prende il testo, che cosa vi si legge, con quale frequenza e quando è stata letta l'ultima volta. Ogni lettura e il suo esito: [monitoring/](monitoring/README.md).

| Fonte | Che cosa si legge | Cartelle | Frequenza | Ultima lettura | Stato |
| --- | --- | --- | --- | --- | --- |
| [Arianna (Consiglio regionale del Piemonte)](https://arianna.cr.piemonte.it/) | il dataset aperto delle leggi regionali vigenti (Regione Piemonte, un CSV) e il testo vigente di ogni legge nuova e di un trentesimo delle leggi presenti qui ogni giorno (servizio testi normacat) | `lr/` | ogni giorno | 2026-11-24 00:40 UTC | sorvegliata: il servizio testi (serviziweb.csi.it) è letto attraverso l'uscita UE: non accetta connessioni dall'indirizzo del sorvegliante; lo Statuto non è presente (il robots.txt di Arianna esclude /leggistatutarie/) |

Le fonti si leggono nel rispetto del loro robots.txt e delle loro condizioni, con pause tra le richieste.
