# ANNEX C: MATERIAL AND DATA TRANSFER AGREEMENT (MTA/DTA)

## FOR THE TRANSFER OF DE-IDENTIFIED CLINICAL IMAGING DATA

**Agreement Reference:** MTA-AKUH-UON-2026-001

**Project Title:** Hybrid Deep Learning Framework for Intracranial Aneurysms Detection: Algorithmic Development and Fairness Evaluation for Kenyan Public Health Settings

**Principal Investigator:** Cavin Otieno Ouma, MSc Candidate, Public Health Data Science, University of Nairobi

**Data Custodian:** Dr. Kevin Ombati, Programme Director and Senior Instructor, Department of Radiology, Aga Khan University Hospital, Nairobi

**Effective Date:** [To be completed upon execution]

---

## TABLE OF CONTENTS

| Section | Title | Page |
|---------|-------|------|
| 1 | Parties to this Agreement | 1 |
| 2 | Definitions | 1 |
| 3 | Purpose and Scope | 2 |
| 4 | Description of Materials | 2 |
| 5 | Data Transfer Procedures | 3 |
| 6 | Data Anonymization Requirements | 3 |
| 7 | Data Custody and Security | 4 |
| 8 | permitted Uses | 5 |
| 9 | Restrictions on Use | 5 |
| 10 | Intellectual Property | 6 |
| 11 | Publication and Dissemination | 6 |
| 12 | Term and Termination | 7 |
| 13 | Confidentiality | 7 |
| 14 | Liability and Indemnification | 8 |
| 15 | Compliance with Applicable Laws | 8 |
| 16 | Dispute Resolution | 9 |
| 17 | Miscellaneous | 9 |
| 18 | Signatures | 10 |
| Appendix A | Description of Data Elements | 11 |
| Appendix B | Anonymization Certification Checklist | 12 |
| Appendix C | Incident Response Protocol | 13 |

---

## SECTION 1: PARTIES TO THIS AGREEMENT

This Material and Data Transfer Agreement ("Agreement") is entered into by and between:

**PROVIDER:**
Aga Khan University Hospital, Nairobi
3rd Parklands Avenue, Limuru Road
P.O. Box 30270 - 00100, Nairobi, Kenya
("AKUH")

**RECIPIENT:**
University of Nairobi, Department of Mathematics
P.O. Box 30197 - 00100, Nairobi, Kenya
("UoN")

**PRINCIPAL INVESTIGATOR (under UoN):**
Cavin Otieno Ouma
MSc Candidate, Public Health Data Science
Department of Mathematics, University of Nairobi
Email: otienocavin@gmail.com
Phone: +254 715 169 531

**DATA CUSTODIAN (under AKUH):**
Dr. Kevin Ombati
Programme Director and Senior Instructor
Department of Radiology, Aga Khan University Hospital, Nairobi
Email: kevin.onyinkwa@aku.edu
Phone: +254 720 878 844

---

## SECTION 2: DEFINITIONS

For the purposes of this Agreement, the following terms shall have the meanings set forth below:

**2.1 "Anonymized Data"** means data that has been processed to remove all direct and indirect identifiers such that the data subject cannot be identified, directly or indirectly, by any means reasonably likely to be used. Anonymization shall be performed in accordance with the HIPAA Safe Harbor method and the Kenya Data Protection Act, 2019.

**2.2 "Confidential Information"** means any information disclosed by either party to the other party, either directly or indirectly, in writing, orally, or by inspection of tangible objects, that is designated as "Confidential," "Proprietary," or some similar designation, or that reasonably should be understood to be confidential given the nature of the information and circumstances of disclosure.

**2.3 "Data"** means the de-identified CT Angiography (CTA) imaging studies and associated metadata to be transferred from AKUH to UoN pursuant to this Agreement, as described in Section 4 and Appendix A.

**2.4 "Data Custodian"** means Dr. Kevin Ombati, who shall hold the linking key for re-identification and shall be responsible for ensuring compliance with anonymization requirements before any data transfer.

**2.5 "Linking Key"** means the code or identifier that could be used to re-identify anonymized data subjects. The Linking Key shall remain exclusively with the Data Custodian at AKUH and shall not be transferred to the Recipient.

**2.6 "Materials"** means the Data and any associated documentation, including metadata, imaging protocols, and quality assessment reports.

**2.7 "Principal Investigator"** means Cavin Otieno Ouma, who shall be responsible for ensuring that all uses of the Data are in compliance with this Agreement.

**2.8 "Research Project"** means the research project titled "Hybrid Deep Learning Framework for Intracranial Aneurysms Detection: Algorithmic Development and Fairness Evaluation for Kenyan Public Health Settings" as described in the associated ERC application.

**2.9 "Safe Harbor Method"** means the de-identification standard established under HIPAA Privacy Rule (45 CFR 164.514(b)) which requires removal of 18 specified identifiers of the individual and the individual's relatives, employers, and household members.

---

## SECTION 3: PURPOSE AND SCOPE

**3.1 Purpose.** This Agreement governs the transfer of Anonymized Data from AKUH to UoN for the sole purpose of conducting the Research Project as described in the associated ethics review committee application. The purpose of this transfer is to enable external validation of an AI model for intracranial aneurysm detection on the Kenyan clinical population, thereby assessing cross-population generalizability and algorithmic fairness.

**3.2 Scope.** This Agreement applies to all Anonymized Data transferred from AKUH to UoN under the Research Project, including but not limited to CT Angiography images, metadata, and any derived datasets.

**3.3 Limitations.** This Agreement does not cover any other data, materials, or intellectual property. Any additional transfers require a separate written agreement.

**3.4 Ethics Approval.** This Agreement is contingent upon receipt of ethics approval from the KNH-UoN Ethics Review Committee (Reference: P550/06/2026) and the Aga Khan University Hospital Ethics Review Committee. No data transfer shall commence until such approvals are obtained.

---

## SECTION 4: DESCRIPTION OF MATERIALS

**4.1 Data Type.** The Data consists of de-identified CT Angiography (CTA) studies of the brain obtained from the AKUH radiology department Picture Archiving and Communication System (PACS).

**4.2 Volume.** The Data shall comprise approximately 200-300 CTA studies, representing the available historical cases meeting the inclusion criteria during the specified time period.

**4.3 Time Period.** The Data shall cover CTA studies performed at AKUH between January 2020 and December 2025.

**4.4 Inclusion Criteria.** CTA studies included in the Data shall meet the following criteria:

- Studies performed at AKUH between January 2020 and December 2025
- Studies of adult patients (18 years of age or older)
- Studies with complete patient demographic information (age, sex)
- Studies with available scanner manufacturer information
- Studies with adequate image quality for computational analysis
- Studies without previous surgical interventions for aneurysms

**4.5 Data Elements.** The specific data elements to be included are described in Appendix A. The Data Custodian shall ensure that only the data elements specified in Appendix A are transferred.

**4.6 Exclusions.** The following information shall be explicitly excluded from the Data:

- Patient names
- Medical record numbers
- Dates of birth (age only, generalized to 5-year bands)
- Exact dates of service (year and month only)
- Full postal addresses (region only)
- Phone numbers
- Email addresses
- Social Security numbers or national ID numbers
- Any other direct or indirect identifiers

---

## SECTION 5: DATA TRANSFER PROCEDURES

**5.1 Initiation of Transfer.** The data transfer shall be initiated only after:

- Ethics approval has been obtained from both KNH-UoN ERC and AKUH ERC
- This Agreement has been fully executed by authorized representatives of both parties
- The Data Custodian has certified completion of anonymization per Appendix B
- The Principal Investigator has confirmed receipt of the data transfer notification

**5.2 Extraction.** Data extraction from AKUH PACS shall be performed exclusively by authorized AKUH radiology IT staff under the supervision of the Data Custodian.

**5.3 Anonymization.** Anonymization shall be performed by AKUH personnel before any data leaves AKUH systems. The Recipient shall receive only Anonymized Data. Details of anonymization requirements are in Section 6.

**5.4 Transfer Method.** Data transfer shall be conducted via secure encrypted file transfer protocol (SFTP) or physical encrypted storage media, at the discretion of the Data Custodian. All transfer methods shall use encryption meeting or exceeding AES-256 standards.

**5.5 Verification.** Upon receipt, the Principal Investigator shall verify the integrity of transferred files using SHA-256 checksums provided by AKUH. Any discrepancies shall be reported to the Data Custodian within 48 hours.

**5.6 Documentation.** Both parties shall maintain records of all data transfers, including date, volume, checksums, and responsible personnel.

---

## SECTION 6: DATA ANONYMIZATION REQUIREMENTS

**6.1 Standard.** Anonymization shall comply with the HIPAA Safe Harbor method (45 CFR 164.514(b)) and the Kenya Data Protection Act, 2019.

**6.2 Identifiers to be Removed.** The following 18 HIPAA Safe Harbor identifiers shall be removed or generalized:

| # | Identifier Category | Required Action |
|---|-------------------|-----------------|
| 1 | Names | Remove entirely |
| 2 | Geographic data smaller than state | Remove; retain region only |
| 3 | Dates (except year) | Remove; retain year and month only |
| 4 | Phone numbers | Remove entirely |
| 5 | Fax numbers | Remove entirely |
| 6 | Email addresses | Remove entirely |
| 7 | Social Security numbers | Remove entirely |
| 8 | Medical record numbers | Remove; assign sequential study IDs |
| 9 | Health plan beneficiary numbers | Remove entirely |
| 10 | Account numbers | Remove entirely |
| 11 | Certificate/license numbers | Remove entirely |
| 12 | Vehicle identifiers | Remove entirely |
| 13 | Device identifiers/serial numbers | Remove entirely |
| 14 | Web URLs | Remove entirely |
| 15 | IP addresses | Remove entirely |
| 16 | Biometric identifiers | Remove entirely |
| 17 | Full-face photographs | Remove entirely |
| 18 | Any unique identifying number/code | Remove; use sequential study IDs |

**6.3 Additional Kenyan-Specific Requirements.** In addition to HIPAA Safe Harbor requirements, the following Kenyan-specific identifiers shall be removed:

- National ID numbers
- NHIF (National Health Insurance Fund) numbers
- Passport numbers
- Alien ID numbers

**6.4 Metadata Anonymization.** DICOM header fields shall be reviewed and modified to remove or generalize:

- PatientName → "ANON"
- PatientID → Sequential study ID (e.g., AKU001, AKU002)
- PatientBirthDate → Age in years
- AccessionNumber → Removed
- Other potential identifiers in Private tags

**6.5 Burned-In Annotations.** Any burned-in annotations on images containing patient information shall be removed or pixelated.

**6.6 Certification.** The Data Custodian shall sign and date the certification checklist in Appendix B, confirming that all anonymization requirements have been met before data transfer.

---

## SECTION 7: DATA CUSTODY AND SECURITY

**7.1 Custody of Linking Key.** The Linking Key that could be used to re-identify anonymized data subjects shall remain exclusively in the custody of the Data Custodian at AKUH. Under no circumstances shall the Linking Key be transferred to the Recipient or any third party.

**7.2 Secure Storage.** The Recipient shall store all received Data on:

- Encrypted storage using AES-256 encryption or equivalent
- Password-protected research server with access controls
- All data processing confined to Kenya (UoN or KENET infrastructure)
- No cloud storage outside Kenya without explicit written approval

**7.3 Access Controls.** Access to the Data shall be limited to:

- The Principal Investigator (Cavin Otieno Ouma)
- Research supervisors as listed in the ethics application
- IT support staff with documented need-to-know

All persons with access shall sign confidentiality agreements.

**7.4 Audit Trail.** The Recipient shall maintain audit logs documenting all access to the Data, including:

- Identity of accessing person
- Date and time of access
- Purpose of access
- Actions performed

Audit logs shall be retained for the duration of the Research Project plus 5 years.

**7.5 Physical Security.** When stored on portable media, the Data shall be stored in locked, secured facilities.

**7.6 Data Segregation.** The Data shall be stored separately from other research datasets to prevent inadvertent mixing or cross-contamination.

**7.7 Return or Destruction.** Upon completion of the Research Project or termination of this Agreement, the Recipient shall:

- Return all Data to AKUH, or
- Provide certification of secure destruction of all Data copies
- The Data Custodian shall verify destruction if requested

---

## SECTION 8: PERMITTED USES

**8.1 Scope of Use.** The Recipient is permitted to use the Data solely for the following purposes in connection with the Research Project:

- Training and validation of machine learning algorithms for intracranial aneurysm detection
- Evaluation of algorithmic fairness across demographic subgroups
- Assessment of cross-population model generalizability
- Analysis of model performance across different scanner manufacturers
- Preparation of academic publications and thesis
- Preparation of presentations for academic conferences

**8.2 Secondary Uses.** Any secondary uses of the Data, including but not limited to commercial applications, teaching materials, or sharing with third parties, require prior written approval from AKUH.

**8.3 No Individual Results Return.** The Recipient shall not attempt to return individual diagnostic results to patients. The research is purely analytical and does not constitute clinical diagnosis.

---

## SECTION 9: RESTRICTIONS ON USE

**9.1 Prohibited Uses.** The Recipient shall NOT:

- Attempt to re-identify any data subject
- Transfer the Data to any third party without written approval
- Use the Data for any commercial purpose
- Use the Data for clinical decision-making without appropriate regulatory approvals
- Use the Data for any purpose other than the Research Project
- Publish or disseminate any results that could lead to re-identification
- Remove the Data from Kenya without explicit written approval
- Store the Data on non-encrypted media or public cloud services
- Share login credentials for data access

**9.2 Incidental Findings.** In the event that the research team identifies potential incidental findings during analysis, the following procedure applies:

- The finding shall be documented internally with study ID only
- The finding shall NOT be returned to the patient
- The finding shall be reported to the Data Custodian within 48 hours
- The Data Custodian shall determine appropriate clinical follow-up
- The research team shall not contact patients directly

This restriction is absolute and non-negotiable.

**9.3 Compliance Monitoring.** AKUH reserves the right to audit the Recipient's compliance with these restrictions upon reasonable notice.

---

## SECTION 10: INTELLECTUAL PROPERTY

**10.1 Ownership.** The Data remains the property of AKUH. Transfer of Data does not transfer ownership of any intellectual property rights.

**10.2 Derivative Works.** Any algorithms, models, or analysis methods developed using the Data ("Derivative Works") shall be jointly owned by the Recipient and AKUH, with the following provisions:

- The Principal Investigator shall be credited as primary developer
- AKUH shall receive royalty-free license for non-commercial use
- Commercialization requires separate negotiated agreement

**10.3 Background IP.** Pre-existing intellectual property of either party remains the property of that party.

**10.4 Patent Rights.** Neither party shall file patent applications on Derivative Works without prior written agreement on ownership and commercialization terms.

---

## SECTION 11: PUBLICATION AND DISSEMINATION

**11.1 Right to Publish.** The Recipient has the right to publish results of the Research Project, subject to the restrictions in this Section.

**11.2 Pre-Publication Review.** AKUH reserves the right to review publications for:

- Confidential information disclosure
- Potential for re-identification
- Accuracy of descriptions of AKUH data or procedures

Such review shall be completed within 30 days of submission and shall not unreasonably delay publication.

**11.3 Acknowledgment.** All publications shall include acknowledgment of AKUH as the source of validation data and the Data Custodian by name.

**11.4 Re-Identification Prohibition.** Publications shall not include any information that could enable re-identification of data subjects.

**11.5 AKUH ERC Notification.** Prior to submission of any publication, the Recipient shall notify AKUH ERC and receive confirmation that all obligations have been met.

**11.6 Open-Source Release.** Release of code or models on public repositories is permitted provided:

- No Data is included in the release
- The release acknowledges AKUH data contribution
- The release is for non-commercial academic purposes

**11.7 Thesis.** The Recipient's thesis shall include appropriate acknowledgment of AKUH data contribution.

---

## SECTION 12: TERM AND TERMINATION

**12.1 Term.** This Agreement shall commence on the Effective Date and shall continue until:

- Completion of the Research Project and fulfillment of all obligations, or
- Termination as provided in this Section

**12.2 Duration of Data Use.** The Recipient is authorized to use the Data for a period of five (5) years from the Effective Date, unless terminated earlier.

**12.3 Termination by Either Party.** Either party may terminate this Agreement:

- For material breach by the other party, upon 30 days written notice if the breach remains uncured
- For any reason, upon 90 days written notice

**12.4 Termination for Non-Compliance.** AKUH may terminate this Agreement immediately if:

- The Recipient violates any anonymization or confidentiality requirement
- The Recipient attempts to re-identify data subjects
- Ethics approval is revoked

**12.5 Effect of Termination.** Upon termination:

- The Recipient shall immediately cease all use of the Data
- The Recipient shall return or certify destruction of all Data within 30 days
- Surviving provisions include Sections 7 (Data Custody), 9 (Restrictions), 11 (Publication), 13 (Confidentiality), 14 (Liability), and 15 (Compliance)

---

## SECTION 13: CONFIDENTIALITY

**13.1 Obligation.** Each party shall maintain the confidentiality of the other party's Confidential Information and shall not disclose such information to any third party without prior written consent.

**13.2 Exceptions.** Confidentiality obligations do not apply to information that:

- Is or becomes publicly available through no fault of the receiving party
- Was known to the receiving party prior to disclosure
- Is independently developed by the receiving party
- Is required to be disclosed by law or court order (with prompt notice to the disclosing party)

**13.3 Duration.** Confidentiality obligations survive for 10 years following termination of this Agreement.

---

## SECTION 14: LIABILITY AND INDEMNIFICATION

**14.1 Representations.** The Data Custodian represents that:

- The Data has been properly anonymized per Section 6
- The Data Custodian has authority to enter into this Agreement
- The Data consists of legitimate medical records

**14.2 Warranty Disclaimer.** THE DATA IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. AKUH DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.

**14.3 Indemnification by Recipient.** The Recipient shall indemnify and hold harmless AKUH from any claims arising from:

- Unauthorized use of the Data
- Violation of this Agreement by the Recipient
- Re-identification attempts by the Recipient or anyone with access through the Recipient

**14.4 Limitation of Liability.** NEITHER PARTY SHALL BE LIABLE FOR INDIRECT, INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES.

**14.5 Risk Allocation.** The parties acknowledge that the allocations of risk in this Section reflect the nature of the Data and the Research Project.

---

## SECTION 15: COMPLIANCE WITH APPLICABLE LAWS

**15.1 Kenya Data Protection Act, 2019.** Both parties shall comply with all requirements of the Kenya Data Protection Act, 2019, including but not limited to:

- Lawful processing (Section 30 - research exemption)
- Data minimization
- Storage limitation
- Appropriate security measures

**15.2 HIPAA.** To the extent applicable, the parties shall comply with HIPAA Privacy Rule requirements for protected health information.

**15.3 Medical Practice Laws.** The Recipient shall comply with all applicable Kenyan laws governing medical practice and clinical research.

**15.4 Export Controls.** The Recipient shall not export the Data from Kenya without explicit written approval and compliance with applicable export control laws.

**15.5 Regulatory Compliance.** The Recipient shall obtain all necessary regulatory approvals before commencing research activities.

---

## SECTION 16: DISPUTE RESOLUTION

**16.1 Good Faith Resolution.** The parties shall attempt in good faith to resolve any dispute arising out of or relating to this Agreement through direct negotiation.

**16.2 Escalation.** If the dispute cannot be resolved through direct negotiation within 30 days, the matter shall be escalated to designated senior representatives of each party.

**16.3 Mediation.** If escalation fails, the parties shall submit to mediation administered by the Chartered Institute of Arbitrators (Kenya Branch).

**16.4 Arbitration.** If mediation fails, the dispute shall be finally resolved by arbitration under the Arbitration Act, 1995 of Kenya.

**16.5 Governing Law.** This Agreement shall be governed by and construed in accordance with the laws of Kenya.

---

## SECTION 17: MISCELLANEOUS

**17.1 Entire Agreement.** This Agreement, including all appendices, constitutes the entire agreement between the parties regarding its subject matter and supersedes all prior agreements and understandings.

**17.2 Amendment.** This Agreement may be amended only by written instrument signed by authorized representatives of both parties.

**17.3 Waiver.** Failure to enforce any provision of this Agreement shall not constitute a waiver of that provision or any other provision.

**17.4 Severability.** If any provision is held invalid, the remaining provisions shall continue in full force and effect.

**17.5 Assignment.** Neither party may assign this Agreement without prior written consent of the other party.

**17.6 Notices.** All notices shall be in writing and delivered to the contact information listed in Section 1.

**17.7 Independent Contractors.** The parties are independent contractors, not agents or partners.

**17.8 Force Majeure.** Neither party shall be liable for failure to perform due to causes beyond reasonable control.

**17.9 Counterparts.** This Agreement may be executed in counterparts.

**17.10 Language.** This Agreement is written in English.

---

## SECTION 18: SIGNATURES

By signing below, the authorized representatives confirm that they have read, understood, and agree to be bound by all terms and conditions of this Agreement.

---

**FOR AGA KHAN UNIVERSITY HOSPITAL:**

Signature: ________________________

Name: ________________________

Title: ________________________

Date: ________________________

Official Stamp:

---

**FOR UNIVERSITY OF NAIROBI:**

Signature: ________________________

Name: ________________________

Title: ________________________

Date: ________________________

Official Stamp:

---

**PRINCIPAL INVESTIGATOR (Acknowledgment):**

Signature: ________________________

Name: Cavin Otieno Ouma

Date: ________________________

---

**DATA CUSTODIAN (Certification):**

I certify that the Data transferred under this Agreement has been anonymized in compliance with Section 6 and Appendix B.

Signature: ________________________

Name: Dr. Kevin Ombati

Date: ________________________

---

## APPENDIX A: DESCRIPTION OF DATA ELEMENTS

The following data elements shall be included in the transferred Data:

### A.1 Imaging Data

| Element | Description | Format |
|---------|-------------|--------|
| CTA Series | CT Angiography image series of the brain | DICOM (.dcm) files |
| Study Instance UID | Unique identifier for the study (modified) | Alphanumeric code |
| Series Instance UID | Unique identifier for the series (modified) | Alphanumeric code |
| SOP Instance UID | Unique identifier for each slice (modified) | Alphanumeric code |

### A.2 Demographic Metadata

| Element | Description | Format |
|---------|-------------|--------|
| Study ID | Sequential anonymized identifier | AKU001, AKU002, ... |
| Age | Patient age at time of study (generalized to 5-year bands) | 20-25, 25-30, etc. |
| Sex | Patient biological sex | Male / Female |
| Study Year | Year of the CTA study | YYYY |
| Study Month | Month of the CTA study | MM |

### A.3 Technical Metadata

| Element | Description | Format |
|---------|-------------|--------|
| Scanner Manufacturer | Manufacturer of CT scanner | GE Healthcare / Siemens / Philips / Canon |
| Scanner Model | Model of CT scanner (generalized) | e.g., "64-slice" |
| Slice Thickness | Reconstruction slice thickness | Numerical (mm) |
| Matrix Size | Image matrix dimensions | e.g., 512 x 512 |
| Number of Slices | Total number of slices in series | Integer |

### A.4 Clinical Metadata

| Element | Description | Format |
|---------|-------------|--------|
| Clinical Indication | Reason for CTA study (generalized) | Headache / Stroke workup / Other |
| Laterality | Left / Right / Bilateral | Left / Right / Bilateral |
| Aneurysm Presence | Whether aneurysm is present | Yes / No |
| Aneurysm Location | General location (generalized) | Anterior / Posterior circulation |
| Aneurysm Size | Maximum diameter (if present) | <7mm / 7-10mm / 10-25mm / >25mm |

---

## APPENDIX B: ANONYMIZATION CERTIFICATION CHECKLIST

I, Dr. Kevin Ombati, as Data Custodian, certify that the Data has been anonymized according to all requirements:

| Requirement | Verified (Yes/No) | Notes |
|-------------|-------------------|-------|
| All 18 HIPAA Safe Harbor identifiers removed | ☐ Yes / ☐ No | |
| All Kenyan-specific identifiers removed | ☐ Yes / ☐ No | |
| PatientName field replaced with "ANON" | ☐ Yes / ☐ No | |
| PatientID replaced with sequential Study ID | ☐ Yes / ☐ No | |
| PatientBirthDate replaced with age band | ☐ Yes / ☐ No | |
| AccessionNumber removed | ☐ Yes / ☐ No | |
| All DICOM private tags reviewed | ☐ Yes / ☐ No | |
| Burned-in annotations removed/pixelated | ☐ Yes / ☐ No | |
| SHA-256 checksums generated | ☐ Yes / ☐ No | |
| Data quality verified | ☐ Yes / ☐ No | |
| No direct identifiers in metadata | ☐ Yes / ☐ No | |
| Indirect identifiers assessed and removed | ☐ Yes / ☐ No | |

**Data Custodian Certification:**

I certify that to the best of my knowledge, the Data described in this transfer contains no information that could be used to identify any individual patient.

Signature: ________________________

Date: ________________________

---

## APPENDIX C: INCIDENT RESPONSE PROTOCOL

### C.1 Security Incident Notification

In the event of a suspected or actual security incident involving the Data:

1. The Recipient shall notify the Data Custodian within 24 hours of discovery
2. Notification shall include: nature of incident, data potentially affected, actions taken
3. The Data Custodian shall assess re-identification risk
4. If re-identification is possible, the Data Custodian shall notify affected patients as required by law

### C.2 Re-Identification Attempt

If any party becomes aware of an attempt to re-identify data subjects:

1. All data access shall be suspended immediately
2. The Data Custodian shall be notified immediately
3. An investigation shall be conducted
4. This Agreement may be terminated immediately

### C.3 Contact Information for Incidents

**Primary Contact:** Dr. Kevin Ombati
**Phone:** +254 720 878 844
**Email:** kevin.onyinkwa@aku.edu
**Alternative:** AKUH IT Security Office: +254 20 366 2000

---

*This Material and Data Transfer Agreement is made effective as of the date of final signature.*

*Reference: MTA-AKUH-UON-2026-001*
