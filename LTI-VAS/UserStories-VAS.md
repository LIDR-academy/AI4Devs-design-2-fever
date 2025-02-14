# User Stories and Backlog

## User Stories [Prompt 1](prompts.md#prompt-1)

User Stories for LTI's Applicant Tracking System (ATS)
### User Story:  
- As a Recruiter, I want to create job postings so that I can attract candidates.
- Estimation: 8 hours
- Acceptance Criteria:
  - Recruiter can fill out a form with job details.
  - Job posting is saved to the database.
  - Job posting is visible on the job board.
### User Story:  
- As a Candidate, I want to apply to job postings so that I can be considered for a position.
- Estimation: 10 hours
- Acceptance Criteria:
  - Candidate can upload a resume and fill out an application form.
  - Application is saved to the database.
  - Candidate receives a confirmation email.
### User Story:  
- As a Hiring Manager, I want to review applications so that I can select suitable candidates for interviews.
- Estimation: 12 hours
- Acceptance Criteria:
  - Hiring Manager can view a list of applications.
  - Applications can be filtered and sorted.
  - Detailed view of each application is available.
### User Story:  
- As a Recruiter, I want to manage applications so that I can track the progress of candidates.
- Estimation: 10 hours
- Acceptance Criteria:
  - Recruiter can update the status of applications.
  - Recruiter can add notes to applications.
  - Application status changes are logged.
### User Story:
- As a Candidate, I want to receive notifications about my application status so that I am informed about the progress.
- Estimation: 6 hours
- Acceptance Criteria:
  - Candidate receives an email notification when the application status changes.
  - Notification includes the current status and next steps.
  - Candidate can opt-in or opt-out of notifications.

## Backlog [Prompt 2](prompts.md#prompt-2)

### Prioritization for MVP

#### Must Have  
- As a Recruiter, I want to create job postings so that I can attract candidates.
- As a Candidate, I want to apply to job postings so that I can be considered for a position.
- As a Hiring Manager, I want to review applications so that I can select suitable candidates for interviews.
#### Should Have
- As a Recruiter, I want to manage applications so that I can track the progress of candidates.
- As a Candidate, I want to receive notifications about my application status so that I am informed about the progress.

This prioritization ensures that the core functionalities are developed first, providing a solid foundation for the ATS while allowing for additional features to be added incrementally.

### Personal opinion

The prioritization is concise and meets the requirements: building an MVP.
However, another option could be starting with the Recruiter point of view, as it's the key member of the system. The rest of interactions can be managed manually or externally.

## Alternative Backlog [Prompt 3](prompts.md#prompt-3)

### Prioritization Based on Cost of Implementation and Risks

#### Must Have
- As a Recruiter, I want to create job postings so that I can attract candidates.
Reason: Low cost of implementation and critical for the system's functionality.
- As a Candidate, I want to apply to job postings so that I can be considered for a position.
Reason: Moderate cost of implementation but essential for user engagement.
- As a Hiring Manager, I want to review applications so that I can select suitable candidates for interviews.
Reason: Higher cost of implementation but necessary for the recruitment process.
#### Should Have:
- As a Recruiter, I want to manage applications so that I can track the progress of candidates.
Reason: Moderate cost and risk, important for tracking but not immediately critical.
- As a Candidate, I want to receive notifications about my application status so that I am informed about the progress.
Reason: Lower cost and risk, enhances user experience but not essential for initial release.

This prioritization ensures that the core functionalities are developed first, considering the cost and potential risks, while allowing for additional features to be added incrementally.

### Personal opinion

This prioritization is just the same as the MVP one. It's true that the first 3 User Stories are totally required to make the system work.
And as said in the previous section, there are some User Stories that can be managed in another way.

## Job tickets [Prompt 4](prompts.md#prompt-4)

### Job Ticket for User Story: "As a Recruiter, I want to create job postings so that I can attract candidates."

**Ticket Type:** Feature

**Title:** Create Job Postings Feature

**Description:**
Goal: Enable recruiters to create job postings to attract candidates.
Specific Details:
- Implement a form for recruiters to input job details (title, description, requirements, etc.).
- Save the job posting to the database.
- Ensure the job posting is visible on the job board.

**Acceptance Criteria:**
- Recruiter can fill out a form with job details.
- Job posting is saved to the database.
- Job posting is visible on the job board.

**Priority:** High

**Estimation:** 8 hours

## Job tickets [Prompt 5](prompts.md#prompt-5)

### Job Tickets for User Story: "As a Recruiter, I want to create job postings so that I can attract candidates."

**Ticket Type:** Feature

**Title:** Create Job Postings Form

**Description:**
Goal: Enable recruiters to input job details.
Specific Details:
- Implement a form for recruiters to input job title, description, requirements, and other relevant details.

**Acceptance Criteria:**
- Recruiter can fill out a form with job details.
- Form fields include job title, description, requirements, and other relevant details.
- Form validation ensures all required fields are filled.

**Priority:** High

**Estimation:** 4 hours

---

**Ticket Type:** Feature

**Title:** Save Job Postings to Database

**Description:**
Goal: Store job postings in the database.
Specific Details:
- Implement backend logic to save job postings from the form to the database.

**Acceptance Criteria:**
- Job posting data is saved to the database upon form submission.
- Confirmation message is displayed to the recruiter after successful save.

**Priority:** High

**Estimation:** 3 hours

---

**Ticket Type:** Feature

**Title:** Display Job Postings on Job Board

**Description:**
Goal: Make job postings visible to candidates.
Specific Details:
- Implement frontend logic to display job postings on the job board.

**Acceptance Criteria:**
- Job postings are visible on the job board.
- Job postings display all relevant details (title, description, requirements).

**Priority:** High

**Estimation:** 3 hours

---

**Ticket Type:** Technical Task

**Title:** Database Schema for Job Postings

**Description:**
Goal: Define the database schema for storing job postings.
Specific Details:
- Create a database table with fields for job title, description, requirements, and other relevant details.

**Acceptance Criteria:**
- Database table for job postings is created.
- Table includes fields for job title, description, requirements, and other relevant details.

**Priority:** High

**Estimation:** 2 hours

---

**Ticket Type:** Technical Task

**Title:** API Endpoint for Job Postings

**Description:**
Goal: Create an API endpoint to handle job postings.
Specific Details:
- Implement an API endpoint to receive job posting data from the frontend and save it to the database.

**Acceptance Criteria:**
- API endpoint is created and accessible.
- Endpoint successfully saves job posting data to the database.

**Priority:** High

**Estimation:** 4 hours

## Effort Estimation [Prompt 6](prompts.md#prompt-6)

### Effort Estimation Using Fibonacci Methodology

**Ticket Type:** Feature

**Title:** Create Job Postings Form
- **Estimation:** 5 hours (Fibonacci: 5)

**Ticket Type:** Feature

**Title:** Save Job Postings to Database
- **Estimation:** 3 hours (Fibonacci: 3)

**Ticket Type:** Feature

**Title:** Display Job Postings on Job Board
- **Estimation:** 3 hours (Fibonacci: 3)

**Ticket Type:** Technical Task

**Title:** Database Schema for Job Postings
- **Estimation:** 2 hours (Fibonacci: 2)

**Ticket Type:** Technical Task

**Title:** API Endpoint for Job Postings
- **Estimation:** 5 hours (Fibonacci: 5)

## Effort Estimation Table [Prompt 7](prompts.md#prompt-7)

| Ticket Type     | Total Effort (hours) |
|-----------------|----------------------|
| Feature         | 11                   |
| Technical Task  | 7                    |
| **Total**       | **18**               |

This table summarizes the total effort required for each type of ticket based on the Fibonacci methodology estimations.
