# Quote Follow-Up Recovery System

A quote is not closed just because it was sent.

A quote is only useful if the business tracks it, follows up on it, and knows whether the buyer moved forward, stalled, or disappeared.

The Quote Follow-Up Recovery System is a Tokra AI workflow for helping businesses recover revenue from estimates, proposals, and quotes that would otherwise go cold.

This system is useful for contractors, service businesses, agencies, professional services firms, sales teams, and any operator-led business where revenue depends on timely quote follow-up.

## Revenue leak

A prospect requests a quote.

The quote gets created.

Then the follow-up breaks down.

Common problems:

* Quote is sent late
* Quote is never sent
* Quote is sent but not tracked
* Sales rep forgets to follow up
* Customer says they need time but no task is created
* Owner cannot see stale quotes
* CRM stage is wrong
* No close reason is recorded
* No second or third follow-up happens

This creates a quote leakage problem.

The buyer showed enough intent to ask for pricing, but the business did not protect the next step.

## System goal

The goal is to make every quote trackable, follow-up-ready, and visible.

The system should answer:

* Who received a quote?
* When was it sent?
* What was the quote value?
* Who owns the follow-up?
* Has the customer responded?
* Is the quote stale?
* What is the next action?
* Did the CRM get updated?
* Can the owner see open quote risk?

## Basic workflow

1. Quote is requested
2. Quote record is created
3. Quote is assigned to an owner
4. Quote is sent to the prospect
5. Follow-up timer starts
6. System creates follow-up tasks
7. Customer response is tracked
8. Stale quotes trigger alerts
9. CRM stage is updated
10. Owner dashboard shows quote status and aging

## Quote fields

Core fields:

* Customer name
* Phone number
* Email address
* Company name, if B2B
* Quote requested date
* Quote sent date
* Quote value
* Service or product quoted
* Sales owner
* Quote status
* Follow-up due date
* Last contact date
* Next step
* Close reason
* Notes

Status fields:

* Quote requested
* Quote in progress
* Quote sent
* Follow-up due
* Customer responded
* Waiting on customer
* Won
* Lost
* Stale
* Needs owner review

## Follow-up sequence

Example follow-up flow:

### Day 0

Quote is sent.

System logs the sent date and creates a follow-up task.

### Day 1

First follow-up.

Message goal: confirm the prospect received the quote and ask if they have questions.

### Day 3

Second follow-up.

Message goal: ask if they want to move forward or adjust scope.

### Day 7

Third follow-up.

Message goal: create urgency, offer help, and confirm whether the project is still active.

### Day 14

Stale quote review.

Message goal: ask for a clear close, next step, or reason for delay.

## Example follow-up message

Hi, just checking that you received the quote we sent over.

Do you have any questions, or would you like help deciding the next step?

## Routing logic

### High-value quote

Route to:

* Owner
* Sales manager
* Senior rep
* Manual review queue

Trigger owner visibility when:

* Quote value is high
* No response after first follow-up
* Quote is older than 7 days
* Customer had high urgency
* Customer is an existing account

### Standard quote

Route to:

* Assigned sales rep
* Follow-up task queue
* CRM pipeline

### Stale quote

Route to:

* Recovery sequence
* Owner dashboard
* Manual review
* Lost reason request

## CRM update

Every quote should update the CRM with:

* Quote value
* Quote sent date
* Assigned owner
* Quote status
* Follow-up due date
* Last follow-up date
* Next step
* Close reason
* Revenue outcome

## Owner visibility

The owner should be able to see:

* Total open quotes
* Total quoted revenue
* Quotes sent this week
* Quotes waiting for follow-up
* Quotes older than 7 days
* High-value stale quotes
* Quotes won
* Quotes lost
* Close rate
* Average quote response time
* Revenue stuck in open quotes

## Common failure points

* Quote is sent but no follow-up task is created
* Follow-up depends on memory
* CRM is not updated
* No one owns quote recovery
* Quotes go stale with no alert
* Owner only sees revenue after it is already lost
* Lost reasons are not captured
* Sales team treats quote sending as the finish line

## Success metrics

Track:

* Quotes requested
* Quotes sent
* Quote send time
* Quote value
* Follow-up completion rate
* Stale quotes
* Quote response rate
* Won quotes
* Lost quotes
* Close rate
* Revenue recovered from follow-up
* Average time from quote sent to decision

## Tokra principle

A quote is not the end of the sales process.

It is a high-intent moment that needs structure.

The system should make sure every quote has ownership, follow-up, status, and visibility.

Find Leaks. Fix Follow-Up. Scale Cleaner.
