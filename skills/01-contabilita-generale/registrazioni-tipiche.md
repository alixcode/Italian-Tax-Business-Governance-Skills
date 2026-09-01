---
name: Registrazioni Contabili Tipiche
description: Tavola delle scritture contabili standard per le operazioni ricorrenti di un'impresa italiana. Formato dare/avere con causale e riferimento normativo. Copre fatturazione, incassi, pagamenti, ammortamenti, accantonamenti e imposte.
area: Contabilità Generale
fonti:
  - "Codice Civile art. 2425 (schema Conto Economico, agg. novembre 2024)"
  - "Codice Civile art. 2424 (schema Stato Patrimoniale, agg. novembre 2024)"
  - "OIC 15 — Crediti (marzo 2024)"
  - "OIC 16 — Immobilizzazioni materiali (marzo 2024)"
  - "OIC 19 — Debiti (marzo 2024)"
  - "OIC 25 — Imposte sul reddito (marzo 2024)"
  - "OIC 31 — Fondi per rischi e oneri e TFR (marzo 2024)"
  - "OIC 34 — Ricavi (aprile 2023)"
aggiornamento: "2024-04"
---

# Registrazioni Contabili Tipiche

Le scritture di seguito sono espresse nel formato standard a partita doppia:

```
CONTO IN DARE          |  CONTO IN AVERE         |  Importo  |  Causale
```

Per ciascuna operazione sono indicati: il momento di rilevazione, i conti coinvolti e il riferimento normativo/OIC applicabile.

---

## 1. Fattura di vendita (ricavo + IVA a debito + credito verso cliente)

**Momento:** emissione della fattura al cliente (trasferimento dei rischi e benefici o momento contrattuale ex OIC 34 § 31).

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Crediti verso clienti | — | Imponibile + IVA | Credito commerciale sorto |
| — | Ricavi di vendita | Imponibile | Ricavo di competenza ex OIC 34 |
| — | IVA a debito (c/erario) | IVA esposta in fattura | Debito IVA verso Erario |

**Note:** I ricavi si rilevano al netto degli sconti commerciali indicati in fattura. L'IVA esposta non è componente di ricavo (OIC 34 § 7). Per le vendite con resa differita verificare il momento del trasferimento dei rischi e benefici.

---

## 2. Fattura di acquisto (costo + IVA a credito + debito verso fornitore)

**Momento:** ricevimento della fattura del fornitore e contestuale maturazione del costo di competenza.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Costo (per natura: acquisti, servizi, ecc.) | — | Imponibile | Costo di competenza dell'esercizio |
| IVA a credito (c/erario) | — | IVA esposta in fattura | Credito IVA detraibile |
| — | Debiti verso fornitori | Imponibile + IVA | Debito commerciale sorto |

**Note:** La detraibilità dell'IVA è condizionata all'inerenza e all'utilizzo del bene/servizio in operazioni imponibili. Per acquisti misti (uso promiscuo) occorre applicare il pro-rata ex art. 19-bis TU IVA.

---

## 3a. Incasso da cliente

**Momento:** accredito bancario o emissione ricevuta di pagamento.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Banca c/c (o Cassa) | — | Importo incassato | Entrata finanziaria |
| — | Crediti verso clienti | Importo incassato | Estinzione credito commerciale |

**Note:** In caso di pagamento parziale, il credito residuo rimane iscritto. Se il cliente ha applicato una ritenuta d'acconto, occorre rilevare separatamente il credito per ritenuta subita.

---

## 3b. Pagamento a fornitore

**Momento:** uscita bancaria o emissione assegno/bonifico.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Debiti verso fornitori | — | Importo pagato | Estinzione debito commerciale |
| — | Banca c/c (o Cassa) | Importo pagato | Uscita finanziaria |

---

## 4. Ammortamento delle immobilizzazioni

**Momento:** fine esercizio (o fine periodo di riferimento). Quota calcolata secondo i criteri OIC 16 (immobilizzazioni materiali) o OIC 24 (immobilizzazioni immateriali).

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Quota ammortamento (costo per natura) | — | Quota di competenza | Ammortamento di esercizio ex OIC 16 |
| — | Fondo ammortamento | Quota di competenza | Rettifica indiretta del valore dell'immobilizzazione |

**Note:** Il fondo ammortamento è una rettifica del valore dell'immobilizzazione (iscrizione nello SP in detrazione dal costo storico). L'aliquota di ammortamento deve essere economicamente giustificata in base alla vita utile stimata (OIC 16 § 62). Le aliquote fiscali previste dal DM 31 dicembre 1988 (TUIR art. 102) non coincidono necessariamente con quelle civilistiche.

---

## 5. Accantonamento TFR (quota annuale)

**Momento:** fine esercizio (o fine periodo di paga per accantonamenti mensili).

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Quota TFR (costo del personale — CE B.9.c) | — | Quota maturata | Costo di competenza |
| — | Fondo TFR | Quota maturata | Debito maturato verso i dipendenti |

**Calcolo della quota annuale di TFR (ante-riforma 2007 per aziende sotto 50 dipendenti):**

```
Quota TFR = Retribuzione annua utile / 13,5
```

La retribuzione utile comprende tutte le voci continuative (paga base, contingenza, eventuali superminimi), con esclusione delle voci variabili non continuative. Il fondo è rivalutato al 31 dicembre di ogni anno applicando il coefficiente: 1,5% fisso + 75% dell'indice ISTAT dei prezzi al consumo (ex art. 2120 c.c.).

**Note:** Per le aziende con più di 50 dipendenti, le quote maturate dopo il 1° gennaio 2007 confluiscono all'INPS (Fondo Tesoreria) o in forme pensionistiche complementari, e il relativo debito è verso INPS anziché verso il fondo aziendale.

---

## 6. Rateo passivo

**Momento:** fine periodo (mese, trimestre, anno).

**Definizione OIC 18 § 5:** i ratei passivi rappresentano quote di costi di competenza dell'esercizio in corso, la cui manifestazione finanziaria avverrà in esercizi successivi.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Costo di competenza (per natura) | — | Quota di competenza | Costo maturato senza documento |
| — | Ratei passivi | Quota di competenza | Debito maturato da liquidare in futuro |

**Formula:**

```
Quota rateo = Importo totale × (Giorni di competenza dell'esercizio / Giorni totali del contratto)
```

**Esempio:** canone semestrale di affitto da pagare il 31 marzo dell'anno successivo pari a 6.000 €. Al 31 dicembre si iscrive un rateo passivo di 4.000 € (4 mesi su 6).

---

## 7. Risconto attivo

**Momento:** fine periodo.

**Definizione OIC 18 § 5:** i risconti attivi rappresentano quote di costi già sostenuti nell'esercizio in corso, ma di competenza di esercizi futuri.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Risconti attivi | — | Quota non di competenza | Rinvio del costo al futuro |
| — | Costo (per natura) | Quota non di competenza | Storno quota non di competenza |

**Formula:**

```
Quota risconto = Costo già pagato × (Giorni non di competenza / Giorni totali del contratto)
```

**Esempio:** polizza assicurativa annuale pagata il 1° luglio per 12.000 €. Al 31 dicembre si iscrive un risconto attivo di 6.000 € (6 mesi non ancora di competenza).

---

## 8. Fattura da ricevere (costo di competenza senza documento)

**Momento:** fine esercizio, quando il costo è di competenza ma la fattura del fornitore non è ancora pervenuta.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Costo (per natura) | — | Importo stimato | Costo di competenza senza fattura |
| — | Fatture da ricevere | Importo stimato | Debito stimato verso fornitore |

**Note:** L'importo è una stima basata su contratti, ordini, consuntivi o comunicazioni del fornitore. Quando perviene la fattura nell'esercizio successivo, si storna la voce "Fatture da ricevere" e si registra il debito definitivo verso il fornitore, rilevando l'eventuale scarto tra stima e importo effettivo.

---

## 9. Accantonamento a fondo rischi e oneri

**Momento:** fine esercizio, al sorgere di un'obbligazione implicita o esplicita che soddisfa i requisiti OIC 31 § 14.

**Condizioni per l'accantonamento (OIC 31 § 14):**
1. Esiste un'obbligazione attuale (legale o implicita) verso terzi.
2. L'esborso futuro è probabile.
3. L'importo può essere stimato in modo attendibile.

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Accantonamento per rischi (CE B.13 o B.12) | — | Importo stimato | Rilevazione onere probabile |
| — | Fondo rischi e oneri | Importo stimato | Passività stimata iscritta a SP |

**Note:** Il fondo deve essere utilizzato solo per gli oneri per cui è stato costituito (OIC 31 § 20). Non è consentito iscrivere fondi per perdite future o rischi generici non specificati.

---

## 10. Rilevazione IRES e IRAP (imposte di competenza)

**Momento:** fine esercizio, in sede di assestamento. Le imposte correnti, anticipate e differite sono disciplinate da OIC 25.

### 10a. Imposte correnti (IRES e IRAP dell'esercizio)

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Imposte correnti — IRES (CE 20) | — | IRES calcolata | Imposta di competenza |
| Imposte correnti — IRAP (CE 20) | — | IRAP calcolata | Imposta di competenza |
| — | Debiti tributari — IRES | IRES calcolata | Debito verso Erario |
| — | Debiti tributari — IRAP | IRAP calcolata | Debito verso Erario |

### 10b. Imposte anticipate (differenze temporanee deducibili in futuro)

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Imposte anticipate (SP Attivo CII.5-ter) | — | Differenza × aliquota IRES | Beneficio fiscale futuro |
| — | Imposte anticipate — CE (voce 20) | Differenza × aliquota IRES | Riduzione imposte di competenza |

### 10c. Imposte differite (differenze temporanee imponibili in futuro)

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Imposte differite — CE (voce 20) | — | Differenza × aliquota IRES | Maggiori imposte future |
| — | Fondo imposte differite (SP Passivo B.2) | Differenza × aliquota IRES | Passività fiscale differita |

**Note:** L'iscrizione delle imposte anticipate è subordinata alla ragionevole certezza del loro recupero (OIC 25 § 44), ossia alla previsione di redditi imponibili futuri sufficienti ad assorbirle.
