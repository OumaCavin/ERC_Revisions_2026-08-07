# KNH-UoN ERC Application Form — Cavin Otieno Ouma

**Source File:** `user_input_files/KNH-UoN ERC APPLICATION FORM_Supervisors_3_copies.pdf`
**Document Type:** KNH-UoN Ethics Research Committee Application Form
**Submitted:** April 19, 2026
**Principal Investigator:** Cavin Otieno Ouma (BSc. Computer Science; MSc Candidate, Public Health Data Science)
**Application Status:** Reviewed — Revisions Requested (5 August 2026)

---

## I. Principal Investigator

| Field | Detail |
|-------|--------|
| Last Name | OUMA |
| First Name | Cavin Otieno |
| Academic Degrees | BSc. Computer Science |
| Position | MSc Candidate, Public Health Data Science; Junior Researcher, Department of Mathematics, University of Nairobi |
| Home Institution | Department of Mathematics, University of Nairobi |
| Mailing Address | P.O. Box 42681-00100, Nairobi, Kenya |
| Telephone | +254 715 169 531 |
| Email | otienocavin@gmail.com |

> All correspondence shall be addressed to the Principal Investigator.

---

## II. Project Title

> **"Hybrid Deep Learning Framework for Intracranial Aneurysms Detection: Algorithmic Development and Fairness Evaluation for Kenyan Public Health Settings"**

---

## III. Research Personnel

### Personnel Block 1 — Research Administrator / Institutional Lead

| Field | Detail |
|-------|--------|
| Last Name | Okwoyo |
| First Name | Dr. James |
| Academic Degrees | PhD (Applied Mathematics) |
| Position | Senior Lecturer & Chair, Department of Mathematics, University of Nairobi |
| Email | jmkwoyo@uonbi.ac.ke |
| Telephone | +254 116 394 903 |
| Date Signed | April 19, 2026 |

### Personnel Block 2 — Primary Supervisor / Co-Investigator

| Field | Detail |
|-------|--------|
| Last Name | Waiganjo |
| First Name | Prof. Peter |
| Academic Degrees | PhD |
| Position | Professor, Department of Computing and Informatics, University of Nairobi |
| Email | waiganjo@uonbi.ac.ke |
| Telephone | +254 723 488 114 |
| Date Signed | April 19, 2026 |

### Additional Supervisor (per Cover Letter & Study Demographics)

| Field | Detail |
|-------|--------|
| Name | Dr. Pamela Mandela (Idenya) |
| Affiliation | University of Nairobi |
| Email | pamela.idenya@uonbi.ac.ke |
| Telephone | +254 724 277070 |

### Local Data Co-Investigator (AKUH)

| Field | Detail |
|-------|--------|
| Name | Dr. Kevin Ombati |
| Affiliation | Aga Khan University Hospital, Nairobi — Department of Radiology |
| Role | Local data extraction, curation, and secure de-identification |

---

## IV. Funding Information

- **Source:** Self-funded by PI + Institutional in-kind support
- **Total Estimated Budget:** KES 116,000
- **No external commercial grants or active contracts currently pending.**

### Current Resources

1. **Personal Funds** — Direct administrative costs, data management software, local storage.
2. **KENET In-kind Support** — Verified access to **KENET CHUI HPC Cluster** (NVIDIA L40S GPUs).
3. **UoN In-kind Support** — Supplementary local computing nodes and departmental admin resources.
4. **AKUH In-kind Support** — Supervised radiology archive data extraction, curation, and secure de-identification (managed by Dr. Kevin Ombati).

---

## V. Description of Research Project

### 1) Background and Purpose of Research

#### a) Justification & Significance
> Bulging or weakened blood vessels in the brain (intracranial aneurysms) affect roughly **3% of people globally**. Rupture causes severe, life-threatening brain bleeding with **mortality rate 35-50%**. Sub-Saharan Africa faces critical diagnostic backlogs due to a severe shortage of radiologists (~**1 per 100,000 in Kenya**). Automated AI screening tools offer scalable assistance, but existing software is almost exclusively trained on Western populations. This study validates/refines an AI tool optimized for **Kenyan clinical environments**.

#### b) Literature Review
- The 2025 RSNA Aneurysm Detection challenge established definitive AI benchmarks using thousands of global brain scans.
- **Stanford's 2025 structural models** in computational biology showed that teaching computers to understand fixed mathematical shapes significantly improves predictive accuracy.
- This project translates those concepts to medical imaging by building a **"Morphological Template Library"** (a dictionary of physical aneurysm shapes — vessel angles, neck sizes) and fuses it with deep learning pattern recognition.
- **No prior published work has combined these shape-matching techniques with explicit local testing on African populations to audit algorithmic fairness.**

#### c) Research Questions & Objectives

**Primary Research Question:**
> Can a hybrid AI model combining anatomical shape dictionaries with pattern-recognition software achieve elite diagnostic accuracy while maintaining equal performance across patient age, biological sex, and hospital equipment types?

**Specific Objectives:**
- Develop an AI model that combines an anatomical shape dictionary (derived from international open-access scans) with deep-learning image processing.
- Measure baseline accuracy against international benchmarks.
- Conduct a rigorous fairness analysis across demographic subgroups on native Kenyan data from AKUH.

---

### 2) Research Ethics

Four strict protocols govern ethics:

1. **Data Privacy & Anonymization** — All 18 standard personal identifiers stripped at source; files assigned generic random tracking numbers (e.g., AKU001).
2. **Consent Waiver** — Formal waiver requested (retrospective review, impractical to contact patients).
3. **Algorithmic Justice & Cross-Population Bias** — Mandatory local validation on Kenyan data; software accuracy statistically dissected across age, sex, scanner brands.
4. **Data Sovereignty** — All local validation data remains physically inside Kenya on KENET secure servers (Kenya Data Protection Act 2019 compliance).

---

### 3) Research Methodology and Procedures

#### a) Study Design
> Retrospective diagnostic accuracy study using historical, de-identified CTA scans. **No active clinical trials, patient interventions, or changes to patient care.**

#### b) Research Procedures (Five Steps)
1. **Data Download** — ~2,500 studies from RSNA-ICA open dataset.
2. **Local Data Extraction & De-identification** — AKUH historical brain scans (Jan 2020 – Dec 2025), supervised by Dr. Kevin Ombati.
3. **AI Model Training** — Mathematical shape-matching combined with deep pattern recognition.
4. **Local Performance Validation** — Testing on anonymized Kenyan AKUH scans.
5. **Fairness Assessment** — Statistical breakdown by age, sex, equipment manufacturer.

#### c) Source, Amount or Dose of Products/Materials
- **Products/Materials:** Not applicable (no drugs, contrast agents, radioactive materials, biological products, or medical devices).
- **Data Materials:**
 - Source 1: Open-access RSNA-ICA dataset (~2,500 de-identified CTA scans)
 - Source 2: Retrospective AKUH radiology archive (**200–300 de-identified CTA scans**)

#### d) Biological Specimen Shipment
- **Not applicable.** No human biological specimens collected/stored/processed. No cross-border transfer of physical samples or local patient data.

---

### 4) Human Participants in the Project

- **Number and Type:** No living human participants; study subjects are secondary, de-identified historical CTA imaging studies (~2,500 RSNA + 200–300 AKUH).
- **Inclusion Criteria (AKUH):** Brain CTA studies between Jan 2020 – Dec 2025; complete demographic data; scanner manufacturer info available.
- **Exclusion Criteria:** Severe artifacts/poor image quality; prior surgical interventions/clipping; pediatric (<18 years).
- **Recruitment:** Not applicable — retrospective audit only.

---

### 5) Study Location

| Site | Role |
|------|------|
| **Aga Khan University Hospital, Nairobi (AKUH)** — Department of Radiology, 3rd Parklands Avenue, Limuru Road | Primary Local Validation Site (data extraction & anonymization supervised by Dr. Kevin Ombati) |
| **Department of Mathematics, University of Nairobi** | Data analysis |
| **Department of Computing and Informatics, University of Nairobi** | Data analysis |
| **KENET CHUI HPC Cluster, Kenya Education Network** | Primary Computational Resource (NVIDIA L40S GPUs) |
| **University of Nairobi GPU Facility, DCI** | Supplementary Computational Resource |

---

### 6) Risks, Benefits & Adverse Events

#### a) Nature and Degree of Risk

**Zero physical/physiological/medical risk** (retrospective, de-identified data only). Minimal non-physical risks:

1. **Privacy/Confidentiality Risk** — Theoretical re-identification if anonymized files are insecurely managed.
2. **Algorithmic Disparity Risk** — Performance variations across demographic subgroups.
3. **Reputational Risk** — Trust shifts if local validation highlights systematic drops.

**Minimization of Risk:**
- Source anonymization (HIPAA Safe Harbor 18 identifiers + quasi-identifiers).
- DICOM header scrubbing (dedicated toolkit).
- Strict key separation (linking key held only by AKUH data custodian).
- Data sovereignty & access control (encrypted KENET servers; role-based auth; secure logging).
- Vulnerability exclusion (pediatric cases removed).

#### b) Unknown Conditions
- Cannot return unexpected findings to individuals.
- Aggregate reporting only for population-level findings.

#### c) Benefits

- **Direct to participants:** None.
- **To Kenyan Health System:**
 1. First baseline for state-of-the-art neuro-imaging AI on native Kenyan/African populations.
 2. Evidence-based guidelines for equitable AI deployment in regional public health networks.
 3. Local capacity building through reusable Morphological Template Library.
 4. Blueprint for reducing radiologist workload and time-to-treatment.

#### d) Adverse Events Treatment
- Not applicable for physical AE (no human subjects exposed to procedures).
- Digital breaches/deviations/IT security alerts reported to KNH-UoN ERC within **7 days**.

#### e) Adverse Events Facilities
- UoN Dept. of Mathematics + KENET CHUI HPC infrastructure provide encrypted backups, firewalls, and audit logs.

#### f) Financial Responsibilities
- PI assumes complete financial responsibility (~**KES 105,000 personal funds** + in-kind support).

---

### 7) Confidentiality of Research Data

- **Direct Identifiers:** Completely stripped at source by data custodian; randomized codes only (e.g., AKU001).
- **Data Storage:** Encrypted partitions on KENET CHUI HPC Cluster.
- **Data Access:** Restricted to authorized investigators; audit logs.
- **Data Retention:** 5 years post-study, then permanent cryptographic deletion.
- **Data Sharing:** Raw imaging datasets NOT shared externally. Aggregated metrics, statistical tables, and final trained model weights shared via public GitHub repo (open-source license) per Kenya Data Protection Act 2019.

---

### 8) Ethical Considerations Summary

1. Privacy & Confidentiality — HIPAA Safe Harbor anonymization, encrypted storage, role-based access.
2. Informed Consent — Waiver requested (retrospective, fully anonymized, minimal risk).
3. Algorithmic Fairness — Mandatory performance evaluation across age, sex, scanner manufacturer, clinical population.
4. Cross-Population Bias — Direct evaluation using native African AKUH data.
5. Data Sovereignty — All local data in Kenya on KENET infrastructure.
6. Vulnerability — Pediatric scans explicitly excluded; no vulnerable populations targeted.
7. Conflict of Interest — None declared (PI is MSc candidate with no commercial stake).

---

### 9) Additional Information

- **Radiation Exposure:** Not applicable.
- **Access to Private Records:** Limited to anonymized CTA scans (Dr. Kevin Ombati supervision).
- **Audio-Visual Recordings:** None.
- **Use of AI Tools:** Research purposes only; not intended for active clinical decision support without separate regulatory approval.
- **International Data Sources:** RSNA-ICA is open-access via RSNA Imaging Portal and AWS Registry of Open Data. No cross-border health record transfer.

---

### 10) Consent / Assent Forms and Waiver

- **[X] Waiver of informed consent is requested.**

**Justification:** Secondary, retrospective analysis of fully anonymized historical medical imaging. Tracking ~200–300 historical patients is impractical. Research involves zero direct patient interaction, fully scrubbed headers, and no return of individual clinical findings. Waiver does not adversely affect rights, privacy, or welfare of any patient. Supplementary open-access training data is public and licensed for academic research.

- [ ] Written informed consent — Not applicable.
- [ ] Oral informed consent — Not applicable.

---

## PI Declaration (signed April 19, 2026)

> *As the Principal Investigator in this research, I declare that:*
> 1. *Any change to this protocol and/or procedure shall be notified to and effected only after approval by the KNH-UoN ERC.*
> 2. *I shall notify the KNH-UoN ERC of intended publication, or any other form of dissemination of results of this study, and provide the draft contents.*
> 3. *Other members of the research team are bound by 1) and 2) above.*

---

## Required Attachments Checklist

- [ ] Letters of Study Approval from PI's Home Institution (Department)
- [ ] CV of each research team member
- [ ] Research Personnel Information (detailed roles and responsibilities)

---

## Note on ERC Review Outcome

This application was reviewed by the KNH-UoN Ethics and Research Committee on **5 August 2026** (Letter Ref: KNH-ERC/RR/561mm). The committee issued **revisions required before approval** — see `01_KNH_UoN_ERC_Letter_P550_06_2026.md` for the full list of required corrections.
