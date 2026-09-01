---
name: Scritture di Assestamento
description: Procedure e scritture contabili per le operazioni di assestamento di fine periodo. Copertura completa di ratei, risconti, fatture da emettere e ricevere, accantonamenti a fondi per rischi e oneri, TFR e imposte. Riferimento a OIC 11 (competenza), OIC 18 (ratei e risconti), OIC 31 (fondi).
area: Contabilità Generale
fonti:
  - "OIC 11 — Finalità e postulati del bilancio d'esercizio, § 30 (marzo 2024)"
  - "OIC 18 — Ratei e risconti (maggio 2022)"
  - "OIC 31 — Fondi per rischi e oneri e Trattamento di Fine Rapporto (marzo 2024)"
  - "OIC 25 — Imposte sul reddito (marzo 2024)"
  - "Codice Civile artt. 2423-bis, 2424, 2425 (agg. novembre 2024)"
aggiornamento: "2024-03"
---

# Scritture di Assestamento

## Definizione e fondamento normativo

Le **scritture di assestamento** (o scritture di rettifica e integrazione) sono le registrazioni contabili effettuate al termine di un periodo contabile (mese, trimestre, anno) per adeguare i saldi dei conti al principio di competenza economica.

**OIC 11 § 30** stabilisce che i ricavi e i costi devono essere imputati all'esercizio di competenza, indipendentemente dalla data di incasso o di pagamento. Il principio di competenza economica (matching principle) richiede che i costi siano correlati ai ricavi dell'esercizio cui si riferiscono.

**Art. 2423-bis, comma 1, n. 3, c.c.:** si deve tener conto dei proventi e degli oneri di competenza dell'esercizio, indipendentemente dalla data dell'incasso o del pagamento.

Le scritture di assestamento si suddividono in:
- **Scritture di rettifica:** eliminano costi/ricavi non di competenza già rilevati (risconti).
- **Scritture di integrazione:** aggiungono costi/ricavi di competenza non ancora rilevati (ratei, fatture da emettere/ricevere, accantonamenti).

---

## 1. Ratei attivi

### Definizione OIC 18

**OIC 18 § 5:** i ratei attivi sono quote di ricavi di competenza dell'esercizio in corso, ma la cui manifestazione finanziaria avverrà in esercizi futuri. Si tratta di ricavi già maturati economicamente ma non ancora incassati né documentati da fattura.

**Classificazione SP:** i ratei attivi si iscrivono nell'Attivo Circolante alla voce **D — Ratei e risconti** (art. 2424 c.c.).

### Formula di calcolo

```
Rateo attivo = Importo totale del contratto × (Giorni di competenza dell'esercizio in corso / Giorni totali del contratto)
```

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Ratei attivi (SP — D) | — | Quota di competenza | Maturazione ricavo senza documento |
| — | Ricavo (per natura) | Quota di competenza | Ricavo di competenza dell'esercizio |

### Esempio

Contratto di locazione attiva: canone semestrale (gennaio–giugno) da incassare al 30 giugno, pari a 12.000 €. Alla chiusura del 31 dicembre dell'anno precedente, il rateo attivo da rilevare è:

```
12.000 × (1/6) = 2.000 € (solo il mese di dicembre è di competenza dell'anno in corso)
```

Nell'esercizio successivo, la scrittura viene stornata all'1 gennaio con scrittura inversa, e il ricavo definitivo è rilevato all'incasso/fatturazione.

---

## 2. Ratei passivi

### Definizione OIC 18

**OIC 18 § 5:** i ratei passivi sono quote di costi di competenza dell'esercizio in corso, ma la cui manifestazione finanziaria avverrà in esercizi futuri.

**Classificazione SP:** i ratei passivi si iscrivono nel Passivo alla voce **E — Ratei e risconti** (art. 2424 c.c.).

### Formula di calcolo

```
Rateo passivo = Importo totale del contratto × (Giorni di competenza dell'esercizio in corso / Giorni totali del contratto)
```

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Costo (per natura) | — | Quota di competenza | Costo maturato senza documento |
| — | Ratei passivi (SP — E) | Quota di competenza | Debito maturato, manifestazione futura |

### Esempio

Mutuo bancario: interesse semestrale (luglio–dicembre) da pagare il 31 gennaio dell'anno successivo, pari a 3.000 €. Alla chiusura del 31 dicembre, il rateo passivo da rilevare è:

```
3.000 × (6/6) = 3.000 € (tutti i 6 mesi sono di competenza dell'anno in corso)
```

---

## 3. Risconti attivi

### Definizione OIC 18

**OIC 18 § 5:** i risconti attivi sono quote di costi già sostenuti nell'esercizio, ma di competenza di esercizi futuri. Rappresentano la rettifica di costi anticipati.

**Classificazione SP:** i risconti attivi si iscrivono nell'Attivo alla voce **D — Ratei e risconti** (art. 2424 c.c.).

### Formula di calcolo

```
Risconto attivo = Costo già pagato × (Giorni di competenza futura / Giorni totali del contratto)
```

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Risconti attivi (SP — D) | — | Quota non di competenza | Rinvio costo a esercizi futuri |
| — | Costo (per natura) | Quota non di competenza | Storno quota non di competenza |

### Esempio

Polizza assicurativa annuale (1° ottobre – 30 settembre): premio pagato il 1° ottobre per 4.800 €. Alla chiusura del 31 dicembre, il risconto attivo è:

```
4.800 × (9/12) = 3.600 € (i 9 mesi da gennaio a settembre sono competenza dell'anno futuro)
```

---

## 4. Risconti passivi

### Definizione OIC 18

**OIC 18 § 5:** i risconti passivi sono quote di ricavi già incassati o rilevati nell'esercizio, ma di competenza di esercizi futuri.

**Classificazione SP:** i risconti passivi si iscrivono nel Passivo alla voce **E — Ratei e risconti** (art. 2424 c.c.).

### Formula di calcolo

```
Risconto passivo = Ricavo già rilevato × (Giorni di competenza futura / Giorni totali del contratto)
```

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Ricavo (per natura) | — | Quota non di competenza | Storno quota non di competenza |
| — | Risconti passivi (SP — E) | Quota non di competenza | Rinvio ricavo a esercizi futuri |

---

## 5. Fatture da emettere

**Definizione:** ricavi di competenza dell'esercizio per i quali non è ancora stata emessa fattura (il ciclo attivo non è ancora documentato).

**Momento di rilevazione:** quando il fatto gestionale generatore del ricavo si è già verificato (es. consegna merce, completamento del servizio) ma la fattura non è ancora stata emessa.

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Fatture da emettere (SP — Crediti) | — | Importo stimato + IVA | Credito commerciale stimato |
| — | Ricavi di vendita | Importo imponibile | Ricavo di competenza |
| — | IVA a debito (se applicabile) | IVA stimata | Debito IVA stimato |

**Nota:** l'IVA si rileva solo se il presupposto impositivo si è già verificato (effettuazione dell'operazione ex art. 6 DPR 633/1972). Nell'anno successivo, all'emissione della fattura, si storna il conto "Fatture da emettere" e si iscrive il credito definitivo verso il cliente.

---

## 6. Fatture da ricevere

**Definizione:** costi di competenza dell'esercizio per i quali non è ancora pervenuta la fattura del fornitore.

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Costo (per natura) | — | Importo stimato | Costo di competenza senza documento |
| IVA a credito (se detraibile e applicabile) | — | IVA stimata | Credito IVA stimato |
| — | Fatture da ricevere (SP — Debiti) | Importo stimato | Debito stimato verso fornitore |

**Nota:** l'IVA sulle fatture da ricevere è detraibile solo quando la fattura viene ricevuta e registrata nel registro acquisti, non in sede di stima. La rilevazione dell'IVA in sede di assestamento è pertanto da evitare o da trattare come debito stimato. All'arrivo della fattura nell'esercizio successivo, si storna il conto "Fatture da ricevere" e si rileva il debito definitivo.

---

## 7. Accantonamenti a fondi per rischi e oneri

### Condizioni per l'accantonamento (OIC 31 § 14)

Un fondo per rischi e oneri si costituisce quando si verificano congiuntamente le seguenti condizioni:

1. **Obbligazione attuale:** esiste un'obbligazione legale o implicita verso terzi, originata da un evento già accaduto.
2. **Probabilità di esborso:** è probabile che per adempiere all'obbligazione sarà necessario un esborso di risorse economiche.
3. **Stima attendibile:** l'importo dell'obbligazione può essere stimato in modo ragionevolmente attendibile.

Se una delle tre condizioni non è soddisfatta, non si può iscrivere un fondo; si dà eventuale informativa in nota integrativa come passività potenziale (OIC 31 § 18).

### Scrittura contabile

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Accantonamento per rischi (CE — B.13 o voce specifica) | — | Importo stimato | Rilevazione onere probabile |
| — | Fondo rischi e oneri (SP — B.3 o B.2) | Importo stimato | Passività potenziale iscritta |

**Utilizzo del fondo:** quando si manifesta l'esborso effettivo, il fondo viene utilizzato:

| DARE | AVERE | Importo | Causale |
|------|-------|---------|---------|
| Fondo rischi e oneri | — | Importo utilizzato | Utilizzo del fondo |
| — | Debiti / Banca | Importo effettivo | Esborso effettivo |

Se l'esborso effettivo eccede il fondo, la differenza è rilevata come costo di periodo. Se il fondo risulta esuberante, si effettua una ripresa a CE (provento straordinario o ordinario per rilascio fondo).

---

## 8. Checklist di fine periodo

Utilizzare questa lista prima di chiudere ogni periodo contabile (mensile, trimestrale, annuale):

### Ratei e risconti
- [ ] Verificare tutti i contratti pluriennali in corso (affitti, leasing, assicurazioni, abbonamenti, mutui, prestiti) e calcolare i ratei/risconti di competenza.
- [ ] Controllare che i ratei e risconti dell'esercizio precedente siano stati correttamente stornati a inizio periodo.

### Fatture da emettere
- [ ] Verificare le consegne di merce o prestazioni di servizi completate entro la data di chiusura per le quali non è ancora stata emessa fattura.
- [ ] Stimare l'importo e rilevare il credito commerciale.

### Fatture da ricevere
- [ ] Verificare i DDT di ricevimento merce senza fattura, le prestazioni di servizi ricevute senza documento, i contratti a consuntivo non ancora liquidati.
- [ ] Confrontare con il registro degli ordini aperti e le conferme dei fornitori.

### Ammortamenti
- [ ] Calcolare le quote di ammortamento di tutte le immobilizzazioni materiali e immateriali di competenza del periodo.
- [ ] Verificare eventuali dismissioni o vendite di cespiti avvenute nel periodo.
- [ ] Controllare che non vi siano cespiti completamente ammortizzati per i quali si continuano ad addebitare quote.

### TFR
- [ ] Calcolare la quota TFR maturata nel periodo per tutti i dipendenti in forza.
- [ ] Rivalutare il fondo TFR per i dipendenti che non hanno optato per la previdenza complementare (coefficiente ex art. 2120 c.c.).

### Fondi rischi e oneri
- [ ] Verificare l'esistenza di nuove obbligazioni probabili (contenziosi legali, garanzie prestate, penali contrattuali, controversie fiscali).
- [ ] Aggiornare la stima dei fondi esistenti in base alle informazioni più recenti.
- [ ] Verificare se fondi esistenti sono ancora necessari o se possono essere rilasciati.

### Imposte
- [ ] Calcolare la stima delle imposte IRES e IRAP correnti di competenza del periodo.
- [ ] Verificare eventuali differenze temporanee deducibili/imponibili che generano imposte anticipate/differite (OIC 25).
- [ ] Aggiornare il calcolo delle imposte anticipate in base alla previsione di redditi futuri.

### Verifiche finali
- [ ] Riconciliare i saldi bancari con gli estratti conto.
- [ ] Verificare che i crediti IVA/debiti IVA siano coerenti con le liquidazioni periodiche.
- [ ] Controllare la quadratura del bilancio di verifica (totale dare = totale avere).
- [ ] Verificare che nessun conto di assestamento dell'esercizio precedente abbia saldo residuo anomalo.
