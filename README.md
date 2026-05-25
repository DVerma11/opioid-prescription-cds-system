# Clinical Decision Support System for Reducing Unnecessary Opioid Prescriptions

## Project Overview
This project presents a rule-based Clinical Decision Support System (CDSS) developed to support safer opioid prescribing practices in outpatient settings. The system was designed using Exsys Corvid and implements the 2022 CDC Clinical Practice Guidelines for Prescribing Opioids for Pain.

The CDSS guides clinicians through patient-specific decision pathways and generates evidence-based recommendations related to opioid prescribing, overdose prevention, and opioid use disorder risk mitigation.

## Objectives
- Reduce unnecessary opioid prescribing
- Support evidence-based prescribing decisions
- Improve adherence to CDC opioid prescribing guidelines
- Identify opioid overdose risk factors
- Recommend safer prescribing practices
- Mitigate opioid misuse and adverse outcomes

## Technologies Used
- Exsys Corvid Expert System Software
- Rule-based Expert Systems
- Clinical Decision Trees
- IF/THEN Heuristic Logic
- Healthcare Informatics
- Clinical Decision Support Systems (CDSS)

## Clinical Guidelines Implemented
The system operationalizes the 2022 CDC Clinical Practice Guidelines for Prescribing Opioids for Pain, including:
- Nonopioid therapy recommendations
- Immediate-release opioid recommendations
- Morphine Milligram Equivalent (MME) dose checks
- Prescription duration limits
- Naloxone recommendations
- PDMP review checks
- Urine drug screening recommendations
- Benzodiazepine interaction warnings
- Opioid Use Disorder recommendations

## CDS Logic Design
The system uses:
- Decision trees
- Sequential IF/THEN rules
- Confidence variables
- Structured questionnaires
- Recommendation-triggering alerts

Separate clinical workflows were developed for:
- Acute pain
- Subacute pain
- Chronic pain

## Key Features
- Outpatient eligibility screening
- Age-based applicability checks
- Exclusion criteria handling
- Opioid-naive patient evaluation
- MME dose validation
- PDMP review recommendations
- Naloxone consideration
- Urine drug testing recommendations
- Concurrent benzodiazepine safety checks
- Opioid Use Disorder identification

## Methodology
1. Developed decision trees based on CDC opioid guidelines
2. Created rule-based logic using Exsys Corvid
3. Built clinician questionnaires and variables
4. Designed alert and recommendation workflows
5. Implemented sequential clinical decision pathways
6. Tested the system using 32 clinical case scenarios

## Example Clinical Logic
Example rule:
- If opioid dosage exceeds 50 MME/day:
  - Trigger overdose risk warning
  - Recommend tapering and reassessment

Example rule:
- If concurrent benzodiazepine use is detected:
  - Trigger recommendation to avoid concurrent opioid prescribing

## Results
Testing using multiple clinical case examples demonstrated that the CDS system successfully:
- Guided clinicians through CDC recommendations
- Identified overdose risk factors
- Recommended safer opioid prescribing practices
- Suggested alternative therapies
- Supported evidence-based prescribing decisions

## Research Paper
This repository includes the accompanying research paper describing:
- Literature review
- CDS design methodology
- Clinical logic implementation
- System evaluation
- Results and conclusions

## Files
- `A Clinical Decision Support System for Reducing Unnecessary Opioid Prescriptions_DV.pdf`
- `Opioid Prescription Control CDS System by Divya Verma- Corvid download.pdf`

## Author
Divya Verma
Rutgers University
MS Health Informatics
