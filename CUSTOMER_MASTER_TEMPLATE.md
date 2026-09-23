Helvetica;
Document Type: TEMPLATE
Template Type: CUSTOMER_MASTER
Version: 1.0
Last Updated: 2026-09-18
Purpose:
Define the canonical structure for CUSTOMER_MASTER documents used by Strategic Account Intelligence.
This document defines structure only.
METHODOLOGY defines interpretation and evidence rules.
OUTPUT_STANDARD defines output rules.

---

# [ACCOUNT] - CUSTOMER MASTER
Document Type: CUSTOMER_MASTER
Account: [customer name]
Account ID: [permanent account id]
Canonical File Name: [account-id]_account.md
Version: [version]
Last Updated: [YYYY-MM-DD]
Baseline: [YYYY-MM-DD]
Purpose: Persistent account knowledge base for recurring Customer Success intelligence and weekly updates.
Evidence labels:
CONFIRMED = supported by customer/project evidence
REPORTED = reported by customer, partner or internal team
ACHIEVED = measured result already realized
TARGET = planned/expected result
POTENTIAL = opportunity/business case not yet realized
INFERENCE = analytical interpretation requiring validation
Data handling rules:
- Preserve valid historical data with its reference period.
- Historical data must not be represented as current data unless newer evidence confirms it.
- Use TBD when a future date, checkpoint or status has not yet been defined or confirmed.
- Use DADO FALTANTE only when material expected information is not available in valid evidence.
- A valid historical value is not DADO FALTANTE merely because a newer measurement is unavailable.
- Roadmap does not equal implementation.
- POC does not equal production.
- Capability availability does not equal adoption.
- Token consumption does not equal business value.

---

## 1. ACCOUNT PROFILE
Customer:
[customer]
Platform:
[platform]
License / entitlement reference:
[if available]
Architecture/context:
[current supported architecture context]
Current lifecycle:
[current lifecycle]
Primary themes:
- [theme]
- [theme]
- [theme]
CSP:
[status]
EOP:
[status]
Current governance:
[governance model/cadence]
Primary account progression:
[current progression]

---

## 2. CURRENT EXECUTIVE STATUS
Provide an integrated current-state narrative.
Prioritize:
- business situation;
- material execution;
- adoption;
- achieved value;
- critical risks;
- dependencies;
- next movement.
Do not structure this section as a product inventory.
Clearly distinguish:
- achieved result;
- execution progress;
- target;
- potential;
- inference.
Current account priority:
[priority statement]

---

## 3. BUSINESS OBJECTIVES / DRIVERS
Supported objectives:
- [objective]
- [objective]
- [objective]
Only include objectives supported by account evidence.
Do not convert vendor recommendations into customer objectives without evidence.

---

## 4. CUSTOMER KPIs / MEASUREMENT
### [Workstream / Business Dimension]
Measurement dimensions:
- [KPI]
- [KPI]
- [KPI]
Baseline:
[value + period if available]
Target:
[value if available]
Current measured outcome:
[value if available]
If a valid historical baseline exists, preserve it with its period.
If material information does not exist:
DADO FALTANTE: completar [information].

---

## 5. ADOPTION SNAPSHOT
### Current evidence
Licenses / users:
[value and reference period]
Feature adoption:
[value and reference period]
AI / tokens:
[value and reference period]
Eligible population:
[value if available]
Active population:
[value if available]
Production/pilot status:
[state]
### Historical adoption
Preserve relevant historical measurements with explicit dates/periods.
Do not infer current adoption from historical trends.
### Adoption interpretation
Distinguish:
- entitled;
- available;
- configured;
- pilot;
- productive pilot;
- production;
- active use;
- measured business value.

---

## 6. ACTIVE INITIATIVES
Create one subsection for each material active initiative.
Do not create a subsection merely because a product/capability exists.
### 6.X [INITIATIVE NAME]
Status:
[current maturity]
Business objective:
[if supported]
Current situation/activity:
[factual current state]
Result:
[ACHIEVED / confirmed progress / none yet]
Risk/dependency:
[if applicable]
Next:
[next material action]
Checkpoint:
[date or TBD]
Repeat as required.

---

## 7. EOP / CSP
### CSP
Status:
[status]
Describe:
- current maturity;
- strategic role;
- execution/governance implications.
Do not convert CSP roadmap into completed execution.
### EOP
Status:
[Draft / Presented / Validated / In Review / Blocked / Next Cycle]
Reference:
[date if available]
Describe:
- strategic direction;
- prioritized areas;
- adoption/value baseline;
- maturity.
Rules:
- EOP roadmap does not equal implementation.
- EOP projection does not equal saving.
- EOP recommendation does not automatically equal customer priority.

---

## 8. RESULTS / VALUE REALIZED
### ACHIEVED
List measured realized outcomes.
For every quantified result preserve when available:
- population;
- timeframe;
- baseline;
- measured change;
- context.
### CONFIRMED PROGRESS - NOT BUSINESS VALUE
List execution/adoption progress that is real but not a business outcome.
### TARGET / POTENTIAL
List future targets, business cases and opportunities.
Never mix these categories.

---

## 9. RISKS & BLOCKERS
### R1 - [Risk]
Status:
[active/monitoring/etc.]
Type:
[technical/adoption/value/architecture/relationship/commercial/etc.]
Context:
[fact]
Impact:
[impact]
Dependency/owner:
[when supported]
Action:
[action]
Checkpoint:
[date/TBD]
Repeat by materiality.
Do not state hypotheses as root causes.

---

## 10. CRITICAL CASES
### [CASE NUMBER] - [SEVERITY IF SUPPORTED]
Context:
[issue]
Impact:
[business/operational impact]
Status:
[current supported status]
Dependencies:
[if applicable]
Next:
[next action]
Checkpoint:
[date/TBD]
If no current critical numbered case is established:
N/A based on available evidence.
If a material case exists but its formal number is unavailable:
DADO FALTANTE: completar formal case number.
Do not interpret mitigation/stabilization as closure unless evidence confirms closure.

---

## 11. CTA / WORKSTREAM STRUCTURE
### [CTA / WORKSTREAM]
Status:
[current status]
Current:
[current situation/activity]
Result:
[result if available]
Risk:
[dependency/risk]
Next:
[next action]
Checkpoint:
[date/TBD]
CTA represents work, not a product list.

---

## 12. NEXT MILESTONES
- [date]: [milestone]
- [date]: [milestone]
- [workstream]: TBD
Use only supported dates.
Do not invent dates to make the roadmap appear complete.

---

## 13. CUSTOMER / ACCOUNT DECISIONS
Preserve material decisions such as:
- architecture decisions;
- prioritization decisions;
- rollout/scale decisions;
- customer ownership;
- partner responsibilities;
- validated roadmap decisions.
Do not convert recommendation into decision.

---

## 14. GOVERNANCE
Describe the governance model.
Include relevant organizational roles/categories without unnecessary individual contact details.
Explicitly distinguish:
- customer responsibility;
- Genesys responsibility;
- partner responsibility;
- supplier dependency;
- support;
- project;
- adoption;
- architecture;
- business value.
Include cadence when supported.

---

## 15. EVIDENCE LEDGER
### [YYYY-MM-DD] - [Evidence/Cycle]
Type:
[CONFIRMED / REPORTED / ACHIEVED / TARGET / POTENTIAL / HISTORICAL]
Material evidence:
- [fact]
- [fact]
- [fact]
Do not use this section as a meeting transcript.
Preserve only material account intelligence.

---

## 16. HISTORICAL TIMELINE
### [YYYY-MM-DD] - [Cycle/Event]
Current state:
- [state]
Changes:
- NEW:
- UPDATED:
- UNCHANGED:
- COMPLETED:
- BLOCKED:
- SUPERSEDED:
- CONFLICT:
Use only applicable classifications.
Decisions:
- [decision]
Results:
- [result]
Risks:
- [risk]
Completed:
- [completed item]
Next:
- [next movement]
Preserve previous material outcomes.

---

## 17. OUTPUT RULES FOR FUTURE UPDATES
Include account-specific rules that must survive future updates.
Examples:
1. Preserve measured outcomes with population/timeframe.
2. Historical adoption must not be represented as current adoption.
3. Roadmap does not equal implementation.
4. Capability availability does not equal adoption.
5. Token consumption does not equal business value.
6. POC does not equal production.
7. Business case does not equal saving.
8. Customer-owned technology does not equal vendor adoption.
9. Preserve material architecture decisions.
10. Preserve material case numbers and supported status.
11. Use DADO FALTANTE only when material information is actually unavailable.
12. Use TBD for unresolved future dates/checkpoints.
13. Every active CTA should contain next step/checkpoint when supported.
14. Preserve account-specific evidence rules.
15. Supported outputs:
- Lideranca
- Gerencial
- CTAs
- Completo
- Status Semanal Brasil