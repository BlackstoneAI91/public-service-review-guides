---
title: "Chatbot Escalation Review for Booking Changes: A Staff Worksheet"
description: "A practical review worksheet for Malaysian service teams handling booking changes a chatbot cannot confirm, mapping ambiguous chat to staff review to customer confirmation, with statuses, actions and reviewer notes."
---

Published by [Blackstone Intelligence](https://www.blackstoneintelligence.com.my/).

A practical review worksheet for Malaysian service teams handling booking changes a chatbot cannot confirm, mapping ambiguous chat to staff review to customer confirmation, with statuses, actions and reviewer notes.

## Why a booking change needs a review worksheet

A booking change looks simple from the customer's side: move a slot, add a person, keep the price. Inside a service desk it is rarely one request. A message may contain a date change and a request for a different service at the same time, and the chatbot has no authority to confirm either. The risk is not that the chatbot fails to answer. The risk is that it answers confidently and the customer treats that as confirmation.

A review worksheet fixes this by separating three moments: what the customer asked, what staff decided, and what the customer finally agreed to. Each moment gets its own status and its own owner. The worksheet is not a script for the chatbot. It is a record that a human can read before the next test, so the team can see where the bot stopped and why.

This guide is written for Malaysian service business owners and the staff who prepare and review these workflows. It uses a fictional service desk so the decisions stay concrete. Blackstone Intelligence, a technology consultancy based in Kuching, Sarawak and operated by Blackstone Consultancy Sdn Bhd, lists AI chatbots and workflow automation among its services, which is the kind of work this worksheet is meant to govern. The worksheet itself is an author heuristic, not a certified method.

One rule frames everything below: a chatbot may collect and restate, but only a named person confirms a booking change.

When reviewing the scope of a [customer-service chatbot](https://www.blackstoneintelligence.com.my/chatbot-for-customer-service), identify which booking changes need a staff decision before testing the reply.

## The fictional desk: two overlapping requests

Meet Seri Pantai Services, a fictional Malaysian service desk that handles site visits, equipment checks and short training sessions. A customer writes in through the chat widget:

"Hi, can we move Thursday's session to Friday morning? Also my colleague wants to join, so maybe two people. Same price right?"

Three requests sit in one message. The date moves. The headcount changes. The price question is conditional. A chatbot can recognise the words, but it cannot confirm any of the three without checking availability, capacity and the pricing rule for additional attendees.

The desk's bot is set to handle routine questions and to hand over anything that changes a booking. In this case it should reply that it has logged the request, that a staff member will confirm, and that the current booking remains unchanged until then. That last sentence matters. Without it, the customer may assume Friday is already held.

Write the case down before designing anything. The worksheet below is built around this single message, because a real desk will meet many variations and the team needs one shared way to record them.

## Statuses that keep the route visible

Use a small set of statuses and do not invent new ones mid-review. Each status should tell the next reader exactly where the request sits.

Received: the customer's message is logged, nothing is confirmed.
Needs information: staff cannot decide because a detail is missing, such as which Friday or how many attendees.
Under review: a named staff member is checking availability, capacity or pricing.
Held provisionally: a slot is reserved for a stated period, with the customer told it is not final.
Confirmed by staff: a named person has approved the change and the customer has been told the new details.
Declined with alternative: the requested change cannot be made, and the customer has been offered another option.
Closed: the customer has replied to the confirmation and the record is complete.

Two habits make these statuses useful. First, the status changes only when the action behind it has happened, not when someone intends to do it. Second, the provisional hold always carries an end point, so a slot does not sit reserved indefinitely because nobody followed up.

A chatbot escalation review for booking changes depends on this discipline. If the status is vague, the review cannot tell whether the bot overstepped or the staff member was slow.

## What the reviewer writes before agreeing to the next test

The reviewer's job is not to approve the chatbot. It is to decide whether the route from chat to confirmation is clear enough to test again. Write short notes under fixed headings so two reviewers can compare answers.

What the customer asked: quote the request in one line, in the customer's words.
What the bot said: record the bot's reply and whether it confirmed anything it should not have.
What was missing: list the details staff needed before deciding.
Who decided: name the role, not just the team, and the time the decision was made.
What the customer was told: the exact wording of the confirmation or the provisional hold.
What the customer replied: the customer's response, or a note that none has arrived.
What changes before the next test: one or two specific edits, such as a new handover phrase or a required field in the chat form.

Keep the notes factual. "Bot was confusing" is not reviewable. "Bot said the Friday slot was available before checking the calendar" is. The second version points to a fix.

This is where a governed approach helps. Blackstone Intelligence positions its AI work around human review and business logic remaining central, and its public materials describe AI systems that support triage, retrieval and review while preserving human responsibility. The worksheet is a small, practical expression of that idea.

## A worked pass through the worksheet

Return to Seri Pantai Services and run the message through the headings.

The customer asked to move Thursday to Friday morning, add a colleague, and asked whether the price stays the same. The bot replied that it had logged the request and that staff would confirm, but it also wrote "Friday should be fine" — a phrase that reads as confirmation. That is the first finding.

Staff needed to know which Friday, how many attendees in total, and whether the additional attendee falls under a different pricing rule. The desk manager checked the calendar and found the morning slot free but the room set up for one person. The decision was made by the desk manager at 10:40 and recorded as held provisionally until 4pm that day.

The customer was told the slot was held until 4pm, that the second attendee could be added, and that the price for the extra attendee would be confirmed separately. The customer replied at 1:15pm agreeing to the hold and asking for the price in writing.

The reviewer's note before the next test: remove "should be fine" from the bot's handover wording, and add a required field for the number of attendees. Two edits, both specific, both testable.

## Where the worksheet meets the wider system

A worksheet is only as good as the system around it. If the chat widget cannot pass the customer's message and the bot's reply into a shared record, staff will retype it, and the review will drift. If the booking calendar is separate from the chat tool, the provisional hold may not appear anywhere the customer can see.

This is why the route matters more than the wording. The bot collects, the record carries, the staff member decides, and the customer confirms. Each handover needs a visible owner. When the desk grows, the same worksheet can be reused for other change types, such as cancellations or reschedules, without redesigning the whole flow.

Teams that want the customer-facing side to match the internal process often review their service pages at the same time, so the wording on the website, in the chat and in the confirmation email agree. That is a content and structure question as much as a technical one, and it is the kind of connected work Blackstone Intelligence describes in its public materials, where websites, AI agents and workflows are framed as one operating system rather than isolated deliverables. The company also lists AI consulting, integrations, training and maintenance among its services, which are the pieces that keep a reviewed workflow from decaying after launch.

If the chat is also a destination for a campaign, have the [digital marketing team](https://www.blackstoneintelligence.com.my/digital-marketing-agency) count the original enquiry once and treat a booking change as a separate support action.

## A short checklist before the next test

Before agreeing to another test, the reviewer should be able to answer yes to each of these. Treat the list as an example checklist, not a scored standard.

Does the bot have a clear handover phrase that does not imply confirmation?
Does every booking change reach a named person by role?
Is there a status for provisional holds, with an end time?
Can staff see the customer's original words alongside the bot's reply?
Is the customer told what is not yet confirmed?
Is the customer's final reply recorded before the case closes?
Are the agreed edits written down, with an owner and a date?

If any answer is no, the next test will repeat the same ambiguity. Fix the smallest item first. A single handover phrase often removes more confusion than a new feature.

The worksheet does not need to be long. One page per case, filled in honestly, gives the team something better than memory: a record of where the bot stopped, who decided, and what the customer actually agreed to. That record is what makes the next test worth running.

Blackstone Intelligence is a technology consultancy based in Kuching, Sarawak, and operated by Blackstone Consultancy Sdn Bhd. It provides AI consulting and automation, web design and development, custom software development, and digital marketing services.
