---
name: IVA — Detrazione e Pro-rata
description: Diritto alla detrazione IVA, calcolo del pro-rata generale per i soggetti che effettuano operazioni esenti, rettifica della detrazione sui beni ammortizzabili e separazione delle attività. Raccordo tra DPR 633/1972 e nuovo TU IVA (D.Lgs. 10/2026).
area: IVA
fonti:
  - "DPR 26 ottobre 1972, n. 633, artt. 19, 19-bis, 19-bis1, 19-bis2, 36 (vigente fino al 31/12/2026)"
  - "D.Lgs. 19 gennaio 2026, n. 10 — Testo unico IVA, artt. 56 ss. (efficace dal 1/1/2027)"
  - "Direttiva 2006/112/CE, artt. 167-192"
  - "Corte di Giustizia UE — giurisprudenza su imputazione e pro-rata (es. C-378/15 Mercedes Benz Italia)"
aggiornamento: "2026-10"
conflitti_noti: "Nessun conflitto contabile OIC/IAS: l'IVA indetraibile da pro-rata è un costo accessorio dell'acquisto (OIC 16 § 32, OIC 13) o un onere diverso di gestione (CE B.14) se non imputabile a beni specifici; IAS 16 § 16 e IAS 2 § 11 adottano lo stesso criterio per le imposte non recuperabili."
---

# IVA — Detrazione e Pro-rata

> **Nota sul quadro normativo.** Fino al 31 dicembre 2026 si applica il DPR 633/1972. Dal **1° gennaio 2027** è efficace il **TU IVA (D.Lgs. 19 gennaio 2026, n. 10)**: il diritto alla detrazione (ex art. 19) è trasfuso nell'**art. 56**, le limitazioni oggettive (ex art. 19-bis1) nell'**art. 58**. La disciplina sostanziale è confermata; i riferimenti agli articoli vanno aggiornati.

---

## 1. Diritto alla detrazione — principi (art. 19 DPR 633/1972)

- **Nascita:** il diritto sorge quando l'imposta diventa **esigibile** e può essere esercitato, al più tardi, con la dichiarazione relativa all'anno in cui il diritto è sorto (art. 19, c. 1).
- **Presupposti:** possesso della fattura, **inerenza** dell'acquisto all'attività, utilizzo in operazioni che danno diritto alla detrazione.
- **Operazioni che danno diritto alla detrazione:** operazioni imponibili, non imponibili (art. 8, 8-bis, 9, 72, intracomunitarie), operazioni fuori campo per carenza del requisito territoriale ma che darebbero diritto se effettuate in Italia (art. 19, c. 3, lett. b).
- **Operazioni che non danno diritto alla detrazione:** operazioni **esenti** (art. 10) e operazioni fuori campo diverse da quelle sopra (salvo eccezioni dell'art. 19, c. 3).

### Indetraibilità oggettive (art. 19-bis1)

Limitazioni indipendenti dal pro-rata, tra cui:

| Bene/servizio | Detrazione |
|---------------|-----------|
| Autovetture e relative spese (uso non esclusivamente strumentale) | 40% |
| Spese di rappresentanza | Indetraibile, salvo beni di costo unitario ≤ 50 € |
| Alberghi e ristoranti | Detraibile se inerenti (dal 2008) |
| Fabbricati abitativi (impresa non costruttrice/di locazione) | Indetraibile |

L'indetraibilità oggettiva si applica **prima** del pro-rata.

---

## 2. Il pro-rata generale (art. 19, c. 5 e art. 19-bis)

### Ambito

Si applica ai soggetti che effettuano **sia operazioni che danno diritto alla detrazione sia operazioni esenti**. La detrazione dell'IVA su tutti gli acquisti (inclusi quelli specificamente destinati a operazioni imponibili) è ammessa in misura pari alla **percentuale di detrazione**.

⚠️ Nel sistema italiano il pro-rata ha natura **generale**: non è ammesso, in via ordinaria, il criterio dell'imputazione specifica degli acquisti alle singole operazioni, salvo il caso della **separazione delle attività** (art. 36).

### Formula

```
Pro-rata di detrazione (%) = A / (A + B) × 100

A = ammontare delle operazioni che danno diritto alla detrazione effettuate nell'anno
B = ammontare delle operazioni esenti effettuate nell'anno
```

Arrotondamento: all'**unità superiore** se la parte decimale è superiore a 0,5; all'unità inferiore negli altri casi (art. 19-bis, c. 1).

```
Pro-rata di indetraibilità = 100% − Pro-rata di detrazione
```

### Operazioni escluse dal calcolo (art. 19-bis, c. 2)

Non si computano né al numeratore né al denominatore:

- le **cessioni di beni ammortizzabili** (compresi quelli immateriali);
- i **passaggi interni** tra attività separate (art. 36, c. 5);
- le operazioni esenti di cui all'art. 10, c. 1, **nn. 1-9** (operazioni finanziarie, assicurative, su immobili, ecc.) **quando non formano oggetto dell'attività propria** del soggetto passivo o sono **accessorie** alle operazioni imponibili;
- le operazioni esenti di cui all'art. 10, c. 1, n. 27-quinquies (cessioni di beni con IVA indetraibile).

### Esempio

Società che nel 2026 effettua:

| Voce | Importo (€) |
|------|-------------|
| Operazioni imponibili | 800.000 |
| Esportazioni non imponibili | 150.000 |
| Operazioni esenti art. 10 (attività propria) | 300.000 |
| Cessione di un macchinario (bene ammortizzabile) | 50.000 |
| Interessi attivi su depositi bancari (accessori) | 2.000 |

```
A = 800.000 + 150.000 = 950.000
B = 300.000   (escluse: cessione bene ammortizzabile e interessi accessori)
Pro-rata = 950.000 / 1.250.000 = 76%
```

IVA sugli acquisti dell'anno: 100.000 € → detraibile 76.000 €; indetraibile 24.000 € (costo).

---

## 3. Applicazione provvisoria e conguaglio

- **In corso d'anno:** nelle liquidazioni periodiche si applica la **percentuale definitiva dell'anno precedente** (art. 19, c. 5).
- **In dichiarazione annuale:** si calcola la percentuale definitiva e si effettua il **conguaglio** della detrazione (quadro VF della dichiarazione IVA).
- **Inizio attività:** si utilizza una percentuale presunta, comunicata in dichiarazione di inizio attività o determinata in via previsionale, con conguaglio a fine anno.

### Scrittura contabile di conguaglio a fine anno

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| IVA indetraibile da pro-rata (CE B.14 o costo accessorio) | — | Maggiore IVA indetraibile | Conguaglio pro-rata |
| — | Erario c/IVA | Maggiore IVA indetraibile | Riduzione credito IVA |

---

## 4. Rettifica della detrazione (art. 19-bis2)

### Beni ammortizzabili

Se la percentuale di detrazione dell'anno **varia di oltre 10 punti** rispetto a quella dell'anno di acquisto/entrata in funzione del bene, la detrazione va rettificata:

```
Rettifica annuale = IVA sul bene × (Pro-rata anno corrente − Pro-rata anno di acquisto) / 5
```

- **Periodo di osservazione:** anno di entrata in funzione e i **4 successivi** (5 anni); **10 anni** per fabbricati e porzioni di fabbricato.
- Non si applica ai beni di costo unitario non superiore a **516,46 €**, né ai beni con coefficiente di ammortamento superiore al 25%.
- La rettifica opera in aumento (maggiore detrazione) o in diminuzione.

### Altri casi di rettifica

- Mutamento del regime fiscale delle operazioni attive o dell'utilizzo dei beni/servizi (art. 19-bis2, c. 1-3).
- Passaggio a regimi speciali o forfettario (art. 19-bis2, c. 3).
- Cessione del bene ammortizzabile nel periodo di osservazione: rettifica in unica soluzione per gli anni residui.

---

## 5. Separazione delle attività (art. 36)

Alternativa al pro-rata generale per i soggetti che esercitano più attività:

| Ipotesi | Regime |
|---------|--------|
| Attività esenti + attività imponibili distinte | **Opzione** per la separazione (comma 3), vincolante per almeno un triennio, comunicata in dichiarazione annuale |
| Attività con regimi speciali diversi | Separazione **obbligatoria** in alcuni casi (comma 2) |

Con la separazione, ciascuna attività ha la propria contabilità IVA; l'IVA sui beni/servizi promiscui è detratta secondo criteri oggettivi; i **passaggi interni** di beni/servizi tra attività sono soggetti a rilevazione (art. 36, c. 5).

---

## 6. Riflessi contabili e fiscali dell'IVA indetraibile

| Destinazione | Trattamento OIC | Riflesso IRES/IRAP |
|--------------|-----------------|--------------------|
| IVA su beni ammortizzabili | Capitalizzata nel costo (OIC 16) | Deducibile tramite ammortamento |
| IVA su rimanenze | Incrementa il costo di acquisto (OIC 13) | Segue il costo del bene |
| IVA su costi d'esercizio / pro-rata generale | Onere diverso di gestione (B.14) o costo di natura | Deducibile ex art. 99, c. 1 TUIR (imposta indetraibile) |

---

## Note interpretative

- **Interessi attivi bancari** di un'impresa industriale: operazione esente accessoria → esclusa dal pro-rata (prassi consolidata AdE).
- **Holding**: l'acquisto/detenzione di partecipazioni non è attività economica; l'IVA sui costi generali è detraibile solo nella misura in cui la holding svolge attività rilevanti (servizi alle controllate). Valutare caso per caso alla luce della giurisprudenza UE.
- **Pro-rata pari a zero**: se il soggetto effettua solo operazioni esenti, può optare per la dispensa dagli adempimenti (art. 36-bis), perdendo integralmente la detrazione.
- **TU IVA**: dal 2027 verificare i nuovi articoli del TU per pro-rata, rettifica e separazione, e le eventuali circolari attuative dell'Agenzia delle Entrate.
