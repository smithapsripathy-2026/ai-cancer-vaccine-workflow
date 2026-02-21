**AI‑Augmented No‑Code Workflow for Generating Cancer Vaccine Regulatory Documents**

📌 **Purpose of This Workflow**
This document provides a step‑by‑step, no‑code execution guide for generating:
- A Phase 1/2 cancer vaccine clinical trial protocol
- Patient narratives based on synthetic data
- Module 2‑style summaries (Nonclinical Overview, Clinical Overview, Clinical Summary)
- QC reports
- A fully traceable, reproducible AI‑driven regulatory writing package
All steps use free AI tools (ChatGPT Free, Gemini Free, Claude Free, etc.) and require no programming.

🧭 How to Use This Workflow
Each module below corresponds to a folder in this repository:
- /prompts/ → Prompts to run
- /templates/ → Documents to paste outputs into
- /data/ → Synthetic dataset
- /outputs/ → Save your generated documents here
You will run prompts in order, paste outputs into templates, and assemble the final documents.

🚀 **MODULE 1 — Landscape & Rationale Generation**
Goal:
Generate the scientific foundation for the protocol and Module 2 documents.
Steps:
- Open the file:
/prompts/protocol_prompts.md
- Run the prompts in the section:
“M1 — Landscape & Rationale Builder”
- Copy the outputs into:
/templates/protocol_template.docx
→ Paste into the Background & Rationale section.
- Save your updated file in:
/outputs/protocol/protocol_draft_v1.docx

🧬 **MODULE 2 — Synthetic Dataset Creation**
Goal:
Create a realistic dataset to drive narratives, baseline tables, and eligibility criteria.
Steps:
- Open:
/prompts/dataset_prompts.md
- Run the prompt:
“Generate synthetic melanoma patient dataset”
- Paste the output into:
/data/synthetic_dataset_template.xlsx
- Save as:
/data/synthetic_dataset_filled.xlsx
- Run the prompt:
“Generate baseline characteristics table”
- Paste the output into:
/data/baseline_characteristics_table.md

📄 **MODULE 3 — Protocol Generation**
Goal:
Generate a complete Phase 1/2 protocol using modular prompts.
Steps:
- Open:
/prompts/protocol_prompts.md
- Run prompts in this order:
- Objectives
- Endpoints
- Study Design
- Eligibility Criteria
- Schedule of Assessments
- Statistical Considerations
- Safety Monitoring
- Ethics & Regulatory Considerations
- Paste each output into the corresponding section of:
/templates/protocol_template.docx
- Paste each output into the corresponding section of:
/templates/protocol_template.docx
- Save as:
/outputs/protocol/protocol_draft_v2.docx
- After final edits, save as:
/outputs/protocol/protocol_final.docx

🧪 **MODULE 4 — Patient Narrative Generation**
Goal:
Generate 3–5 regulatory‑style patient narratives.
Steps:
- Open:
/prompts/narrative_prompts.md
- Select 3–5 patients from:
/data/synthetic_dataset_filled.xlsx
- For each patient, run the prompt:
“Generate regulatory‑style patient narrative”
- Paste each narrative into:
/templates/patient_narrative_template.docx
- Save each as:
/outputs/narratives/narrative_patient_XXX.docx
- Combine into a single PDF (optional):
/outputs/narratives/narratives_final.pdf

📘 **MODULE 5 — Module 2 Document Generation**
Goal:
Generate high‑level regulatory summaries.
Steps:
- Open:
/prompts/module2_prompts.md
- Run prompts in this order:
- Nonclinical Overview (2.4‑style)
- Clinical Overview (2.5‑style)
- Clinical Summary (2.7‑style)
- Paste outputs into:
- /templates/module2_nonclinical_overview_template.docx
- /templates/module2_clinical_overview_template.docx
- /templates/module2_clinical_summary_template.docx
- Save drafts in:
/outputs/module2/
- Zip the final package as:
/outputs/module2/module2_package_final.zip

🧹 **MODULE 6 — Quality Control (QC)**
Goal:
Ensure consistency, accuracy, and alignment across all documents.
Steps:
- Open:
/prompts/qc_prompts.md
- Run prompts:
- Protocol QC
- Module 2 QC
- Narrative QC
- Paste outputs into:
- /outputs/qc/qc_report_protocol.md
- /outputs/qc/qc_report_module2.md
- /outputs/qc/qc_report_narratives.md
- Make final edits to documents based on QC findings.

📦 **MODULE 7 — Final Packaging & Versioning**
Goal:
Prepare the project for portfolio presentation.
Steps:
- Ensure all final documents are in:
/outputs/
- Update:
- README.md
- workflow_description.md
- automation_strategy.md
- prompt_chaining_map.md
- Commit all changes to GitHub.
- (Optional) Create a Release:
- Click Releases → Draft a new release
- Upload final protocol, Module 2 package, narratives
- Tag as v1.0
