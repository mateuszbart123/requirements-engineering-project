# 4.1 Problem, Stakeholders and Goals
## 1. Current Situation.

A community organisation manages many sport facilities, they currently use a booking system that consists of a combination of phone calls, emails, spreadsheets and calenders. They are considering software system to improve the booking systems

## 2. Problems
- Bookings are conflicted within the system
- There is difficulty checking availability of facilities
- There are cancellations and no-shows that confuse booking further
- Staff needs to spend time answering the booking queries manually
- Information struggles to be up to date
- Diffrent sport facilities have a diffrent rule set
- User data needs to be protected at all times
- There is accessibility and usability concerns with the current system

## 3. stakeholders and how they are affected
| Stakeholder | How? | 
| :--- | :--- |
| Users | Accessibility and usability issues harden users experience for those not fully capable. Cancelling, up-to-date information and availability diffculties make it hard to for users to plan ahead .
| Staff | Manually checking bookings through multiple methods is time consuming. Having inaccurate information will cause conflicting bookings to be placed. User date might be exposed to staff which isn't ethical.
| Facility maintenance | Cancellitions and no-shows cause wasted effort on cleaning before arrival. Diffrent rules cause maintence to differ in time and quality.
| Community Organisation | Having conflicting bookings messes with finances.
| Administration | Need to be more efficient with staff taking more time. The need to focus on data deletion of user information.

## 4. Stakeholder needs and concern
| Stakeholders | Needs | Concerns |
| :--- | :--- | :--- |
| Users | Ability to book sport facilities | Users will have difficulty trying to book
| Staff | To manage bookings efficiently | System will be inefficent and hard to operate
| Facility maintenance | Know certainly when people come and have rules for cleaning | Operations may be wasteful if cancelled
| Community Organisation | Manage staff and finances | Staff are inefficient and will need more hiring that squeezes finance
| Administration | Manage User data and staff within facilities | User data will be stored forever and staff may be unable to operate faster
## 5. goals of proposed system
- Prevent conflicting bookings
- make it more user accessible and usable
- Booking for staff becomes automatic
- Information will be up to date
- User data will be deleted upon finished order
- Unified rules for booking
- Availability will be visible clearer
## 6. Scope of system
- Unification of booking methods
- Up-to-date database connect to system
- User accessibility options
- Staff and User versions of system
- Quick editing power of bookings for staff
- Notification system for when a booking is confirmed to facility maintenance

## 7. Important assumptions and unknows
| Assumptions | Results |
| :--- | :--- |
| Internet Access | If internet goes down, staff won't be able to manage the system
| Device Access | Devices breaking would cause the system to be unable to be accessed
| Digital Literacy | Staff would need training in the system to operate it efficiently
| Cut-off times | A one day limit for cancellations to prevent wasteful cleaning
| Data laws | Would have to follow GDPR laws seriously

| Unknowns | Results |
| :--- | :--- |
| Hosting | Will the system be hosted in the organisation or outsourced?
| No-show Penilities | What happens if someone decides to not show up multiple times, will penalties apply?
| Language support | For international groups, will there be support for diffrent languages?
| Rules differences | How wildly do rules differ between facilities?
| Data deletion | How much of a window is there to delete data?

## 8. Areas where further information would be useful
- Legal data retention time window
- Time slot of each facilities
- User verification
- Refund policies
- Usability laws to see what is required

# 4.2 Requirement

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR01 | The system shall prevent conflicting bookings by blocking used time slots | Must | Problems stated | One of the main issues from the last system and also the biggest impact on both staff and user | Automated system testing trying to book the identical slots |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR02 | The system shall unique UI versions to staff and the user | Must | Scope of system | Having separate versions where staff can edit and user can only book keeps power balance | Log into the system using a User account and check if they have admin access |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR03 | The system shall notify staff facility meaintanace of a booking | High | User expereiance | Allows Facility maintenance to know when they need to get cleaning | Reserve a time slot and check facility maintanace email inbox to see if a notification arrived |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR04 | The system shall have real-time updates of facility availibility | Must | Problem stated | Removes the issue of not having up-to-date information of availibity | Use user view and book a test timeslot to see if it instantly turns booked |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR05 | The system shall allow users to cancell their bookings through their own system | Must | Problem stated | Eliminates confusion around cancelling bookings and also reduces staff manual work needed | Cancel a test timeslot to see if it becomes available to be booked again |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR06 | The system shall enforce unified rules accross every facility in the app | Must | Problem stated | Handles the problem of diffirent facilities having diffirent rulesets for simplicity | Try to book a facility while trying to break hours allowed timeslot to see if system blocks it |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR07 | The system shall provide an admin dashboard for staff | Must | Scope of system | This solves having multiple systems for staff to quickly make edits, cancellations or bookings within the system | Log into staff account and try to edit a booking that was made |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR08 | The system shall flag accounts that do multiple cancellations | Medium | Unknowns | This would prevent people from wasting facility resources by flagging them as frequent cancellations | Have a test account book three times and cancel each time to see if system flags |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| FR09 | The system shall provide text-to-speech and UI constrasts for ease of use | High | Problem stated | This would solve the hard to use UI while also becoming more accessible for everyone | Have someone test the various UI options to see if texts and images change |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR01 | The system shall completelty comply with EU/Irish GDPR laws | Must | Assumption | assesses the strict laws regrading data within the country to prevent legal breaches | Rewview system documenation to ensure compliance |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR02 | The system page should load in under two seconds | High | Assumption | Stops users from frustration and minimizes staff waiting time | Run stress tests on the page and optimise until the page loads under two seconds |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR03 | The system shall automatically delete user transaction data within 24 hours after booking is finished | Must | Unknown | Satisfies both retention time and also user safety | Run a test booking in the database then remove it and wait 24 hours |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR04 | The system encrypt all sensitive user data | Must | Problem stated | Avoids unethical data exposure to staff and ensures user data safety | Intercept data during a transaction to see if it's encrypted |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR01 | The system shall be easy to have a toggle between english and irish | High | Unknowns | This makes sure that the targetted local area is supported | try out the change language button to see if text and images translate well |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| BR01 | The system shall block any attempts of cancellation if there is less than 24 hours remaining | Must | Assumptions | Stops facility maintence from wasting time and also prevents money issues with user knowing the cut-off window | Have a test booking try to be cancelled a hour before arrival |

| ID | Requirements | Priority | Source | Rationale | Verification |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NR01 | The system shall be easy to have a toggle between english and irish | High | Unknowns | This makes sure that the targetted local area is supported | try out the change language button to see if text and images translate well |
| BR01 | The system shall block any attempts of cancellation if there is less than 24 hours remaining | Must | Assumptions | Stops facility maintence from wasting time and also prevents money issues with user knowing the cut-off window | Have a test booking try to be cancelled a hour before arrival |

