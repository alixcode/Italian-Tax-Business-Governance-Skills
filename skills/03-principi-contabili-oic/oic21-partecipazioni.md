---
name: OIC 21 — Partecipazioni e Titoli
description: Classificazione, iscrizione e valutazione delle partecipazioni azionarie e titoli di debito. Metodo del costo, patrimonio netto, fair value.
area: Principi Contabili OIC
fonti:
  - "OIC 21 — Partecipazioni (dicembre 2017)"
  - "OIC 20 — Titoli di debito (maggio 2022)"
  - "Codice Civile art. 2424 B.III e C.III — Immobilizzazioni finanziarie e attivo circolante finanziario"
  - "Codice Civile art. 2426 nn. 1, 3, 4 — Criteri di valutazione"
  - "TUIR art. 87 — Participation Exemption (PEX)"
  - "TUIR art. 89 — Dividendi"
aggiornamento: "2017-12"
conflitti_noti: "IAS 28 richiede il metodo del patrimonio netto per tutte le associate (influenza notevole), senza l'alternativa del costo; OIC 21 consente il costo anche per le collegate, salvo riduzione durevole di valore. Per bilanci consolidati IAS: metodo PN obbligatorio."
---

# OIC 21 — Partecipazioni e Titoli

## Classificazione delle Partecipazioni

La classificazione della partecipazione determina sia il criterio di valutazione applicabile sia il trattamento fiscale (in particolare, l'accesso alla Participation Exemption ex art. 87 TUIR).

### Immobilizzazioni finanziarie (B.III) — destinazione duratura

Le partecipazioni classificate tra le immobilizzazioni finanziarie sono **destinate a permanere durevolmente** nel patrimonio aziendale (art. 2424-bis c.c.).

| Voce SP | Denominazione |
|---------|---------------|
| B.III.1a | Partecipazioni in imprese controllate (art. 2359 c.c. n. 1 e 2) |
| B.III.1b | Partecipazioni in imprese collegate (art. 2359 c.c. n. 3 — influenza notevole) |
| B.III.1c | Partecipazioni in imprese controllanti |
| B.III.1d | Partecipazioni in altre imprese |
| B.III.2 | Crediti verso imprese (controllate, collegate, ecc.) |
| B.III.3 | Altri titoli (obbligazioni e titoli di debito a lungo termine) |

### Attivo circolante finanziario (C.III) — destinazione alla vendita

Le partecipazioni iscritte nell'attivo circolante sono **destinate alla negoziazione o alla vendita nel breve termine**.

| Voce SP | Denominazione |
|---------|---------------|
| C.III.1 | Partecipazioni in imprese controllate |
| C.III.2 | Partecipazioni in imprese collegate |
| C.III.3 | Partecipazioni in imprese controllanti |
| C.III.4 | Altre partecipazioni |
| C.III.5 | Strumenti finanziari derivati attivi |
| C.III.6 | Altri titoli (titoli di debito a breve) |

### Criterio di classificazione — principio della destinazione

> **OIC 21 § 16:** La classificazione dipende dall'**intenzione del management** al momento dell'acquisto e nei successivi esercizi, non dalla natura intrinseca del titolo. Una partecipazione in una controllata iscritta in B.III.1a può essere riclassificata in C.III.1 se il management decide di cederla nel breve termine.

**Implicazione fiscale critica:** La classificazione come immobilizzazione finanziaria al **primo bilancio chiuso in corso di possesso** è requisito necessario (non sufficiente) per l'accesso alla PEX (art. 87 TUIR co. 1 lett. b). Una partecipazione iscritta sin dall'origine in C.III non potrà mai accedere alla PEX, indipendentemente dalla durata del possesso.

---

## Metodi di Valutazione

### 1. Metodo del Costo (OIC 21 §§ 25–40)

**Campo di applicazione:** Tutte le partecipazioni classificate nelle immobilizzazioni finanziarie (B.III) e nell'attivo circolante (C.III), salvo scelta del metodo del PN per collegate/controllate.

**Iscrizione iniziale:**
```
Costo di acquisto = Prezzo pagato
                   + Oneri accessori diretti (commissioni intermediari,
                     imposte di bollo, spese notarili)
```

**Valutazione successiva:**
- Il costo rimane invariato negli esercizi successivi (no ammortamento).
- **Svalutazione obbligatoria** se si verificano **perdite durevoli di valore** (OIC 9 — test di impairment).
- **Ripristino di valore** (OIC 21 § 39): se le cause della svalutazione vengono meno, si ripristina il valore fino al limite del costo originario; il ripristino transita a conto economico (voce D.18.a o C.16.d).

**Dividendi ricevuti (metodo del costo):**
- Rilevati a conto economico alla data della delibera assembleare della partecipata (voce C.15 — proventi da partecipazioni).
- Non riducono il valore della partecipazione.

### 2. Metodo del Patrimonio Netto — Equity Method (OIC 21 §§ 41–62)

**Campo di applicazione:**
- **Obbligatorio** nel bilancio consolidato per collegate e JV (OIC 17).
- **Facoltativo** nel bilancio individuale per partecipazioni in controllate e collegate.

**Meccanismo:**
```
Valore partecipazione (anno n) = Valore partecipazione (anno n-1)
                                + Quota di utile/perdita della partecipata
                                - Dividendi ricevuti
                                ± Altre variazioni del PN della partecipata
```

**Rilevazione della quota di risultato:**
- Quota di utile della partecipata → incremento del valore della partecipazione + ricavo finanziario (voce D.18).
- Quota di perdita della partecipata → riduzione del valore della partecipazione + onere finanziario (voce D.19).

**Dividendi ricevuti (metodo del PN):**
- **Non** rilevati a conto economico: rappresentano un rimborso parziale dell'investimento → riducono il valore della partecipazione.

**Avviamento incorporato:**
- Se il costo di acquisizione supera la quota del PN della partecipata alla data di acquisto, la differenza è interpretata come maggior valore degli asset o avviamento implicito → viene ammortizzata lungo la vita utile stimata.

**Differenza negativa:**
- Se il costo è inferiore alla quota di PN acquistata → "badwill" → rilevato a conto economico se corrisponde a perdite attese; altrimenti iscritto come riserva nell'attivo a rettifica della partecipazione.

> **Conflitto OIC/IAS 28:** IAS 28 richiede il metodo del PN per **tutte le associate** (influenza notevole ≥ 20%, salvo prova contraria) nel bilancio individuale e consolidato, senza alternativa del costo. OIC 21 lascia la scelta al redattore del bilancio individuale. Per bilanci ordinari italiani: OIC 21 è la fonte prevalente.

### 3. Valutazione al Minore tra Costo e Fair Value (partecipazioni in C.III)

Per le partecipazioni nell'attivo circolante (OIC 21 § 28):

```
Valore di bilancio = MIN(costo di acquisto; fair value)
```

**Determinazione del fair value:**
- Per titoli quotati: prezzo di mercato alla data di chiusura dell'esercizio (o media del periodo).
- Per titoli non quotati: stima basata su multipli di mercato, transazioni comparabili, modelli valutativi (DCF).

---

## Participation Exemption (PEX) — TUIR art. 87

### Requisiti cumulativi

Le plusvalenze da cessione di partecipazioni sono **esenti al 95%** (imponibili solo il 5%) se sussistono **contemporaneamente** tutti e quattro i seguenti requisiti:

| N. | Requisito | Dettaglio |
|----|-----------|-----------|
| 1 | **Holding minimo** | Ininterrotto possesso per almeno **12 mesi** antecedenti la cessione |
| 2 | **Classificazione** | Iscritta tra le **immobilizzazioni finanziarie** nel primo bilancio chiuso durante il periodo di possesso |
| 3 | **Residenza fiscale** | La partecipata **non è residente** in un Paese a fiscalità privilegiata (black list ex art. 47-bis TUIR) — o, se lo è, è dimostrato che non è un'interposizione fittizia |
| 4 | **Attività commerciale** | La partecipata **esercita un'attività commerciale** (non è una holding pura o una società con prevalenti attivi finanziari o immobiliari) |

### Verifica del requisito di commercialità (n. 4)

La commercialità della partecipata si verifica in modo sostanziale: una società holding pura (che detiene solo partecipazioni senza svolgere attività imprenditoriale diretta) non soddisfa il requisito. L'Amministrazione Finanziaria verifica la prevalenza degli asset e dei ricavi commerciali.

### Plusvalenze non PEX

Se i requisiti non sono soddisfatti, la plusvalenza concorre integralmente al reddito imponibile IRES (aliquota 24%) o IRPEF (per imprenditori individuali).

**Minusvalenze:** Se non PEX, le minusvalenze su partecipazioni sono deducibili (art. 101 TUIR). Se PEX, le minusvalenze sono **indeducibili** (art. 87 TUIR co. 6 — simmetria del regime).

> **Attenzione operativa:** La classificazione iniziale tra le immobilizzazioni finanziarie è **irrevocabile ai fini PEX** per quel periodo di possesso. Una riclassifica successiva in C.III non recupera la perdita del requisito, ma una partecipazione già in C.III non può essere "promossa" retroattivamente in B.III per accedere alla PEX. Pianificare la classificazione **al momento dell'acquisto**.

---

## Svalutazione e Impairment (OIC 9 applicato a OIC 21)

### Indicatori di perdita durevole di valore (OIC 21 § 63)

Segnali che impongono la verifica dell'impairment:

**Indicatori interni alla partecipata:**
- Perdite d'esercizio significative o reiterate.
- Patrimonio netto contabile inferiore al valore di carico della partecipazione.
- Deterioramento grave della posizione finanziaria netta.
- Avvio di procedure concorsuali o pre-concorsuali.

**Indicatori di mercato:**
- Calo prolungato del valore di mercato (per partecipazioni quotate).
- Variazioni negative del settore o del contesto macroeconomico.
- Deterioramento della posizione competitiva.

### Determinazione del valore recuperabile

```
Valore recuperabile = MAX(Valore d'uso; Valore di mercato/fair value)
```

**Valore d'uso:** Valore attuale netto dei flussi di cassa futuri attesi dalla partecipazione (dividendi + valore terminale), attualizzati a un tasso che riflette il rischio specifico dell'investimento.

**Metodi pratici per partecipazioni non quotate:**
- Multipli settoriali (EV/EBITDA, P/E) applicati ai dati della partecipata.
- DCF (Discounted Cash Flow) — modello a 5 anni + terminal value.
- Patrimonio netto rettificato (per holding/real estate).

### Rilevazione contabile della svalutazione

```
Svalutazione partecipazione (D.19 CE) a Partecipazioni (B.III o C.III SP)
```

### Ripristino di valore

- Se le cause della svalutazione vengono meno (es. la partecipata torna in utile, migliora la posizione finanziaria), il valore della partecipazione può essere **ripristinato fino al limite del costo storico originario**.
- Il ripristino transita a conto economico (voce C.16.d o D.18.a a seconda della classificazione).
- Il ripristino non è automatico: richiede valutazione esplicita e documentazione a supporto.

---

## Titoli di Debito (OIC 20)

I titoli di debito (obbligazioni, BOT, BTP, commercial paper) sono disciplinati dall'**OIC 20** e possono essere classificati:

| Classificazione SP | Criterio di valutazione |
|--------------------|------------------------|
| B.III.3 — Immobilizzazioni finanziarie | Costo ammortizzato (se scadenza > 12 mesi e importo significativo) |
| C.III.6 — Attivo circolante | Minore tra costo e fair value |

**Costo ammortizzato OIC 20:**
- Analogamente ai debiti (OIC 19): il disaggio/aggio di emissione è ammortizzato con il metodo dell'EIR.
- Gli interessi attivi sono rilevati per competenza secondo il tasso effettivo.

---

## Check-list Operativa per il Commercialista

- [ ] Verificare la classificazione (B.III vs C.III) fin dall'acquisto e documentarla — rilevante sia per la valutazione sia per la PEX.
- [ ] Se si prevede di cedere la partecipazione con plusvalenza PEX: assicurarsi della classificazione in B.III al primo bilancio in corso di possesso.
- [ ] Per collegate (influenza notevole ≥ 20%): valutare se adottare il metodo del PN nel bilancio individuale.
- [ ] Verificare annualmente i 4 requisiti PEX per ogni partecipazione strategica.
- [ ] Eseguire il test di impairment (OIC 9) in presenza di indicatori di perdita durevole.
- [ ] Per partecipazioni valutate al costo: i dividendi percepiti vanno a CE voce C.15 (non riducono il valore).
- [ ] Per partecipazioni valutate con metodo PN: i dividendi riducono il valore della partecipazione (non a CE).
- [ ] Applicare la ritenuta fiscale del 26% sui dividendi distribuiti a persone fisiche (art. 27 D.P.R. 600/1973).
- [ ] Per ripristino di valore: verificare che non superi il costo storico originario e documentare le motivazioni.
- [ ] In nota integrativa: indicare per ogni categoria di partecipazione il metodo di valutazione adottato, i movimenti dell'esercizio e le svalutazioni effettuate.
