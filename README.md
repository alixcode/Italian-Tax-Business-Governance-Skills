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

Le skills contenute in questo repository sono esclusivamente strumenti didattici e di aggiornamento professionale a uso del consulente o del responsabile amministrativo già in possesso di qualifiche professionali riconosciute.

Esse non costituiscono parere professionale vincolante, consulenza legale o fiscale, e non sostituiscono in alcun modo la valutazione caso per caso da parte di un dottore commercialista abilitato, di un avvocato, di un revisore legale, o di altro professionista competente e responsabile della pratica specifica.

Limitazioni esplicite di responsabilità:

Le skills non possono essere utilizzate a fini di lucro, per prestazioni a terzi in conto proprio, o come base di parcellazione professionale senza ulteriore elaborazione, studio approfondito, e responsabilità diretta del professionista abilitato;
Non sono ammesse implementazioni automatizzate, deleghe totali a sistemi software non controllati da un professionista qualificato, o sostituzioni della valutazione professionale discrezionale;
L'applicazione delle normative richiede sempre la verifica caso per caso delle circostanze specifiche, degli aggiornamenti legislativi successivi alla data di pubblicazione, della prassi amministrativa e delle interpretazioni dell'Agenzia delle Entrate, delle sentenze della Cassazione, e delle linee guida dell'Ordine professionale;
Le skills possono contenere semplificazioni, generalizzazioni, o errori involontari che non riflettono le eccezioni di legge, i regimi speciali, o le particolari combinazioni fattispecie che alterano l'applicazione della norma.

Casi d'uso legittimi (esclusivamente):

Studio personale e aggiornamento individuale per professionisti già iscritti agli ordini professionali;
Preparazione di materiali di ricerca preliminari, da validare e approfondire con fonti ufficiali (Agenzia delle Entrate, normativa primaria, sentenze, orientamenti degli ordini);
Brainstorming interno di uno studio professionale, con successiva verifica gerarchica da parte del professionista incaricato;
Formazione interna di staff tecnico non abilitato, sotto la supervisione diretta del professionista responsabile;
Base di discussione in riunioni collegiali tra professionisti qualificati che mantengono piena responsabilità della conclusione finale.

Casi d'uso esclusi (non consentiti):

Applicazione diretta a pratiche professionali senza verifica e sottoscrizione personale del professionista responsabile;
Utilizzo per prestazioni a terzi dietro compenso, senza rielaborazione e responsabilità diretta del consulente;
Automazione totale di processi decisionali o interpretativi della normativa;
Sostituzione della consulenza professionale vera e propria;
Utilizzo da parte di soggetti non abilitati (non iscritti agli ordini professionali) come se rappresentasse consulenza;
Integrazione in software commerciali o prodotti SaaS senza autorizzazione esplicita e adattamento normativo;
Applicazione a giurisdizioni diverse dall'Italia, senza adattamento alle norme locali.

Declinazione finale della responsabilità:
L'autore del repository non si assume alcuna responsabilità per:

Decisioni, azioni, o omissioni prese sulla base esclusiva o prevalente del contenuto delle skills;
Danni diretti, indiretti, consequenziali, o di qualsiasi natura derivanti dall'utilizzo, dal mancato utilizzo, o dall'interpretazione errata del materiale;
Incorrettezze, ritardi, omissioni, o violazioni normative conseguenti all'affidamento esclusivo sulle skills;
Sanzioni amministrative, tributarie, penali, o civili derivanti dall'applicazione non verificata di quanto contenuto nelle skills;
Perdita di opportunità, danni reputazionali, o altri pregiudizi economici derivanti dall'uso del repository.

Ogni professionista rimane integralmente responsabile delle proprie conclusioni, della propria firma, e della qualità della propria prestazione secondo il codice deontologico del proprio ordine professionale.
