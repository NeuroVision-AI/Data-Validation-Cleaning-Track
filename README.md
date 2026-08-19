# NeuroVision-AI: Data Validation & Cleaning Track
**Project:** Brain Tumor Detection, Classification & Segmentation Research Paper  
**Track:** Data Validation & Cleaning (Task 1)  
**Organization:** NeuroVision-AI  

This repository is the definitive, version-controlled archive and final handoff package from the **Data Validation & Cleaning Team**. It contains the governance documents, phased deliverables, and audit trails required to ensure every citation, claim, and dataset used in the final manuscript is accurate, traceable, and publication-ready.

---

## 🏗️ The 3-Layer Architecture & Workflow

To prevent data corruption and duplication of effort, this track operates on a strict 3-Layer system governed by a **Hard Gate**:

1. **Layer 1 (The Master Tracker - Live Cloud):** The central Google Sheet database holding all hard data, metadata, and status tracking.
2. **Layer 2 (Exception & Judgement Logs - Local/Cloud):** The validator’s workspace for critical thinking, exception logging (e.g., broken DOIs, predatory journals), and professional judgement. 
3. **Layer 3 (Final Synthesis - Local/Cloud):** Narrative reports and publication-ready tables generated from approved Layer 1 data.

🛑 **The Hard Gate Rule:** No paper proceeds to Deep Analysis (Phase 2), and the Manuscript Team cannot begin drafting, until a paper passes the Filter Phase (Phase 1) and receives Track Lead Approval.

---

## 📂 Repository Structure

This repository is organized by execution phase to align with the project timeline.

```text
Brain_Tumor_AI_Project_Repository/
│
├── 📁 00_Project_Governance_and_SOPs/         [Day 1 / Ongoing]
│   ├── DVC_Track_Charter.pdf
│   ├── Master_SOP_and_Rulebook.md
│   ├── HANDOFF.md                             ← Full handoff notes (Start here)
│   └── 📁 Meeting_Agendas_and_Minutes/
│
├── 📁 01_Literature_Validation_Track/
│   ├── 📁 01_Phase1_Filter_and_Cleaning/      [Weeks 1-2] (Tabs 1, 2, 3)
│   ├── 📁 02_Phase2_Deep_Analysis/            [Weeks 3-4] (Tabs 4, 5, 6, 7)
│   ├── 📁 03_Phase3_Publication_Ready/        [Week 5] (Final Formatting)
│   ├── 📁 04_Master_Tracker_Backups/          [Weekly Exports]
│   └── 📁 05_Layer2_Exception_Logs/           [Ongoing]
│       └── FINAL_DATA_VALIDATION_SUBMISSION_FORM.docx
│
├── 📁 02_Training_Data_Validation_Track/      [Weeks 1-4 / Parallel]
│   └── (Image QC, Clinical Data, Splits, Dictionaries)
│
├── 📁 03_Final_Handoff_Package/               [Final Week]
│   ├── 📁 For_Manuscript_Writing_Team/
│   └── 📁 For_Modeling_and_Engineering_Team/
│
└── 📁 99_Archive/                             [Ongoing]
    └── Raw_Data_Collection_Team_Dump/
