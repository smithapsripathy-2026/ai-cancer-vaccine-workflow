# ai-cancer-vaccine-workflow
A No‑Code, Modular, Reproducible Workflow for Generating Regulatory‑Style Documents Using Free AI Tools
     
**Overview**

This repository demonstrates a complete, no‑code automation framework for generating regulatory‑style documents for a therapeutic cancer vaccine using:
- Free, publicly available datasets
- Free AI tools (ChatGPT Free, Gemini Free, Claude Free, LLaMA local, etc.)
- Modular prompt chaining
- Document templates
- Synthetic patient data
- GitHub‑based version control and traceability
The workflow automatically produces:
- A Phase 1/2 clinical trial protocol
- Patient narratives based on synthetic data
- Module 2‑style summaries (Nonclinical Overview, Clinical Overview, Clinical Summary)
- QC checklists and AI‑assisted quality review
- A fully documented, reproducible AI‑augmented regulatory writing pipeline
This project showcases how a medical/regulatory writer can design AI‑driven workflows without programming.

🎯 **Project Goals**
- Demonstrate end‑to‑end regulatory writing using AI
- Use only free tools and no programming
- Build a repeatable, auditable workflow
- Show automation through prompt chaining, templates, and structured data
- Provide a portfolio‑ready example of AI‑augmented scientific communication

🧬 **Therapeutic Area**

Personalized neoantigen cancer vaccine
Indication: Advanced/metastatic melanoma
This area was chosen because it allows rich scientific rationale, strong immunology content, and realistic clinical endpoints.

🗂️ **Repository Structure**

```
ai-cancer-vaccine-workflow/
│
├── README.md
├── RUN_WORKFLOW.md
├── WORKFLOW_DIAGRAM.png
│
├── /data/
│   ├── synthetic_dataset_template.xlsx
│   ├── synthetic_dataset_filled.xlsx
│   ├── data_dictionary.md
│   └── baseline_characteristics_table.md
│
├── /literature/
│   ├── key_papers_list.md
│   ├── clinical_landscape_summary.md
│   ├── immunology_background.md
│   └── references_zotero_export.bib
│
├── /templates/
│   ├── protocol_template.docx
│   ├── module2_nonclinical_overview_template.docx
│   ├── module2_clinical_overview_template.docx
│   ├── module2_clinical_summary_template.docx
│   ├── patient_narrative_template.docx
│   └── qc_checklist_template.xlsx
│
├── /prompts/
│   ├── protocol_prompts.md
│   ├── module2_prompts.md
│   ├── narrative_prompts.md
│   ├── dataset_prompts.md
│   └── qc_prompts.md
│
├── /outputs/
│   ├── protocol/
│   ├── module2/
│   ├── narratives/
│   └── qc/
│
└── /workflow/
    ├── workflow_description.md
    ├── automation_strategy.md
    ├── prompt_chaining_map.md
    └── limitations_and_future_work.md
```


⚙️ **How the Workflow Works (No Code Required)**

This project uses prompt chaining as the automation engine.
Each module feeds into the next:
- Landscape & Rationale Generation
- Synthetic Dataset Creation
- Protocol Section Generation
- Patient Narrative Generation
- Module 2 Document Generation
- AI‑Assisted QC
- Document Assembly & Versioning
All steps are executed using free AI tools and copy/paste workflows.

🚀 **What This Workflow Produces**

1. Clinical Trial Protocol
- Phase 1/2
- Cancer vaccine + checkpoint inhibitor
- Includes objectives, endpoints, design, stats, safety, ethics
2. Patient Narratives
- 3–5 synthetic narratives
- AE timelines, medical history, concomitant meds, outcomes
3. Module 2‑Style Summaries
- Nonclinical Overview
- Clinical Overview
- Clinical Summary
4. QC Reports
- AI‑assisted consistency checks
- Alignment of objectives ↔ endpoints ↔ statistics
5. Workflow Documentation
- Flowchart
- Prompt chaining map
- Automation strategy

🧩 **Tools Used (All Free)**

- ChatGPT Free
- Gemini Free
- Claude Free
- Local LLaMA (optional)
- Zotero for references
- Excel/Google Sheets for synthetic data
- Word/Google Docs for document assembly
- GitHub for version control
No programming is required.

📘 **How to Run the Workflow**

See RUN_WORKFLOW.md for the full step‑by‑step automation guide.
It includes:
- Which prompts to run
- In what order
- What to paste where
- How to assemble the final documents
- How to perform QC
- How to update outputs

📈 **Why This Project Matters**

This repository demonstrates:
- AI‑augmented regulatory writing
- No‑code automation
- Scientific synthesis
- Workflow design
- Document architecture
- Traceability and reproducibility
- Oncology and immunology domain expertise
It is designed as a portfolio artifact for medical writing, regulatory writing, clinical development, and medical affairs roles.
