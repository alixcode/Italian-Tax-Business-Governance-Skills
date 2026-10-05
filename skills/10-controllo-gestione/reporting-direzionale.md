---
name: "Reporting Direzionale e Cruscotto Mensile"
description: "Progettazione del sistema di reporting direzionale per PMI italiane: chiusure mensili gestionali, riclassificazioni di SP e CE, contenuto del cruscotto per CdA e organo di controllo, flussi informativi ex artt. 2381 e 2403-bis c.c., collegamento con gli adeguati assetti."
area: "Controllo di Gestione"
fonti:
  - "Codice Civile art. 2086, c. 2 — Assetti adeguati (agg. novembre 2024)"
  - "Codice Civile art. 2381, cc. 3 e 5 — Flussi informativi tra organi delegati e CdA"
  - "Codice Civile artt. 2403, 2403-bis — Doveri e poteri del collegio sindacale"
  - "D.Lgs. 12 gennaio 2019, n. 14 (CCII), artt. 3 e 25-octies — Segnali di allarme e segnalazione dell'organo di controllo"
  - "OIC 11 — Continuità aziendale (marzo 2024)"
aggiornamento: "2026-10"
conflitti_noti: "Le chiusure gestionali infrannuali non sono bilanci intermedi civilistici: le stime (ratei, ammortamenti, rimanenze, imposte) devono comunque seguire i criteri OIC per garantire confrontabilità con il bilancio d'esercizio. Per IAS-adopter valgono i criteri IAS 34 solo se si redigono bilanci intermedi formali."
---

# Reporting Direzionale e Cruscotto Mensile

## 1. Requisiti normativi del flusso informativo

| Destinatario | Obbligo | Norma |
|--------------|---------|-------|
| Consiglio di amministrazione | Gli organi delegati riferiscono **almeno ogni 6 mesi** (o termine statutario più breve) su andamento della gestione, prevedibile evoluzione e operazioni di maggior rilievo | Art. 2381, c. 5 |
| Consiglio di amministrazione | Valuta l'adeguatezza dell'assetto organizzativo, amministrativo e contabile sulla base delle informazioni ricevute | Art. 2381, c. 3 |
| Collegio sindacale | Vigila sull'adeguatezza degli assetti; può chiedere notizie agli amministratori | Artt. 2403, 2403-bis |
| Organo di controllo | Segnala per iscritto all'organo amministrativo la sussistenza dei presupposti per la composizione negoziata | Art. 25-octies CCII |

Un reporting strutturato, periodico e documentato è la **prova** dell'esistenza di un assetto amministrativo-contabile adeguato (art. 2086 c.c.) e della capacità di **rilevazione tempestiva** dei segnali di crisi (art. 3 CCII).

---

## 2. Processo di chiusura mensile gestionale

| Giorno lavorativo | Attività |
|-------------------|----------|
| G+1 / G+3 | Registrazione fatture attive e passive del mese; riconciliazioni bancarie |
| G+3 / G+5 | Scritture di competenza gestionali: ratei, risconti, fatture da ricevere/emettere, ammortamenti 1/12, TFR, ferie e permessi maturati |
| G+5 / G+7 | Valorizzazione rimanenze (inventario permanente o stima a margine) |
| G+7 / G+8 | Stima imposte di periodo (IRES/IRAP su risultato progressivo) |
| G+8 / G+10 | Riclassificazioni, KPI, analisi scostamenti |
| G+10 / G+12 | Commento e presentazione alla direzione |

Le scritture di competenza seguono le regole di [`../01-contabilita-generale/scritture-assestamento.md`](../01-contabilita-generale/scritture-assestamento.md).

---

## 3. Riclassificazioni di riferimento

### 3.1 Stato patrimoniale funzionale (pertinenza gestionale)

```
IMPIEGHI                                  FONTI
Immobilizzazioni operative nette          Patrimonio netto
+ Capitale circolante netto operativo     + Posizione finanziaria netta (PFN)
  (crediti comm. + rimanenze − debiti comm.
   ± altri crediti/debiti operativi)
− Fondi operativi (TFR, fondi rischi)
= CAPITALE INVESTITO NETTO (CIN)        = FONTI DI FINANZIAMENTO
```

**PFN** = Debiti finanziari (banche, leasing, finanziamenti soci onerosi, obbligazioni) − Disponibilità liquide − Attività finanziarie a breve prontamente liquidabili.

### 3.2 Stato patrimoniale finanziario (liquidità/esigibilità)

Attivo: immobilizzato / circolante (liquidità immediate, differite, disponibilità). Passivo: PN / passività consolidate (> 12 mesi) / passività correnti (≤ 12 mesi). Utile per gli indici di solvibilità e struttura.

### 3.3 Conto economico

A **valore aggiunto** (EBITDA, EBIT) o a **margine di contribuzione** (ricavi − costi variabili = MdC; MdC − costi fissi = EBIT). Raccordo con l'art. 2425 c.c. in [`budget-annuale.md`](budget-annuale.md).

---

## 4. Contenuto del cruscotto mensile (template)

| Sezione | Contenuto minimo | Frequenza |
|---------|------------------|-----------|
| 1. Sintesi esecutiva | 5-7 messaggi chiave; semaforo su obiettivi; principali rischi | Mensile |
| 2. Conto economico | Mese e progressivo: consuntivo vs budget vs anno precedente; bridge EBITDA | Mensile |
| 3. Ricavi | Per linea/cliente/area; portafoglio ordini; top 10 clienti e concentrazione | Mensile |
| 4. Marginalità | Margine di contribuzione per prodotto/commessa; costo del lavoro su ricavi | Mensile |
| 5. Capitale circolante | DSO, DIO, DPO, scaduto clienti per fasce (0-30, 31-60, 61-90, > 90), scaduto fornitori | Mensile |
| 6. Cassa e PFN | Saldo, utilizzo fidi, PFN, previsione di cassa a 13 settimane e a 12 mesi | Mensile / settimanale |
| 7. Debiti fiscali e previdenziali | Scaduti, rateizzati, piani di dilazione AdE-Riscossione / INPS | Mensile |
| 8. Indicatori della crisi | DSCR prospettico, segnali art. 3, c. 4 CCII, covenant | Mensile / trimestrale |
| 9. Investimenti | Avanzamento capex vs budget | Trimestrale |
| 10. KPI non finanziari | Organico, turnover, ore lavorate, qualità, sicurezza, KPI ambientali | Trimestrale |
| 11. Forecast | Chiusura d'anno attesa (rolling forecast) | Trimestrale |

Gli indicatori e le formule sono dettagliati in [`kpi-indici-bilancio.md`](kpi-indici-bilancio.md).

---

## 5. Monitoraggio dei segnali di allarme (art. 3, c. 4 CCII)

Da includere **sempre** nel cruscotto, con evidenza del superamento delle soglie:

| Segnale | Soglia |
|---------|--------|
| Debiti per **retribuzioni** scaduti | Da almeno **30 giorni** e pari a oltre la **metà** dell'ammontare complessivo mensile delle retribuzioni |
| Debiti verso **fornitori** scaduti | Da almeno **90 giorni** e di ammontare **superiore** a quello dei debiti non scaduti |
| Esposizioni verso **banche** e intermediari | Scadute da più di **60 giorni** o oltre il limite degli affidamenti da più di 60 giorni, se rappresentano complessivamente almeno il **5%** del totale delle esposizioni |
| Esposizioni verso **creditori pubblici qualificati** | Soglie dell'art. 25-novies CCII (INPS, INAIL, Agenzia delle Entrate, Agenzia Entrate-Riscossione) |

⚠️ Le soglie dell'art. 25-novies (segnalazioni dei creditori pubblici qualificati) sono state oggetto di modifiche successive: **verificare gli importi vigenti**.

---

## 6. Principi di qualità del reporting

- **Tempestività** prima della precisione assoluta (stime documentate e coerenti).
- **Confrontabilità**: stessi criteri nel tempo; evidenza delle riclassifiche.
- **Responsabilità**: ogni KPI ha un owner e un target.
- **Riconciliazione**: il progressivo di dicembre deve riconciliarsi con il bilancio d'esercizio (differenze spiegate).
- **Tracciabilità**: verbalizzazione dell'esame del report nel libro delle adunanze del CdA, per documentare la valutazione degli assetti (art. 2381, c. 3).

---

## Note interpretative

- **Micro e piccole imprese:** il principio di proporzionalità consente un reporting semplificato (trimestrale; CE riclassificato, cassa a 12 mesi, scaduti, segnali CCII), purché formalizzato.
- **Organo di controllo:** il collegio sindacale/revisore utilizza il reporting per la vigilanza sugli assetti; la sua assenza o inaffidabilità è un rilievo ricorrente nelle verifiche periodiche.
- **Strumenti:** la produzione automatizzata (BI, Power BI, fogli collegati al gestionale) è raccomandata ma richiede **controlli di quadratura** con la contabilità generale.
