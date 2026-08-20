# Way Forward — Action Plan for ERC Revisions

**Proposal:** P550/06/2026 — *A Hybrid Deep Learning Framework for Intracranial Aneurysms Detection*
**PI:** Cavin Otieno Ouma | **Primary Supervisor:** Prof. Peter Waiganjo
**ERC Review Date:** 5 August 2026
**Deadline for Resubmission:** **2 September 2026 (4 weeks)**
**Current Status:** REVISIONS REQUIRED — Conditional approval pending

---

## Executive Summary

The KNH-UoN ERC has reviewed your research proposal and issued a **conditional decision: revise and resubmit within 4 weeks**. The 12 main feedback points are largely **administrative and structural** (not fundamental ethical objections), with **one critical ethical cluster** (Sections 4.7.i–v) that requires substantive new content. The good news: **all issues are addressable within the 4-week window** with focused work. The bad news: missing the deadline restarts the review cycle and may delay your graduation.

This document provides:
1. **Cover letter template** (with the required summary table).
2. **Detailed revision roadmap** organized by priority and effort.
3. **Sample SMART objective format** to follow.
4. **Sample restructuring of Chapter 2** literature review.
5. **Draft paragraphs** for the four ethical gaps.
6. **Draft incidental findings escalation protocol**.
7. **Recommended stakeholder consent form** outline.
8. **4-week Gantt chart** for the work.
9. **Submission checklist**.

---

## 1. Cover Letter Template

Use the following cover letter when resubmitting. The ERC requires a table summarizing how each comment was addressed and where (page numbers) in the revised proposal.

```
KNH-UoN ERC
P.O. Box 19676 Code 00202
Nairobi, Kenya
Email: uonknh_erc@uonbi.ac.ke

[Date: 28 August 2026]

The Secretary
KNH-UoN Ethics and Research Committee

Dear Prof. Amugune,

RE: RESUBMISSION OF REVISED RESEARCH PROPOSAL — P550/06/2026
"A Hybrid Deep Learning Framework for Intracranial Aneurysms Detection:
Algorithmic Development and Fairness Evaluation for Kenyan Public Health Settings"

I acknowledge receipt of the KNH-UoN ERC review letter dated 5 August 2026
(Ref: KNH-ERC/RR/561mm) and thank the committee for the thorough and
constructive feedback. I have carefully addressed each of the 12 main
observations and 5 ethical considerations raised. The revised proposal
(3 copies + application form) is enclosed.

Below is a summary table of how each comment has been addressed, with
the page number(s) where the changes have been made. All revisions are
highlighted in **bold** within the body of the proposal for ease of
reference.
```

### 1.1 Required Summary Table

| # | ERC Comment | Action Taken | Page(s) in Revised Proposal |
|---|-------------|--------------|----------------------------|
| **1** | **Preliminaries — Supervisory Team:** Consider getting someone from Department of Radiology as a second supervisor. | **Added Dr. Kevin Ombati (Department of Radiology, AKUH) as Local Data Co-Investigator with defined roles. See revised Section 1.5 (Acknowledgments) and updated Application Form Personnel Block 3.** | pp. 1, revised Application Form |
| **2** | **Abstract — Remove references; restructure with subtitles (Background, Broad Objective, Methodology, Utility).** | **Abstract fully rewritten without in-text citations. Structured under the four required subtitles.** | p. ii–iii (Abstract) |
| **3** | **Section 1.3 — Objectives must be brief, precise, and SMART.** | **Three objectives rewritten as single-sentence SMART objectives (Specific, Measurable, Achievable, Relevant, Time-bound). Objectives 4 and 5 (interview-based) removed from scope.** | pp. 7–8 |
| **4** | **Section 1.4 — Research Questions must be precise.** | **Two research questions rewritten with explicit variables, populations, outcomes, metrics, and timeframes. Research Question 3 (clinical utility) removed from scope.** | pp. 8–9 |
| **5** | **Chapter 2 — Literature Review must follow the four-part flow.** | **Chapter 2 fully restructured: (2.1) Public Burden, (2.2) Past Diagnosis & Treatment Gaps, (2.3) Innovative Approaches & Testing, (2.4) Why Our Approach / Contribution to Knowledge.** | pp. 10–23 |
| **6** | **Section 3.1 — Clarify "mixed-methods" meaning.** | **Section 3.1 rewritten to explicitly state purely experimental quantitative design. Quantitative arms: RSNA-ICA training + AKUH local validation. Health systems assessment reframed as technical workflow analysis. Qualitative/stakeholder-interview arm entirely removed.** | p. 24 |
| **7** | **Section 3.2 — Name and justify study sites.** | **Sites explicitly named and justified: (a) AKUH — primary local validation site under Dr. Kevin Ombati; (b) KENET CHUI HPC — GPU training environment; (c) UoN DoM and DCI — analysis environment. KNH not engaged as data source.** | pp. 24–25 |
| **8** | **Section 3.2 — Define study population and address consent.** | **Study population defined for each arm: (a) RSNA-ICA training: international de-identified historical CTA scans; (b) AKUH local validation: 200–300 retrospective adult CTA scans (Jan 2020–Dec 2025). No interviews conducted.** | pp. 25–26 |
| **9** | **Section 3.3 — Inclusion and Exclusion criteria.** | **New sub-section 3.3 added with explicit inclusion/exclusion criteria for each data source (RSNA-ICA, AKUH).** | pp. 26–27 |
| **10** | **Section 3.3 — Sample size justification.** | **Sample size for AKUH local validation (n=200–300) justified using precision-based estimation: at 3–5% prevalence, expected 6–15 positive cases; sensitivity estimation precision (95% CI width ±30%) explicitly stated. RSNA-ICA training set is the entire open-access dataset (~4,000 studies).** | p. 27 |
| **11** | **Section 3.4 — Is all data retrospective?** | **Section 3.4 explicitly states: (a) RSNA-ICA and AKUH arms are 100% retrospective (no prospective patient contact). (b) Qualitative/stakeholder-interview arm entirely removed from protocol.** | pp. 27–28 |
| **12.i** | **Risk of Study — AKUH data identifiability at source.** | **New sub-section 3.7.1 added acknowledging: AKUH data is identifiable at source before de-identification; downstream use carries indirect patient-safety implications; study is developmental only, NOT diagnostic-in-use.** | pp. 36–37 |
| **12.ii** | **Jurisdictional Gap — AKUH ERC + MTA/DTA.** | **New sub-section 3.7.2 added: (a) AKUH ERC submission planned within one week of KNH-UoN ERC approval. (b) AKUH-UoN MTA/DTA under negotiation; signed copy to be appended or provided as conditional commitment.** | pp. 37–38 |
| **12.iii** | **Informed Consent — Waiver justification for AKUH data.** | **New sub-section 3.7.3 added: waiver justification explaining impracticality of contacting 200–300 historical patients, HIPAA Safe Harbor 18-identifier de-identification, separation of linking key held only by AKUH data custodian (Dr. Kevin Ombati), no return of individual findings, minimal risk.** | pp. 38–40 |
| **12.iv** | **Risk-Benefit & Non-Deployment Safeguard — Incidental findings escalation protocol.** | **New sub-section 3.7.4 added with explicit: (1) Declaration that no AI output will inform patient care during study period. (2) Incidental Findings Escalation Protocol with 6-step table (trigger, action, responsible party, timeline).** | pp. 40–42 |

**All changes are highlighted in bold in the body of the revised proposal.**

Sincerely,

Cavin Otieno Ouma
MSc Candidate, Public Health Data Science
Reg. No. SDS6/46982/2024

cc: Prof. Peter Waiganjo (Primary Supervisor)
cc: Dr. Pamela Mandela (Co-Supervisor)
cc: Dr. [NEW Radiology Supervisor]
cc: Dr. Kevin Ombati (AKUH Local Data Co-Investigator)
cc: Chair, Dept. of Mathematics, UoN
```

---

## 2. Detailed Revision Roadmap

### Priority Tier 1 (CRITICAL — must do first)

| Task | Effort | Target Date | Owner |
|------|--------|-------------|-------|
| **A. Email Prof. Waiganjo + Dr. Pamela Mandela today** to inform them of ERC feedback and request emergency supervisory meeting | 30 min | **7 Aug 2026 (TODAY)** | PI |
| **B. Contact Dr. Kevin Ombati at AKUH** to (1) confirm his willingness to be added as formal co-supervisor OR identify a UoN Department of Radiology faculty member who can serve | 1 day | **8 Aug 2026** | PI |
| **C. Contact AKUH ERC office** to inquire about parallel submission requirements and AKUH-specific MTA/DTA template | 1 day | **8 Aug 2026** | PI |
| **D. Restructure Abstract** (remove references, add 4 subtitles) | 2 hours | **8 Aug 2026** | PI |
| **E. Rewrite Objectives (SMART)** — single sentence each | 2 hours | **9 Aug 2026** | PI |
| **F. Rewrite Research Questions** — precise wording with variables/metrics | 2 hours | **9 Aug 2026** | PI |

### Priority Tier 2 (HIGH — substantive content)

| Task | Effort | Target Date | Owner |
|------|--------|-------------|-------|
| **G. Restructure Chapter 2 Literature Review** into 4-part flow (Burden → Past → Innovations → Why Us) — may require re-ordering existing sections | 2 days | **11–12 Aug 2026** | PI |
| **H. Clarify Section 3.1 "Mixed-Methods"** — explicit quantitative vs qualitative arms | 1 hour | **12 Aug 2026** | PI |
| **I. Section 3.2 Name & Justify Study Sites** | 2 hours | **13 Aug 2026** | PI |
| **J. Section 3.2 Define Study Population + Consent** | 2 hours | **13 Aug 2026** | PI |
| **K. Section 3.3 Inclusion/Exclusion Criteria** | 2 hours | **14 Aug 2026** | PI |
| **L. Section 3.3 Sample Size Justification** — precision-based calculation | 3 hours | **14 Aug 2026** | PI |
| **M. Section 3.4 Data Collection** — address qualitative arm | 2 hours | **15 Aug 2026** | PI |

### Priority Tier 3 (CRITICAL — ethical gaps)

| Task | Effort | Target Date | Owner |
|------|--------|-------------|-------|
| **N. Sub-section 3.7.1: Risk of Study (AKUH identifiability)** | 2 hours | **15 Aug 2026** | PI |
| **O. Sub-section 3.7.2: Jurisdictional Gap (AKUH ERC + MTA)** | 3 hours | **16 Aug 2026** | PI |
| **P. Sub-section 3.7.3: Informed Consent Waiver Justification** | 3 hours | **17 Aug 2026** | PI |
| **Q. Sub-section 3.7.4: Risk-Benefit & Non-Deployment + Incidental Findings Escalation Protocol** | 4 hours | **18 Aug 2026** | PI |
| **R. Sub-section 3.7.5: Stakeholder Engagement Consent** + Draft Annex C consent form | 4 hours | **19 Aug 2026** | PI |

### Priority Tier 4 (FINAL — packaging)

| Task | Effort | Target Date | Owner |
|------|--------|-------------|-------|
| **S. Update Application Form (Personnel Block 3 for new supervisor)** | 1 hour | **20 Aug 2026** | PI |
| **T. Update Similarity Report** (re-run Turnitin) — aim for <10% with all "Not Cited" matches converted to in-text citations | 1 day | **21 Aug 2026** | PI |
| **U. Update Bibliography** (remove references that were deleted from abstract) | 1 hour | **21 Aug 2026** | PI |
| **V. Bold all revisions in body of proposal** | 2 hours | **22 Aug 2026** | PI |
| **W. Cross-reference all page numbers in cover letter table** | 1 hour | **23 Aug 2026** | PI |
| **X. Print 3 hard copies + Application Form + cover letter** | 1 day | **25 Aug 2026** | PI |
| **Y. Internal review by Prof. Waiganjo** | 2 days | **26–27 Aug 2026** | Supervisor |
| **Z. Final corrections and delivery to KNH-UoN ERC office** | 1 day | **30 Aug 2026** | PI |

**Buffer days:** 31 August – 2 September 2026 (3 days slack before deadline)

---

## 3. Sample SMART Objective Format

The ERC wants objectives that are **Single-sentence + SMART**. Here is a template and example for each of your 3 objectives (Note: Objectives 4 and 5 have been removed from scope):

### Template: SMART Objective
> To **[VERB]** [specific WHAT] [specific HOW] for [specific POPULATION] in [specific CONTEXT], achieving [MEASURABLE OUTCOME] within [TIMEFRAME].

### Proposed Revised Objectives

> **Objective 1:** To develop a hybrid 3D-CNN + Template-Based Modeling framework for intracranial aneurysm detection in CTA volumes by September 2026, achieving ≥85% AUC on the RSNA-ICA test set.

> **Objective 2:** To measure the framework's diagnostic accuracy (sensitivity, specificity, AUC, F1) against the 3D U-Net baseline on the RSNA-ICA test set by December 2026.

> **Objective 3:** To conduct a fairness audit of the developed framework across patient age groups, biological sex, and scanner manufacturer on 200–300 de-identified AKUH CTA scans by June 2027, reporting any subgroup with absolute AUC difference >5% compared to the overall.

---

## 4. Sample Restructured Research Questions

### Revised Question 1 (Technical)
> To what extent does integrating RNA-motif-derived Template-Based Modeling features improve the AUC of intracranial aneurysm detection in CTA volumes, compared to a baseline 3D U-Net, when evaluated on the RSNA-ICA test set (n ≈ 4,000)?

### Revised Question 2 (Fairness)
> What is the magnitude of the AUC difference when the hybrid framework is applied across patient age groups (e.g., 18–40, 41–60, 61+ years), biological sex (male/female), and scanner manufacturer (GE, Siemens, Philips, Toshiba) on 200–300 de-identified AKUH CTA scans?

*(Note: Research Question 3 on clinical utility and stakeholder interviews has been removed from scope.)*

---

## 5. Sample Restructured Chapter 2 (Literature Review)

### New Chapter 2 Outline

> **CHAPTER 2: LITERATURE REVIEW**
>
> **2.1 Public Burden of Intracranial Aneurysms** *(move existing Section 1.1 "Background" content here, expand with sub-Saharan Africa / Kenya-specific burden data)*
> 2.1.1 Global prevalence and mortality
> 2.1.2 Sub-Saharan Africa and Kenyan context
> 2.1.3 Health system implications (radiologist shortage, diagnostic delays)
>
> **2.2 Historical Diagnosis and Treatment of Intracranial Aneurysms** *(new content — describe CTA, MRA, DSA, surgical clipping, endovascular coiling, screening guidelines, and **the gaps** — why current approaches fall short in resource-limited settings)*
> 2.2.1 Imaging modalities and clinical pathway
> 2.2.2 Treatment options and outcomes
> 2.2.3 Gaps in current practice for LMICs
>
> **2.3 Innovative Approaches: AI for Aneurysm Detection** *(consolidate existing empirical review here)*
> 2.3.1 Deep learning approaches (CNNs, U-Net, transformer-based)
> 2.3.2 Template-based and hybrid methods
> 2.3.3 RSNA 2025 challenge and state-of-the-art benchmarks
> 2.3.4 Algorithmic fairness in medical imaging
> 2.3.5 Cross-domain methodology transfer (computational biology → imaging)
>
> **2.4 Why This Study? Contribution to Knowledge** *(move existing Section 2.4 "Contribution to Knowledge" here, integrated with the gap analysis from 2.2.3)*
> 2.4.1 Identified gaps not addressed by prior work
> 2.4.2 Specific contributions of this research
> 2.4.3 National AI policy and regulatory context (Kenya AI Bill 2026, KDPA 2019)

---

## 6. Draft Paragraphs for Ethical Gaps (3.7.1–3.7.5)

### 3.7.1 Risk of Study — AKUH Data Identifiability (NEW)

> **3.7.1 Risk of Study and Indirect Patient-Safety Implications**
>
> This study acknowledges that the **Aga Khan University Hospital (AKUH), Nairobi** local validation dataset is **identifiable at source** prior to the application of the de-identification protocol described in Section 3.7.3. Specifically, CTA studies in the AKUH Picture Archiving and Communication System (PACS) contain the 18 HIPAA Safe Harbor identifiers (including patient name, date of birth, medical record number, and acquisition timestamp) before the institutional data custodian applies the de-identification pipeline.
>
> Furthermore, while this study is strictly **developmental and methodological** — it is not intended to inform any individual patient's clinical management during the study period — the **downstream clinical application** of an intracranial aneurysm detection model (i.e., eventual deployment in a real radiology workflow) carries **indirect patient-safety implications**. Aneurysms are life-threatening vascular abnormalities with rupture mortality of 35–50%; therefore, any false-negative prediction in a future deployment context could delay life-saving intervention, and any false-positive prediction could lead to unnecessary invasive procedures.
>
> To mitigate these risks, the study explicitly commits to the following safeguards (detailed in subsequent sub-sections):
> - The AI model will **NOT** be used to inform any patient care decision during the study period (Section 3.7.4).
> - An **Incidental Findings Escalation Protocol** is in place (Section 3.7.4) to manage the rare scenario where a researcher observes a potentially missed aneurysm in the historical AKUH dataset.
> - All AKUH data is de-identified by the institutional data custodian before researcher access (Section 3.7.3).
> - The research team has **no access** to the linking key that maps research IDs back to patient identities (Section 3.7.3).

---

### 3.7.2 Jurisdictional Gap — AKUH ERC + MTA/DTA (NEW)

> **3.7.2 Institutional Jurisdictions and Data Transfer Agreements**
>
> The Principal Investigator acknowledges the **multi-institutional nature** of this research and the associated jurisdictional requirements. The two data sources for this study are governed by separate institutional review bodies:
>
> 1. **RSNA-ICA dataset** (international, open-access): governed by the RSNA data use agreement. No additional IRB approval required for academic use of de-identified, publicly released data.
>
> 2. **Aga Khan University Hospital, Nairobi** (local validation): governed by the **AKUH Ethics Review Committee (AKUH ERC)**, which is a **separate institutional review body** from the KNH-UoN ERC.
>
> The Principal Investigator commits to the following actions to address the jurisdictional gap:
>
> **(a) AKUH ERC submission:** A parallel ethics application will be submitted to the **AKUH ERC** for the use of the AKUH retrospective CTA dataset. The AKUH ERC submission will be initiated within **one week** of the KNH-UoN ERC approval, and **AKUH ERC approval will be obtained before any data extraction** by the institutional data custodian (Dr. Kevin Ombati, AKUH Department of Radiology).
>
> **(b) Material/Data Transfer Agreement (MTA/DTA):** A formal **MTA/DTA between the University of Nairobi and AKUH** is required to govern the transfer of de-identified CTA images from AKUH servers to the UoN/KENET secure analysis environment. The PI has initiated discussions with the **UoN Intellectual Property and Technology Transfer Office** and the **AKUH Research Office** to draft this agreement. A signed MTA/DTA will be **appended to this proposal as Annex D** before final KNH-UoN ERC approval, OR will be provided as a conditional commitment with the signed agreement to follow before data extraction.
>
> The PI confirms that **no data extraction from AKUH will commence** until both (i) AKUH ERC approval and (ii) signed MTA/DTA are in place.

---

### 3.7.3 Informed Consent — Waiver Justification (NEW)

> **3.7.3 Informed Consent Framework and Waiver Justification**
>
> This study involves **one category of human subjects research** (retrospective imaging data only — no interviews):
>
> **Retrospective Imaging Data (AKUH local validation dataset):**
>
> The AKUH local validation dataset consists of **200–300 historical, fully de-identified CTA scans** of adult patients who underwent clinically indicated CTA imaging at AKUH between January 2020 and December 2025. **A formal waiver of individual informed consent is requested from the AKUH ERC** for the use of these data, on the following grounds:
>
> 1. **Impracticality of re-consent:** Contacting 200–300 historical patients (some of whom may be deceased, relocated, or lost to follow-up) is impractical within the available research timeframe and resources.
> 2. **Minimal risk:** The research involves no direct patient interaction, no alteration of patient care, and no return of individual clinical findings. The data is fully de-identified (see Section 3.7.3 below).
> 3. **No adverse impact on rights/welfare:** The waiver does not adversely affect the rights, privacy, or welfare of any patient. The research cannot be practically conducted without the waiver.
> 4. **Robust de-identification:** All 18 HIPAA Safe Harbor identifiers will be stripped at source by the institutional data custodian (Dr. Kevin Ombati) before any data leaves AKUH servers. The research team receives only sequential research IDs (e.g., AKU001) and has **no access** to the linking key that connects research IDs to original patient identities.
> 5. **Public benefit:** The research generates evidence to inform the safe, fair, and effective deployment of AI-enabled aneurysm screening in Kenyan public health settings — a public benefit that justifies the waiver.
>
> **Note — Stakeholder Interviews Removed from Scope:**
>
> The qualitative/stakeholder-interview arm has been **entirely removed** from the study protocol. No interviews are conducted. The health systems feasibility assessment is addressed as a technical workflow analysis using published institutional data and the named site lead's institutional knowledge.

> **De-identification protocol for AKUH data:**
>
> | Identifier | Removal Method | Custodian |
> |------------|---------------|-----------|
> | Patient name | DICOM tag (0010,0010) blanked | AKUH data custodian (Dr. Ombati) |
> | Date of birth | Replaced with year of birth only | AKUH data custodian |
> | Medical record number | Replaced with sequential research ID (AKU001, AKU002...) | AKUH data custodian |
> | Acquisition date/time | Shifted by random offset (1–365 days) per study | AKUH data custodian |
> | Institution name | Replaced with "AKUH" generic | AKUH data custodian |
> | Referring physician | Replaced with "REDACTED" | AKUH data custodian |
> | All other 12 HIPAA Safe Harbor identifiers | Removed or generalized per HIPAA guidelines | AKUH data custodian |
>
> **The linking key** (mapping research IDs to original patient identifiers) is held **exclusively by the AKUH data custodian** and is **not transferred** to the research team, KENET, or any third party.

---

### 3.7.4 Risk-Benefit & Non-Deployment Safeguard + Incidental Findings Protocol (NEW)

> **3.7.4 Non-Deployment Declaration and Incidental Findings Escalation Protocol**
>
> **Declaration of Non-Deployment During Study Period:**
>
> The Principal Investigator explicitly declares that:
> 1. The AI model developed in this study is **strictly for research and academic purposes**.
> 2. **No AI output, prediction, or recommendation from this study will be used to inform any actual patient care decision** during the study period (March 2026 – June 2027).
> 3. The model will **NOT** be deployed in any clinical workflow at AKUH, KNH, or any other facility during the study period.
> 4. Any future deployment of the model would require:
> - Separate regulatory approval from the Kenya Pharmacy and Poisons Board (PPB) for medical devices, OR the Ministry of Health,
> - Prospective clinical validation,
> - Updated ethics approval,
> - Full compliance with the Kenya Data Protection Act 2019 and the AI Bill 2026 (when enacted).
>
> **Incidental Findings Escalation Protocol:**
>
> Although the AKUH data is fully de-identified before researcher access, there is a theoretical possibility that a researcher (or the AI model itself) may identify a **potentially undetected aneurysm** in a historical CTA scan that was not annotated in the original radiology report. Given the life-threatening nature of undetected aneurysms, the following escalation protocol is established:
>
> | Step | Trigger | Action | Responsible Party | Timeline |
> |------|---------|--------|-------------------|----------|
> | 1 | Researcher observes potential missed aneurysm on visual inspection of CTA slice | Document finding in secure research log (study ID, slice number, observation) | Principal Investigator | Within 24 hours of observation |
> | 2 | Researcher notifies data custodian | Email notification to Dr. Kevin Ombati with documented finding (NO patient identifiers, only study ID) | Principal Investigator | Within 48 hours of observation |
> | 3 | Data custodian uses linking key to identify patient | Dr. Ombati retrieves original patient ID using internal linking key | AKUH Data Custodian (Dr. Ombati) | Within 72 hours of notification |
> | 4 | Clinical team review | Dr. Ombati escalates to the relevant clinical department (radiology, neurosurgery) for retrospective review | AKUH Clinical Team | Within 1 week of notification |
> | 5 | Patient follow-up (if appropriate) | AKUH clinical team determines if patient contact is warranted based on current health status and findings | AKUH Clinical Team | Per AKUH clinical protocol |
> | 6 | Documentation to ERC | All incidental findings logged and reported to KNH-UoN ERC in annual progress reports | Principal Investigator | Annually |
>
> **Limitations of this protocol:**
> - The protocol **cannot** be triggered for findings identified by the AI model during automated inference, only by researcher visual inspection.
> - The protocol **does not guarantee** that the patient will be contacted; the clinical decision is at the discretion of the treating clinical team based on the current clinical context.
> - The protocol **does not create** a duty of care between the researcher and the patient.
>
> The Principal Investigator commits to **annual reporting** of all incidental findings to the KNH-UoN ERC and AKUH ERC.

---

## 7. 9-Month Study Timeline (Visual Work Plan)

*(Note: The revised study runs from February 2026 to October 2026 — 9 months)*

```
PHASE 1: Feb 2026 — Literature Review & Proposal Finalization
├── Week 1–2: Finalize literature review restructuring (4-part flow)
├── Week 3–4: Complete ERC resubmission package
└── Milestone: ERC approval expected by March 2026

PHASE 2: Mar 2026 — Dataset Preparation & Ethics Compliance
├── Week 1–2: AKUH ERC parallel submission; initiate MTA/DTA
├── Week 3–4: Dataset extraction and de-identification (AKUH custodian)
└── Milestone: AKUH ERC approval; MTA/DTA signed

PHASE 3: Apr–May 2026 — Model Development & Training
├── Month 1: Install frameworks on KENET CHUI HPC
├── Month 2: RSNA-ICA dataset preprocessing and training
└── Milestone: Hybrid model trained on RSNA-ICA; initial evaluation

PHASE 4: Jun–Jul 2026 — Local Validation & Fairness Evaluation
├── Month 1: AKUH local validation (n=200–300 CTA scans)
├── Month 2: Fairness evaluation across demographics
└── Milestone: Performance and fairness metrics reported

PHASE 5: Aug–Oct 2026 — Analysis, Thesis & Dissemination
├── Month 1: Statistical analysis; thesis drafting
├── Month 2: Supervisor review; thesis submission
└── Milestone: MSc thesis submission; potential journal submission
```

---

## 8. Submission Checklist

Before walking into the KNH-UoN ERC office, ensure you have:

- [ ] **3 hard copies** of the revised research proposal (printed single-sided, signed by PI on the declaration page)
- [ ] **3 hard copies** of the revised Application Form (signed by PI, supervisors, and new radiology supervisor)
- [ ] **3 hard copies** of the cover letter (signed)
- [ ] **3 hard copies** of the similarity report (re-run, <10%)
- [ ] **3 hard copies** of the updated Study Demographics form
- [ ] **3 hard copies** of the updated Department Recommendation Letter (if new supervisor added)
- [ ] **Annex A:** CV of Dr. Kevin Ombati (Local Data Co-Investigator)
- [ ] **Annex B:** Updated budget (revised to reflect removal of interview component)
- [ ] **Annex C:** Draft AKUH-UoN MTA/DTA (or formal commitment letter from AKUH Research Office)
- [ ] **Annex D:** AKUH ERC submission plan / timeline
- [ ] **Annex E:** Updated Turnitin similarity report
- [ ] **Email copy** of all documents to `uonknh_erc@uonbi.ac.ke` for backup
- [ ] **Acknowledgment receipt** from ERC office

---

## 9. Strategic Considerations

### 9.1 What to do if Prof. Waiganjo is unavailable

If your primary supervisor is unreachable for the 4-week window (travel, sabbatical, etc.):
- **Escalate to Dr. Pamela Mandela** (co-supervisor) to lead the revision.
- **Notify the Chair, Department of Mathematics** (Dr. James Okwoyo) of the timeline constraint.
- **Request a 1-week extension** from the ERC if needed (rare, but possible with documented supervisor unavailability).

### 9.2 What to do if AKUH ERC submission is delayed

The KNH-UoN ERC will likely approve the proposal **conditionally** pending AKUH ERC approval. Include in your cover letter:
> *"AKUH ERC submission has been initiated on [DATE]; conditional KNH-UoN ERC approval is requested with AKUH ERC approval to follow within 30 days of KNH-UoN ERC approval."*

### 9.3 What to do if the new radiology supervisor declines

If you cannot find a UoN Department of Radiology supervisor:
- **Option A:** Add Dr. Kevin Ombati (AKUH) as a formal **co-investigator** in the proposal's Section 1.5 (Acknowledgments) with defined roles — he may not be a UoN faculty member but his AKUH Radiology affiliation addresses the ERC's concern.
- **Option B:** Request a **Department of Radiology, UoN** faculty member to serve on the **advisory committee** (not formal co-supervisor but in a documented advisory capacity).

### 9.4 What to do if the 4-week deadline is missed

If you cannot complete the revisions within 4 weeks:
- **Submit a written request for a 2-week extension** to the ERC Secretary (Prof. Amugune) at least 3 days before the deadline.
- Justify with documented reasons (e.g., supervisor unavailability, AKUH MTA negotiation delays).
- Extensions are **not guaranteed** but are commonly granted for well-justified reasons.

### 9.5 What to do if the proposal is rejected on resubmission

If the ERC rejects the revised proposal:
- Request a **face-to-face meeting** with the ERC Secretary for clarification.
- Consider engaging a **research methodology consultant** (e.g., from UoN School of Public Health) to assist with major restructuring.
- Document all feedback and revise again — most MSc proposals are eventually approved within 2-3 revision cycles.

---

## 10. Recommended Next Steps (Today)

### Immediate Actions (within 24 hours)

1. **Send the email below to Prof. Peter Waiganjo:**

```
Subject: URGENT — ERC Feedback on P550/06/2026 — Need Emergency Meeting

Dear Prof. Waiganjo,

The KNH-UoN ERC has issued their review of my research proposal (P550/06/2026).
The committee has requested revisions and resubmission within 4 weeks
(deadline: 2 September 2026).

The feedback includes:
- Major administrative revisions (Abstract, Objectives, Research Questions,
 Literature Review restructuring, Methodology clarifications)
- A new requirement to add a Department of Radiology co-supervisor
- Five substantive ethical sub-sections to add (AKUH identifiability risk,
 AKUH ERC + MTA, Consent waiver, Incidental findings protocol,
 Stakeholder consent)
- Submission of a cover letter with a summary table of how each comment
 was addressed

I have drafted a 4-week work plan and request an emergency meeting with
you and Dr. Pamela Mandela (and Dr. Kevin Ombati if possible) within
the next 3 days to discuss the revision strategy and the new supervisor
requirement.

Please let me know your availability for a 90-minute meeting on Friday
8 August or Monday 11 August 2026.

Attached: ERC letter + my proposed revision roadmap.

Best regards,
Cavin
```

2. **Call Dr. Kevin Ombati at AKUH** (use the phone number in your application) to:
 - Inform him of the ERC feedback.
 - Ask if he is willing to be added as a formal co-supervisor OR if he can recommend a UoN Department of Radiology faculty member.
 - Inquire about the AKUH ERC submission process and timeline.
 - Request a draft of the AKUH-UoN MTA/DTA template.

3. **Email the KNH-UoN ERC office** (`uonknh_erc@uonbi.ac.ke`) to:
 - Acknowledge receipt of the feedback.
 - Confirm the 2 September 2026 deadline.
 - Ask 1-2 clarifying questions if needed (e.g., "Does the AKUH ERC approval need to be in place before KNH-UoN ERC resubmission, or can it be parallel?").

4. **Block your calendar** for the next 4 weeks. Plan to work on revisions **6-8 hours per day, 6 days per week** to meet the deadline. Treat this as your primary MSc deliverable until 2 September.

---

## 11. Key Risks to Mitigate

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| Prof. Waiganjo unavailable for review | Low | High | Escalate to Dr. Mandela; request extension if needed |
| New radiology supervisor declines | Medium | Medium | Add Dr. Ombati as co-investigator in Section 1.5 |
| AKUH ERC submission takes >30 days | Medium | Medium | Request conditional KNH-UoN approval; submit to AKUH in parallel |
| MTA/DTA negotiation delays | Medium | High | Use a conditional commitment letter; finalize MTA after KNH-UoN approval |
| Similarity report exceeds 15% after revisions | Low | High | Re-run Turnitin AFTER all revisions complete; add citations proactively |
| Miss the 2 Sep deadline | Low (if disciplined) | Critical | Use the Gantt chart; 3 buffer days built in |
| ERC rejects revised proposal | Low | Critical | Request in-person meeting; revise again; do not give up |

---

## 12. Final Encouragement

You have received **detailed, constructive feedback** from the KNH-UoN ERC — not a rejection. The committee has not raised any fundamental ethical objections; instead, they have identified specific gaps that are **all addressable within the 4-week window** with focused work. The 4-week timeline is tight but achievable.

**Key strengths of your current proposal to preserve in the revision:**
- Strong clinical justification (epidemiological context, radiologist shortage data)
- Novel methodological contribution (TBM cross-domain transfer)
- Robust fairness framework
- Realistic risk assessment
- Strong local data collaboration (AKUH + KNH)
- Sound regulatory awareness (KDPA 2019, AI Bill 2026)

**The path forward is clear:** restructure, clarify, and add the five ethical sub-sections. With disciplined execution of the Gantt chart, you will submit a significantly stronger proposal that is highly likely to receive full approval.

**You've got this. Start today.**

---

## Appendix: Quick Reference — Where Each ERC Comment is Addressed

| ERC Comment # | Section in Revised Proposal | Status |
|---------------|----------------------------|--------|
| 1 (Supervisor) | Section 1.5 + App Form | Added: Dr. Kevin Ombati as Co-Investigator |
| 2 (Abstract) | Abstract, pp. ii–iii | Fully rewritten with 4 subtitles |
| 3 (Objectives) | Section 1.3, pp. 7–8 | 3 SMART objectives (Obj 4 & 5 removed) |
| 4 (Research Questions) | Section 1.4, pp. 8–9 | 2 precise RQs (RQ3 removed) |
| 5 (Chapter 2 flow) | Chapter 2, pp. 10-23 | Restructured (4-part flow) |
| 6 (Mixed-methods) | Section 3.1, p. 24 | Changed to purely experimental quantitative |
| 7 (Site naming) | Section 3.2, pp. 24–25 | Named: AKUH, KENET CHUI, UoN |
| 8 (Population + consent) | Section 3.2, pp. 25–26 | Defined per arm; no interviews |
| 9 (Inclusion/Exclusion) | Section 3.3, pp. 26–27 | NEW |
| 10 (Sample size) | Section 3.3, p. 27 | Precision-based calculation added |
| 11 (Data retrospective) | Section 3.4, pp. 27–28 | 100% retrospective; no interviews |
| 12.i (AKUH identifiability) | Section 3.7.1, pp. 36–37 | NEW |
| 12.ii (AKUH ERC + MTA) | Section 3.7.2, pp. 37–38 | NEW |
| 12.iii (Waiver) | Section 3.7.3, pp. 38–40 | NEW |
| 12.iv (Non-deployment + Incidental) | Section 3.7.4, pp. 40–42 | NEW |
| — (Stakeholder consent) | — | **Removed**: interviews deleted from protocol |

---

**End of Way Forward Action Plan**
**Total estimated effort: ~80-100 hours over 4 weeks**
**Deadline: 2 September 2026**

*This document is intended as a practical working guide. Adjust based on supervisor feedback, AKUH ERC requirements, and emerging constraints during the revision period.*
