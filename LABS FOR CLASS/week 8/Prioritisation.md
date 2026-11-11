# Week 8 — Requirements and Prioritisation

## A. Evidence Check

### Confirmed facts
- Students can make more than one booking request.
- Each request is for one piece of equipment.
- Each booking has a start and end date.
- Staff review requests and approve or reject them.

### Open questions
- Do students get notified when their request is approved or rejected?
- What happens if two students request the same equipment for the same dates?

### Prototype changes
- Show "Submitted for review" after a student sends a request.
- Only show "Approved" once a staff member approves it.
- Make it clear whether a request is pending, approved or rejected.

## B. Requirements Catalogue

| ID | Requirement | Type | Priority | Source | Reason | How to test |
|---|---|---|---|---|---|---|
| FR01 | The system shall allow students to request one piece of equipment for selected dates. | FR | Must | Case study | Main system feature | Test the booking process |
| NFR-C01 | With 50 users using the system, 95% of booking requests should finish within 3 seconds. | NFR | Provisional | Proposed | The system should be fast. | Performance test |
| NFR-C02 | Students should be able to complete a booking using only a keyboard. | NFR | Provisional | Proposed | Makes the system easier to access. | Keyboard test |

## C. Non-Functional Requirements

| ID | Proposed requirement | Evidence needed | How to test |
|---|---|---|---|
| NFR-C01 | With 50 users using the system, 95% of booking requests should finish within 3 seconds. | Agree on performance targets with staff. | Run a performance test. |
| NFR-C02 | Students shall be able to complete a booking using only a keyboard. | Check accessibility needs. | Test keyboard navigation using WCAG 2.2 SC 2.1.1. |
| NFR-C03 | Only authorised staff shall be able to view student booking details. | Confirm staff access permissions. | Test different user accounts. |

**Source:** [PROPOSED — confirm with stakeholders]

### Quick checklist
- [ ] Each requirement has one main purpose.
- [ ] Requirements are clear.
- [ ] Requirements can be tested.
- [ ] Conditions are included.
- [ ] Stakeholder approval is still needed.

## D. MoSCoW Prioritisation

| Item | Priority | Reason |
|---|---|---|
| Student submits a request | Must | This is the main purpose of the system. |
| Staff approves or rejects requests | Must | Staff need to review bookings. |
| Reminder notifications | Unconfirmed | We don't know if reminders are needed. |
| Automatic conflict prevention | Unconfirmed | We need to ask staff how booking clashes should work. |

Automatic approval is not a Must because staff are responsible for making the decision.

## E. Campus Workshop Registration

### Candidate requirement
- NFR-C04: The system shall show workshop capacity when students view workshop details.
- Source: [PROPOSED — confirm with stakeholders]
- Test: Check that the displayed capacity matches the workshop information.

### Main requirements
- Must: Students can view available workshops.
- Must: Students can request a place on a workshop.
- Proposed: Students receive an update after staff review their registration.

### Questions for the coordinator
1. What happens when more students apply than there are available places?
2. How quickly should workshop information load?

## F. Review and Traceability

### Traceability table

| User need | Requirement | Prototype screen | How to test |
|---|---|---|---|
| Students need to book equipment | FR01 | Booking form | Submit a booking request |
| Students need to know their booking status | Booking status requirement | Confirmation screen | Check the status displayed |
| Staff need to manage requests | Staff review requirement | Staff dashboard | Test approving and rejecting requests |

### Verification and Validation
- Verification: Checking that requirements are clear and can be tested.
- Validation: Checking that requirements are what users actually need.
- Validation is still outstanding because we have not received real stakeholder feedback.

### Improving a weak requirement
- Original: The system should be easy to use.
- Improved: Students shall be able to complete a booking using only a keyboard.

## G. My Project Updates
**Section 6 – Prioritisation and Change:** Explain two Must/Should/Could decisions and why I chose them.
This should be completed following this lab
