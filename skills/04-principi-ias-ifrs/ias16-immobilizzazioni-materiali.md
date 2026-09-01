---
name: IAS 16 — Immobilizzazioni Materiali
description: Applicazione dello standard IAS 16 per la rilevazione e valutazione delle immobilizzazioni materiali nei bilanci IAS/IFRS. Confronto con OIC 16.
area: Principi IAS/IFRS
fonti:
  - "IAS 16 — Property, Plant and Equipment (IAS Binder 2025)"
  - "OIC 16 — Immobilizzazioni materiali (marzo 2024) [confronto]"
  - "D.Lgs. 28 febbraio 2005, n. 38 (adozione IAS in Italia)"
conflitti_noti: "IAS 16 prevede modello di rivalutazione (revaluation model) non consentito dall'OIC 16 per bilanci ordinari; IAS 16 obbliga separazione terreno/fabbricato."
aggiornamento: "2025"
---

# IAS 16 — Immobilizzazioni Materiali

## Ambito di applicazione

IAS 16 si applica a tutti i **beni materiali tangibili** (Property, Plant and Equipment — PP&E) detenuti per:
- uso nella produzione o fornitura di beni/servizi
- locazione a terzi
- scopi amministrativi

e per i quali si prevede un utilizzo superiore a un esercizio.

> **Esclusioni:** attività biologiche (IAS 41), beni minerari (IFRS 6), investimenti immobiliari (IAS 40).

---

## Rilevazione iniziale

Un'immobilizzazione materiale è rilevata quando:
1. è probabile che affluiranno benefici economici futuri
2. il costo può essere misurato attendibilmente

**Costo iniziale** include: prezzo di acquisto, dazi, imposte non recuperabili, costi direttamente attribuibili per portare il bene nella condizione e ubicazione d'uso, stima iniziale dei costi di smantellamento (IAS 16 § 16).

---

## Due modelli di valutazione successiva

### 1. Cost Model (Modello del costo)

```
Valore contabile = Costo storico
                 − Ammortamenti accumulati
                 − Perdite durevoli di valore accumulate (IAS 36)
```

Modello prevalente nella pratica; identico nella logica all'OIC 16.

### 2. Revaluation Model (Modello della rivalutazione)

```
Valore contabile = Fair value alla data di rivalutazione
                 − Ammortamenti accumulati successivi
                 − Perdite durevoli successive
```

- La rivalutazione deve essere effettuata con **sufficiente regolarità** per garantire che il valore contabile non differisca materialmente dal fair value
- L'utile da rivalutazione è rilevato in **OCI (Other Comprehensive Income)** e accumulato in una **riserva di rivalutazione** nel patrimonio netto
- Se la rivalutazione comporta un decremento, la perdita è imputata al **conto economico** (salvo capienza della riserva pregressa)

> **Divergenza IAS/OIC — FONTE PREVALENTE:**
> - Bilanci IAS/IFRS: il Revaluation Model è consentito (IAS 16 § 31)
> - Bilanci OIC (ordinari italiani): la rivalutazione non è consentita salvo leggi speciali di rivalutazione fiscale (es. L. 342/2000, art. 110 TUIR). La **fonte prevalente per bilanci ordinari italiani è OIC 16**, che non prevede il revaluation model in via ordinaria.

---

## Component Approach — Separazione dei componenti (IAS 16 § 43)

IAS 16 richiede che ogni componente di un'immobilizzazione con **vita utile significativamente diversa** sia ammortizzata separatamente.

**Esempio pratico:**
- Aeromobile: cellula (20 anni), motori (15 anni), interni (8 anni) → tre piani di ammortamento separati
- Fabbricato: struttura (50 anni), impianti (15 anni), finiture (10 anni)

**Separazione terreno/fabbricato (IAS 16 § 58):** obbligatoria, in quanto i terreni hanno vita utile indefinita e non sono ammortizzabili.

> **OIC 16** non richiede il component approach in modo sistematico, ma consente la separazione per componenti significative.

---

## Ammortamento (IAS 16 §§ 50-62)

- Inizia quando il bene è disponibile per l'uso
- Metodi ammessi: a quote costanti, a quote decrescenti, basato sulle unità prodotte
- La **vita utile** e il **valore residuo** vanno rivisti almeno a ogni fine esercizio
- L'ammortamento non si sospende quando il bene è inutilizzato (salvo metodo unità prodotte)

---

## Leasing e IFRS 16

Dal 1° gennaio 2019, **IFRS 16** ha sostituito IAS 17, eliminando la distinzione tra leasing operativo e finanziario per i **locatari**.

### Modello IFRS 16 per il locatario

- Tutti i contratti di leasing con durata > 12 mesi e per beni > soglia di materialità vanno capitalizzati
- Si iscrivono:
  - **Right-of-Use (ROU) asset** → ammortizzato sulla durata del leasing
  - **Lease liability** → attualizzata al tasso incrementale del finanziamento del locatario
- Effetto sul conto economico: **ammortamento del ROU** + **interessi passivi sulla liability** (in luogo del semplice canone)

### Impatto sui KPI finanziari da IFRS 16

| KPI | Effetto IFRS 16 vs metodo patrimoniale |
|---|---|
| EBITDA | Migliora (i canoni escono dall'EBITDA) |
| EBIT | Neutro o lieve peggioramento (ammortamento ROU vs canone) |
| Utile netto | Può peggiorare nei primi esercizi (interessi > quota interessi canone) |
| NFP | Aumenta significativamente (lease liability) |

> **Divergenza critica IAS/OIC:**
> - **IFRS 16** (bilanci IAS): capitalizzazione obbligatoria di tutti i leasing rilevanti
> - **OIC 16** (bilanci ordinari): leasing operativo → canoni iscritti a CE (metodo patrimoniale). La **fonte prevalente per bilanci ordinari italiani è OIC 16**; per bilanci consolidati di gruppi quotati è **IFRS 16** (obbligatorio).

---

## Impairment — Perdite durevoli di valore

Quando esistono indicatori di perdita di valore, si applica il test di impairment secondo **IAS 36** (vedi skill dedicata `ias36-riduzione-valore-impairment.md`).

---

## Derecognition (eliminazione contabile)

Un'immobilizzazione materiale è eliminata quando:
- è ceduta, oppure
- non si attendono più benefici economici futuri dall'uso o dalla dismissione

Il **risultato da dismissione** (utile o perdita) è la differenza tra provento netto di dismissione e valore contabile, rilevato a conto economico.

---

## Confronto sintetico IAS 16 vs OIC 16

| Aspetto | IAS 16 | OIC 16 |
|---|---|---|
| Modello di valutazione | Cost model o Revaluation model | Solo costo storico (rivalutazione solo per legge) |
| Component approach | Obbligatorio per componenti significative | Facoltativo |
| Separazione terreno/fabbricato | Obbligatoria | Raccomandata ma non sempre applicata |
| Leasing (locatario) | IFRS 16: capitalizzazione obbligatoria | Metodo patrimoniale (canone a CE) |
| Revisione vita utile e valore residuo | Almeno annuale | Almeno a ogni chiusura se vi sono indicatori |
