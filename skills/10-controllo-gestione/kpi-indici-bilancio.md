---
name: "KPI e Indici di Bilancio"
description: "Sistema di indicatori economico-finanziari per PMI italiane: redditività, struttura, liquidità, ciclo del circolante, indebitamento, sostenibilità del debito (DSCR) e indicatori di crisi ex art. 3 CCII; formule, interpretazione e raccordo con le voci degli artt. 2424-2425 c.c."
area: "Controllo di Gestione"
fonti:
  - "Codice Civile artt. 2424, 2425, 2428, c. 2 — Schemi e indicatori nella relazione sulla gestione (agg. novembre 2024)"
  - "D.Lgs. 12 gennaio 2019, n. 14 (CCII), art. 3 e art. 13 — Assetti, segnali di allarme, test pratico e lista di controllo"
  - "Decreto dirigenziale Ministero della Giustizia 21 marzo 2023 — Test pratico e lista di controllo per la composizione negoziata"
  - "CNDCEC — La relazione sulla gestione: indicatori finanziari e non finanziari (2009)"
  - "EBA/GL/2020/06 — Orientamenti in materia di concessione e monitoraggio dei prestiti (indicatori utilizzati dalle banche)"
aggiornamento: "2026-10"
conflitti_noti: "Gli indicatori calcolati su bilanci IAS/IFRS non sono direttamente confrontabili con quelli OIC: IFRS 16 aumenta EBITDA e PFN (debiti per leasing), IFRS 9 modifica la valutazione dei crediti. Esplicitare sempre la base contabile e, per confronti, rettificare l'effetto IFRS 16."
---

# KPI e Indici di Bilancio

## 1. Prerequisito: riclassificazione

Gli indici si calcolano su bilanci **riclassificati** (vedi [`reporting-direzionale.md`](reporting-direzionale.md)):

- **SP funzionale** → CIN, CCN operativo, PFN;
- **SP finanziario** → attivo/passivo correnti e consolidati;
- **CE a valore aggiunto** → EBITDA, EBIT.

Per i valori medi usare (inizio + fine periodo) / 2; per periodi infrannuali **annualizzare** i flussi (× 12 / mesi).

---

## 2. Redditività

| Indice | Formula | Lettura |
|--------|---------|---------|
| **ROE** | Utile netto / PN medio | Rendimento del capitale proprio; confronto con costo opportunità |
| **ROI** | EBIT / CIN medio | Redditività della gestione caratteristica |
| **ROS** | EBIT / Ricavi | Margine operativo per unità di ricavo |
| **Rotazione del capitale investito** | Ricavi / CIN medio | Efficienza nell'uso del capitale |
| **EBITDA margin** | EBITDA / Ricavi | Marginalità operativa prima di ammortamenti |
| **Incidenza oneri finanziari** | Oneri finanziari / Ricavi | Peso del debito sul conto economico |

**Scomposizione DuPont:**

```
ROI = ROS × Rotazione del capitale investito
ROE = ROI × (CIN / PN) × (Utile netto / EBIT)       [effetto leva e incidenza gestione non operativa]
```

---

## 3. Struttura patrimoniale e solidità

| Indice | Formula | Valori di riferimento (indicativi) |
|--------|---------|------------------------------------|
| **Margine primario di struttura** | PN − Immobilizzazioni | ≥ 0 auspicabile |
| **Quoziente primario di struttura** | PN / Immobilizzazioni | ≥ 1 ottimale; 0,7-1 accettabile |
| **Margine secondario di struttura** | (PN + Passività consolidate) − Immobilizzazioni | > 0 necessario |
| **Quoziente secondario di struttura** | (PN + Passività consolidate) / Immobilizzazioni | > 1 |
| **Indipendenza finanziaria** | PN / Totale attivo | > 30-35% buono |
| **Leverage** | Totale attivo / PN | Più alto = maggiore rischio |

---

## 4. Liquidità e solvibilità a breve

| Indice | Formula | Riferimento |
|--------|---------|-------------|
| **Current ratio** | Attivo corrente / Passività correnti | ≥ 1,2-1,5 |
| **Quick ratio (acid test)** | (Liquidità immediate + differite) / Passività correnti | ≥ 1 |
| **CCN finanziario** | Attivo corrente − Passività correnti | > 0 |

---

## 5. Ciclo del circolante

| Indice | Formula | Note |
|--------|---------|------|
| **DSO** (giorni crediti) | Crediti commerciali / Ricavi (IVA inclusa) × 365 | Includere fatture da emettere; escludere fondo svalutazione per il lordo |
| **DPO** (giorni debiti) | Debiti commerciali / (Acquisti + Servizi, IVA inclusa) × 365 | Confronto con termini D.Lgs. 231/2002 (60 gg tra imprese salvo deroghe) |
| **DIO** (giorni scorte) | Rimanenze / Costo del venduto × 365 | Per settore e categoria |
| **Ciclo di conversione di cassa** | DSO + DIO − DPO | Fabbisogno finanziario strutturale del circolante |

---

## 6. Indebitamento e sostenibilità del debito

| Indice | Formula | Riferimento prassi bancaria |
|--------|---------|------------------------------|
| **PFN / EBITDA** | PFN / EBITDA | < 3 buono; 3-5 attenzione; > 5 critico |
| **PFN / PN** | PFN / PN | < 1 buono; > 2-3 critico |
| **Interest coverage** | EBITDA (o EBIT) / Oneri finanziari | > 3-4 |
| **DSCR** | Flussi di cassa al servizio del debito / Servizio del debito (12 mesi) | ≥ 1 sostenibilità; ≥ 1,2 margine di sicurezza |
| **Debiti tributari e previdenziali / Attivo** | (Debiti tributari + previdenziali) / Totale attivo | Monitorare in particolare quelli scaduti |

Il **DSCR prospettico a 12 mesi** è l'indicatore cardine per verificare la sostenibilità dei debiti richiesta dall'art. 3, c. 3, lett. b CCII. Formula in [`budget-annuale.md`](budget-annuale.md).

---

## 7. Indicatori di crisi nel CCII

### 7.1 Assetto normativo vigente

Dopo il D.Lgs. 83/2022 il CCII **non prevede più gli "indici di allerta" CNDCEC** (sistema di allerta abrogato). Restano:

| Strumento | Norma | Contenuto |
|-----------|-------|-----------|
| Misure e assetti adeguati | Art. 3, cc. 1-3 | Rilevare squilibri patrimoniali, economico-finanziari; verificare la sostenibilità dei debiti e le prospettive di continuità almeno per i 12 mesi successivi; ricavare le informazioni per il test pratico |
| Segnali di allarme | Art. 3, c. 4 | Debiti scaduti verso dipendenti, fornitori, banche, creditori pubblici qualificati (vedi [`reporting-direzionale.md`](reporting-direzionale.md)) |
| Test pratico | Art. 13, c. 2 e D.D. 21/03/2023 | Verifica della ragionevole perseguibilità del risanamento |

### 7.2 Test pratico — logica di calcolo

```
Rapporto = Debito da ristrutturare / Flussi annui al servizio del debito

Debito da ristrutturare = Debito scaduto + debito riscadenzato/oggetto di moratoria
                          + rate di mutui e finanziamenti in scadenza nei successivi 2 anni
                          − liquidità e risorse ricavabili da dismissioni/apporti
Flussi annui = MOL prospettico normalizzato − investimenti di mantenimento − imposte
```

| Esito | Indicazione |
|-------|-------------|
| Rapporto ≤ 1 | Difficoltà contenute; risanamento perseguibile con iniziative ordinarie |
| Rapporto > 1 e ≤ 2 | Risanamento perseguibile con iniziative industriali e negoziazione |
| Rapporto > 2 e ≤ 3 | Necessarie iniziative industriali incisive, apporti, cessioni |
| Rapporto > 3 | Rischio di non perseguibilità; valutare attentamente l'accesso alla composizione negoziata |

⚠️ Il test è uno strumento di **prima valutazione**: le soglie hanno natura indicativa (D.D. 21/03/2023) e non sostituiscono il piano di risanamento.

---

## 8. Indicatori non finanziari (art. 2428, c. 2 c.c.)

| Area | Esempi |
|------|--------|
| Personale | Organico medio, turnover, ore di formazione per addetto, tasso di assenteismo, indice di frequenza infortuni |
| Clienti/mercato | Quota di mercato, retention, reclami, puntualità consegne |
| Processi | OEE, scarti, lead time, rotazione scorte per articolo |
| Ambiente | Consumi energetici per unità prodotta, emissioni Scope 1-2, rifiuti |

---

## Note interpretative

- **Benchmark:** confrontare gli indici con medie settoriali (codice ATECO 2025) e con la serie storica dell'impresa (almeno 3 esercizi); i valori di riferimento riportati sono indicativi.
- **Finanziamenti soci:** nella PFN, i finanziamenti soci postergati (art. 2467 c.c.) possono essere esposti separatamente o assimilati a PN nell'analisi del merito creditizio, esplicitando la scelta.
- **Bilancio abbreviato e micro:** in assenza del rendiconto finanziario, ricostruire i flussi dal confronto di due SP e del CE (metodo indiretto, OIC 10).
