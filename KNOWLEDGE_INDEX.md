Document Type: KNOWLEDGE_INDEX
Version: 1.2
Last Updated: 2026-09-23
Purpose:
Define the knowledge map, document hierarchy, account registry and authoritative CUSTOMER_MASTER selection rules for Strategic Account Intelligence.

---

## 1. KNOWLEDGE STRUCTURE

The knowledge base is organized into four document classes:

1. METHODOLOGY
2. OUTPUT_STANDARD
3. CUSTOMER_MASTER
4. TEMPLATE

Supporting EVIDENCE may also be added when required.

The structural files are:

- METHODOLOGY.md
- OUTPUT_STANDARD.md
- CUSTOMER_MASTER_TEMPLATE.md
- KNOWLEDGE_INDEX.md

---

## 2. DOCUMENT AUTHORITY

Use the following precedence:

1. METHODOLOGY
2. OUTPUT_STANDARD
3. CUSTOMER_MASTER
4. EVIDENCE
5. TEMPLATE

METHODOLOGY defines how evidence must be interpreted.

OUTPUT_STANDARD defines how information must be presented.

CUSTOMER_MASTER defines the consolidated state of an account.

EVIDENCE may contain facts newer than the CUSTOMER_MASTER.

TEMPLATE defines the expected CUSTOMER_MASTER structure.

Do not use upload order as authority.

---

## 3. CUSTOMER MASTER SELECTION

Each account has one authoritative CUSTOMER_MASTER.

Identify the account using:

- Account
- Account ID

Do not rely only on physical filename.

If multiple CUSTOMER_MASTER documents exist for the same Account ID:

1. Select the highest internally consistent Version.
2. If Version is tied, select the most recent Last Updated.
3. Flag material duplicates.
4. Do not combine multiple Masters as if they were simultaneously authoritative.
5. Older Masters may be used only as historical evidence when required.
6. Validate consistency between file header (`FILE:` / `VERSION:` / `REPLACES:`) and CUSTOMER_MASTER metadata in the document body (`Version:` / `Last Updated:`).
7. If header and body versions conflict, explicitly report the inconsistency before relying on the disputed version.
8. Do not silently resolve a header/body version conflict through inference.

Never use another account to complete missing information.

---

## 4. ACCOUNT REGISTRY

### C6 Bank

Account:
C6 Bank

Account ID:
c6-bank

Canonical File Name:
c6-bank_account.md

Current known Master Version:
1.8

Last Updated:
2026-09-21

Master Status:
CONSISTENT

---

### Santander Brasil

Account:
Banco Santander Brasil

Account ID:
santander-brasil

Canonical File Name:
santander-brasil_account.md

Current known Master Version:
1.5

Last Updated:
2026-09-22

Master Status:
CONSISTENT

---

### Getnet

Account:
Getnet

Account ID:
getnet

Canonical File Name:
getnet_account.md

Current known Master Version:
1.6

Last Updated:
2026-09-21

Master Status:
CONSISTENT

---

### Banco BMG

Account:
Banco BMG

Account ID:
banco-bmg

Canonical File Name:
banco-bmg_account.md

Current known Master Version:
1.3

Last Updated:
2026-09-22

Master Status:
CONSISTENT

---

### Banco Inter

Account:
Banco Inter

Account ID:
banco-inter

Canonical File Name:
banco-inter_account.md

Current known Master Version:
1.2

Last Updated:
2026-09-21

Master Status:
CONSISTENT

---

### Zurich

Account:
Zurich

Account ID:
zurich

Canonical File Name:
zurich_account.md

Current known Master Version:
1.3

Last Updated:
2026-09-21

Master Status:
CONSISTENT

---

## 5. CANONICAL FILE NAMES

Use exactly:

- c6-bank_account.md
- santander-brasil_account.md
- getnet_account.md
- banco-bmg_account.md
- banco-inter_account.md
- zurich_account.md

The physical filename should match Canonical File Name exactly.

Account ID and Canonical File Name are permanent.

Do not change Account ID or Canonical File Name because of version updates.

---

## 6. CUSTOMER MASTER RULE

CUSTOMER_MASTER is the authoritative consolidated account baseline.

A CUSTOMER_MASTER may contain:

- Current State
- business objectives
- adoption
- active initiatives
- projects
- results
- value
- risks
- blockers
- critical cases
- EOP/CSP
- decisions
- governance
- CTAs
- milestones
- Evidence Ledger
- Historical Timeline

New EVIDENCE may temporarily supersede Current State for reporting.

It becomes permanently consolidated only through:

**Fechar ciclo [Cliente]**

New evidence must not automatically alter the authoritative CUSTOMER_MASTER.

---

## 7. EVIDENCE

EVIDENCE may contain information newer than the CUSTOMER_MASTER.

Evidence must always be associated with the correct account.

Evidence may be used for:

- Atualizar [Cliente]
- Gerar Lideranca [Cliente]
- Gerar Gerencial [Cliente]
- Gerar CTAs [Cliente]
- Gerar Completo [Cliente]
- Gerar Status Semanal Brasil

New evidence does not automatically modify CUSTOMER_MASTER.

Only:

**Fechar ciclo [Cliente]**

permanently consolidates new evidence.

Evidence must preserve when available:

- account;
- evidence date;
- classification;
- population/context;
- maturity;
- dependencies;
- temporal reference.

---

## 8. VERSIONING

CUSTOMER_MASTER Version changes only through:

**Fechar ciclo [Cliente]**

Version rule:

version + 0.1

Example:

1.2 → 1.3

Fechar ciclo must also update:

- Last Updated
- Evidence Ledger
- Historical Timeline

Always preserve:

- Account ID
- Canonical File Name

Do not increment Version only because of:

- filename correction;
- UTF-8 correction;
- Markdown normalization;
- Knowledge-safe formatting;
- removal of problematic characters;
- editorial normalization that does not change account facts;
- correction of header/body metadata inconsistency when account facts do not change.

### Version integrity

The CUSTOMER_MASTER header and body must agree.

Expected:

`VERSION: 1.3`

and:

`Version: 1.3`

If they disagree:

1. Report the inconsistency.
2. Do not silently choose one version.
3. Use supported factual content normally where account identity is unambiguous.
4. Do not represent the disputed version number as validated.
5. Correct the metadata before treating the version as fully consistent.

---

## 9. HISTORICAL DATA

Valid historical data remains part of account knowledge.

Always preserve its reference period.

Example:

Baseline Jun/26:
614 active users / 700 contracted.

This remains valid historical evidence.

It must not be represented as current September adoption unless newer evidence supports that interpretation.

A historical valid value is not DADO FALTANTE merely because a newer measurement is unavailable.

Newer evidence may supersede Current State without deleting valid historical evidence.

---

## 10. DADO FALTANTE

Use:

**DADO FALTANTE: completar [informacao]**

when material expected information is not available in valid evidence.

Examples:

**DADO FALTANTE: completar formal case number.**

**DADO FALTANTE: completar customer-approved business target.**

**DADO FALTANTE: completar taxonomia de Nivel de Orquestracao.**

Do not use DADO FALTANTE merely because existing information is historical.

Do not use DADO FALTANTE merely because a future checkpoint is unresolved.

---

## 11. TBD

Use TBD when a future date, checkpoint or status is unresolved or not yet defined.

Examples:

Checkpoint: TBD.

GPR pilot: TBD.

EOP next review: TBD.

TBD does not mean historical information is missing.

TBD and DADO FALTANTE must remain distinct.

---

## 12. ACCOUNT GUARDRAILS

### C6 Bank

- C6 Pay is current priority.
- C6 owns C6 Pay development.
- Genesys support must not be represented as ownership of customer development.
- Roadmap does not equal implementation.
- GPR assessment does not equal realized benefit.
- Preserve Salesforce/CX Cloud architecture.
- Preserve known critical case numbers.
- EOP adoption baseline must preserve its period.
- Historical adoption must not be represented as current adoption.
- C6 Pay Stage 03 / Cognitive Advanced remains subject to the supported maturity represented in the Master.
- Rastreability architecture is a critical gate for Stage 03 progression.
- Preserve customer ownership of rastreability/data-governance dependencies.
- Do not convert phased roadmap into completed implementation.

### Santander Brasil

- Preserve formal case 0004164800.
- Mitigation/stabilization does not equal closure.
- Technical investigation may remain open after service restoration.
- Preserve measured GPR and Copilot outcomes with their context.
- Preserve adoption baseline period.
- Incident Readiness is separate from historical business-value evidence.
- Preserve separation between Incident Readiness, Genesis Event/GPR Freeze and tactical migration/A3S execution.
- Physical-store rollout is PAUSED, not cancelled, while the peripheral-device incident remains unresolved.
- Migration-wave TARGET dates must not be converted into completed waves without evidence.
- Quality Management and WFM are sequenced after STA homologation/stabilization.
- Decommission scope does not equal completed decommission.
- GPR historical-data requirement must preserve its technical context.
- Preserve formal and missing case numbers exactly according to evidence.

### Getnet

- GPR is in production.
- Preserve approximately 10% initial TMA reduction.
- Preserve approximately 4.2% expanded-sample TMA reduction.
- Do not hide the expanded-sample result behind the initial result.
- Preserve population/sample context.
- Transfer Rate is a guardrail.
- DMM, availability and candidate pool remain INFERENCE until proven.
- CX Advisory/PS perception is separate from project execution.
- June/2026 adoption data is historical baseline.
- Copilot productive pilot does not equal quantified business value.
- AI Scoring queue-segmentation issue must remain separate from confirmed root cause until investigation supports causality.
- Gamification implementation targets remain TARGET until execution evidence confirms them.
- GPR pilot-preparation history must not overwrite the newer production Current State.

### Banco BMG

- Migration is completed.
- Post-migration support issues do not reopen migration.
- Copilot token utilization progression is adoption evidence.
- Token consumption does not equal business value.
- 874 memberships does not equal 874 unique agents.
- GPR assessment does not equal achieved benefit.
- 14 high-potential queues do not equal production adoption.
- EOP remains Draft until supported evidence confirms otherwise.
- EOP projected value remains POTENTIAL.
- Preserve case 0004177350.
- A3S/Snowflake capability does not equal validated Genesys extraction procedure.
- Case 0004177350 remains active/escalated until evidence confirms resolution.
- The 22/09 Salesforce flow-trigger diagnosis is REPORTED technical evidence pending GFT validation.
- Do not convert the Salesforce flow-trigger diagnosis into confirmed root cause before validation.
- Possible correlation with C6 Bank case 0004151486 remains INFERENCE until confirmed through Engineering/Jira.
- Preserve RM LATAM escalation as part of the support/escalation chain.

### Banco Inter

- Preserve multi-technology strategy.
- Do not characterize the account simply as low adoption.
- IBM Watson plus Audio Connector does not equal Genesys Virtual Agent adoption.
- Banco Inter proprietary Copilot does not equal Genesys Agent Copilot adoption.
- GPR approximately 16.31% TMA reduction applies only to the historical POC.
- R$3–4M GPR business case is POTENTIAL, not realized saving.
- GPR rollout is not currently prioritized.
- Agent Qualities project progress does not equal business value.
- Custom IPS technical approval does not equal implemented BCP.
- May/2026 adoption data is historical baseline.
- Preserve customer-owned and third-party technology attribution.
- Newer customer architecture decisions supersede older EOP assumptions where they conflict.

### Zurich

- Preserve implementation/go-live versus formal project closure distinction.
- TARGET closure date does not equal confirmed closure.
- Voice go-live and reported migration do not automatically prove formal project closure.
- Billing/provisioned users do not automatically equal active users.
- Copilot token consumption does not establish business value.
- WFM operational friction does not establish quantified business impact unless measured.
- Voice Bot operational experience and business value must remain separate.
- Business Drivers/KPIs require supported discovery/validation.
- CSP remains initialized/in construction until evidence demonstrates greater maturity.
- Preserve Voice Bot progression: broad deployment → unsatisfactory experience → one-IVR controlled observation → measurement → future decision.
- Full-operation migration remains REPORTED unless stronger evidence supersedes it.
- Implementation completion does not equal value realization.

---

## 13. OUTPUT COMMANDS

Supported commands:

**Atualizar [Cliente]**

**Gerar Lideranca [Cliente]**

**Gerar Gerencial [Cliente]**

**Gerar CTAs [Cliente]**

**Gerar Completo [Cliente]**

**Gerar Status Semanal Brasil**

**Fechar ciclo [Cliente]**

Interpret these commands according to METHODOLOGY.md and OUTPUT_STANDARD.md.

Only `Fechar ciclo [Cliente]` permanently consolidates evidence and increments the CUSTOMER_MASTER version.

---

## 14. STATUS SEMANAL BRASIL

The authoritative structure is defined in:

OUTPUT_STANDARD.md

Status Semanal Brasil must use exactly 13 columns:

1. Conta
2. Status geral
3. Agendas previstas / atividades da semana
4. Situacao / riscos / blockers
5. Cases Criticos (numero, contexto e status)
6. Plano de acao / apoio necessario
7. EOP / CSP
8. Adocao (licencas / features / tokens)
9. Valor & outcomes
10. Oportunidades
11. Proximo marco
12. Nivel de Orquestracao
13. Ultima atualizacao

One account = one row.

Do not replace this structure with one section/card per account.

Historical adoption/value may be used where relevant, but the reference period must remain explicit.

TARGET must not be converted into ACHIEVED.

POTENTIAL must not be converted into realized value.

---

## 15. NIVEL DE ORQUESTRACAO

No formal taxonomy currently exists.

Until a taxonomy is explicitly defined:

**DADO FALTANTE: completar taxonomia.**

Do not infer:

- High;
- Medium;
- Low;
- Red;
- Yellow;
- Green;
- numerical scores

as an approved taxonomy.

Criticality may control output depth without creating an unsupported orchestration classification.

---

## 16. KNOWLEDGE MAINTENANCE

When adding a new account:

1. Assign permanent Account ID.
2. Define Canonical File Name: `[account-id]_account.md`.
3. Create CUSTOMER_MASTER using CUSTOMER_MASTER_TEMPLATE.md.
4. Add the account to this Knowledge Index.
5. Never copy factual information from another account.
6. Start with supported evidence only.

When closing a cycle:

1. Locate authoritative CUSTOMER_MASTER.
2. Validate Account and Account ID.
3. Validate header/body version consistency.
4. Incorporate valid evidence.
5. Increment Version by 0.1.
6. Update Last Updated.
7. Preserve Account ID.
8. Preserve Canonical File Name.
9. Update Evidence Ledger.
10. Update Historical Timeline.
11. Produce complete CUSTOMER_MASTER.
12. Update Current known Master Version in this index when required.

When a Master version changes through a valid cycle closure, update the Account Registry.

Do not use the Knowledge Index to overwrite CUSTOMER_MASTER account facts.

---

## 17. KNOWLEDGE-SAFE FILE GUIDANCE

Preferred format:

Markdown (.md)

Preferred encoding:

UTF-8

Physical filename should match Canonical File Name.

Avoid accidental extensions such as:

`.md.txt`

Structural documents should use exactly:

- METHODOLOGY.md
- OUTPUT_STANDARD.md
- CUSTOMER_MASTER_TEMPLATE.md
- KNOWLEDGE_INDEX.md

Account Masters should use their canonical filenames.

Before loading a CUSTOMER_MASTER into Knowledge, validate:

- Document Type
- Account
- Account ID
- Canonical File Name
- Header Version
- Body Version
- Last Updated
- UTF-8 readability

A header/body version mismatch must be corrected or explicitly reported before treating the version metadata as validated.

---

## 18. CURRENT KNOWLEDGE HEALTH

As of 2026-09-23:

### Consistent CUSTOMER_MASTER metadata

- C6 Bank — v1.8 — Last Updated 2026-09-21
- Banco Santander Brasil — v1.5 — Last Updated 2026-09-22
- Getnet — v1.6 — Last Updated 2026-09-21
- Banco BMG — v1.3 — Last Updated 2026-09-22
- Banco Inter — v1.2 — Last Updated 2026-09-21
- Zurich — v1.3 — Last Updated 2026-09-21

### CUSTOMER_MASTER metadata requiring correction

None identified in the currently registered CUSTOMER_MASTER files.

---

## 19. RELIABILITY PRINCIPLE

When completeness conflicts with evidence:

**prefer evidence.**

Never guess to make an account appear complete.

Use according to context:

- historical value with reference period;
- CONFIRMED;
- REPORTED;
- ACHIEVED;
- TARGET;
- POTENTIAL;
- INFERENCE;
- TBD;
- DADO FALTANTE.

Account intelligence must remain:

- traceable;
- temporally correct;
- isolated by customer;
- explicit about evidence maturity;
- resistant to silent assumptions.

The Knowledge Index is a registry and governance document.

It must not overwrite factual CUSTOMER_MASTER content or silently resolve conflicts that belong to source evidence.