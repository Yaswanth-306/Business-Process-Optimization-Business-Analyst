# Business Requirements Document (BRD) - Loan Process Optimization

## 1. Functional Requirements (FR)
These requirements define the specific behaviors and functions the new Loan Origination System (LOS) must perform to address current process gaps.

### 1.1 Digital Intake & Data Management
* **FR-01: Customer Portal:** The system shall provide a secure web portal for customers to submit loan applications and upload supporting documentation digitally.
* **FR-02: Automated Data Extraction (OCR):** The system shall use Optical Character Recognition (OCR) to automatically extract data from uploaded IDs and financial statements, reducing manual entry.
* **FR-03: Real-time Validation:** The system shall instantly validate that all required fields and documents are present before allowing a submission.

### 1.2 Workflow & Decisioning
* **FR-04: Automated Routing:** The system shall automatically route completed applications to the Credit and Compliance work queues simultaneously.
* **FR-05: Integrated Risk Scoring:** The system shall calculate risk metrics and credit scores using pre-defined internal logic, eliminating the need for external Excel calculations.
* **FR-06: Digital Approvals:** The system shall support digital approval signatures and record time-stamped audit trails for every decision made by Underwriters or Compliance officers.

### 1.3 Communication & Integration
* **FR-07: Automated Notifications:** The system shall trigger automatic email and SMS updates to the customer and RM at each stage of the process.
* **FR-08: Core Banking Integration:** The system shall automatically push data for approved loans to the Core Banking System to activate accounts and disburse funds.
* **FR-09: Status Dashboard:** The system shall provide a real-time dashboard for Relationship Managers and Leadership to track the status of all applications in the pipeline.

---

## 2. Non-Functional Requirements (NFR)
These requirements define the operation of the system and the quality of the user experience.

### 2.1 Performance & Efficiency
* **NFR-01: Processing Speed:** The system shall support a target reduction in Turnaround Time (TAT) from 14 days to a maximum of 5 business days.
* **NFR-02: Availability:** The LOS and Customer Portal shall be available 99.9% of the time during standard business hours.

### 2.2 Security & Compliance
* **NFR-03: Data Security:** All data at rest and in transit must be encrypted in accordance with Union Bank’s security policies.
* **NFR-04: Regulatory Compliance:** The system must adhere to all local banking regulations and maintain a complete audit log for all manual interventions.

### 2.3 Reliability
* **NFR-05: Data Consistency:** The system shall ensure data integrity across all modules, preventing the data discrepancies currently caused by manual handoffs.
* **NFR-06: Error Rate:** The system shall aim for a 0% error rate in automated disbursement triggers through robust integration testing.

---

## 3. Requirement Traceability Matrix (Preview)

| Requirement ID | Pain Point Addressed | Business Objective |
| :--- | :--- | :--- |
| **FR-01 / FR-02** | Manual Data Entry | Reduce TAT & Human Error |
| **FR-05** | Spreadsheet Reliance | Centralize Risk Analysis |
| **FR-09** | Lack of Visibility | Improve Process Transparency |
| **FR-06 / NFR-04** | Email Approvals | Enhance Auditability & Compliance |
