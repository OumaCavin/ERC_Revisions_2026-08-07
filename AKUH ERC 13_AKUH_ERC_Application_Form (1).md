# AGA KHAN UNIVERSITY HOSPITAL
## ETHICS REVIEW COMMITTEE (ERC) APPLICATION FORM

## RESEARCH PROTOCOL APPLICATION FOR ETHICS APPROVAL

---

## TABLE OF CONTENTS

| Section | Title | Page |
|---------|-------|------|
| A | Application Details | 1 |
| B | Principal Investigator Information | 1 |
| C | Supervisor Information | 1 |
| D | Research Title | 2 |
| E | Research Site Information | 2 |
| F | Research Details (Background, Objectives, Design, Data Sources, Population, Collection) | 2 |
| G | Risk Assessment and Management | 4 |
| H | Benefits | 5 |
| I | Confidentiality and Data Protection | 5 |
| J | Ethical Considerations | 6 |
| K | Research Team Qualifications | 7 |
| L | Budget | 7 |
| M | Institutional Approvals | 8 |
| N | Declarations | 8 |
| O | List of Abbreviations and Acronyms | 9 |
| P | Operational Definitions | 9 |
| Q | Structured Abstract | 10 |
| R | Study Results Dissemination Plan | 10 |
| S | Timeline / Time Frame | 10 |
| T | Study Limitations and Mitigation Strategies | 11 |

---

## LIST OF ABBREVIATIONS AND ACRONYMS

| Abbreviation | Full Term |
|--------------|-----------|
| AI | Artificial Intelligence |
| AUC | Area Under the Receiver Operating Characteristic Curve |
| AKU | Aga Khan University |
| AKUH | Aga Khan University Hospital |
| CTA | Computed Tomography Angiography |
| GHTC | Global Health Training Centre |
| TRREE | Training and Resources in Research Ethics Evaluation |
| DCI | Department of Computing and Informatics |
| DL | Deep Learning |
| DICOM | Digital Imaging and Communications in Medicine |
| DoM | Department of Mathematics |
| ERC | Ethics Review Committee |
| GPU | Graphics Processing Unit |
| ICA | Intracranial Aneurysm |
| KNH | Kenyatta National Hospital |
| MRA | Magnetic Resonance Angiography |
| MRI | Magnetic Resonance Imaging |
| MTA | Material Transfer Agreement |
| NACOSTI | National Commission for Science, Technology and Innovation |
| PACS | Picture Archiving and Communication System |
| PI | Principal Investigator |
| RSNA | Radiological Society of North America |
| RSNA-ICA | RSNA Intracranial Aneurysm Detection |
| TBM | Template-Based Modeling |
| TM-score | Template Modeling Score |
| UoN | University of Nairobi |
| 3D | Three-Dimensional |

---

## OPERATIONAL DEFINITIONS

**Algorithmic Fairness:** The principle that an AI system should perform equitably across different demographic subgroups (e.g., age, sex, ethnicity) and clinical populations without systematic disadvantage to any group.

**Cross-Population Validation:** The evaluation of a model's performance on a population different from the one used for training, to assess generalizability.

**Deep Learning (DL):** A subset of machine learning that uses multi-layered artificial neural networks to progressively extract higher-level features from raw input.

**Hybrid Framework:** An architecture that combines two or more computational approaches (e.g., Template-Based Modeling and Deep Learning) to leverage the strengths of each.

**Intracranial Aneurysm (ICA):** A localized, abnormal, weak spot on a blood vessel in the brain that causes an outward bulging of the arterial wall.

**Material Transfer Agreement (MTA):** A contract that governs the transfer of tangible research materials between two organizations, defining the rights and obligations of the provider and recipient.

**Multi-Task Learning:** A machine learning approach in which a model is trained on multiple related tasks simultaneously, using shared representations to improve generalization.

**Template-Based Modeling (TBM):** A computational method that predicts a target structure by identifying and adapting similar known structures (templates) from a database.

---

## STRUCTURED ABSTRACT (Approximately 250 words)

**Background:** Intracranial aneurysms affect approximately 3.2% of the global population, with limited detection capacity in low-resource settings such as Kenya. Automated AI-based detection tools offer a potential solution, but cross-population generalizability and algorithmic fairness remain unaddressed gaps, particularly for African populations.

**Objective:** To develop, validate, and evaluate a hybrid Template-Based Modeling and Deep Learning framework for intracranial aneurysm detection from CT angiography images, with comprehensive fairness assessment across demographic subgroups and populations, specifically targeting Kenyan clinical settings.

**Methods:** This retrospective diagnostic accuracy study employs a multi-source data architecture: (1) RSNA Intracranial Aneurysm Detection dataset (approximately 2,500 annotated CTA studies, open-access) for primary model training, (2) supplementary morphological dataset for template library construction, and (3) retrospective CTA studies from Aga Khan University Hospital, Nairobi (200-300 cases) for local African population validation. The hybrid framework integrates TBM-derived anatomical priors with convolutional neural networks. Algorithmic fairness is evaluated across age, sex, scanner manufacturer, and population subgroups.

**Expected Outcomes:** The framework is expected to achieve high discriminative performance (AUC >0.90) while maintaining equitable performance across subgroups. The local validation on Kenyan clinical data will provide critical evidence on model generalizability to African populations.

**Public Health Significance:** Findings will inform equitable deployment of AI-enabled aneurysm detection in Kenyan public health facilities, addressing the critical radiologist shortage and supporting responsible AI deployment in healthcare settings.

**Keywords:** Intracranial Aneurysm; Deep Learning; Template-Based Modeling; Algorithmic Fairness; CT Angiography; Kenya; African Healthcare

---

## SECTION A: APPLICATION DETAILS

**Application Type:** New Research Project

**Review Category:** Full Review

**Application Date:** May 2026

**Proposed Study Start Date:** January 2026

**Proposed Study End Date:** October 2026

**Reviewing Committee:** Aga Khan University Hospital Ethics Review Committee

---

## SECTION B: PRINCIPAL INVESTIGATOR INFORMATION

**Full Name:** Cavin Otieno Ouma

**Academic Qualification:** Bachelor's Degree in Computer Science

**Current Enrollment:** MSc Public Health Data Science, University of Nairobi

**Student Registration Number:** SDS6/46982/2024

**Department:** Department of Mathematics, University of Nairobi

**Postal Address:** 42681 -001 GPO Nairobi

**Email Address:** otienocavin@gmail.com

**Phone Number:** +254715169531

---

## SECTION C: SUPERVISOR INFORMATION

**Primary Supervisor:**

- **Name:** Prof. Peter Waiganjo
- **Title:** Senior Lecturer
- **Department:** Department of Computing and Informatics, University of Nairobi
- **Institution:** University of Nairobi
- **Email:** p.waiganjo@uonbi.ac.ke
- **Phone:** [To be verified]

**Secondary Supervisor:**

- **Name:** Dr. Pamela Mandela Idenya
- **Title:** Lecturer
- **Department:** Department of Human Anatomy and Medical Physiology, University of Nairobi
- **Institution:** University of Nairobi
- **Email:** p.idenya@uonbi.ac.ke

**Co-Supervisor (Health Systems):**

- **Name:** Dr. Vincent Okungu
- **Title:** Adjunct Lecturer
- **Department:** Department of Public and Global Health, University of Nairobi
- **Institution:** University of Nairobi
- **Email:** v.okungu@uonbi.ac.ke

**Co-Supervisor (Radiology - Aga Khan University Hospital):**

- **Name:** Dr. Kevin Ombati
- **Title:** Programme Director and Senior Instructor
- **Department:** Department of Radiology, Aga Khan University Hospital, Nairobi
- **Institution:** Aga Khan University Hospital
- **Role:** Facilitate local validation data access and provide clinical expertise

---

## SECTION D: RESEARCH TITLE

**Full Title:**

"Hybrid Template-Based Modeling and Deep Learning Framework for Intracranial Aneurysm Detection: Algorithmic Development and Fairness Evaluation for Kenyan Public Health Settings"

**Short Title:**

AI-Enabled Intracranial Aneurysm Detection for Kenyan Healthcare

**Research Topic Classification:** Health informatics, Medical imaging, Artificial Intelligence, Multi-source data integration

---

## SECTION E: RESEARCH SITE INFORMATION

**Primary Research Site:**

- **Name:** Aga Khan University Hospital (AKUH), Nairobi
- **Address:** 3rd Parklands Avenue, Limuru Road, Nairobi, Kenya
- **Type:** Teaching Hospital and Tertiary Care Facility
- **Contact:** Department of Radiology, under Dr. Kevin Ombati
- **Role:** Local validation data provider for African population assessment

**Secondary Research Sites:**

- University of Nairobi, Department of Mathematics (Data analysis, administrative coordination)
- University of Nairobi, Department of Computing and Informatics (GPU computing, model training)
- University of Nairobi Secure Computing Environment (3D mesh processing, template library construction)

---

## SECTION F: RESEARCH DETAILS

### F.1 Background and Rationale

Intracranial aneurysms represent a significant neurological health concern globally, with prevalence estimated at 3.2% in the general population (Vlak et al., 2011). In Kenya, the detection of unruptured aneurysms before catastrophic hemorrhage occurs remains a critical unmet clinical need due to limited radiological expertise. The country has approximately 0.41 radiologists per 100,000 population, with most specialists concentrated in Nairobi and major urban centers (KMPDC, 2026).

**Table F.1: Distribution of Radiologists in Kenya by Region**

| Region | Number of Radiologists | Population (Approx.) | Radiologists per 100,000 |
|--------|----------------------|---------------------|------------------------|
| Nairobi | 119 | 4,800,000 | 2.48 |
| Mombasa | 21 | 1,350,000 | 1.55 |
| Kisumu | 10 | 1,250,000 | 0.80 |
| Nakuru | 8 | 2,300,000 | 0.34 |
| Eldoret | 17 | 1,250,000 | 1.36 |
| Other Counties | ~50 | 45,000,000 | 0.09 |
| **Total** | **~225** | **56,000,000** | **0.41** |

*Source: Kenya Medical Practitioners and Dentists Council (KMPDC), Specialist Register (Radiology), 2026*

This research proposes to develop and evaluate a hybrid artificial intelligence framework combining Template-Based Modeling from computational biology with deep learning methodologies for automatic detection of intracranial aneurysms from CT angiography images. The study will specifically evaluate algorithmic fairness across demographic subgroups and populations, with local validation on data from Aga Khan University Hospital, Nairobi to assess generalizability to Kenyan clinical populations.

**Research Enhancement - Cross-Population Validation Focus:**

The research is specifically designed to address the critical gap in understanding how aneurysm detection models perform on African patients:

1. **Local Validation on Kenyan Clinical Data:** Aga Khan University Hospital provides a diverse patient population reflecting the demographic diversity of Nairobi and surrounding regions, enabling assessment of model generalizability to the target deployment context.

2. **Fairness Evaluation Framework:** The research conducts comprehensive algorithmic fairness assessment examining model performance across demographic subgroups (age, sex, scanner characteristics), with explicit attention to implications for African healthcare contexts.

3. **Clinical Translation Pathway:** Findings from Aga Khan University Hospital validation will inform recommendations for deployment in other Kenyan healthcare facilities, supporting the national strategy for AI in healthcare.

### F.2 Research Objectives

**Primary Objective:**
To develop and evaluate a hybrid TBM-Deep Learning framework for detecting intracranial aneurysms from CT angiography images, with performance assessment and fairness evaluation across multiple populations, including direct validation on Kenyan clinical data from Aga Khan University Hospital.

**Specific Objectives:**
1. Develop a hybrid detection algorithm integrating Template-Based Modeling components with convolutional neural network architectures
2. Evaluate detection performance against established benchmarks (RSNA 2025 challenge results)
3. Conduct comprehensive algorithmic fairness assessment across demographic subgroups and populations
4. Validate model performance on Aga Khan University Hospital clinical data (African population)
5. Assess deployment feasibility in Kenyan public health facilities

### F.3 Study Design

**Design:** Retrospective diagnostic accuracy study with prospective feasibility assessment

**Methodology:**
- Retrospective analysis of anonymized CT angiography images from Aga Khan University Hospital radiology department
- Development and training of hybrid AI model using RSNA-ICA dataset (open-access)
- Local validation using anonymized data from Aga Khan University Hospital
- Performance evaluation using standard metrics (sensitivity, specificity, AUC)
- Fairness evaluation across demographic subgroups and populations
- Cross-population generalizability assessment (international → Kenyan population)

**Sample Size:**
- RSNA-ICA training: Approximately 2,500 annotated studies (open-access dataset)
- Aga Khan University Hospital local validation: 200-300 CT angiography studies (based on available historical data over retrospective period January 2020 to December 2025)

### F.4 Data Sources

**Primary Data Source - RSNA-ICA:**
- Source: RSNA Imaging Portal (Dataset 7) - https://imaging.rsna.org/dataset/7
- Type: Annotated CT Angiography DICOM images (open-access)
- Volume: Approximately 2,500 annotated studies
- Purpose: Primary detection model training
- Citation: RSNA Intracranial Aneurysm Detection AI Challenge (2025)

**Supplementary Data Source:**
- Source: RSNA-ICA Intracranial Aneurysm Dataset (open-access)
- Type: CTA images with detailed morphological measurements and 3D surface mesh models
- Volume: 143 subjects (99 patients, 44 controls), 105 annotated aneurysms
- Key Features: Bifurcation angles, neck dimensions, aspect ratios, parent vessel diameters
- Purpose: Morphological template library construction

**Local Validation Data Source - Aga Khan University Hospital:**
- Source: Aga Khan University Hospital, Nairobi - Department of Radiology
- Type: CT Angiography DICOM images (retrospective only)
- Volume: 200-300 studies (based on available historical data)
- Purpose: External validation on African patient population
- Collection: Authorized Aga Khan University Hospital radiology staff extract anonymized data from PACS
- Data Custodian: Aga Khan University Hospital Radiology Department (under Dr. Kevin Ombati's supervision)
- Data Sovereignty: All data processing conducted within Kenya per Kenya Data Protection Act 2019 requirements

### F.5 Study Population

**Inclusion Criteria (Aga Khan University Hospital Data):**
- CT angiography studies performed at Aga Khan University Hospital between January 2020 and December 2025
- Studies with complete patient demographic information (age, sex)
- Studies with available scan manufacturer information
- Studies with adequate image quality for analysis

**Exclusion Criteria:**
- Studies with poor image quality rendering them uninterpretable
- Studies with previous surgical interventions for aneurysms
- Pediatric studies (under 18 years)
- Studies with incomplete metadata

### F.6 Data Collection Procedures

1. **RSNA-ICA Data Acquisition** (Completed):
   - Download from RSNA Imaging Portal (https://imaging.rsna.org/dataset/7)
   - Verification using provided checksums
   - Storage on encrypted local storage at University of Nairobi

2. **Supplementary Data Acquisition** (Completed):
   - Download supplementary morphological dataset from designated repository
   - Verify integrity using SHA-256 checksums
   - Store DICOM volumes and STL mesh files on University of Nairobi secure environment

3. **Aga Khan University Hospital Data Collection** (Pending ERC Approval):
   - Formal data sharing agreement with Aga Khan University Hospital Radiology Department
   - Authorized AKUH radiology IT staff extract anonymized data from PACS
   - Anonymization performed by AKUH data custodian before transfer
   - Secure transfer via encrypted file transfer protocol
   - All data transfers and storage confined within Kenya

4. **Data Integration:**
   - Harmonize preprocessing pipeline across all data sources
   - Maintain data separation between training and validation sets
   - Implement rigorous quality control procedures

---

## SECTION G: RISK ASSESSMENT AND MANAGEMENT

### G.1 Potential Risks

| Risk Category | Risk Description | Likelihood | Severity | Mitigation Strategy |
|---------------|------------------|------------|----------|---------------------|
| Privacy | Breach of patient confidentiality | Low | High | Data anonymization; encrypted storage; access controls; Safe Harbor method |
| Psychological | Emotional distress from unexpected findings | Very Low | Moderate | Findings will not be returned to patients; retrospective design |
| Legal | Non-compliance with data regulations | Low | High | Compliance with Kenya Data Protection Act 2019 |
| Technical | Data loss or corruption | Low | Moderate | Regular backups; secure cloud storage; redundancy |
| Cross-Population Bias | Model performs differently on African populations | Medium | High | Comprehensive fairness evaluation; AKUH validation |
| Institutional | Non-compliance with Aga Khan University Hospital policies | Low | High | Close collaboration with AKUH radiology; proper agreements |
| Data Sovereignty | Health data leaving Kenyan jurisdiction | Low | High | All processing on Kenyan infrastructure; documented compliance |

### G.2 Risk Mitigation Measures

1. **Data Anonymization:** All patient identifiers will be removed before analysis. For Aga Khan University Hospital data, a separate linking key will be maintained securely by AKUH IT department. The research team will receive only anonymized data.

2. **Secure Storage:** Data will be stored on encrypted, password-protected servers with access limited to research team members. All storage confined within Kenya.

3. **Access Controls:** Only authorized research team members with signed confidentiality agreements will access the data.

4. **Training:** All research team members will complete research ethics training prior to data collection. The following free, open-access training programs are available:
   - **TRREE (Training and Resources in Research Ethics Evaluation):** An international online training program offering modules on research ethics, informed consent, and responsible conduct of research. Available at: https://elearning.gchrtraining.org/
   - **Global Health Training Centre:** Provides comprehensive research ethics training modules including Good Clinical Practice (GCP) and human subjects protection. Available at: https://globalhealthtrainingcentre.tghn.org/

   *Note: The principal investigator will complete at least one of these training programs prior to initiating any data collection activities.*

5. **Cross-Population Validation:** Comprehensive fairness evaluation will assess model performance across international (RSNA-ICA) and Kenyan (AKUH) populations, with appropriate bias mitigation strategies if disparities are identified.

6. **Institutional Compliance:** Close collaboration with Aga Khan University Hospital Radiology Department under Dr. Kevin Ombati's supervision ensures compliance with all institutional policies.

---

## SECTION H: BENEFITS

### Direct Benefits to Participants
This retrospective study involves anonymized data analysis. No direct benefits to individual patients whose data may be included.

### Benefits to the Kenyan Health System
1. Improved understanding of AI tool performance on Kenyan patient populations
2. Evidence-based recommendations for AI deployment in public health facilities
3. Enhanced capacity for AI research in medical imaging in Kenya
4. Potential for reduced radiologist workload in aneurysm detection
5. Framework for evaluating algorithmic fairness in African healthcare contexts
6. Contribution to the growing body of knowledge on AI in resource-constrained settings

### Benefits to Aga Khan University Hospital
1. Participation in cutting-edge AI research in radiology
2. Enhanced understanding of model generalizability across patient populations
3. Potential for improved diagnostic workflows in the future
4. Contribution to academic publications and presentations

---

## SECTION I: CONFIDENTIALITY AND DATA PROTECTION

### I.1 Data Handling Procedures

**Data Collection - RSNA-ICA:**
- Download from RSNA Imaging Portal (open-access)
- Storage on encrypted local storage
- Preprocessing for model training

**Data Collection - Aga Khan University Hospital (Pending ERC Approval):**
- DICOM files extracted from AKUH PACS by authorized hospital IT staff
- Demographic metadata extracted using standardized templates
- No patient names or unique identifiers collected
- Anonymization performed by AKUH data custodian before data transfer

**Data Anonymization:**
- AKUH data: All patient identifiers removed using Safe Harbor method; study IDs assigned sequentially
- Direct identifiers (name, medical record number, dates) removed or generalized
- Geographic data reduced to region level only
- Sequential study IDs assigned (AKU001, AKU002, etc.)
- Linking key maintained separately by AKUH only - not transferred to research team

**Data Storage:**
- Encrypted storage on password-protected research server
- Cloud storage using institutional Azure subscription (East Africa)
- Access logged and audited regularly
- All data retained within Kenya per Data Protection Act 2019

**Data Retention:**
- Data retained for 5 years following study completion
- Secure deletion thereafter
- Retention period complies with institutional and regulatory requirements

### I.2 Compliance with Kenya Data Protection Act 2019

This research complies with the Kenya Data Protection Act 2019 in the following ways:

1. **Lawful Processing:** Data processing is necessary for scientific research purposes (Section 30)
2. **Data Minimization:** Only necessary data elements collected
3. **Storage Limitation:** Data retained only for necessary period
4. **Security Measures:** Appropriate technical and organizational security measures implemented
5. **Data Sovereignty:** All processing conducted within Kenya; health data not transferred outside jurisdiction without special approval

---

## SECTION J: ETHICAL CONSIDERATIONS

### J.1 Algorithmic Fairness

This research specifically addresses algorithmic bias and fairness concerns with enhanced focus on cross-population generalizability:

- Evaluation of model performance across different demographic groups (age, sex) in training and validation datasets
- Assessment of performance variation across different scanner manufacturers
- Cross-population performance comparison: international (RSNA-ICA) → Kenyan (AKUH)
- Evaluation of model generalizability to African patient populations
- Recommendations for fair AI deployment in diverse populations

### J.2 Local Validation Ethics

The Aga Khan University Hospital local validation component raises specific ethical considerations:

1. **Population Representation:** International training datasets (RSNA-ICA) predominantly represent non-African populations. The research explicitly addresses this limitation through comprehensive AKUH validation and cross-population fairness analysis.

2. **Clinical Collaboration:** The validation is conducted through a formal collaboration with Aga Khan University Hospital Radiology Department under Dr. Kevin Ombati's supervision, ensuring clinical relevance and proper protocols.

3. **Data Sovereignty:** All processing of AKUH data conducted within Kenya, respecting national data protection requirements.

### J.3 Informed Consent

**Waiver Request:**
This study requests a waiver of individual informed consent because:
1. It involves retrospective analysis of anonymized data
2. The research presents minimal risk to subjects
3. Obtaining consent is impractical given the large sample size and retrospective nature
4. The waiver will not adversely affect the rights and welfare of subjects
5. Data will be fully anonymized before transfer to research team

### J.4 Vulnerable Populations

This study does not target vulnerable populations. While some patients may have compromised health status, the retrospective anonymized design minimizes risk. AKUH data includes adult patients with intracranial aneurysms; no pediatric data is included.

---

## SECTION K: RESEARCH TEAM QUALIFICATIONS

**Principal Investigator:**
- Cavin Otieno Ouma, MSc Public Health Data Science candidate
- Training in research methods (SDS 6203)
- Training in data science and machine learning
- Training in 3D medical imaging processing
- CITI Human Subjects Protection training (to be completed)

**Research Supervisors:**

*Prof. Peter Waiganjo (Primary Supervisor)*
- Senior Lecturer, Department of Computing and Informatics, UoN
- Extensive experience in health information systems research
- Expertise in deep learning and medical imaging
- University of Nairobi faculty liaison for GPU computing resources

*Dr. Pamela Mandela Idenya (Supervisor)*
- Lecturer, Department of Human Anatomy and Medical Physiology, UoN
- Expertise in neuroanatomy relevant to aneurysm detection
- Background in medical education and research supervision

*Dr. Vincent Okungu (Co-supervisor)*
- Adjunct Lecturer, Department of Public and Global Health, UoN
- Expertise in health systems and implementation science
- Background in global health research

*Dr. Kevin Ombati (Co-supervisor - AKUH)*
- Programme Director and Senior Instructor, Department of Radiology, AKUH
- Expertise in neuroradiology and clinical imaging
- Facilitates Aga Khan University Hospital data access and clinical guidance

**Computational Resources:**
- University of Nairobi GPU Facility, Department of Computing and Informatics
- NVIDIA A100 or RTX series GPU with 16GB+ VRAM
- Secure computing environment with institutional security controls
- Technical support from University of Nairobi staff

---

## SECTION L: BUDGET

| Item | Cost (KES) | Source | Notes |
|------|-------------|--------|-------|
| AKUH Data extraction personnel | 50,000 | Research budget | AKUH data extraction coordination |
| AKUH data storage | 12,000 | Personal | Cloud storage for local validation data |
| Supplementary dataset storage | 18,000 | Personal | Dataset download and template library storage |
| UoN GPU access contribution | 10,000 | Personal | Reduced from commercial cloud allocation |
| Specialized software (MeshLab, VTK) | 15,000 | Personal | 3D mesh processing tools |
| Google Colab Pro (supplementary) | 8,000 | Personal | Quick experiments and prototyping |
| Travel to AKUH | 12,000 | Personal | Data collection coordination visits |
| Travel to UoN | 4,000 | Personal | GPU training sessions |
| ERC application fee | 2,000 | Personal | Ethics committee submission |
| NACOSTI license | 10,000 | Personal | Research license |
| Contingency | 13,700 | Personal | Unexpected expenses |
| **Total** | **154,700** | **Personal (100%)** | |

**Budget Note:** The budget is fully funded by the principal investigator's personal resources. No external funding is being sought for this research. All computational resources are either freely available (RSNA-ICA dataset, open-source software) or provided through institutional support (UoN GPU facility).

---

## SECTION M: INSTITUTIONAL APPROVALS

**University of Nairobi Approval:**
[To be obtained from Department of Mathematics]

**Aga Khan University Hospital Research Approval:**
[To be obtained from AKUH Ethics Review Committee]

**Aga Khan University Hospital Data Access:**
[To be arranged with AKUH Radiology Department under Dr. Kevin Ombati's supervision]

**University of Nairobi Resource Allocation:**
[Confirmed - GPU computing resources allocated through Department of Computing and Informatics]

**NACOSTI Research License:**
[To be obtained from National Commission for Science, Technology and Innovation]

---

## SECTION N: DECLARATIONS

### Principal Investigator Declaration

I certify that:
1. The information provided in this application is accurate and complete
2. I have read and understood the Aga Khan University Hospital ERC guidelines and procedures
3. I will comply with all applicable ethical and legal requirements
4. I will report any adverse events or protocol deviations promptly
5. I will not commence data collection until full approval is obtained
6. I have disclosed all data sources and institutional collaborations in this application

**Signature:** ________________________

**Date:** ________________________

### Primary Supervisor Declaration

I certify that:
1. The applicant has adequate training and resources to conduct this research
2. I will provide ongoing supervision as detailed in this application
3. I take responsibility for ensuring ethical conduct of the research

**Signature:** ________________________

**Date:** ________________________

### AKUH Co-Supervisor Declaration

I certify that:
1. The research protocol has been reviewed for clinical appropriateness
2. The Aga Khan University Hospital data access arrangements are properly structured
3. I will oversee the local validation component at AKUH

**Signature:** ________________________

**Date:** ________________________

---

## SECTION R: STUDY RESULTS DISSEMINATION PLAN

The research findings will be disseminated through multiple channels to maximize impact:

1. **Academic Publications:** At least two peer-reviewed publications will be submitted to journals such as *The Lancet Digital Health*, *npj Digital Medicine*, *Radiology*, *Journal of Medical Imaging*, and *IEEE Transactions on Medical Imaging*.

2. **Conference Presentations:** Results will be presented at relevant conferences (e.g., RSNA Annual Meeting, MICCAI, SPIE Medical Imaging, African Radiology Congress).

3. **Master's Thesis:** A complete thesis will be submitted to the University of Nairobi Department of Mathematics in fulfillment of MSc Public Health Data Science requirements.

4. **Stakeholder Reports:** Summary reports will be provided to Aga Khan University Hospital Radiology Department, University of Nairobi, and the Ministry of Health.

5. **Open-Access Release:** Code and reproducibility documentation will be released on a public repository (GitHub) under an open-source license, in line with the Kenya Data Protection Act 2019 research provisions.

6. **AKUH ERC Notification:** All intended publications will be communicated to AKUH ERC prior to submission.

7. **Public Health Policy Briefs:** Two-page policy briefs will be prepared for the Ministry of Health, Kenya Medical Research Institute (KEMRI), and Council of Governors Health Committee.

**Dissemination Timeline:**
- Interim results: Q3 2026 (AKUH ERC progress report)
- Final results: Q4 2026 (Thesis submission, journal submission)
- Policy briefs: Q4 2026 - Q1 2027
- Open-source release: Q1 2027

---

## SECTION S: TIMELINE / TIME FRAME

| Phase | Activity | Start Date | End Date | Duration |
|-------|----------|------------|----------|----------|
| 1 | ERC Applications (UoN, AKUH) & Approval | January 2026 | April 2026 | 4 months |
| 2 | Data Acquisition (RSNA-ICA, supplementary) | November 2025 | February 2026 | 4 months |
| 3 | AKUH Data Anonymization & Transfer | May 2026 | July 2026 | 3 months |
| 4 | Preprocessing Pipeline Development | February 2026 | April 2026 | 3 months |
| 5 | Model Development & Training | March 2026 | June 2026 | 4 months |
| 6 | AKUH Local Validation | July 2026 | August 2026 | 2 months |
| 7 | Fairness & Cross-Population Analysis | July 2026 | September 2026 | 3 months |
| 8 | Thesis Writing & Documentation | August 2026 | October 2026 | 3 months |
| 9 | ERC Final Report & Dissemination | October 2026 | December 2026 | 3 months |

**Key Milestones:**
- AKUH ERC Approval: April 2026
- First Trained Model: June 2026
- AKUH Local Validation Complete: August 2026
- Thesis Submission: October 2026
- Defense & Publication: November 2026

---

## SECTION T: STUDY LIMITATIONS AND MITIGATION STRATEGIES

| Limitation | Description | Mitigation Strategy |
|------------|-------------|---------------------|
| **Cross-Population Bias** | Training datasets predominantly represent non-African populations, raising concerns about generalizability to Kenyan patients. | Mandatory local validation on AKUH data; comprehensive fairness evaluation across age, sex, and scanner manufacturer; transparent reporting of performance disparities. |
| **Retrospective Design** | Retrospective data may have selection bias and variable image quality, which may affect model robustness. | Apply strict image quality inclusion criteria; use multiple scanner types in training; perform quality control on all training data. |
| **Sample Size Constraints** | AKUH validation cohort (200-300 studies) may be limited for subgroup analyses. | Use stratified sampling; report confidence intervals for all subgroup metrics; acknowledge statistical power limitations explicitly. |
| **Single-Center AKUH Validation** | Validation at a single hospital may not represent all Kenyan healthcare settings. | Acknowledge in limitations; propose multi-center validation as future work. |
| **No External Test Set** | Without an independent external test set, optimistic bias in performance reporting is possible. | Use rigorous cross-validation; report all confidence intervals; use bootstrap methods for uncertainty quantification. |
| **Computational Resource Constraints** | Model training depends on UoN GPU access, which may be limited. | Reserve dedicated GPU slots; implement checkpointing; have backup cloud GPU plan (Google Colab Pro). |
| **Class Imbalance** | Aneurysms are relatively rare findings, leading to class imbalance in training data. | Apply class-weighted loss functions; use focal loss; perform stratified sampling; report per-class metrics. |
| **Data Privacy Risks** | Even anonymized DICOM data carries re-identification risk. | Apply Safe-harbor anonymization; remove burned-in identifiers; use DICOM de-identification toolkit; maintain data sharing agreements. |
| **Limited African Training Data** | No African population data in training set limits template representativeness. | Explicitly acknowledge limitation; focus on detecting generalization gap rather than maximizing training diversity. |

---

## CHECKLIST FOR SUBMISSION

- [x] Completed application form (this document)
- [x] Table of contents
- [x] List of abbreviations and acronyms
- [x] Operational definitions
- [x] Structured abstract (200-300 words)
- [x] Full research protocol
- [x] Research proposal (academic)
- [x] CV of principal investigator
- [x] Supervisor CVs
- [x] Data management plan
- [x] Informed consent form (waiver requested) or consent procedure
- [x] Letter of support from AKUH Radiology Department
- [x] Data sharing agreement template
- [x] University enrollment confirmation
- [x] Application fee receipt (if applicable)
- [x] Dissemination plan
- [x] Timeline / time frame
- [x] Study limitations and mitigation strategies
- [x] List of appendices

---

## APPENDICES

### Appendix A: Letter of Support from Aga Khan University Hospital Radiology Department

*[See Annex D - Letter of Support]*

### Appendix B: Data Sharing Agreement Template

*[See Annex C - MTA/DTA Agreement]*

### Appendix C: CV of Principal Investigator

*[To be attached]*

### Appendix D: CVs of Supervisors

*[To be attached]*

### Appendix E: Data Management Plan (v2.0)

*[See separate document]*

---

**FOR AGA KHAN UNIVERSITY HOSPITAL ETHICS REVIEW COMMITTEE USE ONLY**

Application Received: ________________

Application Number: ________________

Review Date: ________________

Decision: [ ] Approved [ ] Approved with Conditions [ ] Deferred [ ] Disapproved

Reviewer Comments:

________________________________________________________________

________________________________________________________________

________________________________________________________________

Signature: ________________

Date: ________________

---

*Aga Khan University Hospital Ethics Review Committee*
*Application Form Version 1.0, May 2026*

*This application has been prepared for ethics review by the Aga Khan University Hospital Ethics Review Committee. The research involves retrospective use of anonymized clinical data from AKUH for local validation of an AI model for intracranial aneurysm detection.*
