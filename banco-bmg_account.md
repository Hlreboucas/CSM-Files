FILE: banco-bmg_account.md
VERSION: 1.3
REPLACES: 1.2

# BANCO BMG - CUSTOMER MASTER

Document Type: CUSTOMER_MASTER
Account: Banco BMG
Account ID: banco-bmg
Canonical File Name: banco-bmg_account.md
Version: 1.3
Last Updated: 2026-09-22
Baseline: 2026-09-16
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
- Token consumption is an adoption indicator, not automatically business value.
- Roadmap does not equal implementation.
- Assessment does not equal realized benefit.

---

## 1. ACCOUNT PROFILE
Customer: Banco BMG
Platform: Genesys Cloud.
Current lifecycle:
Post-migration / stabilization / adoption / value realization.
Architecture/context:
Voice operation integrated with Salesforce/A3S; partner-supported operating model.
Population reference:
Approximately 350 agents, with historical expansion planning of approximately +150.
Primary current themes:
- Copilot
- AI Tokens
- Salesforce dependency
- Predictive Routing (GPR)
- WEM
- Quality
- Speech Analytics
- AI Scoring
- WFM/CRC
- A3S/Snowflake reporting
- External-data integration
- Post-migration support
- Customer Success governance

CSP:
CONFIRMED / established.

EOP:
Draft / not validated as presented to customer.

Current governance:
Direct recurring BMG-Genesys governance.

Historical cadence:
Quinzenal.

Primary account progression:
completed -> stabilization -> adoption -> measurable outcomes -> optimization -> scale

---

## 2. CURRENT EXECUTIVE STATUS
Banco BMG has completed the migration to Genesys Cloud and is now in a post-migration phase focused on operational stabilization, adoption, optimization and measurable value generation.

Copilot remains the most mature AI-adoption workstream.

Historical token utilization increased materially from approximately 7% to 43% of contracted capacity.
This represents material adoption progression but does not establish business value by itself.

Salesforce remains the principal Copilot architecture dependency.
Knowledge replication can take approximately six hours, affecting content freshness and the ability to scale additional use cases.

WEM has moved beyond discovery.
Current evidence supports:
- initial Quality monitoring;
- Speech topics in use;
- published monitoring form;
- approximately 70 questions in the form;
- approximately 15 questions with potential for Speech-supported automation;
- AI Scoring sizing/evolution as a subsequent maturity step.

WFM has a concrete CRC workstream.

Predictive Routing has completed a Benefit Assessment identifying:
- 14 high-potential queues;
- 874 memberships.
This remains assessment/prioritization evidence.
874 memberships must not be interpreted as 874 unique agents.

No GPR business benefit has yet been demonstrated through a controlled production test.

Data/reporting remains a material transversal dependency.
BMG is evaluating how A3S/Snowflake data can be made available to an external Data Warehouse/Data Lake environment.
As of 17/09/2026, there is no official Genesys procedure/documentation available that defines extraction from A3S Snowflake for this requirement.
Available Snowflake mechanisms can be evaluated, but must not be represented as a Genesys-validated A3S procedure.

Intended path:
target requirement/environment -> evaluate applicable Snowflake mechanism -> open Genesys case -> assess implementation/support approach

Professional Services remains a potential alternative, subject to commercial contracting through Claro.

**POST-MIGRATION SUPPORT FRICTION - CRITICAL:**
Case 0004177350 (External Routing / Messaging transfers to queue) exposed evidence-collection, ownership and escalation dependencies involving Claro/Tellmex, GFT and Genesys.
BMG is requesting war room to coordinate investigation across fragmented ownership model.

**UPDATE 22/09/2026 (REPORTED, pending validation):**
Genesys Engineering delivered the first concrete technical diagnosis for Case 0004177350: the Salesforce record-triggered flow behaves differently between record creation (Initial Creation / Non-Transfer scenario, triggered on record CREATE) and record update (Transfer scenario, triggered on record UPDATE). This finding was communicated to the GFT team on 22/09/2026 for review and confirmation. Resolution now depends on GFT validating this configuration on their side; no GFT confirmation recorded yet as of this update.

**UPDATE 21/09/2026 (REPORTED):**
CSM (Hugo Reboucas) formally escalated Case 0004177350 to Resolution Management (RM) LATAM, citing limited visibility into case evolution, prioritization and next steps. CSM also flagged a possible correlation with C6 Bank case 0004151486, which has an indicated correction ETA of end of September 2026 — this correlation is INFERENCE/hypothesis only and has not been confirmed via Jira/Engineering.

The CSP provides the account-level success path from operational stability toward WEM Adoption, Copilot, GPR and business impact.

The EOP Draft provides potential-value and future-capability hypotheses, but remains incomplete and must not be treated as a customer-validated roadmap.

Current account priority:
support -> sustain Copilot adoption -> convert adoption into measured value -> resolve post-migration support friction -> mature WEM -> prioritize GPR -> resolve data architecture -> increase customer autonomy -> scale only after evidence

---

## 3. BUSINESS OBJECTIVES / DRIVERS
Current objectives supported by EOP and subsequent account evidence:

- Convert completed migration into sustainable operational adoption.
- Stabilize the post-migration operating/support model.
- Reduce operational failures and support friction.
- Increase customer autonomy in operating the platform.
- Increase AI adoption and measurable value through Copilot.
- Improve Knowledge availability/freshness supporting Copilot.
- Improve Quality-monitoring governance.
- Centralize Quality evaluations in Genesys where appropriate.
- Use Speech Analytics to support structured Quality processes.
- Progress toward AI Scoring plus human validation.
- Improve WFM maturity for CRC.
- Evaluate GPR in populations with measurable optimization potential.
- Improve data/reporting access.
- Enable reliable A3S/Snowflake data consumption where technically validated.
- Reduce dependency on fragmented/manual operational controls.
- Improve operational efficiency.
- Create a foundation for additional automation and AI.
- Progress from adoption toward measurable business impact.
- Evaluate future cost reduction, CX improvement and efficiency opportunities.
- **Resolve post-migration support escalation model and ownership clarity.**

CSP-level strategic drivers include:
- reduce costs;
- increase revenue;
- increase operational efficiency.

These are strategic goals, not achieved outcomes.

---

## 4. CUSTOMER KPIs / MEASUREMENT

### 4.1 Copilot
Measurement dimensions:
- AI Token consumption.
- Eligible population.
- Usage/adoption.
- Knowledge freshness.
- Salesforce replication delay.
- Operational productivity.
- TMA where applicable.
- Business outcome.

Historical adoption:
7% -> approximately 43% token utilization.

The current eligible-user population and measured operational/business outcome are not available in the consolidated evidence.

DADO FALTANTE: completar current eligible-user population and measured operational/business outcome.

### 4.2 Quality / Speech / AI Scoring
Measurement dimensions:
- evaluation coverage;
- automated-monitoring coverage;
- manual-monitoring reduction;
- Speech automation potential;
- AI Scoring token requirement;
- evaluation consistency;
- operational/Quality outcome.

Current evidence:
- approximately 70 monitoring questions;
- approximately 15 potentially automatable through Speech.

No business-value outcome is yet confirmed.

### 4.3 Predictive Routing
Measurement dimensions:
- TMA;
- Transfer Rate;
- Service Level;
- Wait Time;
- Candidate population;
- Optimization benefit.

Current evidence:
- 14 high-potential queues;
- 874 memberships.

No achieved optimization result.

### 4.4 WFM / CRC
Measurement dimensions:
- forecast;
- adherence;
- planning;
- scale;
- operational productivity.

The consolidated evidence does not contain a confirmed baseline, target and measured business outcome for WFM/CRC.

DADO FALTANTE: completar baseline, target and current measured outcome.

### 4.5 Operational Readiness
Measurement dimensions:
- case ownership;
- evidence availability;
- escalation efficiency;
- partner handoff;
- resolution process.

Checkpoint:
30/09/2026.

---

## 5. ADOPTION SNAPSHOT

### 5.1 Copilot
Status:
Active adoption.

Historical token utilization progressed from approximately 7% to approximately 43%.

Salesforce Knowledge replication remains a dependency.

The 7% to 43% sequence is valid historical adoption evidence and must be preserved until superseded.

### 5.2 Quality / Speech
Status:
Initial operational adoption.

Current evidence:
- Speech topics in use.
- Monitoring form published.
- Approximately 70 questions.
- Approximately 15 with potential Speech automation.

### 5.3 AI Scoring
Status:
Sizing/evolution stage.

No achieved business outcome.

### 5.4 GPR
Status:
Benefit Assessment completed.

Current evidence:
- 14 high-potential queues.
- 874 memberships.
- Assessment/prioritization stage.
- No realized benefit.

### 5.5 WFM
Status:
CRC workstream progressing.

Revised/validated SOW historically established.

### 5.6 Historical EOP Draft telemetry - 31/03/2026
The EOP Draft contains a historical platform snapshot including:
- Knowledge in use.
- Speech and Text Analytics in use.
- AI Forecast in use.
- Workforce Management in use.
- Interaction Recording in use.
- Platform APIs in use.
- Expert Apps in use.

The Draft also contains inconsistent telemetry for some capabilities.

Example:
Agent Copilot is labeled "Entitled, Not Using" while also showing 64 active agents.

Therefore this historical dataset must not be used to infer current Copilot adoption.

Newer account evidence supersedes it.

### 5.7 Historical AI / tokens
The EOP Draft snapshot references:
350 tokens available / no usage as of 31/03/2026.

This is historical and superseded by later Copilot evidence showing approximately 7% to 43% utilization progression.

A complete September snapshot of licenses, active users, feature utilization and absolute token consumption/capacity is not available in the consolidated evidence.

The March data and later token-utilization sequence remain valid historical evidence and must not be classified as missing merely because September data are unavailable.

---

## 6. ACTIVE INITIATIVES

### 6.1 AI Adoption - Copilot Expansion
Status:
Active adoption.

Business objective:
Increase agent productivity and AI-supported service while generating measurable operational value.

Current activity:
- Copilot in adoption.
- Token utilization progressed approximately 7% -> 43%.
- Expansion depends on eligible use cases and Salesforce Knowledge architecture.

Result:
Material adoption progression.

No quantified operational/business outcome confirmed.

Risk/dependency:
- Salesforce Knowledge replication can take approximately 6 hours.
- Knowledge freshness.
- Eligible-use-case availability.
- Consumption may increase without proven business outcome.

Next:
Identify/expand eligible use cases and connect usage to operational KPIs.

Checkpoint:
TBD.

---

### 6.2 WEM Adoption - Quality / Speech / AI Scoring / WFM / Data
Status:
Active adoption/evolution.

This is a consolidated workstream covering:
- Quality.
- Speech Analytics.
- AI Scoring.
- WFM.
- Reporting/data.

#### Quality / Speech
Current:
- Quality monitoring started.
- Speech topics in use.
- Monitoring form published.
- Approximately 70 questions.
- Approximately 15 potentially automatable through Speech.

Maturity sequence:
monitoring -> Speech-assisted monitoring -> AI Scoring -> hybrid AI plus human validation

#### AI Scoring
Current:
Sizing/evaluation stage.

Do not classify as achieved adoption/value until supported.

#### WFM / CRC
Current:
- concrete workstream;
- revised/validated SOW historically established.

#### Data/reporting
Current:
A3S/Snowflake external-data requirement under evaluation.

Risks/dependencies:
- permissions for some Quality participants;
- data/reporting access;
- A3S/Snowflake architecture;
- token/value sizing;
- WFM execution dependencies.

Next:
Continue Quality/Speech adoption -> size AI Scoring -> progress WFM/CRC -> define data target architecture.

Checkpoint:
TBD by sub-workstream.

---

### 6.3 AI Acceleration - Predictive Routing / GPR
Status:
Assessment / prioritization.

Business objective:
Identify queues where routing optimization can generate measurable efficiency.

Current activity:
Benefit Assessment completed.

Evidence:
- 14 high-potential queues.
- 874 memberships.

Result:
Potential population identified.

No achieved business result.

Risk:
Assessment may be mistaken for realized value.

Next:
Prioritize candidate population -> establish baseline -> controlled test -> measure -> decide scale.

Checkpoint:
TBD.

---

### 6.4 Data / A3S / Snowflake
Status:
Architecture/discovery.

Business objective:
Enable Genesys operational data to be consumed in an external analytical environment.

Current requirement:
Make A3S/Snowflake data available to an external Data Warehouse/Data Lake environment.

Current evidence:
No official Genesys procedure/documentation currently supports representing a specific extraction mechanism as the validated A3S approach.

Decision path:
1. Define requirement.
2. Define target environment.
3. Evaluate applicable Snowflake mechanism.
4. Open Genesys case.
5. Validate supported approach.
6. Evaluate Professional Services if required.

Risk:
Generic Snowflake capability may be incorrectly represented as a Genesys-supported A3S procedure.

Next:
Complete requirement/target definition and open case.

Checkpoint:
TBD.

No numbered support case is confirmed for this requirement.

---

### 6.5 Partner Support - Operational Readiness
Status:
Active stabilization / **CRITICAL FRICTION IDENTIFIED — first technical lead obtained 22/09/2026.**

Business objective:
Create reliable ownership, evidence and escalation processes after migration.

Current evidence:
Case 0004177350 exposed:
- ownership gaps (fragmented across Claro, GFT, Genesys, HITSS);
- evidence-flow dependencies;
- delayed logs and evidence collection;
- partner-chain escalation friction;
- lack of aligned schedule for coordinated investigation.

Relevant parties include:
- Claro/Tellmex (telecom partner);
- GFT (systems integrator);
- HITSS (WFM partner);
- Genesys (vendor);
- BMG (customer);
- **Resolution Management (RM) LATAM (engaged 21/09/2026).**

BMG Position:
Requesting war room with all parties to coordinate and establish productive aligned schedule.

Impact:
Post-migration support friction is preventing timely resolution of technical issues.

**Update 22/09/2026 (REPORTED, pending validation):**
Genesys Engineering (Kiran J) delivered the first concrete technical diagnosis: the Salesforce record-triggered flow behaves differently for record creation (Initial Creation / Non-Transfer scenario, triggered on CREATE) versus record update (Transfer scenario, triggered on UPDATE). Sent to GFT for review/confirmation via Andressa Matias (GlobalHitss). No GFT confirmation recorded yet.

Next:
1. GFT to validate the Salesforce flow-trigger configuration flagged by Genesys Engineering on 22/09/2026.
2. Schedule war room (BMG request) <- PENDING CLARO.
3. Prioritize investigation via Claro escalation.
4. Conduct coordinated Salesforce + Genesys analysis.
5. Await RM LATAM response to the 21/09/2026 escalation.

Checkpoint:
30/09/2026.

---

### 6.6 Customer Success Recurrence
Status:
Active governance.

Historical cadence:
Quinzenal / recurring.

Used for:
- adoption;
- cases/risks;
- Copilot;
- WEM;
- GPR;
- data/reporting;
- specialist engagement;
- support;
- new opportunities;
- customer enablement/autonomy.

Next:
Continue recurring governance while shifting basic operational knowledge toward greater customer autonomy.

---

### 6.7 Migration
Status:
COMPLETED.

Migration to Genesys Cloud is complete.

Residual issues must be classified separately as:
- support;
- adoption;
- architecture;
- data;
- AI expansion;
- operational readiness.

Migration completion must not be reopened solely because post-migration support issues exist.

---

## 7. EOP / CSP

### 7.1 CSP
Status:
CONFIRMED / established.

The CSP establishes a success path across Q2-Q4 around:
- operational stability;
- recurring governance;
- WEM Adoption;
- Copilot;
- GPR;
- business reviews;
- priority reviews.

Strategic goals:
- reduce costs;
- increase revenue;
- increase operational efficiency.

The CSP roadmap should be interpreted as governance/intent unless individual initiatives have newer execution evidence.

Current account evidence shows the account has already progressed beyond the CSP's original implementation-stage context because migration is now completed.

### 7.2 EOP
Status:
DRAFT / not customer-validated.

EOP Draft date reference:
15/04/2026.

The Draft contains incomplete CSM Input fields and an uncompleted readiness checklist.

Therefore it must not be classified as:
- presented;
- approved;
- validated;
- committed roadmap.

The Draft identifies potential evolution toward:
- Virtual Agent / Agentic Virtual Agent.
- Unified Strategic CX Platform.
- Virtual Supervisor.
- Journey Management.
- Predictive Routing.
- AI/automation.

It also contains forward-looking value projections.

These are POTENTIAL, not achieved savings or committed forecasts.

### 7.3 EOP Draft potential value
Total projected annual value:
US$2.15M POTENTIAL.

Indicative Draft components include:
- Operational Efficiency and Cost Optimization: approximately US$2.07M POTENTIAL.
- Improved Workforce Productivity and Compliance: approximately US$17.7K POTENTIAL.
- Enhanced Customer Experience and Loyalty: approximately US$51.5K POTENTIAL.
- Revenue Growth and Conversion Optimization / Predictive Routing: approximately US$9.2K POTENTIAL.

These values are model projections based on assumptions.

They are not:
- achieved savings;
- customer commitments;
- production results;
- approved business cases.

The consolidated evidence does not establish a future presentation/validation date for the EOP.

Checkpoint:
TBD.

---

## 8. RESULTS / VALUE REALIZED

### 8.1 ACHIEVED
- Migration to Genesys Cloud completed.
- Copilot token utilization increased materially from approximately 7% to approximately 43%.
- Quality/Speech entered initial operational adoption.
- Monitoring form published.
- Speech topics in use.
- GPR Benefit Assessment completed.
- 14 high-potential GPR queues identified.

Important:
Some of these items represent achieved migration/adoption/assessment milestones, not necessarily business-value outcomes.

### 8.2 CONFIRMED PROGRESS - NOT BUSINESS VALUE
- AI Scoring sizing/evaluation.
- WFM/CRC defined workstream.
- A3S/Snowflake architecture evaluation.
- Operational Readiness governance.
- CSP established.
- EOP Draft available.
- Post-migration support friction documented and escalated (Case 0004177350).
- **First technical diagnosis for Case 0004177350 delivered by Genesys Engineering (22/09/2026), pending GFT validation.**

### 8.3 TARGET / POTENTIAL
- Copilot operational/business value.
- GPR optimization benefit.
- AI Scoring productivity/cost benefit.
- Full Quality-monitoring centralization.
- WFM/CRC business outcome.
- Data Lake/reporting benefit.
- EOP Draft projected annual value.
- Virtual Agent/Agentic AI opportunities.
- Journey Management opportunity.
- Post-migration support model resolution.

### 8.4 VALUE RULES
Token consumption is an adoption indicator, not automatically business value.

EOP projection is potential value, not saving.

GPR Benefit Assessment is prioritization evidence, not achieved routing benefit.

---

## 9. RISKS & BLOCKERS

### R1 - Salesforce dependency for Copilot
Type:
Architecture / adoption.

Replication can take approximately six hours.

Impact:
Content freshness and Copilot expansion can be constrained.

Action:
Govern eligible use cases and architecture before scaling.

---

### R2 - Copilot value-realization gap
Type:
Adoption/value.

Token utilization increased materially, but measured business outcome remains incomplete.

Action:
Connect adoption to operational KPI.

---

### R3 - Quality permissions
Type:
Operational.

Some agent profiles historically required permission updates for evaluation participation.

Current resolution status is not available in the consolidated evidence.

DADO FALTANTE: completar current status of Quality permissions.

---

### R4 - Reporting / A3S / Snowflake
Type:
Data / architecture.

No validated Genesys A3S extraction procedure currently supports the external-data requirement.

Action:
Define target -> evaluate mechanism -> open Genesys case -> validate.

---

### R5 - Post-migration support model fragmentation (CRITICAL)
Type:
Operational / relationship / escalation.

Claro/Tellmex/GFT/HITSS/Genesys ownership and evidence-flow dependencies can delay resolution.

Evidence: Case 0004177350 exposed no aligned schedule for coordinated investigation across teams.

**Update 22/09/2026 (REPORTED, pending validation):**
Genesys Engineering proposed a candidate root cause — Salesforce flow trigger differs between record creation (non-transfer) and record update (transfer) scenarios — and requested GFT validation. CSM escalated to RM LATAM on 21/09/2026 for prioritization support. A possible correlation with C6 Bank case 0004151486 was flagged by CSM as INFERENCE/hypothesis, not confirmed.

Action:
Operational Readiness review + schedule war room (BMG requested). Await GFT validation of the flow-trigger configuration. Await RM LATAM response.

Current blocker:
Unable to establish aligned schedule for multi-party coordination. Resolution now also depends on GFT confirmation turnaround.

Impact:
Technical issues take longer to resolve; customer frustration; client (Jessika Cardoso, Vinicius Ferrari) reinforced on 21-22/09 that the WhatsApp/CX Cloud migration should have been completed since August 2026.

---

### R6 - Local-team autonomy
Type:
Enablement.

Some recurring sessions historically included highly granular/basic questions.

Impact:
Customer Success capacity can be consumed by support-like activity instead of adoption/value orchestration.

Action:
Continue enablement while increasing customer self-sufficiency.

---

### R7 - GPR still pre-benefit
Type:
Adoption/value.

High-potential queues identified, but no controlled production test/result.

---

### R8 - EOP Draft maturity
Type:
Governance.

Draft contains incomplete customer-specific fields and projections.

Impact:
Risk of treating generated opportunity/projection as customer-approved strategy.

Action:
Complete, validate and present before changing maturity.

---

## 10. CRITICAL CASES

### 10.1 Case 0004177350 - High (POST-MIGRATION TECHNICAL DEBT)

**Status:** ACTIVE / ESCALATED — first technical diagnosis obtained 22/09/2026, pending GFT validation.

**Date opened:** 09/09/2026 (go-live)

**Evidence complete:** 18/09/2026

**Issue Type:** External Routing / Messaging-to-queue transfer failure

**Context:**
Post-migration, WhatsApp Messaging transfers to queue not being processed effectively by External Routing integration. Transfer requests detected but processing skipped with error "Could not find active participant for transfer."

**Technical Details:**
- Messaging Session/Work Item ID: 0MwU600000yIDWqKAO
- Genesys Cloud Conversation ID: ac5d53af-4d97-481f-97e2-71fed1a08b5b
- Expected destination queue: WhatsApp SAF Outros
- Error message: "Could not find active participant for transfer"

**Technical Evidence (Salesforce logs, 18/09):**
- TransferGCInteractionService failures (Queueable Job failures)
- Multiple transfer attempts with consistent error
- PendingServiceRouting records created (IsReadyForRouting: true) but no effective transfer
- Conversation ended without effective transfer
- Same agent successfully transferred another interaction 5 minutes later (inconsistent pattern)

**Versions Identified:**
- CX Cloud: v1.19
- External Routing: V2.41

**Timeline:**
- 09/09/2026: Issue began after production go-live
- 11/09-18/09: Evidence collection and log gathering
- 16/09: Evidence submitted to Genesys Support
- 18/09: Still awaiting Claro prioritization
- **21/09: CSM escalated to Resolution Management (RM) LATAM citing limited visibility; possible correlation with C6 Bank case 0004151486 flagged as unconfirmed hypothesis.**
- **21/09: Client (BMG) issued repeated status requests throughout the day; support team attempted phone follow-up with no update obtained; Genesys confirmed engineering still analyzing with no conclusive position and no ETA possible while analysis is ongoing.**
- **22/09, ~14h30 UTC: Genesys Engineering (Kiran J) delivered first concrete technical diagnosis (see below) and requested GFT validation.**

**Status:**
- Case in Genesys: YES (since 16/09)
- Genesys analysis: In progress — **first diagnosis delivered 22/09, awaiting GFT confirmation**
- Ownership fragmentation: Claro (telecom partner), GFT (systems integrator), HITSS (WFM partner), Genesys (vendor), BMG (customer)
- Escalation status: BMG requesting war room with all parties; CSM escalated to RM LATAM (21/09)

**Current Blocker:**
No aligned schedule between teams for coordinated investigation (async activity). Evidence collected and sent to Genesys 16/09. **Resolution now also depends on GFT confirming the flow-trigger configuration flagged by Engineering on 22/09.**

**Business Impact:**
Customer service interruption: WhatsApp transfers fail intermittently. Behavior is random/inconsistent (unable to establish precise failure %). Affects operational reliability post-migration. **Client reinforced (21-22/09) that the WhatsApp/CX Cloud migration should have been completed since August 2026 and that the GoLive of WhatsApp remains on hold pending this case.**

**Validated/Confirmed:**
- Transfer Omni-Channel Flow: active and configured
- Queue mappings: properly configured in GC External Routing Integration
- OAuth client blind transfer scopes: confirmed present

**Engineering Diagnosis — 22/09/2026 (REPORTED, pending GFT validation):**
Genesys Engineering (Kiran J) reviewed the Salesforce configuration and reported a distinction in flow-trigger behavior:
- Initial Creation (Non-Transfer scenario): the flow is triggered on record CREATE.
- Transfer scenario: the flow is triggered on record UPDATE.
This was communicated to the GFT team (via Andressa Matias/GlobalHitss) with a direct request: "Poderia revisar essa configuração que Genesys cita e nos dar a devolutiva?" No GFT confirmation received as of this entry. This diagnosis is the first concrete technical lead obtained since evidence submission on 16/09 and should be treated as REPORTED / candidate root cause, not CONFIRMED, until GFT validates.

**RM LATAM Escalation — 21/09/2026 (REPORTED):**
CSM (Hugo Reboucas) formally requested Resolution Management LATAM involvement, citing limited visibility into case evolution, prioritization and next steps, and difficulty managing customer expectations. CSM flagged a possible correlation with C6 Bank case 0004151486 (indicated correction ETA: end of September 2026) but explicitly noted lack of Jira access to confirm whether both cases share the same root cause. **This correlation is INFERENCE/hypothesis only and must not be presented as CONFIRMED.**

**BMG Position:**
Requesting war room with all parties to coordinate investigation and resolution. Emphasized need for productive aligned schedule. Reinforced (21-22/09, via Jessika Cardoso and Vinicius Ferrari) that the operation should have migrated to CX Cloud since August 2026 and is requesting cross-team support to resume the WhatsApp GoLive.

**Next Action:**
1. GFT to validate the Salesforce flow-trigger configuration flagged by Engineering on 22/09/2026.
2. Schedule war room (BMG request) <- PENDING CLARO
3. Prioritize investigation via Claro escalation
4. Conduct coordinated Salesforce + Genesys analysis
5. Await RM LATAM response to the 21/09/2026 escalation
6. Validate or rule out correlation with C6 Bank case 0004151486

**Escalation Chain:**
BMG -> Claro -> Genesys Support + GFT + HITSS coordination + RM LATAM (added 21/09/2026)

**Checkpoint:** TBD (dependent on Claro scheduling and GFT confirmation)

**Related to Operational Readiness Initiative (6.5):** Yes - this case validates the post-migration support-model fragmentation identified in the workstream.

---

### 10.2 A3S/Snowflake Requirement
No numbered support case confirmed.

Current state:
Requirement/target environment must be defined before the supported technical path is validated.

Next:
Define requirement and target environment, then open Genesys case.

Checkpoint:
TBD.

---

## 11. CTA / WORKSTREAM STRUCTURE

### AI Adoption - Copilot Expansion
Status:
Active.

Current:
7% -> approximately 43% token utilization.

Result:
Adoption growth.

Risk:
Salesforce replication / value-realization gap.

Next:
Expand eligible use cases and connect usage to KPI.

Checkpoint:
TBD.

### WEM Adoption
Status:
Active.

Current:
Quality/Speech in initial use; AI Scoring sizing; WFM/CRC active; data/reporting evolution.

Result:
Adoption progression, no consolidated business outcome yet.

Risk:
Permissions/data/token sizing.

Next:
Continue maturity sequence and measurement.

Checkpoint:
TBD.

### AI Acceleration - GPR
Status:
Assessment/prioritization.

Current:
14 high-potential queues / 874 memberships.

Result:
Potential identified.

Risk:
No controlled benefit yet.

Next:
Prioritize -> baseline -> controlled test -> measure.

Checkpoint:
TBD.

### Data / A3S / Snowflake
Status:
Discovery/architecture.

Next:
Define target requirement and open Genesys case.

Checkpoint:
TBD.

### Partner Support - Operational Readiness
Status:
Active / CRITICAL FRICTION IDENTIFIED — first technical lead obtained 22/09/2026, pending GFT validation.

Current:
Post-migration support stabilization.

Evidence:
Case 0004177350 + ownership fragmentation + Engineering diagnosis (22/09) + RM LATAM escalation (21/09).

Next:
Await GFT validation of flow-trigger configuration. Schedule war room (BMG requested). Await RM LATAM response. Review support model and establish aligned escalation process.

Checkpoint:
30/09/2026.

### Customer Success Recurrence
Status:
Active.

Cadence:
Quinzenal / recurring.

Next:
Continue governance and increase customer autonomy.

### Migration
Status:
COMPLETED.

Residual items belong to other workstreams.

### CSP
Status:
CONFIRMED / established.

### EOP
Status:
Draft.

Next:
Complete customer-specific inputs -> validate -> present.

Checkpoint:
TBD.

---

## 12. NEXT MILESTONES

- 30/09/2026: Operational Readiness / support-model review.
- **GFT validation of Salesforce flow-trigger configuration: pending, requested 22/09/2026.**
- **RM LATAM response to Case 0004177350 escalation: pending, requested 21/09/2026.**
- War room scheduling: TBD (pending Claro).
- Case 0004177350 resolution: TBD (pending coordinated investigation and GFT confirmation).
- Copilot value/adoption checkpoint: TBD.
- GPR prioritization: TBD.
- WEM / AI Scoring checkpoint: TBD.
- WFM/CRC: continue current process; next confirmed date TBD.
- A3S/Snowflake requirement/case: TBD.
- EOP review/presentation: TBD.

---

## 13. CUSTOMER / ACCOUNT DECISIONS

- Migration is completed.
- Salesforce remains part of the architecture supporting Copilot Knowledge.
- Customer strategy historically avoids creating a second Knowledge Base at this stage.
- Quality monitoring is moving into Genesys.
- Speech topics are in use.
- AI Scoring is a later monitoring-maturity stage.
- GPR remains assessment/prioritization, not realized benefit.
- A3S/Snowflake external-data requirement requires supported technical validation.
- Generic Snowflake capability must not be presented as a Genesys-validated A3S procedure.
- Professional Services may be evaluated for data work subject to commercial flow through Claro.
- Post-migration support ownership requires continued governance and clarification (escalated via Case 0004177350).
- CSP is established.
- EOP remains Draft until completed/validated/presented.
- EOP projections remain POTENTIAL.
- **BMG has reinforced (21-22/09/2026) that the WhatsApp/CX Cloud migration should have been completed since August 2026; WhatsApp GoLive remains on hold pending resolution of Case 0004177350.**

---

## 14. GOVERNANCE

Account governance requires coordination across:
- BMG Business/Operations.
- BMG Technology/Planning.
- Genesys Customer Success.
- Genesys specialists.
- Genesys Support/Care.
- Genesys Professional Services where engaged.
- Claro/Tellmex.
- HITSS for relevant WFM process.
- GFT where applicable.
- Salesforce-related dependencies.
- **Resolution Management (RM) LATAM (engaged 21/09/2026 for Case 0004177350).**

The CSM governance must explicitly distinguish:
- customer responsibility;
- Genesys responsibility;
- partner responsibility;
- supplier dependency;
- adoption issue;
- support issue;
- data issue;
- architecture constraint;
- project progress;
- business value.

Customer Success governance remains direct and recurring.

Historical cadence:
Quinzenal.

**Post-Migration Support Governance Enhancement Required:**
Ownership clarification needed across Claro/GFT/Genesys for escalation and evidence flow (Case 0004177350 highlighted gaps). **RM LATAM added to escalation chain on 21/09/2026; response pending.**

---

## 15. EVIDENCE LEDGER

### 2026-09-22 - Case #0004177350: Engineering Diagnosis + RM LATAM Escalation Context

**Type:** REPORTED / TECHNICAL / INFERENCE

**Engineering diagnosis (22/09, ~14h30 UTC):**
Genesys Engineering (Kiran J) reviewed the Salesforce configuration and reported:
- Initial Creation (Non-Transfer scenario): flow is triggered on record CREATE.
- Transfer scenario: flow is triggered on record UPDATE.
Communicated to GFT (via Andressa Matias/GlobalHitss) with a direct request for review and confirmation. No GFT confirmation recorded yet as of this entry.

**RM LATAM escalation (21/09, 21h11 UTC):**
CSM (Hugo Reboucas) formally requested Resolution Management LATAM support, citing limited visibility into case evolution/priority and difficulty managing customer expectations. Flagged a possible correlation with C6 Bank case 0004151486 (indicated fix ETA: end of September 2026) as an explicitly unconfirmed hypothesis — CSM stated no Jira access to validate whether the cases share root cause. No RM response recorded yet.

**Client escalation pattern (21-22/09):**
BMG (Jessika Cardoso, Vinicius Ferrari) issued repeated status requests across 21/09 (multiple pings throughout the day) and again on 22/09, reinforcing that the WhatsApp/CX Cloud migration should have completed in August 2026 and requesting cross-team support to resume WhatsApp GoLive. Genesys (Hugo Reboucas) responded on 21/09 (18h04 UTC) confirming Engineering was still analyzing with no conclusive position even after the last evidence submission, and that no ETA could be estimated while analysis remained ongoing.

**Classification note:**
The flow-trigger diagnosis is REPORTED technical evidence from Genesys Engineering, not yet a CONFIRMED root cause — confirmation depends on GFT's review. The C6 Bank correlation is INFERENCE raised by the CSM and must remain unconfirmed until validated through Jira/Engineering.

### 2026-09-18 - Case #0004177350 Escalation / Evidence Collection Complete

**Type:** REPORTED / CONFIRMED / TECHNICAL

**Context:**
Post-migration External Routing issue affecting Messaging-to-queue transfers on WhatsApp channel. Evidence collection complete; case awaiting Claro prioritization for coordinated investigation.

**Issue Details:**
- Messaging Session/Work Item ID: 0MwU600000yIDWqKAO
- Genesys Cloud Conversation ID: ac5d53af-4d97-481f-97e2-71fed1a08b5b
- Expected destination queue: WhatsApp SAF Outros
- Error message: "Could not find active participant for transfer"

**Technical Evidence (Salesforce logs, 18/09):**
- TransferGCInteractionService failures (Queueable Job failures)
- Multiple transfer attempts with consistent error
- PendingServiceRouting records created (IsReadyForRouting: true) but no effective transfer
- Conversation ended without effective transfer
- Same agent successfully transferred another interaction 5 minutes later (inconsistent pattern)

**Versions Identified:**
- CX Cloud: v1.19
- External Routing: V2.41

**Timeline:**
- 09/09/2026: Issue began after production go-live
- 11/09-18/09: Evidence collection and log gathering
- 16/09: Evidence submitted to Genesys Support
- 18/09: Still awaiting Claro prioritization

**Status:**
- Case in Genesys: YES (since 16/09)
- Genesys analysis: In progress (awaiting prioritization)
- Ownership fragmentation: Claro, GFT, Genesys, HITSS, BMG
- Escalation status: BMG requesting war room with all parties

**Blocker:**
No aligned schedule between teams for coordinated investigation (async activity).

**Impact:**
- WhatsApp transfers failing intermittently
- Behavior is inconsistent; unable to define exact failure percentage
- Affects customer service workflow

**Validated/Confirmed:**
- Transfer Omni-Channel Flow: active and configured
- Queue mappings: properly configured in GC External Routing Integration
- OAuth client blind transfer scopes: confirmed present

**Next Action:**
1. Schedule war room (BMG requested)
2. Prioritize via Claro
3. Conduct coordinated Salesforce + Genesys investigation

**Checkpoint:** TBD (pending Claro)

---

### 2026-09-18 - Cycle Closure v1.2 / CSP and EOP Consolidation

**Type:** CONFIRMED / HISTORICAL / TARGET / POTENTIAL

- CUSTOMER_MASTER v1.1 preserved as authoritative pre-cycle baseline.
- Duplicate v1.0 identified; v1.1 used due to higher Version.
- CSP incorporated as established.
- CSP success path incorporated.
- EOP Draft incorporated as Draft only.
- EOP readiness gaps preserved.
- EOP projected annual value approximately US$2.15M classified as POTENTIAL.
- EOP capability recommendations classified as opportunities, not implementation.
- 31/03 EOP telemetry retained only as historical context where non-conflicting.
- Newer Copilot/WEM/GPR evidence preserved over older EOP telemetry.
- Current A3S/Snowflake and Operational Readiness states preserved.
- Post-migration support friction documented and escalated (Case 0004177350).

### 2026-09-17 - Data / A3S / Snowflake

**Type:** CONFIRMED / REPORTED

- BMG requirement to make A3S/Snowflake data available externally.
- No official Genesys A3S extraction procedure available.
- Snowflake mechanisms may be evaluated but are not Genesys-validated A3S procedures.
- Target environment/requirement must be defined.
- Genesys case should follow.
- PS remains a potential alternative through Claro commercial flow.

### 2026-09-16 - Account Consolidation

**Type:** CONFIRMED / REPORTED

- Migration completed.
- Copilot utilization progressed approximately 7% -> 43%.
- Salesforce replication can take approximately 6h.
- Quality monitoring started.
- Speech topics in use.
- Approximately 70-question monitoring form.
- Approximately 15 questions potentially supported automatically through Speech.
- AI Scoring sizing in progress.
- WFM/CRC revised/validated SOW.
- GPR assessment: 14 high-potential queues / 874 memberships.
- Post-migration support remains active risk.
- Direct BMG-Genesys governance active.

### 2026-09 - Post-Migration Support

**Type:** REPORTED

- Case 0004177350 highlighted ownership/evidence/escalation gaps.
- GFT log dependency delayed evidence delivery.

### 2026-07-17 - Quality / Speech Working Session

**Type:** CONFIRMED / REPORTED

- Manual monitoring plus Speech strategy established.
- AI Scoring future maturity discussed.
- Monitoring form structure reviewed.
- QA data requested for token/value sizing.

### 2026-04-15 - EOP Draft

**Type:** DRAFT / POTENTIAL

- Automated EOP Draft generated.
- Customer-specific CSM fields incomplete.
- Readiness checklist incomplete.
- Potential-value model generated.
- Capability recommendations generated.
- No evidence of customer validation/presentation.
- Projections remain POTENTIAL.

### 2026-03-31 - Historical EOP telemetry

**Type:** HISTORICAL

- Platform snapshot generated.
- Some telemetry contains status/value inconsistencies.
- Later account evidence supersedes conflicting adoption information.

---

## 16. HISTORICAL TIMELINE

### 2026-09-22 - Engineering Diagnosis + RM LATAM Escalation Context

**Current state**
- Case 0004177350 remains ACTIVE/ESCALATED.
- First concrete technical diagnosis delivered by Genesys Engineering: Salesforce flow-trigger difference between record creation (non-transfer) and record update (transfer scenario).
- Diagnosis sent to GFT for validation; awaiting confirmation.
- CSM escalated to RM LATAM (21/09); response pending.
- Possible (unconfirmed) correlation flagged with C6 Bank case 0004151486.
- Client (BMG) continues daily status pressure; WhatsApp GoLive still on hold; client states migration should have completed since August 2026.

**Changes**
- NEW: Engineering diagnosis (flow-trigger creation vs. update) - pending GFT validation.
- NEW: RM LATAM escalation requested by CSM.
- NEW: Possible correlation hypothesis with C6 Bank case 0004151486 - REQUIRES VALIDATION, not confirmed.
- NEW: Client statement that WhatsApp/CX Cloud migration was expected since August 2026.
- UNCHANGED: Case remains open/critical; no resolution date confirmed.

**Decisions**
- Treat the flow-trigger diagnosis as REPORTED/technical lead, not yet a confirmed root cause until GFT validates.
- Treat the C6 correlation as INFERENCE/hypothesis until confirmed via Jira/Engineering.
- Continue tracking RM LATAM engagement as a new escalation channel alongside the existing Claro/GFT/HITSS chain.

**Results**
- No resolution achieved yet.
- First actionable technical lead obtained after evidence had been sitting with Genesys Support since 16/09 without a conclusive position.

**Risks**
- Resolution now also depends on GFT turnaround time (new dependency beyond Claro/Genesys).
- If correlation with C6 case is confirmed, fix timing may become linked to C6's own case, which has an indicated end-of-September ETA - could work for or against BMG's timeline.
- Prolonged delay since August is a relationship risk independent of the technical resolution.

**Next**
- Await GFT confirmation on flow-trigger configuration.
- Await RM LATAM response.
- Validate or rule out correlation with C6 Bank case 0004151486.
- Continue monitoring client pressure/relationship risk given prolonged delay since August.

### 2026-09-18 - Cycle Closure v1.2 / CSP and EOP / POST-MIGRATION SUPPORT FRICTION ESCALATED

Current state:
- Migration completed.
- Copilot remains most mature AI-adoption workstream.
- Token utilization approximately 7% -> approximately 43%.
- Salesforce remains Copilot dependency.
- Quality/Speech in initial operational adoption.
- AI Scoring in sizing/evolution.
- WFM/CRC active.
- GPR assessment completed with 14 high-potential queues.
- No GPR business result yet.
- A3S/Snowflake remains architecture/data workstream.
- POST-MIGRATION SUPPORT FRICTION - CRITICAL: Case 0004177350 exposed ownership fragmentation across Claro/GFT/Genesys/HITSS. BMG requesting war room. Awaiting Claro prioritization.
- CSP established.
- EOP remains Draft.

Changes:
- UPDATED: CSP formally classified as established.
- NEW HISTORICAL: CSP success path incorporated.
- NEW HISTORICAL: EOP Draft incorporated.
- NEW POTENTIAL: approximately US$2.15M EOP projected annual value preserved as POTENTIAL.
- NEW HISTORICAL: EOP capability opportunity set incorporated.
- NEW CRITICAL: Case 0004177350 escalated - ownership fragmentation exposed, war room requested by BMG.
- UNCHANGED: Copilot Current State.
- UNCHANGED: WEM maturity.
- UNCHANGED: GPR pre-benefit status.
- UNCHANGED: A3S/Snowflake dependency.
- UNCHANGED: migration completion.

Decisions:
- Use v1.1 as prior authoritative Master.
- Preserve v1.0 as superseded duplicate.
- Treat CSP as established.
- Treat EOP as Draft.
- Do not convert EOP projections into savings.
- Do not convert EOP recommendations into implementation.
- Preserve newer account evidence over March/April EOP telemetry.
- Preserve 874 as memberships, not unique agents.
- Maintain WEM as consolidated workstream.
- Maintain Operational Readiness as CRITICAL and escalated (Case 0004177350).
- Treat Case 0004177350 as post-migration technical debt requiring coordinated multi-party investigation.

Results:
- Migration remains achieved.
- Copilot adoption growth remains achieved.
- Quality/Speech initial adoption remains achieved.
- GPR assessment remains completed.
- Post-migration support friction NOW DOCUMENTED and escalated.
- No new business-value outcome established by this closure.

Risks:
- Salesforce/Copilot dependency.
- Copilot value-realization gap.
- A3S/Snowflake architecture.
- Post-migration support ownership fragmentation (CRITICAL - Case 0004177350).
- Customer autonomy.
- GPR pre-benefit.
- EOP Draft maturity.

Completed:
- CSP incorporated.
- EOP Draft incorporated.
- EOP potential-value classification established.
- Duplicate Master handled by version priority.
- Case 0004177350 escalated and documented.

Next:
- Schedule war room (BMG requested, pending Claro). Establish aligned multi-party process.
- Operational Readiness review 30/09.
- Connect Copilot adoption to KPI/outcome.
- Prioritize GPR candidate queues.
- Continue WEM maturity.
- Progress WFM/CRC.
- Define A3S/Snowflake requirement and open case.
- Complete/validate EOP before presentation.
- Continue recurring CS governance.

### 2026-09-17 - CUSTOMER_MASTER v1.1
- A3S/Snowflake external-data requirement added.
- Current post-migration/adoption state preserved.
- Operational Readiness remained active.

### 2026-09-16 - Baseline
- Migration completed.
- Copilot adoption growing materially.
- Salesforce identified as Copilot constraint.
- Quality/Speech entered initial operational use.
- AI Scoring sizing initiated.
- WFM/CRC active.
- GPR assessment identified 14 high-potential queues.
- Support model required stabilization.
- Direct Customer Success governance active.

---

## 17. OUTPUT RULES FOR FUTURE UPDATES

1. Preserve ACHIEVED / TARGET / POTENTIAL / CONFIRMED / REPORTED / INFERENCE.
2. Preserve historical Copilot sequence approximately 7% -> 43% until superseded.
3. Token consumption does not equal business value.
4. Migration is completed.
5. Post-migration support issues do not mean incomplete migration.
6. Salesforce replication remains an adoption dependency until superseded.
7. WEM remains one consolidated theme: WFM + Quality + Speech Analytics + AI Scoring + reporting/data.
8. Preserve Quality maturity: manual monitoring -> Speech -> AI Scoring -> hybrid AI plus human validation.
9. 874 memberships does not equal 874 unique agents.
10. GPR assessment does not equal achieved benefit.
11. 14 high-potential queues does not equal production adoption.
12. GPR value requires controlled test and measurement.
13. A3S/Snowflake capability does not equal validated Genesys A3S extraction procedure.
14. Do not state data architecture as implemented until supported.
15. CSP is established.
16. CSP roadmap does not equal individual initiative completion.
17. EOP remains Draft until evidence confirms presentation/validation.
18. EOP projected value does not equal saving.
19. EOP recommendation does not equal customer priority.
20. EOP roadmap does not equal implementation.
21. March/April EOP telemetry is historical and may be superseded by newer evidence.
22. Do not use inconsistent EOP telemetry to override current adoption evidence.
23. A valid historical value is not DADO FALTANTE merely because a newer measurement is unavailable.
24. Preserve historical values with their reference period.
25. Use DADO FALTANTE only when material expected information is unavailable in valid evidence.
26. Use TBD for future dates/checkpoints/statuses that are not yet defined or confirmed.
27. Partner/support dependencies must be distinguished from Genesys responsibility.
28. Customer internal initiatives must not be attributed to Genesys.
29. Preserve Case 0004177350 with its context, ownership fragmentation, impact and escalation status.
30. Treat post-migration support friction as CRITICAL until ownership and escalation model are clarified.
31. Every active CTA/workstream must include next step/checkpoint when supported.
32. Customer Success governance remains recurring/quinzenal until superseded.
33. Supported outputs:
- Lideranca
- Gerencial
- CTAs
- Completo
- Status Semanal Brasil
34. Treat the 22/09/2026 Salesforce flow-trigger diagnosis as REPORTED technical lead pending GFT validation - not a confirmed root cause until GFT responds.
35. Treat the correlation between Case 0004177350 (BMG) and C6 Bank case 0004151486 as INFERENCE/hypothesis until confirmed by Engineering/Jira - do not present as CONFIRMED.
36. Preserve the RM LATAM escalation (21/09/2026) as a distinct entry in the escalation chain alongside Claro/GFT/HITSS.
