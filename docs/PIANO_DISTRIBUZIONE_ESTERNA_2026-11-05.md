# StudioMargin — piano distribuzione esterna (05/11/2026)

> Stato: PRELANCIO / SOLO VALIDAZIONE / NESSUN CHECKOUT. Documento interno di lavoro: non è un parere fiscale, previdenziale o legale.

## Decisione di indirizzo
Il commercialista ha suggerito inizialmente di appoggiarsi a piattaforme esterne, senza usare la partita IVA professionale per vendere StudioMargin. Questo è un orientamento operativo, NON una conferma che la vendita senza partita IVA sia lecita nel caso concreto. Non attivare vendite né link di pagamento prima di un riscontro esplicito sulla configurazione proposta, inclusa Inarcassa.

## Perché preferire un Merchant of Record (MoR)
- Un MoR gestisce la vendita al consumatore e le imposte indirette sulle transazioni secondo le proprie condizioni.
- Non è una esenzione per il percettore italiano: natura del reddito, obblighi dichiarativi, abitualità/organizzazione, attività commerciale o sfruttamento di proprietà intellettuale e copertura previdenziale restano da qualificare.
- Evitare di confondere MoR con semplice payment processor o piattaforma vetrina.
- Le risposte generiche e la soglia ipotetica dei 5.000 € non costituiscono un lasciapassare per l'attività organizzata.

## Shortlist verificata da fonti ufficiali
| Servizio | Modello dichiarato | Commissioni pubbliche | Note prima dell'attivazione |
| --- | --- | --- | --- |
| Gumroad | MoR sulle vendite | vendite da link diretti: 10% + $0.50, oltre a elaborazione carta 2,9% + $0.30 secondo help; Discover: 30% | Italia supportata per bonifico EUR; account Individual possibile, dati personali/KYC; soglie e tempi di pagamento da verificare nelle impostazioni del singolo account |
| Lemon Squeezy | MoR | riferimento 5% + $0.50, maggiorazioni possibili (transazioni internazionali/PayPal ecc.), e possibili costi payout | identità verificata e negozio approvato prima delle vendite; reverse invoice payout; soglia payout dichiarata $50 |

**Scelta provvisoria:** Gumroad per semplicità di distribuzione dell'XLSX; Lemon Squeezy come alternativa potenzialmente più conveniente su volumi medi. Nessun account o store dichiarato esistente, nessun prodotto messo in vendita.

Fonti:
- https://gumroad.com/help/article/121-sales-tax-on-gumroad
- https://gumroad.com/help/article/66-gumroads-fees
- https://gumroad.com/help/article/260-your-payout-settings-page
- https://gumroad.com/help/article/13-getting-paid
- https://docs.lemonsqueezy.com/help/payments/merchant-of-record
- https://docs.lemonsqueezy.com/help/getting-started/fees
- https://docs.lemonsqueezy.com/help/getting-started/getting-paid
- https://rivista.inarcassa.it/it/-/l-iscrizione-a-inarcassa-quando-%C3%A8-obbligatoria-e-quali-sono-i-requisiti
- https://www.inps.it/it/it/dettaglio-scheda.it.schede-servizio-strumento.schede-servizi.50172.iscrizione-gestione-commercianti.html

## Parere specifico da ottenere dal commercialista (e, ove opportuno, da Inarcassa)
1. La distribuzione tramite Gumroad come MoR di un workbook Excel originale ideato dall'autore, con promozione tramite landing GitHub Pages e vendite potenzialmente ripetute, consente davvero di operare **senza utilizzare la partita IVA professionale**? In quali condizioni verificabili?
2. Come si qualificano i compensi: proventi da licenza di opera dell'ingegno, redditi diversi, reddito d'impresa o altro? Il file originale e la licenza d'uso proposta rientrano effettivamente nella disciplina invocata?
3. Chi fattura a chi e quali documenti servono per contabilizzare i payout del MoR? Cosa cambia tra persona fisica e società, e per vendite B2C/B2B italiane/estere?
4. Quali condizioni fanno diventare l'attività abituale/organizzata (sito, catalogo, licenze ripetute, supporto, marketing)? Quale perimetro è autorizzato nel test iniziale?
5. Vi sono obblighi di iscrizione alla Gestione INPS commercianti, Gestione Separata o altre forme? Se sì, quale impatto avrebbe sulla posizione Inarcassa attuale?
6. Obblighi sui dati personali, licenza d'uso, assistenza, recesso per contenuti digitali, policy del marketplace, eventuale DAC7 e reportistica: chi è responsabile di cosa?

**Gate fiscale-previdenziale:** risposta scritta sufficientemente specifica, o altro parere documentato che definisca modalità consentita. La sola iscrizione a una piattaforma MoR non equivale al superamento del gate.

## Piano d'azione
### Fase A — oggi, senza incassi
- [x] Verificare condizioni generali e documentazione MoR di Gumroad e Lemon Squeezy.
- [x] Mantenere landing come demo/feedback con «nessuna vendita attiva»; inserire FAQ sul futuro canale esterno.
- [x] Documentare il gate fiscale e il possibile impatto Inarcassa.
- [ ] Verificare test manuali Excel desktop, stampa A4 XLSX/HTML, calcoli e casi limite; non caricare file premium pubblicamente.
- [ ] Raccogliere feedback **spontanei**: domanda prioritaria «Qual è il problema più oneroso: prezzo orario, margine del preventivo o flusso di cassa?». Nessuna mailing list promozionale senza consenso.

### Fase B — test di domanda senza vendita
- [ ] Definire 3 segmenti: freelance tecnici; micro-studi 2–5 persone; piccoli studi 6–15 persone.
- [ ] Preparare una scheda prodotto di 1 pagina e demo con dati simulati, senza prezzo impegnativo né promesse di risparmio.
- [ ] Pubblicare soltanto nei canali dove il regolamento ammette feedback su prodotti o autopromozione; verificare regola esatta, data e link ufficiale prima di ciascun post.
- [ ] Conservare risposte aggregate, problemi citati e disponibilità non vincolante a testare; mai contare tali segnali come vendite.

### Fase C — preparazione tecnica (senza pubblicazione)
- [ ] Verificare policy prodotti, KYC, privacy, licenza, rimborso e struttura delle commissioni della piattaforma selezionata.
- [ ] Preparare pacchetto XLSX, guida, changelog, test e screenshot realmente rappresentativi.
- [ ] Preparare una pagina di vendita **in bozza**, non pubblica, e prezzo da validare dopo il gate.

### Fase D — soltanto dopo gate positivo e autorizzazione
- [ ] Registrazione/approvazione account MoR con titolarità corretta.
- [ ] Caricamento del prodotto, impostazione del prezzo e test consentiti dalla piattaforma (no autoacquisti).
- [ ] Attivazione di checkout e link dalla landing, informativa privacy e condizioni aggiornate.
- [ ] Registrazione commissioni, eventuali payout, ricavi netti e imposte secondo indicazioni professionali.

## Misurazione della sfida
Capitale nominale iniziale: €1 (secondo README, **non ancora materialmente versato**). Spese verificate: €0. Ricavi verificati: €0. Incremento realizzato: €0. Nessuna casella raddoppiata. La prima casella si considera completata solo a **capitale effettivo almeno €2**, con almeno €1 di incremento netto realizzato e documentato, al netto delle commissioni e senza confondere incassi lordi o importi ancora da incassare con liquidità effettiva. Obblighi fiscali da considerare nel risultato finale.

## Vincoli per tutte le azioni autonome
- Non usare la partita IVA dello studio per la vendita; non attivare checkout né incassare.
- Non inserire credenziali/dati bancari e non accettare termini contrattuali al posto dell'utente senza autorizzazione.
- In Gmail leggere solo messaggi chiaramente relativi a StudioMargin (es. `subject:StudioMargin`), senza ispezionare il resto della posta.
- Nessuno spam, nessuna promozione indesiderata. Separare sempre fatti verificati, ipotesi e lavoro da completare.
