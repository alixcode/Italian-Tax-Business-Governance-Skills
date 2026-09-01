---
name: IAS 36 — Riduzione Durevole di Valore (Impairment)
description: Test di impairment secondo IAS 36 per immobilizzazioni materiali, immateriali, avviamento e partecipazioni. Confronto con OIC 9 e OIC 24.
area: Principi IAS/IFRS
fonti:
  - "IAS 36 — Impairment of Assets (IAS Binder 2025)"
  - "OIC 9 — Svalutazioni per perdite durevoli di valore delle immobilizzazioni materiali e immateriali (maggio 2022) [confronto]"
  - "OIC 24 — Immobilizzazioni immateriali (marzo 2024) [confronto — avviamento]"
conflitti_noti: "IAS 36 vieta l'ammortamento sistematico dell'avviamento e impone impairment test annuale obbligatorio; OIC 24 prevede invece ammortamento sistematico max 20 anni senza impairment test annuale obbligatorio."
aggiornamento: "2025"
---

# IAS 36 — Riduzione Durevole di Valore (Impairment)

## Ambito di applicazione

IAS 36 si applica a:
- Immobilizzazioni **materiali** (IAS 16)
- Immobilizzazioni **immateriali** (IAS 38), incluso l'avviamento
- **Partecipazioni** in controllate, collegate e joint venture (valutate con il metodo del patrimonio netto nei bilanci separati)
- Investimenti immobiliari valutati al costo (IAS 40)

> **Esclusioni principali:** rimanenze (IAS 2), attività finanziarie (IFRS 9), attività fiscali differite (IAS 12), attività biologiche (IAS 41).

---

## Identificazione degli indicatori di impairment (IAS 36 § 12)

L'entità deve valutare ad ogni data di riferimento del bilancio se esistono indicatori di perdita di valore.

### Indicatori esterni
- Significativa diminuzione del valore di mercato dell'attività
- Cambiamenti negativi nell'ambiente tecnologico, di mercato, economico o normativo
- Aumento dei tassi di interesse o di mercato che influisce sul tasso di attualizzazione
- Valore di mercato della società inferiore al valore contabile del patrimonio netto

### Indicatori interni
- Obsolescenza o danno fisico dell'attività
- Significativi cambiamenti nell'uso dell'attività (ristrutturazione, dismissione pianificata)
- Peggioramento delle performance economiche attese
- Flussi di cassa effettivi inferiori a quelli previsti

> **Avviamento, immateriali a vita utile indefinita, immateriali non ancora disponibili per l'uso:** impairment test **annuale obbligatorio**, indipendentemente dalla presenza di indicatori (IAS 36 § 10).

---

## Valore recuperabile (IAS 36 § 18)

```
Valore recuperabile = MAX(Fair Value meno costi di vendita; Valore d'uso)
```

Si calcola il maggiore tra:

### Fair Value meno costi di vendita (FVLCTS)
Importo ottenibile dalla vendita dell'attività in una transazione tra parti consapevoli e disponibili, al netto dei costi di dismissione.
- Gerarchia: prezzo di mercato attivo → transazioni recenti simili → tecniche di valutazione

### Valore d'uso (Value in Use)
Valore attuale dei flussi di cassa futuri stimati dall'utilizzo continuato dell'attività e dalla sua dismissione finale.

```
Valore d'uso = Σ [FCt / (1 + r)^t] + Valore terminale / (1 + r)^n
```

- **FCt**: flussi di cassa futuri stimati (pre-imposte)
- **r**: tasso di attualizzazione pre-imposte che riflette il rischio specifico dell'attività
- Le proiezioni si basano su budget/previsioni ragionevoli (IAS 36 § 33); oltre 5 anni, tasso di crescita stabile o decrescente

---

## Cash Generating Unit (CGU) — Unità Generatrice di Flussi (IAS 36 § 65)

Se non è possibile stimare il valore recuperabile del **singolo asset** (perché genera flussi di cassa non indipendenti), l'impairment test è condotto a livello di **CGU**: il gruppo più piccolo di attività che genera flussi di cassa indipendenti.

- La perdita di valore della CGU è ripartita tra le attività della CGU proporzionalmente al loro valore contabile
- L'avviamento è allocato alle CGU o gruppi di CGU che beneficiano delle sinergie dell'aggregazione

---

## Avviamento — Impairment test obbligatorio annuale (IAS 36 § 96)

L'avviamento acquisito in una business combination deve essere:
1. Allocato alle CGU beneficiarie delle sinergie
2. Sottoposto ad **impairment test almeno annualmente**, anche in assenza di indicatori di perdita

### Procedura
1. Determinare il valore recuperabile della CGU (incluso avviamento)
2. Confrontare con il valore contabile della CGU (incluso avviamento)
3. Se valore recuperabile < valore contabile → perdita da impairment
4. La perdita riduce prima l'avviamento allocato, poi le altre attività pro-quota

> **Divergenza critica IAS 36 / OIC 24 — FONTE PREVALENTE:**
>
> | Aspetto | IAS 36 (bilanci IAS/IFRS) | OIC 24 (bilanci ordinari italiani) |
> |---|---|---|
> | Avviamento | **Solo impairment test** — nessun ammortamento sistematico | **Ammortamento sistematico** (max 20 anni; in casi eccezionali motivati, max 20 anni) |
> | Cadenza del test | **Annuale obbligatoria** + ogni volta che vi siano indicatori | **Non obbligatorio annualmente**; svalutazione solo se perdita durevole manifesta |
> | Ripristino avviamento | **Non consentito** (IAS 36 § 124) | Non consentito (principio della prudenza) |
>
> La **fonte prevalente per bilanci ordinari italiani** è **OIC 24** (ammortamento sistematico).
> La **fonte prevalente per bilanci IAS/IFRS** è **IAS 36** (solo impairment, no ammortamento).

---

## Rilevazione della perdita da impairment

Se il valore recuperabile è inferiore al valore contabile:

```
Perdita da impairment = Valore contabile − Valore recuperabile
```

- Imputata a **conto economico** come costo
- Per attività rivalutate (Revaluation Model IAS 16/38): prima riduce la **riserva di rivalutazione** (OCI), poi il conto economico

---

## Ripristino di valore (IAS 36 §§ 109-125)

Consentito per tutte le attività **eccetto l'avviamento**, se vengono meno le condizioni che avevano determinato la svalutazione.

- Il ripristino non può superare il **valore contabile che si sarebbe avuto** se la perdita non fosse mai stata rilevata
- Imputato a conto economico (o OCI se l'attività era stata rivalutata)

> **OIC 9:** prevede anch'esso il ripristino di valore, con logica analoga.

---

## Confronto sintetico IAS 36 vs OIC 9

| Aspetto | IAS 36 | OIC 9 |
|---|---|---|
| Valore recuperabile | MAX(FVLCTS; Valore d'uso) | MAX(valore realizzabile; valore d'uso) — logica analoga |
| Valore d'uso | DCF con tasso specifico pre-imposte | DCF o stima ragionevole — meno formalizzato |
| CGU | Disciplinata in dettaglio | Concetto presente ma meno sviluppato |
| Avviamento | Solo impairment annuale | OIC 24: ammortamento (non OIC 9) |
| Ripristino | Consentito (non per avviamento) | Consentito |
