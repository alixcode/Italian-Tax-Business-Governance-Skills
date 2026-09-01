# Skill Dottore Commercialista — Repository Skills per la Gestione Contabile, Fiscale e Societaria delle Imprese Italiane

Repository di skills professionali per Claude Code, progettato per supportare dottori commercialisti, responsabili amministrativi e CFO nella gestione delle imprese italiane. Le skills sono strutturate per coprire l'intero ciclo di vita contabile, fiscale e societario, con riferimento costante alle normative vigenti.

Le fonti di riferimento sono aggiornate a:
- **OIC Binder 2024** (principi contabili nazionali, revisioni marzo 2024)
- **IAS Binder 2025** (principi internazionali omologati UE)
- **TUIR** — DPR 22 dicembre 1986, n. 917, aggiornamento 2026
- **TU IVA** — D.Lgs. 10 gennaio 2026 (testo unico consolidato)
- **Codice Civile** — aggiornamento novembre 2024
- **IRAP** — D.Lgs. 15 dicembre 1997, n. 446

---

## Aree tematiche

| # | Area | Cartella | Descrizione |
|---|------|----------|-------------|
| 01 | Contabilità Generale | [`skills/01-contabilita-generale/`](skills/01-contabilita-generale/) | Piano dei conti, registrazioni tipiche, scritture di assestamento |
| 02 | Bilancio d'Esercizio | [`skills/02-bilancio-esercizio/`](skills/02-bilancio-esercizio/) | Schemi Stato Patrimoniale e Conto Economico ex artt. 2424–2425 c.c., nota integrativa, relazione sulla gestione |
| 03 | Principi Contabili OIC/IAS | [`skills/03-principi-contabili/`](skills/03-principi-contabili/) | Applicazione pratica degli OIC 11–34 e IAS/IFRS per casi tipici |
| 04 | Fiscalità d'Impresa (IRES/IRAP) | [`skills/04-fiscalita-impresa/`](skills/04-fiscalita-impresa/) | Determinazione reddito imponibile IRES, variazioni fiscali, IRAP base imponibile |
| 05 | IVA e Adempimenti Periodici | [`skills/05-iva-adempimenti/`](skills/05-iva-adempimenti/) | Liquidazione IVA, reverse charge, pro-rata, dichiarazione annuale |
| 06 | Operazioni Straordinarie | [`skills/06-operazioni-straordinarie/`](skills/06-operazioni-straordinarie/) | Fusioni, scissioni, conferimenti, cessioni d'azienda, trasformazioni |
| 07 | Diritto Societario | [`skills/07-diritto-societario/`](skills/07-diritto-societario/) | Assemblee, delibere, distribuzione utili, riduzione capitale, recesso |
| 08 | Controllo di Gestione | [`skills/08-controllo-gestione/`](skills/08-controllo-gestione/) | Budget, analisi scostamenti, reporting direzionale, KPI |
| 09 | Adempimenti e Scadenze | [`skills/09-adempimenti-scadenze/`](skills/09-adempimenti-scadenze/) | Calendario fiscale, dichiarazioni, comunicazioni obbligatorie, sanzioni |

---

## Come usare le skills con Claude Code

Le skills di questo repository sono progettate per essere caricate in Claude Code come contesto di riferimento normativo e procedurale. Ogni skill è un file Markdown autonomo con frontmatter YAML che specifica area, fonti e data di aggiornamento.

**Utilizzo diretto:**

```bash
# Avviare Claude Code nella cartella del repository
claude

# Oppure caricare una skill specifica come contesto
claude --context skills/01-contabilita-generale/registrazioni-tipiche.md
```

**Utilizzo tramite CLAUDE.md:**

Aggiungere al file `CLAUDE.md` del progetto cliente un riferimento alle skills rilevanti:

```markdown
## Riferimenti normativi
Consulta le skills in /path/to/Italian-Tax-Business-Governance-Skills/skills/
per procedure contabili, fiscali e societarie standardizzate.
```

**Struttura di ogni skill:**

Ogni file di skill contiene:
1. **Frontmatter YAML** — nome, descrizione, area, fonti normative, data aggiornamento
2. **Corpo della skill** — procedure, esempi, tavole di riferimento, formule
3. **Note interpretative** — chiarimenti su casi limite, circolari, prassi

---

## Fonti principali

| Fonte | Riferimento normativo | Versione |
|-------|-----------------------|----------|
| Codice Civile (Libro V, Titolo V) | R.D. 16 marzo 1942, n. 262 | Aggiornamento novembre 2024 |
| TUIR | DPR 22 dicembre 1986, n. 917 | Aggiornamento 2026 |
| TU IVA | D.Lgs. 10 gennaio 2026 | Testo unico consolidato |
| IRAP | D.Lgs. 15 dicembre 1997, n. 446 | Vigente |
| TU Sanzioni Tributarie | D.Lgs. 5 novembre 2024, n. 173 | Vigente |
| TU Riscossione | D.Lgs. 24 marzo 2025, n. 33 | Vigente |
| OIC Binder | Principi OIC 10–34 | Revisioni marzo 2024 / maggio 2022 |
| IAS/IFRS Binder | IAS 1–40, IFRS 9/15/16 | IAS Binder 2025 |

Il dettaglio completo di tutte le fonti è in [`FONTI.md`](FONTI.md).

---

## Gestione dei conflitti normativi OIC / IAS

Le skills distinguono sempre tra il regime contabile applicabile:

- **Bilanci in forma ordinaria (imprese non quotate):** si applica il Codice Civile (artt. 2423–2435-ter) e i **principi OIC**. In caso di lacuna OIC, si può fare riferimento agli IAS/IFRS in via analogica, ma solo se compatibili con la disciplina codicistica (OIC 11 § 10).
- **Bilanci consolidati di società quotate o che adottano volontariamente gli IAS:** si applicano i **principi IAS/IFRS** omologati dall'UE, ai sensi del D.Lgs. 28 febbraio 2005, n. 38.
- **Conflitti diretti:** quando OIC e IAS prevedono trattamenti contabili incompatibili (es. rivalutazione delle immobilizzazioni, capitalizzazione degli oneri finanziari), la skill indica esplicitamente quale regime si applica e in quale contesto.

---

## Disclaimer

Le skills contenute in questo repository sono **strumenti di supporto professionale** a uso del consulente o del responsabile amministrativo. Non costituiscono parere professionale, consulenza legale o fiscale, e non sostituiscono la valutazione caso per caso da parte di un dottore commercialista abilitato o di un avvocato. L'applicazione delle normative richiede sempre la verifica delle circostanze specifiche, degli aggiornamenti legislativi successivi alla data di pubblicazione delle skills e della prassi amministrativa dell'Agenzia delle Entrate.

L'autore del repository non si assume responsabilità per decisioni prese sulla base esclusiva del contenuto delle skills.
