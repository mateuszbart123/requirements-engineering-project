# Week 5 - activity diagram
## Process modelled

I processed the task of booking equipment from a professors point of view towards the behind scene project
## Purpose
it shows how booking seems simple on the outside but there is many parts od the diagram that show there is hidden complexitiy behind the scenes for administration and equipment mechanics that the professor doesnt't see, the purpose was to highlight these various hidden compartments
## Activities
- Administration creates booking in system.
- Professor opens up booking system UI.
- Finds equipment that is needed and selects it.
- Shows when the equipment can be booked and for how much (if available).
- Prevents booking and shows return time before kicking out of the selected equipment (if not available).
- Clicking agree with the data provided, the professor takes the equipment and has a return date.
- Mechanics check on the equipment before handing it over to the professor.
- Administration gets notification that equipment is booked.
- Professor gets notified that the equipment return is overdue and administration gets notified of late returns (if not returned on time).
- Equipment returned late is recorded.
- Mechanics get notified to inspect the equipment after use.
- Administration puts equipment back up on the booking system.
- Availability of equipment is back.


## Decision and guards
- Available? No- prevents booking and shows return time before kicking out of selected equipment Yes- Continue
- Returned on time? No- Professor gets notified that the equipment return is overdue. administration get notified of late returns Yes- continue

## unknown
Equipment returned late is recorded.
If someone booked it at the same time

## stakeholder question
If a student is sent by a professor, should they get the same prvillages to book equipment?


## modelling decision
I put everything downwards as its usally read from up to down in many diffirent forms of media like books, also the idea to only use the only three shapes is to simply the matter and make
it easy to be understood by everyone

## reflection
Diagrams like these help identify alot of the hidden compartments that intially you might not enough is needed until these
