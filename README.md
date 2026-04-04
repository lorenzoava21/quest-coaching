# Quest Coaching — Mappa del Progetto

> Framework di coaching professionale (ICF-aligned) che integra meccaniche di game design e TTRPG con metodologie di coaching evidence-based. Design originale ispirato ai principi di Not The End (Pustorino / Fumble GDR, 2020).

**Versione:** 3.0
**Ultimo aggiornamento:** 4 Aprile 2026
**Stato:** Framework v3 completo. Pronto per prima sessione pilota.

---

## Come usare questo progetto

**Per la prima sessione pilota servono solo 3 cose:**
1. Stampa `v3/mappa_template_v2.pdf` (A3) - la Mappa per il cliente
2. Stampa `v3/cheat_sheet.pdf` (A4) - il tuo foglio di riferimento
3. Penne colorate

**Per prepararti:** leggi `v3/checklist_pre_sessione.md`, poi `v3/esempio_mappa_compilata.md`.

**Per invitare qualcuno:** usa i messaggi in `v3/messaggi_invito.md`.

---

## Struttura del progetto

```
Coaching/
├── README.md                        ← Sei qui
│
├── v3/                              ← FRAMEWORK v3 (versione attiva)
│   │
│   ├── FRAMEWORK
│   │   ├── framework_v3.md             Documento centrale: blueprint completo
│   │   ├── 00_note_di_design.md        Principi, terminologia, fonti
│   │   └── toolkit_completo.md         I 5 strumenti in dettaglio
│   │
│   ├── GUIDE SESSIONE
│   │   ├── session_zero.md             Guida Session Zero (75-90 min)
│   │   ├── sessione_tipo.md            Guida sessione regolare (60 min)
│   │   ├── guida_prime_5_sessioni.md   Evoluzione sessione per sessione
│   │   ├── esempio_mappa_compilata.md  Elena, 32, UX designer - Mappa completa
│   │   └── simulazione_sessione_elena.md  Sessione 3 completa (dialogo realistico)
│   │
│   ├── STAMPABILI
│   │   ├── mappa_template_v2.pdf       Mappa A3 per il cliente (6 zone con icone)
│   │   ├── session_zero_print.pdf      Session Zero stampabile
│   │   └── cheat_sheet.pdf             Foglio A4 fronte-retro per la sessione
│   │
│   ├── PER IL CLIENTE
│   │   ├── guida_benvenuto_cliente.md  Cosa aspettarsi (da inviare pre-Session Zero)
│   │   └── consenso_informato.md       GDPR + consenso partecipazione studio
│   │
│   ├── PER IL COACH
│   │   ├── checklist_pre_sessione.md   Preparazione prima sessione pilota
│   │   ├── messaggi_invito.md          3 messaggi pronti (amico, collega, LinkedIn)
│   │   ├── template_note_sessione.md   Diario di bordo post-sessione
│   │   └── mappa_del_personaggio.md    Concept Mappa del Personaggio
│   │
│   ├── STUDIO PILOTA
│   │   ├── questionari_studio_pilota.md  WEMWBS + GSE con istruzioni e scoring
│   │   └── carte_oracolo_note.md       Verifica compatibilità v3 (ok, 2 micro-fix)
│   │
│   ├── LINKEDIN
│   │   ├── idee_post_linkedin.md       20 angoli per post (4 categorie)
│   │   └── profilo_linkedin.md         Headline + about + sezioni
│   │
│   └── AMMINISTRATIVO
│       ├── confronto_scuole_icf.md     11 scuole confrontate, raccomandazione ICTF
│       └── guida_registrazione_marchio.md  Step-by-step UIBM (~149 EUR)
│
├── ricerca/                         ← Fondamenti teorici e ricerca di contesto
│   ├── SINTESI_RICERCA_COMPLETA.md     Executive summary + piano 90 giorni
│   ├── report_mercato_2026.md          Mercato globale/Italia + 12 business model
│   ├── report_normativo_target.md      Normativa + GDPR + marchio + target
│   ├── evidenze_2024_2026.md           20 studi scientifici nuovi (2024-2026)
│   ├── report_rischi_opportunita.md    8 rischi (4 critici) + 8 opportunità
│   ├── step1_game_design.md            Game design, TTRPG, meccaniche
│   ├── step2_coaching.md               Coaching professionale, ICF, 9 modelli
│   ├── analisi_critica.md              13 criticità identificate + mitigazioni
│   └── analisi_competitiva.md          10 competitor analizzati + gap analysis
│
├── framework_v2.md                  ← Blueprint v2 (archivio, basato su Blades/Fate)
│
├── strumenti/                       ← Toolkit v2 (archivio, ancora utile per Carte Oracolo)
│   ├── carte_oracolo/mazzo_completo.md   50 carte in 4 categorie (compatibile v3)
│   ├── scheda_personaggio/              Template + esempio v2
│   ├── clock_templates/                 Clock 4/6/8 v2
│   └── session_zero/                    Script v2 (927 righe)
│
├── manuale_e_moduli/                ← Formazione v2 (archivio)
│   ├── manuale_v1.md                   Manuale operativo (1.816 righe)
│   └── moduli/                         4 moduli tematici (32 sessioni)
│
├── simulazioni/                     ← Sessioni simulate v2
│   └── sessione_completa_marco.md      Sessione 3 v2 (4.564 parole)
│
├── comunicazione/                   ← Marketing v2 (da aggiornare per v3)
│   ├── landing_page/                   Copy completo
│   ├── pitch_deck/                     20 slide + speaker notes
│   ├── piano_editoriale/               12 articoli + 2 scritti
│   ├── email_nurturing/                6 email su 14 giorni
│   └── video_script/                   2 video script
│
├── business/                        ← Strategia v2 (da aggiornare per v3)
│   ├── modello_finanziario/            Pricing, scenari, break-even
│   ├── proprieta_intellettuale/        Trademark, copyright, licensing
│   ├── partnership/                    20 partner italiani
│   └── obiezioni_vendita/              15 obiezioni + risposte
│
├── cliente/                         ← Materiali cliente v2 (sostituiti da v3/)
│   ├── welcome_guide/                  Guida benvenuto v2
│   ├── email_templates/                8 email percorso
│   └── quick_start_coach/              Cheat sheet v2
│
├── validazione/                     ← Ricerca e testing
│   ├── interviste/                     Protocollo 10-15 interviste
│   └── studio_pilota/                  Protocollo completo (1.410 righe)
│
├── workshop/                        ← Formato workshop
│   └── workshop_introduttivo.md        2.5 ore, script, handout
│
└── _archivio/                       ← Versioni precedenti
```

---

## I 5 Principi del Quest Coaching

1. **Il coaching viene prima del gioco.** Le competenze ICF sono il fondamento. Le meccaniche sono amplificatori, non sostituti.
2. **Il cliente sceglie il livello di gioco.** Tre livelli: Leggero / Integrato / Immersivo. Mai imporre.
3. **Meno è meglio.** Kit Minimo: Mappa del Personaggio + Tappe + "Ogni fine è un inizio".
4. **La sicurezza non è opzionale.** Pausa, Confini, screening, referral. Sempre.
5. **Misura, itera, migliora.** Scale validate pre/post. Il framework è un prototipo permanente.

## I 6 Principi di Design (v3)

1. **La fisicità crea presenza.** Oggetti reali: carte, fogli, penne.
2. **Il cliente sceglie il livello di esposizione.** Il coach propone, il cliente decide.
3. **Le difficoltà appartengono al cliente.** Il coach chiede, non interpreta.
4. **I segni del passato sono anche risorse.** Dualità: vulnerabilità e forza.
5. **Ogni fine è un inizio.** Il fallimento non chiude, apre.
6. **Le parole definiscono, i numeri riducono.** Mai punteggi o scale identitarie.

## Terminologia v3

| Termine | Significato |
|---------|-------------|
| **Mappa** | Il documento centrale del cliente (foglio A3 con 6 zone) |
| **Tratti** | Parole che descrivono chi è il cliente |
| **Fuochi** | Qualità che si accendono quando il cliente è nel suo elemento |
| **Segni** | Esperienze che hanno lasciato un'impronta (vulnerabilità + forza) |
| **Legami** | Le persone significative |
| **Valori** | I principi non negoziabili |
| **Direzione** | L'obiettivo del percorso, formulato come intenzione |
| **Tappe** | Marcatori visivi di progresso (forma libera) |
| **Crocevia** | Momento significativo dopo il quale la Mappa cambia |
| **Patto** | L'accordo su come lavorare insieme |
| **Pausa** | Il segnale per fermarsi, senza bisogno di spiegare |

---

## Cosa è stato fatto

| Fase | Deliverable | Versione | Stato |
|------|-----------|---------|-------|
| **FRAMEWORK v3** | | | |
| Framework | Blueprint v3 completo | v3 | done |
| Framework | Note di design (principi, terminologia) | v3 | done |
| Framework | Toolkit completo (5 strumenti) | v3 | done |
| **GUIDE SESSIONE** | | | |
| Sessione | Session Zero (75-90 min) | v3 | done |
| Sessione | Sessione tipo (60 min) | v3 | done |
| Sessione | Guida prime 5 sessioni | v3 | done |
| Sessione | Esempio Mappa compilata (Elena) | v3 | done |
| Sessione | Simulazione sessione 3 (dialogo) | v3 | done |
| **STAMPABILI** | | | |
| Stampabile | Mappa del Personaggio A3 (6 zone, icone) | v3 | done |
| Stampabile | Session Zero stampabile | v3 | done |
| Stampabile | Cheat sheet A4 fronte-retro | v3 | done |
| **PER IL CLIENTE** | | | |
| Cliente | Guida benvenuto (pre-Session Zero) | v3 | done |
| Cliente | Consenso informato GDPR | v3 | done |
| **PER IL COACH** | | | |
| Coach | Checklist pre-sessione pilota | v3 | done |
| Coach | Messaggi di invito (3 versioni) | v3 | done |
| Coach | Template note post-sessione | v3 | done |
| **STUDIO PILOTA** | | | |
| Pilota | Questionari WEMWBS + GSE | v3 | done |
| Pilota | Verifica Carte Oracolo v3 | v3 | done |
| **LINKEDIN** | | | |
| LinkedIn | 20 idee per post (4 categorie) | v3 | done |
| LinkedIn | Struttura profilo ottimizzata | v3 | done |
| **AMMINISTRATIVO** | | | |
| Admin | Confronto 11 scuole ICF Italia | v3 | done |
| Admin | Guida registrazione marchio UIBM | v3 | done |
| **RICERCA** | | | |
| Ricerca | Mercato globale/Italia (80+ fonti) | 2026 | done |
| Ricerca | Contesto normativo + GDPR + marchio | 2026 | done |
| Ricerca | Evidenze scientifiche 2024-2026 (20 studi) | 2026 | done |
| Ricerca | 8 rischi + 8 opportunità | 2026 | done |
| Ricerca | Sintesi completa + piano 90 giorni | 2026 | done |
| **ARCHIVIO v2** | | | |
| Framework | Blueprint v2 (Blades/Fate) | v2 | archivio |
| Strumenti | Scheda Personaggio + Carte Oracolo + Clock | v2 | archivio* |
| Formazione | Manuale (1.816 righe) + 4 moduli (32 sessioni) | v2 | archivio |
| Simulazione | Sessione completa Marco | v2 | archivio |
| Comunicazione | Landing, pitch, piano editoriale, email, video | v2 | da aggiornare |
| Business | Finanziario, IP, partnership, obiezioni | v2 | da aggiornare |
| Validazione | Guida interviste + protocollo studio | v2 | da aggiornare |
| Workshop | Workshop introduttivo 2.5 ore | v2 | da aggiornare |

*Le Carte Oracolo v2 sono compatibili con v3 (2 micro-fix, vedi `v3/carte_oracolo_note.md`).

---

## Piano d'azione 90 giorni (aprile-giugno 2026)

### Settimana 1-4 (aprile)
- [ ] **Prima sessione pilota** con volontario (Mappa A3 + cheat sheet + penne colorate)
- [ ] **Primo post LinkedIn** (scegli un angolo da `v3/idee_post_linkedin.md`, scrivilo con la tua voce)
- [ ] Contattare scuole ICF per certificazione ACC (vedi `v3/confronto_scuole_icf.md`, raccomandazione: ICTF)
- [ ] Registrare trademark UIBM (vedi `v3/guida_registrazione_marchio.md`, ~149 EUR)
- [ ] Definire strategia finanziaria (fonte reddito alternativa per 12-18 mesi)

### Mese 2 (maggio)
- [ ] Lanciare newsletter Substack (bisettimanale)
- [ ] Reclutare partecipanti studio pilota (consenso: `v3/consenso_informato.md`, questionari: `v3/questionari_studio_pilota.md`)
- [ ] Richiedere licenza WEMWBS su warwick.ac.uk (gratuita, non-commerciale)

### Mese 3 (giugno)
- [ ] Aprire community Discord (30 membri in 60 giorni)
- [ ] Iterare framework sulla base delle prime 10-15 sessioni reali
- [ ] Aggiornare materiali comunicazione e business per v3

---

## Fonti e ispirazioni

- **Not The End** (Pustorino, Airoldi, Serena / Fumble GDR, 2020) - principi di design
- **Blades in the Dark** (Harper, 2017) - ispirazione per le Tappe
- **Fate** (Evil Hat, 2013) - ispirazione per i Tratti narrativi
- **Ironsworn** (Tomkin, 2018) - sistema oracolo, impegno emotivo
- **ICF Core Competencies** (2019) - fondamento professionale
- **Self-Distancing** (Kross et al., 2014) - narrazione in terza persona
- **Self-Determination Theory** (Deci & Ryan, 2000) - test per ogni meccanica

Nessuna meccanica è copiata. Tutte sono originali, ispirate ai principi sopra citati.
