-End-to-End HR Process Automation Using UiPath
This project presents an intelligent HR automation system developed using UiPath that streamlines the entire recruitment lifecycle — from collecting resumes to onboarding selected candidates. The solution eliminates repetitive manual tasks, improves accuracy, and boosts efficiency across HR workflows.

- Key Workflow Overview
Resume Collection from Email

Automatically fetches incoming job application emails.

Downloads attached resumes to the designated Resumes/ folder.

Automated Resume Screening

Extracts candidate information (Name, Email, Skills, Degree, Experience).

Uses regex, OCR, and NLP-based scoring to evaluate candidate fit.

Generates a ranked list of candidates in Output/CandidateScores.xlsx.

Automatic Interview Scheduling

Automatically sends interview invites to shortlisted candidates via Outlook.

Allows HR to review and finalize interview time slots within Outlook Calendar.

Selection and ID Card Generation

Generates employee ID cards for selected candidates using UiPath’s document automation.

Stores output in the Output/IDCards/ directory.

ERP Data Upload

Updates candidate details (Name, Role, Joining Date, Employee ID, etc.) directly into the organization’s ERP system using UI or API automation.

Ensures centralized recordkeeping and seamless onboarding.

- Technologies Used
UiPath Studio – Automation development and orchestration

UiPath Mail Activities – Email reading and attachment handling

Regex & OCR – Resume text extraction and structured parsing

Excel Automation – Ranking and reporting of candidates

Outlook Integration – Interview scheduling and communication

ERP Automation – Data upload through UI or API integration

Document Generation – ID card creation for selected candidates

- Output Summary
  
- | Process Stage        | Output File            | Description                                 |
|----------------------|------------------------|---------------------------------------------|
| Resume Screening     | CandidateScores.xlsx    | Ranked list of applicants with final scores|
| Interview Scheduling | InterviewInvites.log    | Status of email invites sent                |
| ID Card Generation   | IDCards/ folder         | Auto-generated employee ID PDFs             |
| ERP Upload           | UploadLog.xlsx          | Confirmation of successful ERP entries      |

- Future Enhancements
  
AI-powered virtual interview assistants for sentiment and communication analysis

Self-learning bots improving candidate screening dynamically through machine learning

Blockchain integration for instant, secure credential verification

Intelligent candidate engagement chatbots providing real-time personalized communications
