---
name: IVA — Adempimenti e Liquidazione Periodica
description: Registri IVA, liquidazioni mensili e trimestrali, dichiarazione annuale, fatturazione elettronica, esterometro. Adempimenti periodici e scadenze.
area: IVA
fonti:
  - "TU IVA — D.Lgs. 10 gennaio 2026, artt. 23, 25, 27, 28"
  - "DPR 22 luglio 1998, n. 322 (dichiarazione annuale IVA)"
  - "DPR 23 marzo 1998, n. 100 (liquidazioni periodiche)"
  - "DPR 14 ottobre 1999, n. 542 (opzione trimestrale e maggiorazione interessi)"
  - "D.Lgs. 5 agosto 2015, n. 127 (fatturazione elettronica)"
conflitti_noti: "Le soglie per l'opzione trimestrale (400.000 € / 800.000 €) fanno riferimento al volume d'affari dell'anno precedente — verificare eventuali aggiornamenti normativi per l'anno in corso."
aggiornamento: "2026"
---

# IVA — Adempimenti e Liquidazione Periodica

## 1. Registri IVA obbligatori

### Registro delle vendite (art. 23 TU IVA)

Ogni soggetto passivo IVA deve annotare le fatture emesse nel **registro delle vendite** (o dei corrispettivi, per i commercianti al dettaglio) entro il giorno 15 del mese successivo a quello di emissione, con riferimento al mese di effettuazione dell'operazione.

Dati obbligatori per ogni annotazione:
- Data e numero progressivo della fattura
- Identificativo del cessionario/committente
- Imponibile e imposta per aliquota
- Natura dell'operazione (se esente, non imponibile, fuori campo)

### Registro degli acquisti (art. 25 TU IVA)

Le fatture di acquisto devono essere annotate nel **registro degli acquisti** anteriormente alla liquidazione periodica nella quale si esercita il diritto alla detrazione, e comunque entro il termine di presentazione della dichiarazione annuale relativa all'anno di ricezione della fattura.

Dati obbligatori per ogni annotazione:
- Numero progressivo attribuito
- Data della fattura del fornitore
- Identificativo del fornitore
- Imponibile e IVA detraibile per aliquota

### Registro di prima nota IVA

Le operazioni devono essere annotate in **ordine cronologico**. I registri possono essere tenuti in forma elettronica (file informatici con firma digitale o equivalente garanzia di immodificabilità).

---

## 2. Liquidazione periodica IVA

### Periodicità: mensile (regime ordinario)

Il regime ordinario prevede liquidazioni **mensili** (art. 27 TU IVA):

```
IVA a debito (da registro vendite) − IVA a credito (da registro acquisti) = IVA da versare / credito
```

**Versamento**: entro il **giorno 16 del mese successivo** al periodo di riferimento (es. liquidazione gennaio → versamento 16 febbraio).

### Periodicità: trimestrale (su opzione)

Possono optare per le liquidazioni **trimestrali** (art. 7 DPR 542/1999) i soggetti passivi con volume d'affari nell'anno precedente non superiore a:

- **400.000 €** per i soggetti che esercitano attività di prestazione di servizi
- **800.000 €** per i soggetti che esercitano altre attività (cessione di beni, attività miste)

**Versamento trimestrale**: entro il **16 del secondo mese successivo** al trimestre:

| Trimestre | Scadenza versamento |
|---|---|
| I trimestre (gen-mar) | 16 maggio |
| II trimestre (apr-giu) | 16 agosto |
| III trimestre (lug-set) | 16 novembre |
| IV trimestre (ott-dic) | 16 marzo dell'anno successivo (contestualmente alla dichiarazione annuale) |

### Maggiorazione interessi per liquidazione trimestrale

I contribuenti trimestrali applicano una **maggiorazione dell'1%** sull'IVA a debito di ciascuna liquidazione trimestrale, a titolo di interessi per il differimento del versamento (art. 7 DPR 542/1999). Tale maggiorazione non si applica al IV trimestre, versato direttamente in sede di dichiarazione annuale.

### Acconto IVA di dicembre

Entro il **27 dicembre** di ogni anno, i soggetti passivi devono versare un acconto IVA, calcolato con uno dei seguenti metodi:

- **Metodo storico**: 88% del versamento effettuato (o dovuto) per il mese/trimestre corrispondente dell'anno precedente
- **Metodo previsionale**: 88% dell'IVA dovuta per il periodo in corso
- **Metodo analitico**: IVA effettivamente dovuta al 20 dicembre

---

## 3. Dichiarazione annuale IVA

La **dichiarazione annuale IVA** (art. 8 DPR 322/1998) deve essere presentata in via telematica entro il **30 aprile** dell'anno successivo all'anno di imposta.

La dichiarazione riepiloga:
- Tutte le operazioni attive e passive dell'anno
- IVA a debito e IVA a credito per aliquota
- Rettifiche della detrazione (pro-rata, rettifica annuale ex art. 19-bis2 TU IVA)
- Credito IVA a riportare o a rimborso
- Dati per la comunicazione delle liquidazioni periodiche (LIPE)

### Comunicazione liquidazioni periodiche (LIPE)

I soggetti passivi devono trasmettere telematicamente i **dati delle liquidazioni periodiche** (LIPE) entro:

| Trimestre | Scadenza LIPE |
|---|---|
| I trimestre | 31 maggio |
| II trimestre | 16 settembre |
| III trimestre | 30 novembre |
| IV trimestre | 28 febbraio dell'anno successivo |

---

## 4. Fattura elettronica obbligatoria (D.Lgs. 127/2015)

### Ambito di applicazione

La fatturazione elettronica tramite il **Sistema di Interscambio (SdI)** dell'Agenzia delle Entrate è obbligatoria per:

- **Tutti i soggetti passivi IVA residenti o stabiliti in Italia** dal **1° gennaio 2019** (operazioni B2B e B2C)
- **Operazioni con la Pubblica Amministrazione** (PA): obbligo in vigore dal 6 giugno 2014 (fattura PA)

### Regime forfettario — estensione dell'obbligo

I soggetti in **regime forfettario** (art. 1, cc. 54-89, L. 190/2014) sono stati inclusi nell'obbligo di fatturazione elettronica:

- Dall'**1° luglio 2022**: per i forfettari con compensi/ricavi superiori a **25.000 €** nell'anno precedente
- Dal **1° gennaio 2024**: per tutti i forfettari, indipendentemente dal volume di compensi/ricavi

### Formato e processo

- Formato obbligatorio: **XML FatturaPA** (schema ministeriale)
- Trasmissione tramite SdI, che verifica la correttezza formale e recapita al destinatario
- Conservazione sostitutiva obbligatoria per **10 anni**
- Termini di emissione: entro **12 giorni** dall'effettuazione dell'operazione (fattura immediata) o entro il 15 del mese successivo (fattura differita)

---

## 5. Esterometro — Comunicazione operazioni transfrontaliere

L'**esterometro** (già "spesometro estero") è la comunicazione telematica dei dati delle operazioni con soggetti non stabiliti in Italia (art. 1, c. 3-bis D.Lgs. 127/2015).

### Scadenza

Entro il **15° giorno del mese successivo** alla data:
- Di emissione della fattura (per le operazioni attive verso soggetti esteri)
- Di ricezione del documento (per le operazioni passive da soggetti esteri)

### Esonero

Sono escluse dall'esterometro le operazioni per le quali è stata emessa o ricevuta una bolletta doganale, nonché quelle effettuate con soggetti non passivi IVA (privati consumatori finali).

---

## 6. Prospetto riepilogativo degli adempimenti IVA

| Adempimento | Frequenza | Scadenza |
|---|---|---|
| Annotazione fatture emesse | Continuativa | Entro il 15 del mese successivo |
| Annotazione fatture ricevute | Continuativa | Prima della liquidazione di riferimento |
| Liquidazione IVA mensile | Mensile | 16 del mese successivo |
| Liquidazione IVA trimestrale | Trimestrale | 16 del 2° mese successivo al trimestre |
| Comunicazione LIPE | Trimestrale | Vedi tabella |
| Esterometro | Mensile | 15 del mese successivo |
| Acconto IVA dicembre | Annuale | 27 dicembre |
| Dichiarazione annuale IVA | Annuale | 30 aprile anno successivo |
