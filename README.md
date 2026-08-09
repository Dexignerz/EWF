# Hallaniyat Island Project

## 📌 Overview
The Hallaniyat Island Project is a major infrastructure and housing development in Dhofar, Oman. Managed by East Waterfalls Trading & Contracting (EWF) under AMEC Consultant, the project delivers housing units, facilities, and supporting infrastructure.

## 🎯 Objectives
- Deliver housing units and community facilities.
- Ensure compliance with HI Contract Document (May 2019 Rev.01) and Oman Tender Board requirements.
- Maintain quality, safety, and sustainability standards.
- Provide transparent reporting and documentation.

## 🛠️ Repository Structure
- `/Planning` → schedules, BOQs, resource allocation.
- `/Reports` → daily, weekly, monthly progress reports.
- `/Compliance` → Tender Board forms, Oman Standard Documents references.
- `/Automation` → scripts for report generation, resource validation.

## 📑 Rules & Governance
- Branch protection: PRs required before merging.
- Documentation: Every PR must include updated progress reports or compliance checklists.
- Naming convention: `ProjectName_Report_Month_Year` (e.g., `Hallaniyat_MPR_July2026.html`).
- Copilot usage: AI-generated scripts tagged `AI-Suggested` and reviewed before deployment.

## 📊 Reporting
- Monthly Progress Reports uploaded in HTML/PDF format.
- Revised BOQs stored in Google Drive and linked here.
- Earned Value Management tracked via Google Sheets.

## 📌 Stakeholders
- Client: Oman Tender Board
- Consultant: AMEC
- Contractor: East Waterfalls Trading & Contracting (EWF)

## 🚀 Next Steps
- Integrate GitHub Projects with Primavera/Excel schedules.
- Automate compliance workflows for tender submissions.
- Expand Copilot usage for risk logs, meeting minutes, and claim documentation.
Folder Tree
/Planning
    ├── BOQ_Revised_Aug2026.xlsx
    ├── Project_Schedule_P6.mpp
    └── Resource_Allocation.xlsx

/Reports
    ├── Daily_Reports
    ├── Weekly_Reports
    └── Monthly_Reports
        └── Hallaniyat_MPR_July2026.html

/Compliance
    ├── TenderBoard_Form1792.pdf
    ├── Oman_Standard_Documents_2019Rev01.pdf
    └── HSE_Compliance_Policy.docx

/Automation
    ├── report_publish.yml
    ├── boq_validation.yml
    └── teams_notification.yml
