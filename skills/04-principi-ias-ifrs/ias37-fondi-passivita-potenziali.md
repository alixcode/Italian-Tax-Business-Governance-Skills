---
name: IAS 37 — Fondi, Passività e Attività Potenziali
description: Criteri di rilevazione, misurazione e disclosure di fondi rischi, passività potenziali e attività potenziali secondo IAS 37. Confronto con OIC 31.
area: Principi IAS/IFRS
fonti:
  - "IAS 37 — Provisions, Contingent Liabilities and Contingent Assets (IAS Binder 2025)"
  - "OIC 31 — Fondi per rischi e oneri e Trattamento di Fine Rapporto (marzo 2024) [confronto]"
conflitti_noti: "IAS 37 richiede l'attualizzazione della provision quando l'effetto finanziario del tempo è rilevante; OIC 31 non richiede l'attualizzazione salvo effetto significativo. Struttura del modello decisionale analoga ma con differenze applicative."
aggiornamento: "2025"
---

# IAS 37 — Fondi, Passività e Attività Potenziali

## Schema decisionale generale

```
Obbligazione attuale?
├── NO → Passività potenziale o nulla
└── SI → Esborso probabile?
          ├── NO (possibile) → Passività potenziale → solo disclosure
          ├── NO (remoto)   → Nessuna rilevazione né disclosure
          └── SI → Stima attendibile?
                    ├── NO → Passività potenziale → disclosure
                    └── SI → PROVISION (fondo) → rilevazione in bilancio
```

---

## Provision (Fondo rischi e oneri)

### Condizioni per la rilevazione (IAS 37 § 14)

Una provision è rilevata quando **tutte e tre** le seguenti condizioni sono soddisfatte:
1. **Obbligazione attuale** (legale o implicita) risultante da un evento passato
2. **Esborso probabile** di risorse che incorporano benefici economici per estinguere l'obbligazione
3. **Stima attendibile** dell'importo dell'obbligazione

> **"Probabile"** in IAS 37 = più probabile che no (> 50%). Soglia analoga a OIC 31.

### Misurazione — Best estimate (IAS 37 § 36)

```
Importo della provision = Valore atteso ponderato per probabilità
                         (expected value approach per popolazioni ampie)
                    oppure = Singola stima più probabile
                         (per obbligazioni singole)
```

- Per rischi con distribuzione continua: valore medio ponderato
- Considerare rischi e incertezze, ma non duplicare la prudenza

### Attualizzazione (IAS 37 § 45)

Se l'effetto finanziario del tempo è **rilevante**, la provision è attualizzata al tasso pre-imposte che riflette le valutazioni di mercato del valore temporale del denaro e i rischi specifici della passività.

```
Provision = Importo nominale / (1 + r)^n
```

- L'incremento del valore della provision nel tempo è rilevato come **onere finanziario** (interest unwind)

> **Divergenza IAS 37 / OIC 31 — ATTUALIZZAZIONE:**
> - **IAS 37**: attualizzazione **obbligatoria** quando l'effetto finanziario è rilevante (standard più rigido)
> - **OIC 31**: attualizzazione **non richiesta** salvo effetto significativo (approccio più flessibile)
>
> La **fonte prevalente per bilanci OIC** è **OIC 31**; per bilanci IAS/IFRS è **IAS 37**.

---

## Passività potenziale — Contingent Liability (IAS 37 § 27)

Una passività potenziale è:
- un'obbligazione **possibile** (ma non certa) risultante da eventi passati, da confermare da eventi futuri non interamente sotto il controllo dell'entità, **oppure**
- un'obbligazione attuale per cui l'esborso **non è probabile** o non può essere stimato attendibilmente

### Trattamento contabile

- **NON rilevata** in bilancio
- **Disclosure in Nota Integrativa** (IAS 37 § 86): natura della passività, stima dell'effetto finanziario, incertezze sull'importo o sulla tempistica, possibilità di rimborso

> Se la probabilità di esborso è **remota**, non è richiesta neanche la disclosure.

---

## Attività potenziale — Contingent Asset (IAS 37 § 31)

Un'attività potenziale è un'attività possibile risultante da eventi passati, la cui esistenza sarà confermata da eventi futuri non interamente sotto il controllo dell'entità.

### Trattamento contabile

| Probabilità | Trattamento |
|---|---|
| **Virtualmente certa** (≈ certezza) | Rilevazione come attività e ricavo in bilancio |
| **Probabile** (> 50%) | Solo **disclosure** in Nota Integrativa |
| **Possibile o remota** | Nessuna rilevazione né disclosure |

> Non si rilevano attività potenziali che potrebbero dar luogo a ricavi mai guadagnati (principio della prudenza applicato con cautela).

---

## Restructuring Provision (IAS 37 §§ 71-83)

Una provision per ristrutturazione è rilevata **solo** quando l'entità ha:
1. Un **piano formale dettagliato** di ristrutturazione che identifichi:
   - L'attività o la parte interessata
   - Le principali localizzazioni coinvolte
   - La funzione, il numero approssimativo e la remunerazione dei dipendenti interessati
   - I costi da sostenere
   - I tempi di implementazione
2. Ha **comunicato** tale piano alle parti interessate, creando un'aspettativa legittima che la ristrutturazione sarà attuata

### Costi inclusi nella provision di ristrutturazione
- Solo i costi **direttamente connessi** alla ristrutturazione (es. buonuscite, penali per rescissione contratti)
- **Esclusi**: costi di riqualificazione del personale rimasto, costi di marketing, investimenti in nuovi sistemi

---

## Contratti onerosi (IAS 37 § 66)

Un contratto è oneroso quando i costi inevitabili per adempierlo superano i benefici economici attesi.

```
Provision = MIN(costo per adempiere il contratto; penali per inadempimento)
```

Esempi: contratti di affitto di immobili inutilizzati, contratti di fornitura con prezzi fissi superiori al prezzo di mercato.

---

## Confronto sintetico IAS 37 vs OIC 31

| Aspetto | IAS 37 | OIC 31 |
|---|---|---|
| Soglia di rilevazione | Probabile (> 50%) + stima attendibile | Probabile + stima attendibile — logica analoga |
| Misurazione | Best estimate ponderata per probabilità | Miglior stima possibile |
| Attualizzazione | Obbligatoria se effetto rilevante | Non richiesta salvo effetto significativo |
| Restructuring | Condizioni stringenti (piano + comunicazione) | Condizioni simili |
| Contratti onerosi | Provision obbligatoria (IAS 37 § 66) | Fondi analoghi previsti |
| Disclosure passività potenziali | Dettagliata (IAS 37 § 86) | Prevista in NI (art. 2427 c.c.) |
| Fonte prevalente bilanci ordinari | — | OIC 31 |
| Fonte prevalente bilanci IAS/IFRS | IAS 37 | — |
