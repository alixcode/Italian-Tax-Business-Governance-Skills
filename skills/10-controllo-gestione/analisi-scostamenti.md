---
name: Analisi degli Scostamenti Budget / Consuntivo
description: Metodologia di variance analysis per PMI italiane: scomposizione degli scostamenti di ricavi (prezzo, volume, mix), costi variabili (prezzo, efficienza), costi fissi (spesa) e margini; budget flessibile, soglie di significatività, reporting e azioni correttive.
area: Controllo di Gestione
fonti:
  - "Codice Civile art. 2086, c. 2 — Assetti adeguati (agg. novembre 2024)"
  - "D.Lgs. 12 gennaio 2019, n. 14 (CCII), art. 3, c. 3 — Rilevazione tempestiva degli squilibri"
  - "Codice Civile art. 2381, c. 5 — Obblighi informativi degli organi delegati (almeno ogni 6 mesi)"
  - "OIC 13 — Rimanenze (marzo 2024): costi standard ammessi se approssimano il costo effettivo"
aggiornamento: "2026-10"
conflitti_noti: "I costi standard sono ammessi in bilancio solo se approssimano il costo effettivo (OIC 13; IAS 2 § 21): gli scostamenti di prezzo/efficienza significativi vanno riallocati alle rimanenze in sede di chiusura."
---

# Analisi degli Scostamenti Budget / Consuntivo

## 1. Finalità

L'analisi degli scostamenti confronta i valori **consuntivi** con quelli di **budget** (o di forecast) per:

- individuare **cause e responsabilità** delle differenze;
- distinguere gli effetti **esterni** (mercato, prezzi) da quelli **interni** (efficienza, mix);
- attivare **azioni correttive** tempestive, documentando l'esercizio della funzione di monitoraggio richiesta dagli assetti adeguati (art. 2086 c.c.; art. 3 CCII).

Gli organi delegati riferiscono al CdA e al collegio sindacale sul generale andamento della gestione e sulla sua prevedibile evoluzione **almeno ogni sei mesi** (art. 2381, c. 5 c.c.): l'analisi degli scostamenti ne è il supporto naturale.

---

## 2. Budget flessibile

Il confronto diretto consuntivo vs budget "statico" mescola effetti di volume ed efficienza. Si introduce il **budget flessibile**: budget ricalcolato ai **volumi effettivi** con prezzi e standard di budget.

```
Budget statico      = Volumi budget  × Standard budget
Budget flessibile   = Volumi effettivi × Standard budget
Consuntivo          = Volumi effettivi × Valori effettivi

Scostamento di volume      = Budget flessibile − Budget statico
Scostamento di efficienza/
prezzo (a volumi effettivi) = Consuntivo − Budget flessibile
```

Convenzione segni: **F** (favorevole) se migliora il risultato, **S** (sfavorevole) se lo peggiora.

---

## 3. Scostamenti dei ricavi

Con **P** = prezzo unitario, **Q** = quantità, pedice *b* = budget, *e* = effettivo.

| Scostamento | Formula |
|-------------|---------|
| Totale | Qe × Pe − Qb × Pb |
| **Prezzo** | (Pe − Pb) × Qe |
| **Volume** (totale) | (Qe − Qb) × Pb |

Con più prodotti lo scostamento di volume si scompone in:

| Componente | Formula |
|------------|---------|
| **Quantità (volume puro)** | (Qtot,e − Qtot,b) × Margine (o prezzo) medio di budget |
| **Mix** | Σ (Qi,e − Qtot,e × %mix i,b) × Margine unitario di budget i |

Per l'analisi della redditività è preferibile calcolare volume e mix sul **margine di contribuzione unitario** anziché sul prezzo.

### Esempio

| Prodotto | Qb | Pb | Qe | Pe |
|----------|----|----|----|----|
| A | 1.000 | 50 € | 1.100 | 48 € |

```
Scostamento prezzo  = (48 − 50) × 1.100 = −2.200 € (S)
Scostamento volume  = (1.100 − 1.000) × 50 = +5.000 € (F)
Scostamento totale  = 52.800 − 50.000 = +2.800 € (F)
```

---

## 4. Scostamenti dei costi variabili (costi standard)

Con **Ps** = prezzo standard del fattore, **Qs** = quantità standard per unità × produzione effettiva, **Pe/Qe** = valori effettivi.

| Scostamento | Formula | Responsabilità tipica |
|-------------|---------|-----------------------|
| **Prezzo** (materie, tariffa oraria) | (Pe − Ps) × Qe | Acquisti / HR |
| **Efficienza** (quantità, rese, tempi) | (Qe − Qs) × Ps | Produzione |
| **Volume** | (Produzione effettiva − Produzione budget) × costo standard unitario | Commerciale / Pianificazione |

### Esempio — materia prima

Standard: 2 kg/unità a 3,00 €/kg. Produzione effettiva 1.100 unità. Consumo effettivo 2.300 kg a 3,20 €/kg.

```
Qs = 2 × 1.100 = 2.200 kg
Scostamento prezzo     = (3,20 − 3,00) × 2.300 = 460 € (S)
Scostamento efficienza = (2.300 − 2.200) × 3,00 = 300 € (S)
Totale vs budget flessibile = 7.360 − 6.600 = 760 € (S)
```

---

## 5. Scostamenti dei costi fissi

| Scostamento | Formula | Significato |
|-------------|---------|-------------|
| **Di spesa (budget)** | Costi fissi effettivi − Costi fissi di budget | Maggiore/minore spesa rispetto all'autorizzato |
| **Di volume (assorbimento)** | (Produzione budget − Produzione effettiva) × quota fissa unitaria standard | Sotto/sovra-assorbimento dei costi fissi nel full costing |

Nelle PMI si raccomanda il **direct costing** per il reporting gestionale (margine di contribuzione), riservando il full costing alla valorizzazione delle rimanenze in bilancio (OIC 13, costo di produzione comprensivo dei costi indiretti di produzione).

---

## 6. Ponte del risultato (bridge EBITDA)

Rappresentazione a cascata consigliata per il reporting all'organo amministrativo:

```
EBITDA di budget
 ± Scostamento volume
 ± Scostamento mix
 ± Scostamento prezzi di vendita
 ± Scostamento prezzi d'acquisto
 ± Scostamento efficienza
 ± Scostamento costi fissi (spesa)
 ± Altri (one-off, non ricorrenti)
= EBITDA consuntivo
```

---

## 7. Soglie di significatività e processo

| Elemento | Prassi raccomandata |
|----------|---------------------|
| Soglia di analisi | Scostamenti > **5%** della voce **e** > importo minimo (es. 1% dell'EBITDA di budget) |
| Frequenza | Mensile (chiusura entro 10-15 giorni lavorativi), con forecast trimestrale |
| Commento | Per ogni scostamento significativo: causa, natura (temporanea/strutturale; controllabile/non controllabile), responsabile, azione, scadenza |
| Escalation | Scostamenti che impattano DSCR, covenant o cassa a 12 mesi → informativa immediata all'organo amministrativo e all'organo di controllo |

### Template di commento

| Voce | Budget | Consuntivo | Δ € | Δ % | Causa | Controllabile | Azione | Owner | Scadenza |
|------|--------|-----------|-----|-----|-------|---------------|--------|-------|----------|

---

## Note interpretative

- **Riallocazione a fine esercizio:** se il magazzino è valorizzato a costi standard, gli scostamenti significativi di prezzo ed efficienza vanno ripartiti tra rimanenze finali e costo del venduto, per rispettare il criterio del costo effettivo (OIC 13).
- **Inflazione e prezzi energia:** separare l'effetto prezzo dei fattori non controllabili (energia, materie quotate) dagli scostamenti gestionali, per una corretta attribuzione delle responsabilità.
- **Collegamento con gli indicatori della crisi:** uno scostamento sfavorevole persistente sui flussi di cassa deve riflettersi nell'aggiornamento del DSCR prospettico (vedi [`budget-annuale.md`](budget-annuale.md) e [`kpi-indici-bilancio.md`](kpi-indici-bilancio.md)).
