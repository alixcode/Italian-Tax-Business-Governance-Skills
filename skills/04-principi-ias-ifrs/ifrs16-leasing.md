---
name: IFRS 16 — Leasing
description: Trattamento contabile dei contratti di leasing secondo IFRS 16 (vigente dal 2019). Confronto con il metodo patrimoniale OIC 16 per i bilanci ordinari italiani.
area: Principi IAS/IFRS
fonti:
  - "IFRS 16 — Leases (IAS Binder 2025)"
  - "OIC 16 — Immobilizzazioni materiali (marzo 2024) [confronto — leasing operativo]"
  - "Art. 2427, n. 22, c.c. (disclosure metodo patrimoniale)"
conflitti_noti: "IFRS 16 elimina la distinzione leasing operativo/finanziario per i locatari e obbliga la capitalizzazione; OIC 16 mantiene il metodo patrimoniale per i bilanci ordinari (canoni a conto economico). Divergenza critica con impatto significativo su EBITDA, NFP e principali KPI finanziari."
aggiornamento: "2025"
---

# IFRS 16 — Leasing

## Contesto normativo

IFRS 16 è in vigore dal **1° gennaio 2019** e ha sostituito IAS 17, eliminando per i **locatari (lessee)** la distinzione tra leasing operativo e leasing finanziario.

> **Per i locatori (lessor):** IFRS 16 mantiene la distinzione tra leasing operativo e finanziario (analoga a IAS 17). Il trattamento per i locatori è rimasto sostanzialmente invariato.

---

## Identificazione di un contratto di leasing (IFRS 16 §§ 9-11)

Un contratto contiene un leasing se trasferisce il diritto di **controllare l'uso di un'attività identificata** per un periodo di tempo in cambio di un corrispettivo. Il controllo richiede:
1. Diritto di ottenere **sostanzialmente tutti i benefici economici** dall'uso dell'attività
2. Diritto di **dirigere l'uso** dell'attività (decidere come e per quali finalità)

---

## Modello contabile IFRS 16 per il locatario

### Rilevazione iniziale

Per ogni contratto di leasing (con durata > 12 mesi e per beni > soglia di materialità) il locatario rileva:

```
RIGHT-OF-USE (ROU) ASSET = Valore attuale dei pagamenti futuri
                          + Pagamenti anticipati
                          + Costi diretti iniziali
                          + Stima costi smantellamento

LEASE LIABILITY          = Valore attuale dei pagamenti futuri
                           (attualizzati al tasso implicito del leasing
                            o, se non determinabile, al tasso incrementale
                            del finanziamento del locatario)
```

### Rilevazione successiva

**ROU Asset:**
- Ammortizzato linearmente sulla durata del leasing (o sulla vita utile se si prevede il trasferimento della proprietà)
- Soggetto a impairment test (IAS 36)

**Lease Liability:**
- Aumenta per gli interessi maturati (interest unwind al tasso di attualizzazione)
- Diminuisce per i pagamenti effettuati

### Conto economico — Effetto IFRS 16

| Voce CE | IFRS 16 | Metodo patrimoniale (OIC/IAS 17 op.) |
|---|---|---|
| Ammortamento ROU asset | Sì (costo operativo) | No |
| Interessi passivi su lease liability | Sì (onere finanziario) | No |
| Canoni di locazione | No (esclusi) | Sì (integralmente) |

---

## Esenzioni previste da IFRS 16

Il locatario può scegliere di non applicare IFRS 16 per:
1. **Leasing a breve termine**: durata ≤ 12 mesi alla data di inizio
2. **Leasing di beni di valore unitario basso**: soglia indicativa ≈ USD 5.000 (es. laptop, telefoni, stampanti)

In questi casi, i canoni sono rilevati a conto economico linearmente.

---

## Impatto sui KPI finanziari

IFRS 16 modifica significativamente i principali indicatori finanziari rispetto al metodo patrimoniale:

| KPI | Effetto IFRS 16 | Spiegazione |
|---|---|---|
| **EBITDA** | Migliora (aumenta) | I canoni (che erano sotto l'EBITDA) escono dall'EBITDA e sono sostituiti da ammortamento + interessi, entrambi sotto l'EBITDA |
| **EBIT** | Sostanzialmente invariato o lieve peggioramento | Ammortamento ROU ≈ quota capitale del canone |
| **Utile netto** | Può peggiorare nei primi anni | Interessi passivi > quota interessi implicita nel canone (curva degli interessi decrescente) |
| **NFP (Posizione Finanziaria Netta)** | Aumenta significativamente | Lease liability inclusa nell'indebitamento |
| **Leverage / Debt-to-Equity** | Peggiora | Maggiore indebitamento iscritto |
| **ROA / ROE** | Impatto misto | Maggiori attività (ROU) e maggiore indebitamento |

---

## Divergenza critica IFRS 16 vs OIC 16 — Leasing operativo

> **Questa è una delle divergenze piu rilevanti tra bilanci IAS e bilanci OIC italiani.**

| Aspetto | IFRS 16 (bilanci IAS/IFRS) | OIC 16 — metodo patrimoniale (bilanci ordinari italiani) |
|---|---|---|
| Rilevazione | ROU asset + Lease liability in stato patrimoniale | Solo canoni a conto economico; nessuna iscrizione in SP |
| CE | Ammortamento + interessi passivi | Canoni di locazione (voce B.8 o B.14 del CE) |
| NFP | Lease liability inclusa | Nessun impatto sulla NFP |
| EBITDA | Migliora (canoni escono da CE operativo) | Invariato rispetto alla realtà economica |
| Disclosure | IFRS 16 §§ 51-60: maturity analysis, tasso, ecc. | Art. 2427, n. 22 c.c.: impegni finanziari per leasing |

**Fonte prevalente per bilanci ordinari italiani:** OIC 16 (metodo patrimoniale)

**Fonte prevalente per bilanci consolidati di gruppi quotati:** IFRS 16 (obbligatorio)

---

## Disclosure OIC per il metodo patrimoniale (art. 2427, n. 22 c.c.)

Per i bilanci redatti con il metodo patrimoniale (OIC), la nota integrativa deve indicare (art. 2427, n. 22 c.c.):
- Impegni non risultanti dallo stato patrimoniale relativi a leasing operativi
- Effetti sul patrimonio netto e sul risultato dell'esercizio qualora i contratti fossero stati trattati come leasing finanziari (informativa comparativa con il metodo finanziario)

> Questa disclosure consente agli analisti di "normalizzare" i bilanci OIC per confrontarli con bilanci IFRS 16.

---

## Trattamento per il locatore (lessor) — IFRS 16

Il locatore continua a classificare i contratti come:

**Leasing finanziario:** sostanzialmente tutti i rischi e benefici sono trasferiti al locatario
- Rilevato come credito finanziario (receivable) pari al valore attuale dei canoni futuri
- Il canone è suddiviso tra quota capitale (riduzione del credito) e quota interessi (ricavo finanziario)

**Leasing operativo:** tutti gli altri contratti
- Il bene rimane in stato patrimoniale del locatore
- I canoni sono rilevati a conto economico linearmente

---

## Interazione con la fiscalità italiana

> Il trattamento fiscale del leasing in Italia (art. 102, c. 7 TUIR) non è allineato automaticamente con IFRS 16. I soggetti IAS/IFRS adottanti applicano le regole fiscali specifiche per i soggetti IAS (D.M. 1° aprile 2009 e successive modifiche). Verificare la normativa fiscale vigente per l'esercizio di riferimento.
