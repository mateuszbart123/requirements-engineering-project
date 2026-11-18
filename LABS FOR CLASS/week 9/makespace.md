# Week 9 - From software process to a defensible Agile backlog

## Establish facts and unanswered questions

- F01: Residents want to browse workshops by topic and date
- F02: Residents want to be able to submit a request for One workshop
- F03: Workshop organiser reviews each request
- F04: Centre manager confirms policies
- F05: Group reservations, automated reminders and cancellations are not yet agreed
- F06: A resident submission doesn't guarantee a place


- Unknown 1: group booking, can you book for people and is there a limit of amount of people? Centre manager
- Unknown 2: cancellation, will there be a time limit or fee? Centre manager
- Unknown 3: reminders, will they use text messages or email? workshop organiser

  Scope exclusion: online payment is not in the scope for this system.
## Connect process and RE work
<img width="501" height="685" alt="image" src="https://github.com/user-attachments/assets/27479743-d1d2-4d5b-abdb-4956a1e67622" />

## Prepare a Mini Requirements Catalogue

| ID | Draft Requirement / Status | Actor | Source | How to Check |
|---|---|---|---|---|
| FR01 | Residents must be able to browse and filter workshops by topic and date. | Resident | Case description | Test that residents can filter the workshops by different topics and dates. |
| FR02 | Residents must be able to view the workshop title, venue, date and remaining places. | Resident | Case description | Open a workshop and check that all four details are displayed correctly. |
| FR03 | Residents must be able to submit a request for ONE place at a selected workshop using their name and contact email. (Supported) | Resident | Case description | Submit a request and check that the resident's name, email and selected workshop are recorded. |
| FR04 | Workshop organisers must be able to review requests and approve or reject them. | Workshop Organiser | Case description | Submit a request and check that the organiser can approve or reject. |
| FR05 | Workshop organisers must be able to maintain workshop details. | Workshop Organiser | Case description | Check that the organiser can update workshop information. |
| NFR-C01 | The system should be easy for residents to understand and navigate when browsing workshops and submitting requests. | Resident | Suggested quality requirement requiring stakeholder approval | Ask residents to complete basic tasks and collect feedback. |

## 4. Write Stories and Testable Criteria

### Story 1 – Browsing and Filtering Workshops (FR01)

As a resident and user of this workshop, I want the ability to browse and filter workshops by topic and date so that I can find workshops that interest me and not general workshops.

### Acceptance Criteria

1. Given that there are workshops available, when a resident opens the workshop list, then the system will display available workshops.
2. Given that a resident selects a topic or date, when they apply the filter, the system will display workshops matching the selected filter they inputted.

### Story 2 – Submit a Workshop Request (FR03)

As a resident, I want the ability to submit a request for one workshop place using my information so that I can request to attend the workshop.

### Acceptance Criteria:

1. Given that a resident has selected a workshop, when the resident enters their name and contact email and then submits the request, then the system will record the request.
2. Given that a resident submits a request, when the request has been recorded, then the system will make it available for the workshop organiser to review.

### Story 3 – Approve or Reject Requests (FR04)

As a workshop organiser, I want to review workshop requests and also approve or reject them so that I can manage attendance requests easily.

### Acceptance Criteria:

1. Given that a resident has fully submitted a request, when the organiser approves it, then the system will record the request as approved.
2. Given that a resident has fully submitted a request, when the organiser rejects it, then the system will record the request as rejected.


## 5. Build a Prioritised Product Backlog

| Order | ID | Item / Story | Status | Priority | Rationale |
|---|---|---|---|---|---|
| 1 | FR01 | Residents can browse and also filter workshops by topic and date. | Supported | High | Residents need to find workshops that interest them personally. |
| 2 | FR03 | Residents can submit a request for one workshop place. | Supported | High | This is the main purpose of the booking request service described. |
| 3 | FR04 | Organisers can review and also approve or reject workshop requests. | Supported | High | Organisers need to manage requests and decide who receives a place to ensure quality. |
| 4 | FR02 | Residents can view workshop titles, venues, dates and remaining places. | Supported | Medium | Residents need workshop information before submitting a request. |
| 5 | FR05 | Organisers can maintain workshop details easily. | Supported | Medium | Organisers need to keep workshop information up to date. |
| 6 | C01 | Allow residents to make group reservations together. | Candidate - Unapproved | Future consideration | The centre manager must decide whether group bookings are allowed. |
| 7 | C02 | Introduce cancellation arrangements for workshop places. | Candidate - Unapproved | Future consideration | The centre manager must confirm cancellation rules and any deadlines or fees. |
| 8 | C03 | Introduce automated workshop reminders. | Candidate - Unapproved | Future consideration | The reminder and arrangements need to be agreed with the relevant stakeholders. |

### Justification for the First Two Priorities

FR01 is the highest priority because residents need to be able to find and browse workshops before they can request a place. Otherwise residents would struggle to discover workshops that interest them.

FR03 is the second priority because submitting a request is the main purpose of the proposed service. It allows residents to request a place at workshops.
