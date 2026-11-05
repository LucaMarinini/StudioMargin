# StudioMargin — prelancio

StudioMargin è un progetto sperimentale di foglio Excel per piccoli studi e freelance. Non è attualmente un prodotto in vendita.

## Disponibile sul sito
- Pagina di presentazione: `index.html`
- Simulatore gratuito di tariffa e margine: `calcolatore.html`
- Preventivo compilabile e stampabile dal browser in A4: `preventivo-stampabile.html`
- Anteprime illustrative con dati dimostrativi: `anteprima-dashboard.svg`, `anteprima-preventivo.svg`
- Informativa preliminare: `privacy.html`

URL previsto: https://lucamarinini.github.io/StudioMargin/

## Workbook v1.1 (in validazione)
7 schede: GUIDA, PARAMETRI, PREVENTIVI, CASSA, CRUSCOTTO, OFFERTA_A4, TEST_VALIDAZIONE.

Novità: 2 grafici nativi Excel, modello di preventivo, 12 controlli di coerenza, 11 regole sui campi modificabili. Il file completo non è pubblicato nel repository pubblico.

## Qualità e limitazioni
- 19 verifiche numeriche e strutturali superate sul file.
- 14 controlli statici del sito superati.
- **Da verificare manualmente:** apertura con Excel desktop, stampa XLSX e confronto browser, stampa Chrome/Edge/Firefox, viewport mobile, accessibilità.
- **Attenzione:** la stampa A4 è preconfigurata nel modello HTML tramite CSS. L'XLSX al momento non memorizza ancora impostazioni di stampa `printArea`, formato A4 o adattamento a pagina: non rivendicare questa funzionalità come completata.
- I grafici e le schermate mostrano soltanto dati dimostrativi, non ricavi reali.
- Checkout, vendite e promozione attiva **non abilitati** finché non è chiarita la situazione fiscale e previdenziale, incluse le condizioni Inarcassa.
- Nessun sistema di tracciamento o invio automatico di dati dai simulatori.

## Distribuzione esterna — decisione del 05/11/2026
Su indicazione del commercialista si valutano piattaforme Merchant of Record per la futura distribuzione, senza utilizzare la partita IVA professionale nel percorso iniziale. Si tratta di un orientamento da precisare: la piattaforma esterna non risolve automaticamente fiscalità del percettore o compatibilità previdenziale con Inarcassa. Checkout e pagamenti restano disabilitati. Piano e fonti: [docs/PIANO_DISTRIBUZIONE_ESTERNA_2026-11-05.md](docs/PIANO_DISTRIBUZIONE_ESTERNA_2026-11-05.md).

## Stato della sfida da 1 €
Capitale iniziale previsto: 1,00 € (ancora da versare).
Ricavi verificati: 0,00 €.
Spesa operativa sostenuta per la sfida: 0,00 €.
Nessun raddoppio considerato acquisito.

## Fonti per il design della dashboard
- https://learn.microsoft.com/en-us/power-bi/create-reports/service-dashboards-design-tips
- https://www.financialprofessionals.org/training-resources/resources/articles/Details/how-to-optimize-your-financial-dashboard-for-faster-more-confident-decision-making
