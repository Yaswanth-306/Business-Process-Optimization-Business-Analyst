# User Stories - Loan Process Optimization

These user stories define the requirements for the new Loan Origination System (LOS) and Customer Portal, focusing on the persona-based needs identified in the TO-BE process.

## 1. Customer Persona
* **Story:** As a loan applicant, I want to upload my financial documents directly to a secure portal so that I don't have to visit a branch or send sensitive data via email.
* **Acceptance Criteria:** * Portal supports PDF and JPEG uploads.
    * Real-time confirmation message is displayed upon successful upload.

## 2. Relationship Manager (RM) Persona
* **Story:** As an RM, I want a centralized dashboard to track the status of my clients' applications so that I can provide accurate updates without calling the Credit team.
* **Acceptance Criteria:**
    * Dashboard shows "In-Progress," "Pending Info," and "Approved/Rejected" statuses.
    * System triggers auto-notifications to RMs when a milestone is reached.

## 3. Credit & Compliance Personas
* **Story:** As a Credit Analyst, I want the system to automatically flag missing documents so that I only review complete applications.
* **Acceptance Criteria:**
    * Application is blocked from the Credit queue if mandatory fields are empty.
    * System highlights extracted OCR data for quick verification.

---

## Gap Analysis Summary (AS-IS vs. TO-BE)

| Feature | AS-IS Method | TO-BE Solution |
| :--- | :--- | :--- |
| **Data Intake** | Manual entry into LAR | Automated OCR Extraction |
| **Validation** | Manual RM Check | System-driven Completeness Check |
| **Communication** | Email-based | Automated System Notifications |
| **Closing** | Physical/Manual Signing | Integrated E-Signatures |
