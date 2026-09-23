FILE: santander-brasil_account.md
VERSION: 1.5
REPLACES: 1.4

# BANCO SANTANDER BRASIL — CUSTOMER MASTER

Document Type: CUSTOMER_MASTER
Account: Banco Santander Brasil
Account ID: santander-brasil
Canonical File Name: santander-brasil_account.md
Version: 1.5
Last Updated: 2026-09-22

Baseline: 2026-09-16
Purpose: Persistent account knowledge base for recurring Customer Success intelligence and weekly updates.

Evidence labels: CONFIRMED = supported by customer/project evidence; REPORTED = reported by customer, partner or internal team; ACHIEVED = measured result already realized; TARGET = planned/expected result; POTENTIAL = opportunity/business case not yet realized; INFERENCE = analytical interpretation requiring validation.

**Correção de versionamento (22/09/2026):** o arquivo v1.4 recebido tinha o cabeçalho (`FILE:`/`VERSION:`) marcando 1.4/REPLACES 1.3, mas o corpo do documento ainda dizia "Version: 1.2 / Last Updated: 2026-09-21" — inconsistência herdada, não corrigida nos ciclos anteriores. Esta v1.5 alinha cabeçalho e corpo. Ver Evidence Ledger de 22/09 para detalhe.

---

## 1. ACCOUNT PROFILE

- **Customer:** Banco Santander Brasil
- **Account profile:** Strategic / Global P1 account.
- **Platform:** Genesys Cloud.
- **Scale:** approximately 4,000 contracted positions in the June/2026 EOP baseline.
- **Operating model:** Multiple Business and Technology stakeholders, Pulse and external delivery dependencies.
- **Primary themes:** Incident Readiness / operational resilience, Predictive Routing, Agent Copilot, Virtual Agent / AI, IVR/Acelerar, Digital, WFM, Analytics, operational stability, adoption and executive governance.
- **Current executive sensitivity:** elevated following the critical incident initiated on 27/08 and executive session of 17/09.
- **CSP:** CONFIRMED as established/realized.
- **EOP:** available and incorporated as historical strategic/adoption evidence. Formal presentation/validation date remains TBD.
- **Tactical execution layer (added 22/09/2026):** phased platform migration rollout (channel waves), physical-store channel stabilization, A3S/STA evolution and legacy decommission (C3 Online / Genesys Engage) — see Sections 6.10 and 6.11.

---

## 2. CURRENT EXECUTIVE STATUS

Santander is simultaneously managing platform evolution, AI adoption and a material operational-resilience agenda.

The highest-criticality current workstream is **Incident Readiness Santander–Genesys**, established following the executive session of 17/09.

The critical incident initiated on 27/08 is **mitigated but remains under technical investigation**. Santander reported more than **40 hours of Customer Center impact**, with technical, operational, executive and reported regulatory relevance. The customer also reported headquarters/Madrid visibility.

Santander and Genesys agreed to construct an **Incident Readiness Framework** covering troubleshooting, telemetry/observability, evidence collection, environment knowledge, ownership, escalation, rollback and operational validation. The framework is **not yet implemented**.

Immediate priorities are:
- team mobilization;
- RACI/owners;
- escalation matrix;
- initial evidence/log package;
- Technical Evaluation.

In parallel, strategic adoption remains active.

GPR has Business approval for **204 queues**, but Technology sequencing and Gravity/change windows constrain execution.

Copilot remains homologated in Ouvidoria with approximately **15% TMA reduction** in applied queues.

Virtual Agent remains an opportunity requiring detailed journey/use-case definition.

Acelerar remains part of Santander's active IVR architecture.

The EOP establishes que GPR já gerou valor mensurável historicamente em populações específicas do Santander, enquanto Speech Analytics e WFM já possuíam presença operacional antes do ciclo atual de expansão.

A narrativa correta é:

**valor histórico comprovado em populações específicas → oportunidade de expansão → aprovação Business → execução condicionada por Technology/change governance → medição antes de escala.**

Current account priority:

**operational resilience and trust recovery + preservation of proven adoption/value + controlled expansion of AI/routing + readiness for future execution windows.**

**UPDATE 21/09/2026 (already incorporated in v1.4 evidence — see Evidence Ledger):** Genesis Event incident-resolution architecture reported ACHIEVED (24h chat incident self-resolved, zero escalations); Select CX narrative reframing reported CONFIRMED (strategy) / REPORTED (implementation); GPR Freeze multi-phase schedule (Gravity Readiness Review → First Approval Gate → 30-day Diagnostic Window) reported TARGET; Scale 6x1 capability (8M interactions/year) reported; Copiloto Ouvidoria (resumo automático, recomendações em tempo real, checklists) reported in implementation; KPIs personalizados, Voicebot URA, redução de filas (timeline estendida), requisito de histórico mínimo de 90-180 dias para GPR, parceria Jander (Planejamento/WFM) e curadoria da base de conhecimento (cartões) all REPORTED on 21/09. These remain as originally recorded below and are not altered by this update.

**UPDATE 22/09/2026 (REPORTED — Resultado da Agenda Tática, NEW):** In parallel to Incident Readiness and to the 21/09 Genesis Event/Select CX/GPR Freeze evidence above, Santander confirmed continuity of a phased migration/rollout to Genesys Cloud across additional channels, with waves completed on 18/08, 20/08, 24/08, 09/09 and 10/09/2026 (ACHIEVED), and upcoming waves TARGET for 13, 14, 15 and 19/10/2026 (remaining scope TARGET for 20/10/2026). The physical-store (lojas) channel rollout remains **paused** due to an active incident with peripheral-device activation intermittency. The tactical session also reported continued functional incidents (specialist disconnection, interaction redirection, pause-return behavior, callback interaction overlap, RBAC/access loss after vacation return, and an open incident on contract/card loading) and functional occurrences in URA PF, Ouvidoria and SAC journeys (two corrections in validation, one SAC occurrence under investigation). The main tactical attention point is stabilizing already-migrated flows — especially stores, IVRs and occurrences affecting interaction continuity/distribution — before the remaining October waves. This tactical update is a separate execution layer from both the Incident Readiness Framework (27/08 critical incident) and the 21/09 Genesis Event/GPR Freeze cycle described above; it does not change the status of either.

---

## 3. BUSINESS OBJECTIVES / DRIVERS

Supported drivers include:

- Improve operational resilience and incident-response capability.
- Reduce mobilization, diagnosis, escalation and recovery time during critical incidents.
- Establish repeatable troubleshooting and standardized evidence collection.
- Improve observability and telemetry.
- Establish clear ownership, RACI, escalation triggers and rollback procedures.
- Preserve operational stability during transformation.
- Reduce TMA and transfers through routing optimization.
- Expand AI adoption linked to measurable operational outcomes.
- Improve agent productivity through Copilot.
- Expand Analytics/Quality-driven decision making.
- Mature WFM/forecast, scale and adherence.
- Evolve automation and self-service in Remoto/IVR journeys.
- Expand Digital/Omnichannel where aligned to customer architecture.
- Strengthen governance between Business, Technology, delivery/support teams and Genesys.
- Convert adoption into measurable business outcomes.
- **Complete the phased channel-migration rollout and decommission legacy platforms (C3 Online, Genesys Engage Call Center) — added 22/09/2026.**

**DADO FALTANTE: completar KPIs de negócio formalmente confirmados pelo cliente quando não cobertos pelas iniciativas atuais.**

---

## 4. CUSTOMER KPIs / MEASUREMENT

### Incident Readiness

Required measurement areas:

- Mobilization time.
- Evidence/log availability.
- Troubleshooting progression.
- Escalation effectiveness.
- Time to technical isolation.
- Recovery effectiveness.
- Exercise/readiness performance.
- Runbook/framework adherence.

**TBD:** formal baseline and targets.

The 1h/2h escalation references discussed on 17/09 were challenged by Santander and are **not agreed SLAs**.

### Predictive Routing

Measurement dimensions:

- TMA/AHT.
- Queue-level performance.
- Transfers.
- Relevant operational guardrails.
- Operational-hours benefit where measured.

### Copilot

Measurement dimensions:

- TMA.
- Utilization/adoption.
- Eligible population.
- Productivity/operational outcome.

### Strategic EOP indicators

The EOP frames broader evolution around:

- TMA.
- Transfers.
- Productivity.
- NPS.
- Retention.
- Omnichannel experience.
- Adherence.
- Planning.
- Utilization.
- Quality.
- Monitoring.
- Operational insights.

These are measurement dimensions and must not be treated as current achieved KPIs without specific evidence.

### Migration Rollout / A3S Evolution (added 22/09/2026)

Measurement dimensions:
- Wave completion (achieved vs. target).
- Store-channel peripheral-incident resolution.
- Functional incident/occurrence backlog closure (URA PF, Ouvidoria, SAC, contract/card loading, RBAC).
- STA access/delivery vs. TARGET date.
- Quality/WFM homologation status post-STA.

**DADO FALTANTE: completar métricas de negócio (não apenas execução) associadas ao rollout e à evolução A3S.**

---

## 5. ADOPTION SNAPSHOT

### EOP baseline — June/2026

- **4,603 active users / 4,000 contracted:** **115% utilization**.
- **8/21 features:** relevant use, **38%**.
- **10/21:** use below potential, **48%**.
- **3/21:** not in use, **14%**.
- AI: **1,269 tokens / 236,708 available**.
- **2/7 AI resources** utilized.
- More than **3.5M interactions** historically analyzed with Speech Analytics.

This is a **June/2026 historical baseline**, not the current September utilization.

**DADO FALTANTE: completar fotografia atual de setembro de licenças/features/tokens.**

### Predictive Routing

- Active historical production/value evidence exists in specific populations.
- 204 queues approved by Business for expansion.
- Expansion remains constrained by Technology/change governance.
- **21/09 update:** GPR Freeze multi-phase schedule reported (Gravity Readiness Review → First Approval Gate → 30-day Diagnostic Window); minimum 90 days / optimal 180 days of historical data required before recalculating GPR optimization; queue-reduction diagnostic window (~30 days) must complete before re-running GPR diagnostics in chat CX queues.

### Agent Copilot

- Homologated in Ouvidoria.
- ~15% TMA reduction in applied queues.
- Additional use cases under development.
- **21/09 update:** Copiloto Ouvidoria piloting 3 features (resumo automático, recomendações em tempo real, checklists de boas práticas); next phase depends on knowledge-base (cartões) curation with Ouvidoria before expanding to other areas.

### Speech Analytics

- Historical EOP evidence: >3.5M analyzed interactions.
- Continued use/tuning historically registrado.
- **Update 22/09/2026:** STA (Speech & Text Analytics) Pulse data access/analysis TARGET for 30/09/2026 — see 6.11.

### WFM

- Historical EOP evidence confirms specialized Genesys consulting to mature forecast, scales and adherence.
- **21/09 update:** Jander partnership (Planejamento/WFM) discussion pending; meeting scheduled for Friday.
- **Update 22/09/2026:** WFM implementation TARGET, sequenced after STA homologation/stabilization — see 6.11.

### Virtual Agent

- Remoto opportunity/use-case discovery.
- No production benefit confirmed.
- **21/09 update:** Voicebot for URA intent recognition reported as a pilot under discussion (POTENTIAL), alternative/complementary to Copilot.

### Migration Rollout (added 22/09/2026)

- Waves ACHIEVED: 18/08, 20/08, 24/08, 09/09, 10/09/2026.
- Waves TARGET: 13, 14, 15, 19/10/2026; remaining scope TARGET 20/10/2026.
- Physical-store (lojas) channel: PAUSED (peripheral-device intermittency incident).
- Get Atende Service (Lojas Santander): communication 15/09/2026, release 16/09/2026 (ACHIEVED), weekly follow-up established.

---

## 6. ACTIVE INITIATIVES

### 6.1 Incident Readiness Framework

**Status:** NEW / prioritized / mobilization and design.

**Objective:** create a documented, repeatable and validated critical-incident operating model.

Scope includes:

- topology;
- versions;
- SDKs;
- integrations;
- dependencies;
- logging/tracing;
- security/tooling;
- troubleshooting;
- rollback;
- runbooks;
- RACI;
- escalation;
- mobilization triggers.

**Short-term protection:**

- Escalation matrix.
- Initial evidence/log package.
- Owners/RACI.
- Mobilization mechanisms.

**TARGET timeline:**

- Up to 10 days from 17/09: mobilization/start.
- Up to 30 days: Technical Evaluation.
- Up to 60 days: documentation/approval/sign-off.
- 60–90 days: exercises/monitoring/validation.
- Up to 90 days: complete framework validated.

These are TARGETS, not achieved milestones.

**Next:** mobilize teams and initiate Technical Evaluation.

**Note (22/09):** the Genesis Event architecture (see 21/09 evidence) reportedly self-resolved a 24h chat incident with zero escalations; this is a separate, narrower capability and does NOT constitute completion of the broader Incident Readiness Framework agreed on 17/09, which remains not yet implemented.

---

### 6.2 Technical Evaluation

**Status:** Planned execution.

Expected assessment:

- Components/versions.
- SDKs.
- Dependencies/integrations.
- Relevant topology.
- Deployments/changes.
- Logging/tracing.
- Tooling/security constraints.
- Incident-window evidence.

**ACHIEVED:** none yet.

**Checkpoint:** TARGET up to 30 days from 17/09.

---

### 6.3 Predictive Routing — GPR

**Status:** Active / expansion constrained / freeze schedule reported 21/09.

Business approved rollout across **204 queues**.

Technology prefers queue adjustments before continuation; Gravity/change windows constrain both adjustment and rollout.

**21/09 update — GPR Freeze Initiative (REPORTED):**
- Phase 1 — Gravity Readiness Review: validates SMS/WhatsApp routing logic under load.
- Phase 2 — First Approval Gate: stakeholder validation checkpoint.
- Phase 3 — Diagnostic Window (30 days): post-launch observation/optimization.
- Dependency: Select CX positioning must be live before GPR public communication.
- Minimum 90 days / optimal 180 days of historical data required for GPR optimization recalculation (CONFIRMED technical requirement).

#### Historical value — EOP

**ACHIEVED — Desacordo Comercial**
- **25.62% TMA reduction**.
- **348 hours accumulated operational gain**.
- Reference: June/2026.

**ACHIEVED — Capitalização**
- **10.21% TMA reduction**.
- **144 hours accumulated operational gain**.
- Reference: June/2026.

These results apply only to the identified historical populations and **must not be generalized to the 204 approved queues**.

The EOP also identified a broader population of high-potential queues for GPR expansion.

This represents **POTENTIAL/prioritization**, not achieved rollout.

**Next:** maintain readiness, monitor Technology adjustments and execute when change governance permits; complete queue-reduction diagnostic window (~30 days) before re-running GPR diagnostics.

**Checkpoint:** October/2026 release-window reference.

---

### 6.4 Agent Copilot

**Status:** Adopted / expanding / piloting new features (21/09).

**ACHIEVED:** ~15% TMA reduction in Ouvidoria queues where applied.

**21/09 update:** Copiloto Ouvidoria piloting 3 functionalities — resumo de atendimento automático, recomendações em tempo real, checklists de melhores práticas (REPORTED / ACHIEVED as features in implementation, not yet a measured business outcome).

**Next:** curate cartões knowledge base with Ouvidoria before expanding to other areas; develop additional use cases and broaden measurement.

**Checkpoint:** TBD.

---

### 6.5 Virtual Agent — Remoto

**Status:** Discovery / opportunity; URA voicebot pilot under discussion (21/09).

Requires:

- Journey definition.
- Volumetry.
- Intents.
- Automation baseline.
- Integrations.
- Human fallback.
- KPI/business outcome.

No benefit or production adoption established.

**21/09 update:** Voicebot for intent recognition in a specific URA reported as a pilot under discussion (POTENTIAL); test readiness pending Select CX stabilization.

**Checkpoint:** TBD.

---

### 6.6 IVR / Acelerar

**Status:** Strategic architecture / advisory.

Acelerar remains operational.

Historical 08/06 customer decision reprioritized internal capacity toward Acelerador and temporarily paused pending Genesys development.

This is historical context and does not represent a current termination/pause of the relationship.

Genesys position remains advisory: demonstrate gains, implications and opportunities without framing the discussion as forced replacement.

**Next:** connect architecture decisions to measurable AI/adoption implications.

**Checkpoint:** TBD.

---

### 6.7 Speech Analytics / Analytics

**Status:** Established historical adoption / evolution.

EOP evidence shows >3.5M analyzed interactions and continuous tuning/categorization aimed at insight generation and Quality evolution.

**DADO FALTANTE: completar utilização e outcomes atuais de setembro.**

**Update 22/09/2026 (REPORTED):** STA (Speech & Text Analytics) Pulse data access/analysis TARGET 30/09/2026; Quality Management and WFM implementation sequenced after STA homologation/stabilization — see 6.11.

---

### 6.8 WFM

**Status:** Strategic adoption/evolution; Jander partnership pending (21/09).

Historical EOP evidence confirms specialized Genesys consulting focused on forecast, scales and adherence, with intent to replace legacy tools and automate critical processes.

**DADO FALTANTE: completar estágio atual e resultados da iniciativa WFM.**

**21/09 update:** Jander partnership proposal (Planejamento + WFM) discussion pending; team to bring structured feedback for a Friday meeting (REPORTED / POTENTIAL).

**Update 22/09/2026 (REPORTED):** WFM implementation TARGET, sequenced after STA homologation (see 6.11); not planned to proceed in parallel with STA.

---

### 6.9 Chat Massivo / Contestation

**Status:** Historical diagnostic / opportunity context.

May/2026 diagnostic:

- 166 interactions.
- 100 detractors / 60.2%.
- PWI 4.54.
- TMO 284.1s.
- TME 37.9s.
- Resolutivity 6.0/10.
- Effort 4.5/10.

On 10/07, AS IS macroflows and evolution proposals were presented for Desacordo Comercial and Golpe/Estelionato.

These remain diagnostic/use-case evidence unless subsequent implementation is confirmed.

---

### 6.10 Platform Migration Rollout — Channel Waves / Legacy Decommission (NEW — 22/09/2026)

**Status:** Active / phased execution.

**Business objective:** Migrate remaining channels/stores to Genesys Cloud and decommission legacy platforms.

**Current activity (REPORTED — Resultado da Agenda Tática, 22/09/2026):**

- Migration waves ACHIEVED: 18/08, 20/08, 24/08, 09/09 and 10/09/2026.
- Migration waves TARGET: 13, 14, 15 and 19/10/2026; remaining scope TARGET 20/10/2026.
- Physical-store (lojas) channel: rollout **PAUSED** — active incident, peripheral-device activation intermittency.
- Get Atende Service (Lojas Santander): communication started 15/09/2026, release 16/09/2026 (ACHIEVED), weekly follow-up established.
- SRB and SARA channels: block TARGET 16/11/2026.
- Seguros (Insurance): rollout TARGET final date 30/09/2026.
- Decommission scope: C3 Online and Genesys Engage (Call Center) — REPORTED, timeline TBD beyond the dates above.
- Gravity: activities remain in freezing (REPORTED, 22/09/2026), consistent with the September/October/November Gravity change-window references already tracked in Section 7.

**Result:** 5 of the planned waves completed; remaining waves and store-channel resumption depend on resolving current incidents.

**Risk:** Peripheral-device intermittency is blocking store-channel rollout; remaining October waves depend on resolving open functional incidents (see Section 9, R10) without introducing new operational impact.

**Next:** Define resumption plan for the store-channel rollout after peripheral-intermittency resolution; execute the October waves; track the SRB/SARA block and the Seguros deadline; confirm decommission timeline for C3 Online/Genesys Engage.

**Checkpoint:** 30/09/2026 (Seguros) and 20/10/2026 (remaining migration waves).

---

### 6.11 A3S Evolution — Speech & Text Analytics (STA) / Quality Management / WFM / Data Lake (NEW — 22/09/2026)

**Status:** Active / sequenced dependency.

**Current activity (REPORTED — Resultado da Agenda Tática, 22/09/2026):**

- STA (Speech & Text Analytics): Pulse data access and analysis TARGET for 30/09/2026.
- Quality Management and WFM implementation: TARGET, planned after STA homologation/stabilization. Sequence dependency: **STA -> Quality Management/WFM**, not parallel execution.
- Data Lake: Genesys Cloud data-ingestion workstream tracked via a dedicated **Data War Room**.
- Project backlog: review, refinement and prioritization of remaining items in progress.
- ESD timeout: improvement TARGET for next quarter.

**Result:** No Quality/WFM implementation has started yet; STA access is the current gating milestone.

**Risk:** Quality/WFM evolution is gated by STA homologation; any delay in STA access/validation cascades into the WEM maturity timeline.

**Next:** Validate STA access/delivery on 30/09/2026; define next Quality/WFM milestones once STA is homologated; consolidate the project backlog with owners, deadlines and dependencies.

**Checkpoint:** 30/09/2026 (STA access).

---

## 7. PROJECT / CHANGE CALENDAR

### Gravity

- September/2026: approval restrictions.
- October/2026: releases expected to resume.
- November/2026: additional freeze reference.
- **Update 22/09/2026 (REPORTED):** Gravity activities remain in freezing.

### Incident Readiness

- 17/09: executive agreement/start reference.
- ~27/09: TARGET mobilization/start.
- ~17/10: TARGET Technical Evaluation.
- ~16/11: TARGET documentation/sign-off.
- 60–90 days: exercises/validation.
- Up to 90 days: complete validated framework.

Dates derived from agreed target horizons remain TARGETS, not commitments of completion.

### GPR Freeze (added from 21/09 evidence)

- Phase 1: Gravity Readiness Review.
- Phase 2: First Approval Gate.
- Phase 3: 30-day Diagnostic Window post-launch.
- Additional ~60-90 days may be required post-queue-reduction before GPR diagnostics resume (90-180 day historical-data requirement).

### Migration Rollout / A3S Evolution (added 22/09/2026)

- 18/08, 20/08, 24/08, 09/09, 10/09/2026: migration waves ACHIEVED.
- 13, 14, 15, 19/10/2026: migration waves TARGET.
- 20/10/2026: remaining migration scope TARGET.
- 30/09/2026: Seguros rollout final date TARGET.
- 30/09/2026: STA (Speech & Text Analytics) Pulse access/analysis TARGET.
- 16/11/2026: SRB and SARA channel block TARGET.
- Next quarter: ESD timeout improvement TARGET.

---

## 8. RESULTS / VALUE REALIZED

### ACHIEVED

- **Copilot/Ouvidoria:** ~15% TMA reduction in applied queues.
- **GPR — Desacordo Comercial:** 25.62% TMA reduction / 348h accumulated operational gain.
- **GPR — Capitalização:** 10.21% TMA reduction / 144h accumulated operational gain.
- Speech Analytics established at material historical scale with >3.5M interactions analyzed.
- **Genesis Event: 24h chat incident self-resolved with zero escalations (21/09, REPORTED/ACHIEVED).**
- **5 platform-migration waves completed (18/08, 20/08, 24/08, 09/09, 10/09/2026) — added 22/09/2026.**
- **Get Atende Service (Lojas Santander) communicated (15/09) and released (16/09/2026) — added 22/09/2026.**

### CONFIRMED PROGRESS — NOT BUSINESS VALUE

- Business approval for 204 GPR queues.
- Incident Readiness executive agreement.
- Copilot homologation.
- WFM consulting/adoption activity.
- Chat Massivo diagnostic and contestation use-case definition.
- **Select CX narrative reframing (strategy CONFIRMED, implementation REPORTED) — 21/09.**
- **Copiloto Ouvidoria 3 features in implementation (resumo, recomendações, checklists) — 21/09.**
- **Migration rollout wave execution and decommission-scope definition (C3 Online, Genesys Engage) — added 22/09/2026.**

### TARGET / POTENTIAL

- GPR value across 204 approved queues.
- Virtual Agent Remoto benefit.
- Broader AI/IVR value.
- Contestation journey benefits.
- Incident Readiness improvements.
- Reduced future incident response/recovery time.
- **GPR Freeze phases (Gravity Readiness Review, First Approval Gate, 30-day Diagnostic Window), Scale 6x1 (8M interactions/year), Voicebot URA pilot, Jander/WFM partnership, KPIs personalizados — 21/09.**
- **Remaining migration waves (13,14,15,19/10 and 20/10/2026), Seguros rollout (30/09/2026), STA access (30/09/2026), Quality/WFM implementation post-STA, SRB/SARA block (16/11/2026) and ESD timeout improvement (next quarter) — added 22/09/2026.**

---

## 9. RISKS & BLOCKERS

### R1 — Critical incident / partnership trust

**Status:** Active / high materiality.

Santander reported >40h Customer Center impact and tied partnership confidence to materially improved future incident response.

No replacement/termination decision is confirmed.

### R2 — Investigation open

Incident mitigated; technical investigation remains open.

### R3 — Incident Readiness execution gap

Framework agreed but not yet implemented.

A new critical event before short-term controls are operational remains a material exposure.

### R4 — Escalation triggers unresolved

1h/2h references were rejected/challenged and remain under review.

### R5 — Executive/regulatory exposure

Santander reported Madrid visibility and referenced DORA/regulatory exposure.

Treat as customer-reported exposure, not independently validated obligation.

### R6 — GPR execution dependency

Business approval exists, but Technology sequencing and Gravity constrain execution. GPR Freeze multi-phase schedule (21/09) adds further sequencing before diagnostics resume.

### R7 — IVR architecture / AI adoption

Acelerar is a customer architecture decision that can affect availability/adoption of some Genesys AI capabilities.

### R8 — Current adoption visibility

June EOP baseline is available, but September utilization across licenses/features/tokens is not.

### R9 — Physical-store (lojas) channel rollout paused (NEW — 22/09/2026)

**Type:** Operational / migration execution.

An active incident with peripheral-device activation intermittency is blocking the store-channel rollout.

**Impact:** Delays remaining migration waves and full decommission of legacy platforms (C3 Online, Genesys Engage).

**Action:** Resolve peripheral intermittency; define a resumption plan for the store-channel rollout.

### R10 — Functional incident/occurrence backlog (NEW — 22/09/2026)

**Type:** Operational.

Multiple functional occurrences were reported in the 22/09/2026 tactical session: specialist disconnection, interaction redirection, pause-return behavior, callback interaction overlap, RBAC/access loss after vacation return, and an open contract/card-loading incident. Additionally, two corrections (URA PF, Ouvidoria) are in validation and one SAC occurrence remains under investigation.

**Impact:** Could affect continuity/distribution of interactions if unresolved before the October migration waves.

**Action:** Track validation of the URA PF/Ouvidoria corrections; monitor the SAC investigation; resolve the contract/card-loading incident.

### R11 — STA-gated WEM evolution (NEW — 22/09/2026)

**Type:** Dependency / sequencing.

Quality Management and WFM implementation are sequenced after STA (Speech & Text Analytics) homologation/stabilization, with STA access TARGET for 30/09/2026.

**Impact:** Any delay in STA delivery/access cascades into the Quality/WFM timeline.

**Action:** Confirm STA delivery/access on 30/09/2026 and define subsequent Quality/WFM checkpoints.

---

## 10. CRITICAL CASES

### Critical incident — 27/08

- Customer Center impact: >40h REPORTED by Santander.
- Status: mitigated / investigation open.
- Incident Readiness established as structural response.

### 0004164800 — Web Messaging

- 504/latency scenario.
- Environment reported stabilized on 29/08.
- Trust/governance and RCA remained relevant after stabilization.

### 0004059615 — Mobile Gateway Rate Limit

Historical request related to rate-limit capacity.

**DADO FALTANTE: completar status atual/closure do case.**

### Incident — Physical-store peripheral-device intermittency (NEW — 22/09/2026, REPORTED)

**Context:** Active incident causing peripheral-device activation intermittency, pausing the lojas (physical store) channel migration rollout.

**Status:** Active / rollout paused.

**DADO FALTANTE: completar número formal do case.**

**Next:** Resolve intermittency; define resumption plan for the store-channel rollout.

### Incident — Contract/card loading (NEW — 22/09/2026, REPORTED)

**Context:** Open incident related to contract and card loading, reported in the 22/09/2026 tactical session.

**Status:** Active / under treatment.

**DADO FALTANTE: completar número formal do case.**

### Occurrence — SAC under investigation (NEW — 22/09/2026, REPORTED)

**Context:** One SAC functional occurrence remains under investigation; two other corrections (URA PF, Ouvidoria) are in validation as of 22/09/2026.

**Status:** Under investigation (SAC) / in validation (URA PF, Ouvidoria).

**DADO FALTANTE: completar número(s) formal(is) do(s) case(s).**

---

## 11. CTA / WORKSTREAM STRUCTURE

### Incident Readiness

**Status:** highest-priority workstream.

**Next:** mobilization, RACI, escalation matrix, evidence package, Technical Evaluation.

**Checkpoint:** up to 10 days from 17/09.

### AI Acceleration — GPR

**Status:** approved by Business / execution constrained / freeze schedule reported 21/09.

**Result:** historical value proven in selected populations.

**Next:** preserve October execution readiness; complete GPR Freeze phases.

**Checkpoint:** October release window.

### Agent Copilot

**Status:** adopted / expansion / new Ouvidoria features piloting.

**Result:** ~15% TMA reduction in applied Ouvidoria queues; 3 new features in implementation (21/09).

**Next:** additional use cases and broader measurement; curate cartões knowledge base.

**Checkpoint:** TBD.

### Virtual Agent / Remoto

**Status:** discovery; URA voicebot pilot under discussion (21/09).

**Next:** define journey, baseline, KPI and use case.

**Checkpoint:** TBD.

### Analytics / Speech Analytics

**Status:** established historical adoption / evolution.

**Next:** validate current usage and measurable current outcomes.

**Checkpoint:** TBD.

### WFM

**Status:** adoption/evolution; Jander partnership pending.

**Next:** validate current maturity and outcomes; Friday meeting on Planejamento/WFM.

**Checkpoint:** TBD.

### IVR / Acelerar

**Status:** advisory / architecture.

**Next:** present measurable implications/opportunities while respecting customer architecture.

**Checkpoint:** TBD.

### Platform Migration Rollout (NEW — 22/09/2026)

**Status:** active / phased execution.

**Current:** 5 waves ACHIEVED; store-channel rollout PAUSED; 4 waves + remaining scope TARGET for October.

**Result:** partial rollout completed; decommission scope (C3 Online, Genesys Engage) defined.

**Risk:** peripheral-device intermittency; functional incident backlog.

**Next:** resolve store-channel incident, execute October waves, track SRB/SARA and Seguros deadlines.

**Checkpoint:** 30/09/2026 (Seguros) and 20/10/2026 (remaining waves).

### A3S Evolution — STA / Quality / WFM / Data Lake (NEW — 22/09/2026)

**Status:** active / sequenced dependency.

**Current:** STA access TARGET 30/09/2026; Quality/WFM sequenced after STA; Data Lake tracked via Data War Room.

**Result:** no Quality/WFM implementation started yet.

**Risk:** STA delay cascades into Quality/WFM timeline.

**Next:** validate STA access, define next Quality/WFM milestones, consolidate backlog.

**Checkpoint:** 30/09/2026 (STA access).

### CSP

**Status:** CONFIRMED / established.

### EOP

**Status:** available and incorporated into account intelligence.

**DADO FALTANTE: completar formal presentation/validation date/status.**

---

## 12. NEXT MILESTONES

- ~27/09: Incident Readiness mobilization/start TARGET.
- ~17/10: Technical Evaluation TARGET.
- October: expected reopening of formal releases / GPR readiness.
- End-Oct: historical GPR rollout target, dependency-based.
- ~16/11: Incident Readiness documentation/sign-off TARGET.
- November: additional Gravity freeze reference.
- Up to mid-Dec: Incident Readiness complete validation TARGET.
- Copilot expansion: TBD.
- Virtual Agent: TBD.
- WFM: TBD.
- EOP next review: TBD.
- **Friday (post-21/09): Jander meeting on Planejamento/WFM (added from 21/09 evidence).**
- **30/09/2026: Seguros rollout final date TARGET (added 22/09/2026).**
- **30/09/2026: STA (Speech & Text Analytics) Pulse access/analysis TARGET (added 22/09/2026).**
- **13, 14, 15, 19/10/2026: Migration wave TARGET dates (added 22/09/2026).**
- **20/10/2026: Remaining migration-wave scope TARGET (added 22/09/2026).**
- **16/11/2026: SRB and SARA channel block TARGET (added 22/09/2026).**
- **Next quarter: ESD timeout improvement TARGET (added 22/09/2026).**

---

## 13. CUSTOMER / ACCOUNT DECISIONS

- Build joint Incident Readiness Framework.
- Execute Technical Evaluation.
- Anticipate short-term incident protections.
- Keep investigation open until evidence supports closure.
- Review escalation triggers; 1h/2h are not agreed SLAs.
- Maintain elevated executive governance.
- Formal Problem / Stabilization Forum established.
- Business approved GPR rollout.
- Technology prefers queue adjustments first.
- Acelerar remains operational.
- Copilot homologated in Ouvidoria.
- Virtual Agent requires further use-case definition.
- CSP is considered established.
- Historical EOP evidence is incorporated without overriding newer Current State.
- **Reframe Select CX narrative around Genesis Event outcomes rather than Q2 negative benchmarking (21/09).**
- **Sequence GPR Freeze phases before public GPR communication (21/09).**
- **Curate cartões knowledge base with Ouvidoria before expanding Copiloto to other areas (21/09).**
- **Santander confirmed continuity of the phased Genesys Cloud migration rollout across remaining channels, with waves tracked through October 2026 (added 22/09/2026).**
- **Decommission of C3 Online and Genesys Engage (Call Center) remains in scope (added 22/09/2026).**
- **Quality Management and WFM implementation will follow STA homologation/stabilization, not proceed in parallel (added 22/09/2026).**

---

## 14. GOVERNANCE

Governance coordinates:

- Santander Business.
- Santander Technology.
- Pulse.
- Santander technical teams.
- Genesys CSM/TAM.
- Product Support.
- Incident Management.
- Resolution Management.
- Engineering.
- Network/Security specialists.
- Professional Services.
- Executive leadership.
- **Data War Room (Data Lake ingestion tracking) — added 22/09/2026.**
- **Get Atende Service (Lojas Santander delivery partner) — added 22/09/2026.**
- **Jander (Planejamento/WFM partnership, pending) — added from 21/09 evidence.**

Incident Readiness adds:

- Formal Problem tracking.
- Stabilization Forum with CIO visibility.
- Executive oversight.
- Cluster ownership/RACI.
- Future standardized evidence and escalation model.

Current initial crisis path:

**Santander / N2 / PS → Product Support → War Room**

Future state should introduce earlier TAM participation, objective mobilization triggers, specialist escalation, documented environment context and standardized evidence.

---

## 15. EVIDENCE LEDGER

### 2026-09-22 — Resultado da Agenda Tática: Migration Rollout, Functional Incident Backlog and A3S Evolution

**Type:** REPORTED / ACHIEVED / TARGET

- Migration waves ACHIEVED: 18/08, 20/08, 24/08, 09/09, 10/09/2026.
- Migration waves TARGET: 13, 14, 15, 19/10/2026; remaining scope TARGET 20/10/2026.
- Physical-store (lojas) channel rollout PAUSED — active incident, peripheral-device intermittency.
- Get Atende Service (Lojas Santander): communication 15/09/2026, release 16/09/2026, weekly follow-up established.
- SRB/SARA channel block TARGET 16/11/2026.
- Gravity activities remain in freezing (REPORTED).
- Seguros rollout TARGET final date 30/09/2026.
- Decommission scope confirmed: C3 Online and Genesys Engage (Call Center).
- Functional incidents reported: specialist disconnection, interaction redirection, pause-return behavior, callback interaction overlap, RBAC/access loss after vacation, contract/card loading incident (open).
- Functional occurrences: URA PF and Ouvidoria corrections in validation; one SAC occurrence under investigation.
- STA (Speech & Text Analytics): Pulse data access/analysis TARGET 30/09/2026.
- Quality Management and WFM implementation sequenced after STA homologation/stabilization.
- Data Lake ingestion workstream tracked via dedicated Data War Room.
- Project backlog under review/refinement/prioritization.
- ESD timeout improvement TARGET next quarter.
- This update is a separate tactical/execution layer from both the Incident Readiness Framework (27/08 critical incident) and the 21/09 Genesis Event/GPR Freeze cycle below; it does not change either workstream's status.

**Versioning correction note:** the v1.4 file received had header (`FILE:`/`VERSION:`) marked 1.4/REPLACES 1.3, while the document body still read "Version: 1.2 / Last Updated: 2026-09-21" (inherited inconsistency, not corrected in prior cycles). This v1.5 aligns header and body to 1.5 / 2026-09-22. Flagged to the CSM per skill guardrail (header/body version mismatch must be reported, not silently assumed).

### 2026-09-21 — Genesis Event + Select CX + GPR Freeze + Scale 6x1 (2026-Q3 Cycle Close)

#### Genesis Event Initiative (CONFIRMED — Success achieved 21/09)
- **Status**: ACHIEVED — 24h chat incident resolved successfully via Genesis Event architecture
- **Evidence Classification**: CONFIRMED / ACHIEVED
- **Capability**: Incident detection + autonomous remediation (real-time context without specialist escalation)
- **Result**: Zero escalations required; incident fully self-resolved within 24-hour window
- **Historical context**: Represents maturation of real-time diagnostic layer; directly addresses Select CX pain point (manual specialist intervention costs)
- **Reference**: Cycle close meeting 2026-09-21 (voice + evidence ledger)

#### Select CX Strategy (REPORTED — Account reframing confirmed 21/09)
- **Status**: CONFIRMED Strategy / REPORTED Implementation Progress
- **Evidence Classification**: CONFIRMED / REPORTED
- **Background**: Previous Select CX benchmark (Q2 2026) showed negative positioning vs. contact resolution efficiency metrics
- **Reframing approach**: Spotlight Genesis Event incident resolution + demonstrate "proactive" vs. "reactive" value perception shift
- **Positioning**: Cost avoidance via autonomous diagnostics (incident detection → resolution without manual specialist time)
- **Checkpoint**: Negative benchmarking data no longer primary narrative; shifted to capability/outcome focus
- **Reference**: 2026-09-21 CSM + Commercial sync (Account Master Cycle Close Brief)

#### GPR Freeze Initiative (REPORTED — Multi-phase schedule confirmed 21/09)
- **Phase 1 — Gravity Readiness Review**: Validates SMS/WhatsApp routing logic under load; baseline for diagnostics
- **Phase 2 — First Approval Gate**: Stakeholder validation checkpoint; release decision authority
- **Phase 3 — Diagnostic Window (30-day)**: Post-launch observation; performance monitoring + optimization adjustments
- **Evidence Classification**: REPORTED / TARGET (phases scheduled, metrics TBD)
- **Dependency**: Select CX positioning must be live before GPR public communication
- **Next checkpoint**: Gravity readiness completion target (TBD, pending technical validation)
- **Reference**: 2026-09-21 Gravity + First Approval Gate scope documentation

#### Scale 6x1 Capability (REPORTED — Quantified scale confirmed 21/09)
- **Achievement**: 8M total interactions (annual extrapolation from engagement baseline)
- **Headcount requirement**: Scale to 6x1 specialist-to-automated-flow ratio (net reduction in manual specialist allocation)
- **Implication**: Cost optimization path via Genesis Event + GPR architectures
- **Evidence Classification**: CONFIRMED (headcount model) / REPORTED (scale targets)
- **Business context**: Supports Santander's operational efficiency objectives; aligns with Select CX reframing narrative
- **Reference**: 2026-09-21 Account Master Cycle Close Brief + Operational Scaling Model

#### Copilot + Voicebot Roadmap (REPORTED — Feasibility assessment 21/09)
- **Status**: REPORTED / POTENTIAL (under assessment)
- **Scope**: Secondary initiatives; dependent on successful GPR launch + Select CX stabilization
- **Evidence Classification**: REPORTED / POTENTIAL
- **Sequencing**: Post-Phase 3 diagnostic window (GPR optimization complete, then copilot + voicebot pilots)
- **Reference**: 2026-09-21 Secondary roadmap discussion (conditional on primary initiatives)

**Nota de integridade (22/09):** o bloco "2026-09-21 — Genesis Event + Select CX + GPR Freeze + Scale 6x1" está duplicado de forma idêntica no arquivo-base v1.4 recebido (aparece duas vezes, uma imediatamente após a outra). Por Guardrail #4 (nunca remover histórico), a segunda ocorrência foi preservada abaixo e apenas marcada como redundante — não foi deletada.

### 2026-09-21 — Genesis Event + Select CX + GPR Freeze + Scale 6x1 (2026-Q3 Cycle Close) — [REDUNDANTE com a seção idêntica imediatamente acima; preservado por Guardrail #4, não deletado]

#### Genesis Event Initiative (CONFIRMED — Success achieved 21/09)
- **Status**: ACHIEVED — 24h chat incident resolved successfully via Genesis Event architecture
- **Evidence Classification**: CONFIRMED / ACHIEVED
- **Capability**: Incident detection + autonomous remediation (real-time context without specialist escalation)
- **Result**: Zero escalations required; incident fully self-resolved within 24-hour window
- **Historical context**: Represents maturation of real-time diagnostic layer; directly addresses Select CX pain point (manual specialist intervention costs)
- **Reference**: Cycle close meeting 2026-09-21 (voice + evidence ledger)

#### Select CX Strategy (REPORTED — Account reframing confirmed 21/09)
- **Status**: CONFIRMED Strategy / REPORTED Implementation Progress
- **Evidence Classification**: CONFIRMED / REPORTED
- **Background**: Previous Select CX benchmark (Q2 2026) showed negative positioning vs. contact resolution efficiency metrics
- **Reframing approach**: Spotlight Genesis Event incident resolution + demonstrate "proactive" vs. "reactive" value perception shift
- **Positioning**: Cost avoidance via autonomous diagnostics (incident detection → resolution without manual specialist time)
- **Checkpoint**: Negative benchmarking data no longer primary narrative; shifted to capability/outcome focus
- **Reference**: 2026-09-21 CSM + Commercial sync (Account Master Cycle Close Brief)

#### GPR Freeze Initiative (REPORTED — Multi-phase schedule confirmed 21/09)
- **Phase 1 — Gravity Readiness Review**: Validates SMS/WhatsApp routing logic under load; baseline for diagnostics
- **Phase 2 — First Approval Gate**: Stakeholder validation checkpoint; release decision authority
- **Phase 3 — Diagnostic Window (30-day)**: Post-launch observation; performance monitoring + optimization adjustments
- **Evidence Classification**: REPORTED / TARGET (phases scheduled, metrics TBD)
- **Dependency**: Select CX positioning must be live before GPR public communication
- **Next checkpoint**: Gravity readiness completion target (TBD, pending technical validation)
- **Reference**: 2026-09-21 Gravity + First Approval Gate scope documentation

#### Scale 6x1 Capability (REPORTED — Quantified scale confirmed 21/09)
- **Achievement**: 8M total interactions (annual extrapolation from engagement baseline)
- **Headcount requirement**: Scale to 6x1 specialist-to-automated-flow ratio (net reduction in manual specialist allocation)
- **Implication**: Cost optimization path via Genesis Event + GPR architectures
- **Evidence Classification**: CONFIRMED (headcount model) / REPORTED (scale targets)
- **Business context**: Supports Santander's operational efficiency objectives; aligns with Select CX reframing narrative
- **Reference**: 2026-09-21 Account Master Cycle Close Brief + Operational Scaling Model

#### Copilot + Voicebot Roadmap (REPORTED — Feasibility assessment 21/09)
- **Status**: REPORTED / POTENTIAL (under assessment)
- **Scope**: Secondary initiatives; dependent on successful GPR launch + Select CX stabilization
- **Evidence Classification**: REPORTED / POTENTIAL
- **Sequencing**: Post-Phase 3 diagnostic window (GPR optimization complete, then copilot + voicebot pilots)
- **Reference**: 2026-09-21 Secondary roadmap discussion (conditional on primary initiatives)

#### Copiloto com IA — Ouvidoria (REPORTED — Implementação em progresso)
- **Status**: REPORTED / ACHIEVED (3 funcionalidades implementando)
- **Evidence Classification**: REPORTED / ACHIEVED (funcionalidades)
- **Funcionalidades em Implementação**:
  1. Resumo de atendimento (automático)
  2. Recomendações em tempo real (durante interação)
  3. Checklists de melhores práticas (guidance)
- **Contexto**: Piloto na área de ouvidoria com 3 recursos funcionais
- **Next Phase**: Curadoria da base de conhecimento de cartões com ouvidoria antes de expandir para outras áreas
- **Reference**: 2026-09-21 meeting recap (Dayan Nakashima update)

#### KPIs Personalizados (REPORTED — Implementação paralela)
- **Status**: REPORTED / TARGET (implementação planejada em paralelo)
- **Evidence Classification**: REPORTED / TARGET
- **Approach**: Implementar KPIs personalizados enquanto aguarda resultado da redução de filas (~30 dias)
- **Dependency**: Complementa redução de filas initiative
- **Reference**: 2026-09-21 meeting (Hugo + Rodrigo Ferreira alignment)

#### Voicebot — URA Intent Recognition (REPORTED — Pilot planning)
- **Status**: REPORTED / POTENTIAL (URA-specific pilot under discussion)
- **Evidence Classification**: REPORTED / POTENTIAL
- **Scope**: Voicebot implementation for intent identification in specific URA (Unidade de Resposta Audível)
- **Business Context**: Alternative automation strategy alongside copilot; leverages existing IVR infrastructure
- **Next Checkpoint**: Test readiness pending Select CX stabilization
- **Reference**: 2026-09-21 meeting (Hugo discussion with Rodrigo)

#### Redução de Filas — Timeline & Diagnostics (REPORTED — Delayed timeline)
- **Status**: REPORTED / IN PROGRESS (complicated, requires extension)
- **Evidence Classification**: REPORTED / IN PROGRESS
- **Challenge**: Activity more complex than initially projected; requires longer execution timeline
- **Diagnostic Window**: Minimum ~30 days after queue reduction migration before re-running GPR diagnostics
- **Next Evaluation**: Assess queue propensity post-optimization adjustments before GPR testing in chat CX queues
- **Reference**: 2026-09-21 meeting (Hugo clarification on timeline extension)

#### GPR Historico Minimo — 90 vs 180 dias (CONFIRMED — Technical requirement)
- **Status**: CONFIRMED / TARGET
- **Evidence Classification**: CONFIRMED (technical requirement) / TARGET (optimal timing)
- **Minimum Viable**: 90 days of historical data for GPR optimization recalculations
- **Optimal Baseline**: 180 days for more robust optimization modeling
- **Implication**: Post-30-day queue reduction window → wait additional 60-90 days before GPR diagnostics
- **Reference**: 2026-09-21 meeting (Hugo technical confirmation)

#### Jander Partnership — Planejamento & WFM (REPORTED — Partnership proposal)
- **Status**: REPORTED / POTENTIAL (partnership discussion pending)
- **Evidence Classification**: REPORTED / POTENTIAL
- **Stakeholder**: Jander (TBD department/role)
- **Agenda**: Planejamento (planning) + WFM (Workforce Management) discussion
- **Structured Feedback**: Team to bring structured feedback for Friday meeting
- **Checkpoint**: Meeting scheduled for Friday to align on planning themes and WFM usage
- **Reference**: 2026-09-21 meeting (Rodrigo + Hugo alignment on Jander meeting)

#### Base de Conhecimento — Cartões + Ouvidoria (REPORTED — Curadoria em progresso)
- **Status**: REPORTED / IN PROGRESS (knowledge base curation ongoing)
- **Evidence Classification**: REPORTED / IN PROGRESS
- **Initiative**: Curate card-related knowledge base articles with ouvidoria team
- **Dependency**: Must complete curation BEFORE expanding copiloto AI to other business areas
- **Owner**: Dayan Nakashima (curadoria coordination)
- **Next Step**: After curation complete, signal Rodrigo Ferreira optimal timing for visit + tracking copiloto gains
- **Reference**: 2026-09-21 meeting (Dayan task assignment)

### 2026-09-18 — EOP / CSP consolidation

**Type:** CONFIRMED / ACHIEVED / HISTORICAL / TARGET

- EOP incorporated as historical strategic/adoption evidence.
- CSP classified as established.
- June/2026 adoption baseline incorporated:
  - 4,603/4,000 users.
  - 8/21 relevant-use features.
  - AI 1,269/236,708 tokens.
- Historical GPR outcomes incorporated:
  - Desacordo Comercial: -25.62% TMA / 348h.
  - Capitalização: -10.21% TMA / 144h.
- >3.5M Speech Analytics interactions incorporated as historical scale evidence.
- Historical WFM consulting/adoption context incorporated.
- EOP opportunity roadmap preserved as opportunity, not implementation.
- Current September state preserved over older EOP evidence.

### 2026-09-17 — Incident Readiness Executive Session

**Type:** CONFIRMED / REPORTED / TARGET

- Executive session held.
- 27/08 incident mitigated but investigation open.
- >40h Customer Center impact reported.
- Madrid visibility reported.
- Incident Readiness Framework agreed.
- Technical Evaluation agreed.
- Short-term protections prioritized.
- 10/30/60/90-day horizons established.
- 1h/2h escalation references challenged.
- DORA/regulatory exposure referenced by customer.
- Formal Problem/Stabilization Forum governance established.

### 2026-09-16 — Account consolidation

- GPR Business approval / Technology dependency.
- Gravity constraint.
- Copilot ~15% TMA reduction.
- Virtual Agent Remoto opportunity.
- Acelerar operational.

### 2026-08-29 — Web Messaging stabilization

- Case 0004164800 reported stabilized.

### 2026-07-10 — Chat Massivo / Contestation

- Diagnostic discussed.
- AS IS macroflows presented.
- Evolution proposals established, not implementation.

### 2026-06 — EOP baseline/value

- GPR Desacordo Comercial and Capitalização measured outcomes.
- Platform/adoption baseline established.
- Speech Analytics scale documented.
- WFM consulting/adoption context documented.

### 2026-06-08 — Acelerador reprioritization

- Santander temporarily reprioritized internal capacity.
- Genesys support governance remained available.
- Decision was reprioritization, not relationship termination.

---

## 16. HISTORICAL TIMELINE

*(Sem novo fechamento de ciclo nesta atualização — "Atualizar" adiciona evidência ao Evidence Ledger e reflete no Estado Atual das seções acima, mas não abre uma nova entrada no Historical Timeline. Isso só acontece em "Fechar ciclo Santander", que ainda não foi executado desde 2026-09-18. Timeline preservado 100% intacto abaixo.)*

### 2026-09-18 — Cycle Closure v1.2 / EOP & CSP Enrichment

**Current state**

- Incident Readiness remains highest-criticality workstream.
- 27/08 incident remains mitigated/investigation open.
- GPR remains Business-approved but execution constrained.
- Copilot remains adopted in Ouvidoria with measured value.
- Virtual Agent remains discovery.
- Acelerar remains operational.
- CSP established.
- EOP enriches historical adoption/value context.

**Changes**

- **NEW HISTORICAL:** June EOP adoption baseline.
- **NEW HISTORICAL ACHIEVED:** GPR Desacordo Comercial -25.62% TMA / 348h.
- **NEW HISTORICAL ACHIEVED:** GPR Capitalização -10.21% TMA / 144h.
- **NEW HISTORICAL:** >3.5M Speech Analytics interactions.
- **NEW HISTORICAL:** WFM specialized consulting/adoption context.
- **UPDATED:** CSP classified as established.
- **UNCHANGED:** Incident Readiness current state.
- **UNCHANGED:** GPR 204-queue execution dependency.
- **UNCHANGED:** Copilot current result.
- **UNCHANGED:** Virtual Agent maturity.
- **UNCHANGED:** Acelerar architecture.

**Decisions**

- Preserve EOP metrics with historical population/timeframe.
- Do not generalize GPR historical results to 204 queues.
- Treat CSP as established.
- Preserve EOP opportunity roadmap as TARGET/POTENTIAL unless newer evidence confirms execution.
- Maintain Incident Readiness as primary current account priority.

**Results**

- Historical GPR value is now quantitatively documented.
- Historical adoption baseline is improved.
- No new September business outcome was established by this closure.

**Risks**

- Partnership trust / operational resilience.
- Open incident investigation.
- Readiness framework not yet implemented.
- Escalation triggers unresolved.
- GPR execution constrained.
- Current September adoption metrics incomplete.

**Completed**

- EOP evidence incorporated.
- CSP status incorporated.
- Historical GPR results incorporated.

**Next**

- Mobilize Incident Readiness.
- Start Technical Evaluation.
- Maintain investigation.
- Preserve October GPR readiness.
- Expand Copilot measurement.
- Validate current adoption.
- Advance Virtual Agent, WFM and Analytics where supported.

### 2026-09-17 — Cycle Closure / Incident Readiness

- Incident mitigated / investigation open.
- >40h impact reported.
- Incident Readiness established.
- GPR Business-approved / constrained.
- Copilot ~15% TMA reduction.
- Virtual Agent discovery.
- Acelerar operational.

### 2026-09-16 — Baseline

- Strategic AI/adoption portfolio active.
- GPR, Copilot, Virtual Agent and IVR architecture established as primary adoption themes.
- Operational incident governance became material.

---

## 17. OUTPUT RULES FOR FUTURE UPDATES

1. Preserve ACHIEVED / TARGET / POTENTIAL / REPORTED / CONFIRMED / INFERENCE distinctions.
2. Preserve EOP metrics with population and reference period.
3. Never generalize GPR historical results to the 204-queue rollout.
4. Do not convert EOP roadmap/opportunities into implementation.
5. June adoption data is historical; do not present as September utilization.
6. CSP is established.
7. EOP exists; formal presentation/validation status remains TBD until evidenced.
8. Copilot ~15% TMA applies only to measured Ouvidoria queues.
9. Incident Readiness is a program being built, not an implemented capability — the Genesis Event self-resolution (21/09) is a narrower capability and does not by itself complete the Framework.
10. Preserve sequence: executive agreement → mobilization → Technical Evaluation → documentation/sign-off → exercises/validation → operational framework.
11. 1h/2h references are not agreed SLAs.
12. >40h incident impact is REPORTED by Santander.
13. Do not infer incident root cause.
14. Mitigation ≠ investigation closure.
15. DORA/regulatory exposure remains customer-reported.
16. Partnership risk does not equal confirmed termination/replacement.
17. Respect Acelerar as customer architecture.
18. Use **DADO FALTANTE: completar [...]** for material missing output data.
19. Every active CTA should show next step/checkpoint when supported.
20. Supported outputs:
   - Liderança
   - Gerencial
   - CTAs
   - Completo
   - Status Semanal Brasil
21. Preserve migration-wave dates (18/08, 20/08, 24/08, 09/09, 10/09/2026 ACHIEVED; 13, 14, 15, 19/10/2026 and 20/10/2026 TARGET) with their status.
22. Treat the physical-store channel rollout as PAUSED, not cancelled, pending peripheral-device intermittency resolution.
23. Quality Management and WFM implementation are sequenced after STA homologation — do not present as parallel or independent workstreams.
24. Decommission scope (C3 Online, Genesys Engage Call Center) is REPORTED/TARGET, not yet executed, unless newer evidence confirms completion.
25. The 22/09/2026 tactical migration/A3S update, the 21/09/2026 Genesis Event/GPR Freeze cycle, and the Incident Readiness Framework (27/08 critical incident, Section 6.1) are three separate execution layers — do not merge or conflate them.
26. GPR requires a minimum of 90 days (optimal 180 days) of historical data before recalculating optimization — preserve this as a CONFIRMED technical requirement, not a TARGET preference.
27. "Atualizar [Cliente]" adds to the Evidence Ledger and may update Current-State sections for reporting, but does not open a new Historical Timeline entry — that only happens on "Fechar ciclo [Cliente]".
28. If the file header (`FILE:`/`VERSION:`) and body (`Version:`) fields are found inconsistent, report it explicitly to the user before proceeding — do not silently pick one.
