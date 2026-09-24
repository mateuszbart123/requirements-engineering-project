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


