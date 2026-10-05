---
name: "Budget Annuale — Economico, Patrimoniale e Finanziario"
description: "Processo di budgeting per PMI italiane: struttura del master budget (operativo, investimenti, finanziario), sequenza di costruzione, collegamento con gli schemi civilistici e con gli adeguati assetti ex art. 2086 c.c. e la verifica prospettica della sostenibilità dei debiti (art. 3 CCII)."
area: "Controllo di Gestione"
fonti:
  - "Codice Civile art. 2086, c. 2 — Assetti organizzativi, amministrativi e contabili adeguati (agg. novembre 2024)"
  - "D.Lgs. 12 gennaio 2019, n. 14 (CCII), art. 3 — Adeguate misure e assetti; segnali di allarme"
  - "Codice Civile artt. 2424, 2425, 2425-ter — Schemi di bilancio"
  - "OIC 10 — Rendiconto finanziario (dicembre 2016)"
  - "CNDCEC — Norme di comportamento del collegio sindacale di società non quotate (edizione vigente), norme sulla vigilanza sugli assetti"
  - "CNDCEC-FNC — Documenti di ricerca in materia di assetti organizzativi, amministrativi e contabili"
aggiornamento: "2026-10"
conflitti_noti: "Il budget è uno strumento gestionale non normato: le regole di valutazione da adottare per coerenza con il consuntivo sono quelle del bilancio d'esercizio (OIC o IAS/IFRS). Per gli IAS-adopter considerare l'effetto IFRS 16 su EBITDA e PFN nel budget finanziario."
---

# Budget Annuale — Economico, Patrimoniale e Finanziario

## 1. Funzione e fondamento

Il budget traduce gli obiettivi strategici dell'anno in **valori economici, patrimoniali e finanziari** attribuiti a centri di responsabilità. Non è obbligatorio per legge in forma tipizzata, ma costituisce lo **strumento cardine dell'assetto amministrativo-contabile adeguato** richiesto dall'art. 2086, c. 2 c.c., perché consente di:

- verificare in via **prospettica** la sostenibilità dei debiti e la continuità aziendale almeno per i **12 mesi successivi** (art. 3, c. 3, lett. b CCII);
- rilevare tempestivamente gli squilibri (art. 3, c. 3, lett. a CCII);
- misurare gli scostamenti e attivare azioni correttive (vedi [`analisi-scostamenti.md`](analisi-scostamenti.md)).

---

## 2. Architettura del master budget

```
                    ┌──────────────────────────┐
                    │  Obiettivi strategici /  │
                    │  piano industriale       │
                    └────────────┬─────────────┘
                                 ▼
   BUDGET OPERATIVI ──────────────────────────────────────────
   1. Budget delle vendite (volumi × prezzi, per prodotto/cliente/area)
   2. Budget della produzione (vendite ± variazione scorte)
   3. Budget acquisti e consumi materie (distinta base × produzione)
   4. Budget del personale (organico, CCNL, TFR, contributi)
   5. Budget costi industriali indiretti, commerciali, generali e amministrativi
                                 ▼
   BUDGET DEGLI INVESTIMENTI (capex, ammortamenti, dismissioni)
                                 ▼
   BUDGET FINANZIARIO (incassi/pagamenti, IVA, imposte, mutui, fidi)
                                 ▼
   CE PREVISIONALE  +  SP PREVISIONALE  +  RENDICONTO FINANZIARIO PREVISIONALE
```

---

## 3. Sequenza di costruzione

| Fase | Attività | Output | Responsabile tipico |
|------|----------|--------|---------------------|
| 1 | Linee guida della direzione (ipotesi macro, prezzi, tassi, inflazione, CCNL) | Documento ipotesi | Direzione / CFO |
| 2 | Previsione vendite per driver (volumi, prezzi, mix, canali) | Budget vendite mensilizzato | Commerciale |
| 3 | Fabbisogni di produzione e magazzino target (DIO obiettivo) | Budget produzione e scorte | Produzione / Logistica |
| 4 | Acquisti e consumi, costo standard per prodotto | Budget acquisti | Acquisti |
| 5 | Organico e costo del lavoro | Budget personale | HR |
| 6 | Costi di struttura per centro di costo | Budget spese | Responsabili CdC |
| 7 | Investimenti e piano ammortamenti | Budget capex | Direzione tecnica |
| 8 | Traduzione in incassi/pagamenti (DSO, DPO, scadenze fiscali) | Budget di cassa mensile | Tesoreria |
| 9 | Consolidamento, quadratura SP, verifica covenant | CE/SP/RF previsionali | Controllo di gestione |
| 10 | Negoziazione e approvazione | Budget approvato dall'organo amministrativo | CdA / Amministratore |

**Approccio:** *top-down* (obiettivi della direzione), *bottom-up* (proposte dei responsabili) o misto (raccomandato per le PMI). Prevedere almeno un **forecast trimestrale** (rolling forecast a 12 mesi) per aggiornare le previsioni.

---

## 4. Budget economico — schema consigliato

Per finalità gestionali si raccomanda il **CE a valore aggiunto** o a **margine di contribuzione**, riconciliabile con lo schema civilistico (art. 2425 c.c.):

| Voce gestionale | Raccordo art. 2425 c.c. |
|-----------------|--------------------------|
| Ricavi netti | A.1 |
| ± Variazione rimanenze prodotti / lavori in corso | A.2, A.3 |
| + Altri ricavi operativi | A.4, A.5 (quota caratteristica) |
| − Consumi di materie (acquisti ± variazione scorte) | B.6, B.11 |
| − Servizi e godimento beni di terzi | B.7, B.8 |
| **= Valore aggiunto** | |
| − Costo del personale | B.9 |
| − Oneri diversi di gestione | B.14 |
| **= EBITDA (MOL)** | |
| − Ammortamenti e svalutazioni | B.10 |
| − Accantonamenti | B.12, B.13 |
| **= EBIT (Risultato operativo)** | A − B |
| ± Gestione finanziaria | C, D |
| − Imposte (IRES, IRAP, differite) | 20 |
| **= Utile netto** | 21 |

Il calcolo delle imposte di budget deve stimare le principali **variazioni fiscali** (TUIR) e la base IRAP (vedi area [`05-fiscalita-impresa`](../05-fiscalita-impresa/)).

---

## 5. Budget finanziario — regole di traduzione

| Componente | Regola |
|------------|--------|
| Incassi da clienti | Fatturato mensile **IVA inclusa** sfasato secondo i giorni medi di incasso (DSO) e la composizione per termini di pagamento |
| Pagamenti a fornitori | Acquisti IVA inclusa sfasati secondo DPO; rispetto dei termini D.Lgs. 231/2002 |
| Personale | Netti a fine mese; contributi e ritenute il 16 del mese successivo; tredicesima/quattordicesima; TFR a fondo/INPS |
| IVA | Liquidazioni mensili/trimestrali, acconto di dicembre, saldo annuale (vedi [`../11-adempimenti-scadenze/calendario-fiscale.md`](../11-adempimenti-scadenze/calendario-fiscale.md)) |
| Imposte dirette | Saldo e primo acconto (giugno/luglio), secondo acconto (novembre) |
| Finanziamenti | Piani di ammortamento (quota capitale + interessi), utilizzo fidi |
| Investimenti | Esborso secondo SAL/consegna; eventuali contributi o crediti d'imposta |

**Budget di tesoreria a 13 settimane:** per le imprese in tensione finanziaria, affiancare al budget mensile un prospetto settimanale degli incassi e pagamenti a breve.

---

## 6. Controlli di coerenza (quadrature)

- [ ] SP previsionale quadrato: Attivo = Passivo + PN
- [ ] Variazione disponibilità liquide del RF = variazione cassa/banche dello SP
- [ ] Utile del CE = variazione del PN al netto di dividendi e apporti
- [ ] Rimanenze finali coerenti con il budget di produzione
- [ ] Crediti e debiti commerciali coerenti con DSO/DPO obiettivo
- [ ] Rispetto dei **covenant** bancari (PFN/EBITDA, PFN/PN, DSCR)
- [ ] **DSCR a 12 mesi** ≥ 1 (verifica della sostenibilità dei debiti, art. 3 CCII)
- [ ] Coerenza con i segnali di allarme art. 3, c. 4 CCII (nessun debito scaduto oltre soglia previsto)

---

## 7. Formula del DSCR prospettico

```
DSCR = Flussi di cassa liberi al servizio del debito (12 mesi) / Servizio del debito (12 mesi)

Flussi al servizio del debito = Flusso di cassa operativo (dopo imposte e variazione CCN)
                               − Investimenti non differibili
Servizio del debito = Quote capitale + interessi dei finanziamenti in scadenza nei 12 mesi
                      (+ debiti fiscali/previdenziali scaduti o rateizzati in scadenza)
```

Un DSCR < 1 indica che i flussi previsti non sono sufficienti a rimborsare i debiti in scadenza: occorre attivare misure (rinegoziazione, apporti, dismissioni) e valutarne gli effetti sulla continuità aziendale (OIC 11 §§ 21-24).

---

## Note interpretative

- **Responsabilità degli amministratori:** l'assenza di strumenti previsionali in un'impresa di dimensioni non trascurabili è considerata indice di **inadeguatezza degli assetti** (orientamento della giurisprudenza di merito successiva al 2019) ed è rilevante per la responsabilità ex art. 2476 / 2392 c.c.
- **Proporzionalità:** per le micro-imprese è sufficiente un budget di cassa semplificato e un CE previsionale annuale, purché aggiornati e verificati periodicamente.
- **Piano industriale vs budget:** il budget è il primo anno del piano pluriennale; in caso di crisi, il piano deve rispettare i principi di redazione dei piani (CNDCEC, Principi per la redazione dei piani di risanamento).
