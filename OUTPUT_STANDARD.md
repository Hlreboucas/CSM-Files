Helvetica;
Document Type: OUTPUT_STANDARD
Version: 1.0
Last Updated: 2026-09-18
Purpose:
Define authoritative output structures and reporting rules for Strategic Account Intelligence.
METHODOLOGY defines evidence interpretation.
CUSTOMER_MASTER defines consolidated account state.
This document defines HOW information must be presented.

---

## 1. GENERAL OUTPUT PRINCIPLES
All outputs must be:
- factual;
- executive;
- direct;
- consultative;
- business-oriented;
- proportional to account criticality.
Always prioritize:
impact -> execution -> value -> risk -> dependency -> next movement.
Do not prioritize technical detail before business context unless the technical issue itself is the critical business risk.
Preserve evidence maturity:
CONFIRMED
REPORTED
ACHIEVED
TARGET
POTENTIAL
INFERENCE
Never silently convert one maturity level into another.

---

## 2. TEMPORAL DATA IN OUTPUTS
When a valid metric exists, show its reference period.
Example:
Baseline Jun/26:
614 active users / 700 contracted.
Do not write:
Current adoption: 614 / 700
the evidence supports current status.
If a newer measurement is unavailable, preserve the historical metric and its period.
Do not automatically write DADO FALTANTE merely because the existing metric is historical.

---

## 3. DADO FALTANTE
Use:
DADO FALTANTE: completar [information]
when material expected information does not exist in valid evidence.
Examples:
DADO FALTANTE: completar formal case number.
DADO FALTANTE: completar customer-approved business target.
DADO FALTANTE: completar taxonomia de Nivel de Orquestracao.
Do not use DADO FALTANTE simply because:
- a metric is historical;
- a future checkpoint is TBD;
- a TARGET has not yet been achieved.

---

## 4. TBD
Use TBD for future information that is unresolved, undefined or not yet confirmed.
Examples:
Checkpoint: TBD.
GPR pilot: TBD.
EOP next review: TBD.
TBD is not automatically a data-quality problem.

---

## 5. LEADERSHIP OUTPUT - LIDERANCA
Command:
Gerar Lideranca [Cliente]
Purpose:
Short C-Level account view.
Required narrative:
1. Current situation.
2. Principal evolution/result.
3. Greatest material risk.
4. Next movement.
Focus on:
- business impact;
- value;
- executive risk;
- strategic decision;
- material next step.
Avoid:
- product inventory;
- unnecessary implementation detail;
- long case histories;
- individual interlocutor lists.
Recommended length:
Short executive narrative.

---

## 6. MANAGEMENT OUTPUT - GERENCIAL
Command:
Gerar Gerencial [Cliente]
Purpose:
Management-level account orchestration.
Include:
- context;
- current state;
- active fronts;
- achieved results;
- adoption;
- risks;
- blockers;
- decisions;
- dependencies;
- cases;
- next movements;
- checkpoints.
Depth must increase with criticality.
Separate:
- execution progress;
- adoption;
- achieved value;
- potential value.

---

## 7. CTA OUTPUT
Command:
Gerar CTAs [Cliente]
Purpose:
Execution-oriented factual updates suitable for Customer Success/Gainsight governance.
Each CTA should contain when supported:
CTA / Workstream
Status
Current situation
Activity completed/in progress
Result
Risk/dependency
Next step
Checkpoint
CTA must represent actual work.
Do not create CTAs as a list of products or capabilities.
Example structure:
### Predictive Routing
Status:
Production / optimization.
Current:
Measured benefit exists but varies by population.
Result:
4.2% TMA reduction in expanded measured sample.
Risk:
Transfer Rate and unexplained performance variability.
Next:
Correlate routing configuration, candidate population, availability and operational KPIs.
Checkpoint:
TBD.

---

## 8. COMPLETE OUTPUT - COMPLETO
Command:
Gerar Completo [Cliente]
Purpose:
Integrated full account narrative.
Do not artificially structure the entire output by CTA.
Consolidate:
- executive situation;
- business objectives;
- architecture;
- adoption;
- projects;
- initiatives;
- results;
- value;
- risks;
- cases;
- decisions;
- EOP/CSP;
- governance;
- dependencies;
- next movements.
Preserve account history where it materially explains Current State.
Do not turn the output into a chronological transcript.

---

## 9. STATUS SEMANAL BRASIL
Command:
Gerar Status Semanal Brasil
Purpose:
Weekly management and orchestration snapshot across available Brazil accounts.
This is a weekly photograph.
It is not a cumulative history report.
The output must use EXACTLY the following 13 columns, in this order:
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
Do not replace this structure with:
- one card per account;
- one cell containing all 13 topics;
- separate sections by account;
- alternative column names.
One account = one row.

---

## 10. STATUS SEMANAL - CONTA
Use the canonical customer/account name.
Do not abbreviate in a way that can create account ambiguity.

---

## 11. STATUS SEMANAL - STATUS GERAL
Status geral must synthesize:
- current business situation;
- execution;
- risk;
- adoption;
- relationship/governance;
- material milestones.
It must not be a generic color/status label without context.
Higher criticality requires more context.
Examples of useful status narratives:
"Post-migration focused on stabilization, adoption and value; Copilot is the most mature AI workstream while data architecture and support ownership remain material dependencies."
"Incident mitigated but technical investigation remains open; executive priority is operationalizing Incident Readiness while preserving GPR/Copilot value."
Do not infer closure from mitigation.

---

## 12. STATUS SEMANAL - AGENDAS / ATIVIDADES
Include when supported:
+ objective + workstream.
Example:
30/09 - Operational Readiness review - support model.
If activity exists but no date is defined, include the activity without inventing a date.
Do not use DADO FALTANTE simply because an activity has no date.

---

## 13. STATUS SEMANAL - SITUACAO / RISCOS / BLOCKERS
For material risks include when supported:
- context;
- impact;
- dependency;
- ownership boundary;
- current state.
Do not reduce a critical risk to a product name.
Do not state INFERENCE as root cause.

---

## 14. STATUS SEMANAL - CASES CRITICOS
Include:
number + context + impact/status.
Example:
0004177350 - post-migration support/evidence escalation; partner-chain log dependency delayed evidence collection; Operational Readiness remains active.
If no current critical numbered case exists:
N/A
If a critical case is evidenced but the formal number is unavailable:
DADO FALTANTE: completar formal case number.
If a formal case number exists anywhere in valid account evidence, preserve it.
Do not omit a known case number merely because a later summary does not repeat it.
Mitigated/stabilized does not equal closed.

---

## 15. STATUS SEMANAL - PLANO DE ACAO
Include:
- actions;
- mobilizations;
- escalations;
- dependencies;
- required support;
- next operational movement.
Prefer actionable language.
Example:
"Define target data environment, open Genesys case and validate supported A3S/Snowflake approach."
Avoid generic wording such as:
"Continue monitoring."
monitoring itself is the supported next action.

---

## 16. STATUS SEMANAL - EOP / CSP
Represent actual maturity.
Examples:
CSP: established.
EOP: presented July/2026.
CSP: established.
EOP: Draft / not customer-validated.
Do not convert:
Draft -> Presented
Presented -> Validated
Roadmap -> Implementation
If a review date is TBD, show TBD when material.

---

## 17. STATUS SEMANAL - ADOPTION
Include the best valid evidence available for:
- licenses;
- active users;
- utilization;
- features;
- AI resources;
- tokens;
- pilot/production stage.
Always preserve reference period.
Example:
Baseline Jun/26:
614/700 active users; 9/21 features; 200/25,320 tokens; 2/7 AI resources.
This is better than:
DADO FALTANTE: September adoption.
If newer September data do not exist, state that the figures are the June baseline and do not represent September automatically.
Token consumption does not equal business value.
Third-party/customer technology does not equal Genesys adoption.

---

## 18. STATUS SEMANAL - VALUE & OUTCOMES
Separate:
ACHIEVED
CONFIRMED PROGRESS
TARGET
POTENTIAL
Prioritize quantified ACHIEVED results.
Example:
ACHIEVED:
16.31% TMA reduction in historical GPR POC.
POTENTIAL:
R$3-4M historical business case.
Never write:
R$3-4M savings
realized savings are evidenced.
Preserve measured population and timeframe when material.

---

## 19. STATUS SEMANAL - OPPORTUNITIES
Show maturity.
Possible maturity language:
Discovery
Assessment
Prioritization
POC
Pilot
Productive pilot
Production
Optimization
POTENTIAL
Do not present:
as implementation;
case as value;
capability as adoption.
Customer or third-party initiatives may create Genesys integration opportunities, but must remain correctly attributed.

---

## 20. STATUS SEMANAL - PROXIMO MARCO
Use the most material actionable next milestone.
Include date/window only when supported.
Examples:
30/09 - Customer homologation.
01/10 - Copilot checkpoint.
GPR optimization review - TBD.
Do not invent dates.

---

## 21. STATUS SEMANAL - NIVEL DE ORQUESTRACAO
No taxonomy is currently defined.
Until a formal taxonomy exists, use:
DADO FALTANTE: completar taxonomia.
Do not infer High/Medium/Low or similar labels.

---

## 22. STATUS SEMANAL - ULTIMA ATUALIZACAO
Use the latest supported account update date.
Do not use the report-generation date if the account evidence itself is older, unless new evidence was actually incorporated on that date.

---

## 23. STATUS SEMANAL - CRITICALITY
Criticality controls depth, not unsupported scoring.
A critical account should receive more context around:
- impact;
- case;
- risk;
- executive sensitivity;
- dependency;
- mitigation;
- next action.
Do not assign unsupported numeric or color risk scores.

---

## 24. STATUS SEMANAL - HISTORICAL DATA
Historical information may be included when it materially supports management.
Examples:
- historical POC result;
- latest available adoption baseline;
- prior achieved outcome still relevant.
Always preserve timeframe.
Historical evidence must not overwrite newer Current State.

---

## 25. STATUS SEMANAL - SYNTHESIS
After the 13-column table, a short management synthesis may be included.
It should focus on:
- highest current orchestration needs;
- cross-account dependencies;
- material value realization;
- transversal gaps.
Do not repeat the full table.

---

## 26. FACT VS INTERPRETATION
Facts:
State directly when supported.
Reported claims:
Identify as reported when material.
Inference:
Explicitly identify as INFERENCE.
Do not make causal statements without supporting evidence.

---

## 27. EXECUTIVE LANGUAGE
Prefer:
"GPR remains in production with positive but variable measured benefit."
Instead of:
"GPR is performing badly."
Prefer:
"Customer reported dissatisfaction with advisory depth."
Instead of:
"Professional Services is poor."
Prefer factual evidence over evaluative language.

---

## 28. VALUE DISCIPLINE
Always distinguish:
outcome
outcome
Example:
43% token utilization = adoption/usage evidence.
It does not automatically equal:
gain;
reduction;
gain.

---

## 29. PROJECT DISCIPLINE
On Track = project schedule state.
It does not automatically equal:
value.
Technical approval does not equal implementation.
Deployment does not equal successful homologation.
Homologation does not equal measured value.

---

## 30. OUTPUT QUALITY CONTROL
Before finalizing an output verify:
1. Correct account.
2. Correct Account ID.
3. Latest authoritative Master.
4. Newer valid evidence considered.
5. No cross-account contamination.
6. Historical metrics have periods.
7. TARGET not converted to ACHIEVED.
8. POTENTIAL not converted to saving.
9. Roadmap not converted to implementation.
10. POC not converted to production.
11. Token usage not converted to value.
12. Customer/third-party technology correctly attributed.
13. Known critical case numbers preserved.
14. Mitigation not converted to closure.
15. TBD used appropriately.
16. DADO FALTANTE used only for actual missing material information.
17. Next steps/checkpoints supported.
18. Status Semanal uses exactly 13 columns.