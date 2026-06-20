# Lead Intake Routing System

A lead is only useful if the business captures the right information and routes it to the right next step.

The Lead Intake Routing System is a Tokra AI workflow for turning messy inbound inquiries into structured, qualified, and trackable opportunities.

This system is useful for service businesses, law firms, healthcare practices, sales teams, agencies, real estate teams, and operator-led companies with inbound demand.

## Revenue leak

A prospect calls, fills out a form, sends an email, or messages the business.

The business captures the basic contact information but misses the details that determine priority, fit, urgency, and next action.

Common intake problems:

* Only name and phone number are captured
* No urgency level
* No job type or issue type
* No service area or location
* No budget or timeline
* No decision-maker status
* No lead source
* No next step
* No clean handoff to sales or operations
* No CRM update

This creates a hidden revenue leak.

The lead technically entered the business, but the business does not have enough structure to act on it cleanly.

## System goal

The goal is to convert raw inbound demand into structured lead records that can be routed, prioritized, followed up on, and measured.

The system should answer:

* Who is the prospect?
* What do they need?
* How urgent is it?
* Where are they located?
* What service or offer fits?
* Are they qualified?
* Who should handle the next step?
* What should happen next?
* Was the CRM updated?
* Can the owner see the lead status?

## Basic workflow

1. Lead enters through phone, form, email, chat, or social DM
2. System captures contact details
3. System asks structured intake questions
4. Lead is categorized by issue type, service line, urgency, location, and fit
5. Lead receives an acknowledgment message
6. Lead is routed to the right owner, rep, department, or queue
7. CRM record is created or updated
8. Follow-up task is created
9. High-priority leads are escalated
10. Owner dashboard updates intake and routing status

## Intake fields

Core fields:

* Full name
* Phone number
* Email address
* Company name, if B2B
* Service needed
* Issue type
* Urgency level
* Location or service area
* Preferred contact method
* Preferred callback time
* Lead source
* Notes

Qualification fields:

* Timeline
* Budget range, if appropriate
* Decision-maker status
* Current provider or current solution
* Problem severity
* Desired outcome
* Prior conversation history
* Existing customer status
* Fit score

Routing fields:

* Assigned owner
* Department
* Priority level
* Next step
* Follow-up due date
* CRM stage
* Escalation status

## Example intake prompt

Thanks for reaching out. To route this correctly, can you share:

1. What issue are you trying to solve?
2. How urgent is it?
3. What city or ZIP code is this for?
4. What is the best callback time?
5. Are you the decision-maker for this request?

## Routing logic

### High-priority lead

Route immediately when:

* Urgency is high
* Timeline is immediate
* Job value appears high
* Customer is existing or high-value
* Legal, medical, or operational deadline exists
* Lead matches ideal customer profile

Route to:

* Owner
* Sales rep
* Office manager
* Service manager
* Intake specialist

### Standard qualified lead

Route to:

* Sales queue
* Booking queue
* Office follow-up
* Next available rep
* CRM pipeline

### Low-fit or unclear lead

Route to:

* Qualification queue
* Manual review
* Nurture sequence
* Referral process
* No-fit response

## CRM update

Every lead should create or update a CRM record with:

* Contact information
* Source
* Issue type
* Urgency
* Service category
* Location
* Qualification notes
* Assigned owner
* Next action
* Follow-up due date
* Current status

## Owner visibility

The owner should be able to see:

* Total new leads
* Leads by source
* Leads by urgency
* Leads by service type
* Leads waiting for follow-up
* Leads with missing intake fields
* Leads not assigned to anyone
* Leads that became booked appointments
* Leads that went cold
* Intake completion rate

## Common failure points

* Intake asks too many questions and hurts conversion
* Intake asks too few questions and creates weak handoffs
* Lead gets routed to the wrong person
* CRM record is missing key fields
* Follow-up task is not created
* High-priority lead is not escalated
* Owner cannot see stuck leads
* Team ignores the system and works from memory

## Success metrics

Track:

* New leads captured
* Intake completion rate
* Average response time
* Leads routed correctly
* Leads with missing fields
* Leads assigned to owner or rep
* Follow-up tasks created
* Booked appointments
* Conversion from lead to booked call
* Lost leads by reason
* Revenue by lead source

## Tokra principle

A lead is not just a name and phone number.

A real lead has context, urgency, ownership, and a next step.

The system should make every inbound opportunity easier to understand, easier to route, and harder to lose.

Find Leaks. Fix Follow-Up. Scale Cleaner.
