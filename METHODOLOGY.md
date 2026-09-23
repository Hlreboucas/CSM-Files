Helvetica;
Document Type: METHODOLOGY
Version: 1.0
Last Updated: 2026-09-18
Purpose:
Define the authoritative rules for interpreting evidence, maintaining CUSTOMER_MASTER documents and generating Strategic Account Intelligence outputs.
This document defines HOW account intelligence must be managed.

---

## 1. CORE PRINCIPLES
Always:
1. Interpret and correlate evidence.
2. Identify material changes.
3. Separate fact from hypothesis.
4. Preserve historical evidence.
5. Prioritize business impact and criticality.
6. Identify next steps, dependencies and checkpoints.
7. Make material information gaps explicit.
8. Preserve account boundaries.
9. Preserve evidence maturity.
10. Prefer newer valid evidence for Current State without destroying valid historical evidence.
Never invent:
- numbers;
- dates;
- results;
- decisions;
- priorities;
- owners;
- checkpoints;
- adoption;
- business value;
- customer commitments.
Never use another customer's information to complete an account.

---

## 2. KNOWLEDGE PRIORITY
Document precedence:
1. METHODOLOGY
2. OUTPUT_STANDARD
3. CUSTOMER_MASTER
4. EVIDENCE
5. TEMPLATE
METHODOLOGY and OUTPUT_STANDARD define HOW to work.
CUSTOMER_MASTER defines WHAT is currently consolidated for an account.
EVIDENCE may contain facts that are newer than the CUSTOMER_MASTER.
TEMPLATE defines the expected document structure.
Do not use upload order as evidence priority.
Use:
- Document Type;
- Account;
- Account ID;
- Version;
- Last Updated;
- evidence date;
- evidence maturity.

---

## 3. ACCOUNT ISOLATION
Each account is independent.
Never mix:
- metrics;
- cases;
- projects;
- risks;
- architecture;
- decisions;
- adoption;
- value;
- stakeholders;
- milestones;
- opportunities
customers.
Account identification must use:
Account
Account ID
Do not rely only on the physical filename.

---

## 4. CUSTOMER MASTER IDENTIFICATION
Each CUSTOMER_MASTER must contain:
Document Type: CUSTOMER_MASTER
Account:
Account ID:
Canonical File Name:
Version:
Last Updated:
Account ID is permanent.
Canonical File Name is permanent.
Canonical naming format:
[account-id]_account.md
Examples:
-bank_account.md
-brasil_account.md
_account.md
-bmg_account.md
-inter_account.md
_account.md
The physical filename should match Canonical File Name exactly.

---

## 5. MULTIPLE CUSTOMER MASTERS
If multiple CUSTOMER_MASTER documents exist for the same Account ID:
1. Select the highest Version.
2. If Version is tied, select the most recent Last Updated.
3. Flag duplicate Masters when material.
4. Never combine two Masters as if both were simultaneously authoritative.
5. Older Masters may be used as historical evidence when required.

---

## 6. EVIDENCE CLASSIFICATION
Use the following classifications.
### CONFIRMED
Supported by customer, project, platform or other reliable evidence.
### REPORTED
Reported by customer, partner, supplier or internal team but not independently demonstrated by measured evidence.
### ACHIEVED
Measured result already realized.
ACHIEVED requires evidence of an actual result.
### TARGET
Planned or expected result.
TARGET is not ACHIEVED.
### POTENTIAL
Opportunity, business case, projection or modeled value that has not been realized.
POTENTIAL is not saving.
### INFERENCE
Analytical interpretation requiring validation.
INFERENCE must never be presented as confirmed root cause or customer fact.

---

## 7. NON-CONVERSION RULES
Never convert:
TARGET -> ACHIEVED
POTENTIAL -> ACHIEVED
case -> saving
-> realized value
-> implementation
-> customer decision
POC -> production
-> adoption
available -> adoption
consumption -> business value
progress -> business outcome
approval -> implementation
perception -> proven fact
issue -> current incident
adoption -> current adoption
initiative -> customer initiative
initiative -> Genesys initiative
-party technology -> Genesys adoption

---

## 8. TEMPORAL EVIDENCE
Every quantified fact should preserve its reference period when available.
Example:
614 active users / 700 contracted - June/2026 baseline.
Do not transform this into:
Current adoption: 614 / 700
newer evidence confirms it is current.
Historical evidence remains valid historical evidence until superseded or invalidated.
New evidence may supersede Current State without deleting historical facts.

---

## 9. DATA FRESHNESS VS MISSING DATA
Freshness and absence are different concepts.
### Existing historical data
If valid information exists but is from an earlier period:
Preserve:
- value;
- reference date/period;
- classification.
Example:
Baseline June/2026:
614 active users / 700 contracted.
A September measurement is not available.
Correct interpretation:
June/2026 baseline remains valid historical evidence. It must not be represented as September utilization.
Do not automatically classify the June value as DADO FALTANTE.
### DADO FALTANTE
Use:
DADO FALTANTE: completar [informacao]
when material expected information is not available in valid evidence.
Examples:
DADO FALTANTE: completar business targets for C6 Pay.
DADO FALTANTE: completar current status of Quality permissions.
DADO FALTANTE: completar formal case number.
### TBD
Use TBD when the information is intentionally unresolved or not yet defined.
Typical examples:
Checkpoint: TBD.
Next review: TBD.
GPR pilot date: TBD.
Do not replace every TBD with DADO FALTANTE.

---

## 10. CURRENT STATE
Current State represents the best-supported current account condition.
When new evidence is received:
1. Identify its date.
2. Identify the affected account.
3. Compare against current CUSTOMER_MASTER.
4. Determine whether it changes Current State.
5. Preserve older evidence as history when still valid.
Older evidence may enrich Historical Timeline without downgrading Current State.
Never allow an older roadmap or EOP to overwrite newer execution evidence.
Example:
Historical EOP:
Copilot = opportunity.
New evidence:
Copilot = productive pilot.
Current State:
Productive pilot.
Historical EOP remains preserved as history.

---

## 11. CHANGE CLASSIFICATION
For updates classify material changes as:
NEW
UPDATED
UNCHANGED
COMPLETED
BLOCKED
SUPERSEDED
CONFLICT
### NEW
New material information not previously represented.
### UPDATED
Existing information materially changed.
### UNCHANGED
New evidence confirms existing state.
### COMPLETED
Previously active activity has evidence of completion.
### BLOCKED
Execution cannot progress because of a material dependency.
### SUPERSEDED
Newer evidence replaces an older Current State.
### CONFLICT
Two valid evidence sources materially disagree and the conflict cannot yet be resolved.
Do not silently resolve CONFLICT through inference.

---

## 12. UPDATE PROTOCOL
When requested:
Atualizar [Cliente]
the following:
1. Locate the correct CUSTOMER_MASTER.
2. Validate Account and Account ID.
3. Read Version and Last Updated.
4. Identify evidence later than or not consolidated into the Master.
5. Compare previous vs current evidence.
6. Classify each material change.
7. Classify evidence maturity.
8. Evaluate only affected areas:
- Current State;
- adoption;
- initiatives;
- projects;
- results;
- risks;
- cases;
- decisions;
- CTAs;
- milestones;
- governance.
9. Preserve historical results.
10. Identify Evidence Ledger entries.
11. Identify Historical Timeline entries.
Atualizar does not consolidate permanently.
Output only the delta.
Do not increment Version.

---

## 13. CYCLE CLOSURE PROTOCOL
Only when explicitly requested:
Fechar ciclo [Cliente]
permanent consolidation.
Rules:
1. Use the authoritative CUSTOMER_MASTER.
2. Incorporate valid evidence.
3. Increment Version by 0.1.
4. Update Last Updated.
5. Modify only affected sections.
6. Preserve historical facts.
7. Update Evidence Ledger.
8. Update Historical Timeline.
9. Preserve Account ID.
10. Preserve Canonical File Name.
11. Produce the complete CUSTOMER_MASTER.
Never return only a delta for Fechar ciclo.
Header:
FILE: [Canonical File Name]
VERSION: [new version]
REPLACES: [previous version]
Do not claim that a physical file was created unless it was actually created.

---

## 14. ADOPTION
Adoption must distinguish:
- contracted licenses;
- active users;
- utilization;
- features in use;
- entitled features;
- AI resources;
- token availability;
- token consumption;
- eligible population;
- active population;
- production use;
- pilot use.
Capability availability is not adoption.
Token consumption is evidence of usage, not automatically business value.
Historical adoption must preserve its measurement period.
Do not infer current adoption from a historical trend.

---

## 15. VALUE AND OUTCOMES
Value reporting must distinguish:
### ACHIEVED VALUE
Measured realized result.
Examples:
- measured TMA reduction;
- measured productivity increase;
- measured complaint reduction;
- measured SLA improvement.
Always preserve:
- population;
- timeframe;
- baseline when available;
- measurement context.
### CONFIRMED PROGRESS
Execution or adoption progress without proven business value.
Examples:
- pilot started;
- project On Track;
- monitoring form published;
- roadmap milestone completed;
- configuration completed.
### TARGET
Expected future outcome.
### POTENTIAL
Business case, modeled benefit or opportunity.
Never generalize a measured result beyond the measured population.

---

## 16. POC AND PILOT
POC demonstrates a result only within its measured scope.
POC does not equal production.
Pilot does not equal scaled adoption.
Productive pilot confirms operational use but not automatically business value.
Preserve:
- measured population;
- timeframe;
- success criteria;
- actual result;
- customer decision regarding scale.

---

## 17. CASES
Critical Cases should include when available:
- case number;
- context;
- impact;
- status;
- dependency;
- next action;
- checkpoint.
Do not invent case numbers.
If evidence establishes that no current critical numbered case exists:
N/A
If a material case exists but its formal number is unavailable:
DADO FALTANTE: completar formal case number.
Mitigation or technical stabilization does not automatically equal case closure.
Investigation may remain open after service stabilization.

---

## 18. RISKS AND BLOCKERS
A risk should contain when supported:
- context;
- business/operational impact;
- dependency;
- owner/responsibility boundary;
- current situation;
- action.
Do not convert a hypothesis into root cause.
Keep separate:
- project risk;
- adoption risk;
- technical risk;
- relationship risk;
- architecture risk;
- commercial risk;
- value-realization risk.

---

## 19. ARCHITECTURE
Respect customer architecture decisions.
Explicitly distinguish:
- Genesys capability;
- customer-developed technology;
- partner technology;
- third-party technology;
- integration layer;
- Professional Services;
- customer implementation.
Do not attribute customer development to Genesys.
Do not classify third-party technology as Genesys adoption.
Example:
IBM Watson integrated through Genesys Audio Connector
not equal
Genesys Virtual Agent adoption.

---

## 20. CTA DEFINITION
CTA represents real work, not a product list.
A strong CTA includes when supported:
- current situation;
- activity completed/in progress;
- result;
- risk/dependency;
- next step;
- checkpoint/date.
Group related topics when this improves governance.
Do not create a new CTA solely because a capability exists.

---

## 21. EOP AND CSP
EOP and CSP maturity must reflect actual evidence.
Possible EOP maturity examples:
Draft
Presented
Validated
In Review
Blocked
Next Cycle
Roadmap inclusion does not equal implementation.
An EOP projection is POTENTIAL unless realized evidence exists.
CSP roadmap is governance/intent unless individual initiatives have execution evidence.

---

## 22. EVIDENCE LEDGER
Evidence Ledger records material evidence incorporated into the account.
Include:
- date;
- evidence type;
- classification;
- material facts;
- decisions;
- results;
- risks where relevant.
Do not use Evidence Ledger as an unfiltered meeting transcript.

---

## 23. HISTORICAL TIMELINE
Historical Timeline preserves material account evolution.
Typical structure:
Current state
Changes
Decisions
Results
Risks
Completed
Next
Historical Timeline must preserve previous achieved outcomes even when the account evolves.

---

## 24. GOVERNANCE
Account governance must distinguish:
- customer responsibility;
- Genesys responsibility;
- partner responsibility;
- supplier dependency;
- architecture decision;
- project progress;
- adoption;
- support;
- business value.
Do not list unnecessary individual email addresses or interlocutor details in executive outputs.

---

## 25. CRITICALITY
Output depth should be proportional to criticality.
Higher criticality requires greater context around:
- impact;
- dependencies;
- ownership;
- mitigation;
- next action;
- checkpoint.
Do not reduce a critical issue to a one-line status solely to shorten an executive table.

---

## 26. STATUS SEMANAL
Status Semanal is a weekly snapshot.
It is not a cumulative history dump.
Use the CUSTOMER_MASTER plus valid newer evidence.
Historical metrics may be included when they materially contextualize the account, but their period must be explicit.
Do not present historical adoption as current adoption.

---

## 27. LEVEL OF ORCHESTRATION
Do not infer N
ível de Orquestra
ão until an explicit taxonomy has been defined.
Until then:
DADO FALTANTE: completar taxonomia.
This is a legitimate missing-data case because the classification framework itself does not yet exist.

---

## 28. OUTPUT LANGUAGE AND STYLE
Default language:
Portuguese for account-management outputs unless requested otherwise.
Style:
- executive;
- direct;
- factual;
- consultative;
- business impact before technical detail.
Always distinguish:
- fact;
- reported information;
- achieved result;
- target;
- potential;
- inference.
Avoid unnecessary verbosity.
Increase detail when criticality requires context.

---

## 29. SUPPORTED COMMANDS
Atualizar [Cliente]
Generate delta only.
Do not consolidate permanently.
Gerar Lideranca [Cliente]
Generate concise C-Level view.
Gerar Gerencial [Cliente]
Generate management view.
Gerar CTAs [Cliente]
Generate factual execution-oriented CTA updates.
Gerar Completo [Cliente]
Generate integrated full account narrative.
Gerar Status Semanal Brasil
Generate the 13-column weekly Brazil management view.
Fechar ciclo [Cliente]
Consolidate valid evidence, increment Version and produce complete CUSTOMER_MASTER.

---

## 30. FINAL CONTROL RULE
When evidence is insufficient:
not guess.
Preserve:
TBD
INFERENCE
period
DADO FALTANTE
to the nature of the gap.
Reliability is more important than apparent completeness.