
# Week 8 — Measurable Requirements and Prioritisation

## A. Evidence Check

### Confirmed facts
- Students can submit multiple booking requests.
- Each request concerns exactly one equipment item.
- Booking records contain start and end dates.
- Staff review and approve or reject requests.

### Open questions
- Are students notified when requests are approved or rejected?
- How are overlapping booking requests handled?

### Prototype updates
- Show "Submitted for review" after submission.
- Only show "Approved" after staff approval.
- Clearly display pending, approved and rejected statuses.

## B. Requirements Catalogue

| ID | Statement | Type | Priority | Source | Rationale | Verification |
|---|---|---|---|---|---|---|
| FR01 | The system shall allow students to submit a request for one equipment item and requested dates. | FR | Must | Lecturer case | Core task | Walkthrough |
| NFR-C01 | With 50 concurrent users, 95% of booking requests shall complete within 3 seconds. | NFR | Provisional | Proposed | Performance | Load testing |
| NFR-C02 | Students shall be able to complete a booking request using keyboard-only navigation. | NFR | Provisional | Proposed | Accessibility | Keyboard walkthrough |

## C. Measurable NFR Candidates

| ID | Proposed requirement | Evidence needed | Verification |
|---|---|---|---|
| NFR-C01 | Under 50 concurrent users, 95% of booking requests shall complete within 3 seconds. | Stakeholder agreement on performance targets. | Load testing |
| NFR-C02 | Students shall complete the booking journey using keyboard-only navigation. | Accessibility requirements. | WCAG 2.2 SC 2.1.1 walkthrough |
| NFR-C03 | Only authorised staff shall access student booking details. | Access permissions and privacy policy. | Access-control testing |

**Source for all:** [PROPOSED — confirm with stakeholders]

### Verification checklist
- [ ] Single concern per requirement.
- [ ] Clear and measurable outcome.
- [ ] Conditions identified.
- [ ] Source recorded.
- [ ] Objective test available.
- [ ] Stakeholder confirmation required.

## D. MoSCoW Prioritisation

| Item | Priority | Justification |
|---|---|---|
| Student submits request | Must | Essential core functionality supported by the case. |
| Staff approves/rejects | Must | Explicitly required by the scenario. |
| Reminder notification | Unconfirmed | No evidence that reminders are required. |
| Automatic conflict prevention | Unconfirmed | Overlapping-date handling needs clarification. |

Automatic approval is not a Must because staff make the approval decision.

## E. Campus Workshop Registration

### Candidate quality requirement
- NFR-C04: The system shall display workshop capacity information when a student views workshop details.
- Source: [PROPOSED — confirm with stakeholders]
- Verification: Check displayed capacity against workshop records.

### Core capabilities
- Must: Students can view available workshops.
- Must: Students can request a workshop place.
- Proposed: Students receive confirmation after staff review.

### Coordinator questions
1. What happens when registration requests exceed workshop capacity?
2. What response time should users expect when viewing workshops?

## F. Review, Consistency and Traceability

### Traceability

| Stakeholder need | Requirement | Prototype screen | Verification |
|---|---|---|---|
| Student requests equipment | FR01 | Booking form | Submit request walkthrough |
| Student understands request status | NFR-C02 | Confirmation screen | Keyboard accessibility test |
| Staff controls bookings | Staff review requirement | Staff dashboard | Approval/rejection walkthrough |

### Verification vs Validation
- Verification: Check requirements are clear, measurable and testable.
- Validation: Confirm requirements meet stakeholder needs.
- Validation status: Outstanding — stakeholder feedback required.

### Requirement revision
- Weak: The system shall be easy to use.
- Improved: Students shall be able to complete the booking journey using keyboard-only navigation.

## G. Individual Project Updates

- Section 2: Add or refine two measurable NFRs.
- Section 5: Explain why those same NFRs matter.
- Section 6.1: Justify two Must/Should/Could decisions.
- Section 1.5: Record remaining assumptions and stakeholder questions.
- Keep the catalogue around 15–25 FRs/NFRs.
- Commit updated documentation to GitHub.
