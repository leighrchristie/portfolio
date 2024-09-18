---
layout: post
title:  "Appointment management workflow"
date:   2021-07-12
tags: [case management, moj, web, working within constraints]
---

## Background
From 26 June 2021, the new probation service is responsible for managing all those on a community order or licence following their release from prison in England and Wales.

A new case management system to replace legacy technology is a component of this programme.

Our team's goal was to support the join-up between existing and new probation services and to accelerate the move away from legacy systems in the sentence management space. As such, our users are probation professionals who use the case management system to manage their cases day-to-day. We are drawing upon existing user research (done by other digital teams in the programme) as well as our own usability testing to develop a prototype system that handles the booking and recording of appointments.

### User needs
For this piece of work, I was asked to explore what could be the smallest amount of information that we can record after a probation appointment, that would satisfy a range of user needs.

> As a probation practitioner I need to record service user attendance so I know if they are complying with their order.

Notes are recorded after a meeting. These notes contain pertinent information, but often in an unhelpful way that is unstructured, so it is difficult to analyse at scale or report on. It's likely that the information captured is duplicated or supersedes information captured in other probation systems.

Unhelpful and unstructured data does not follow the user's mental model of how they would handle a case.

## Exploring probation practitioner's mental models
A quick win in this area was to restructure the process of recording an absence, and align the design more closely to the mental model of the probation practitioner.

In the existing system, a long drop down list of 20 different options are presented to the user, with various branching logic outcomes attached. To begin, I analysed the list and categorised them into the appropriate process path.

![Logic map](/portfolio/assets/images/appointment-workflow/logic_map.png "The available options categorised into logical branching logic")
*The available options categorised into logical branching logic.*

## Testing the feasibility of the design
I began by creating a few paper prototypes to work out the flow of the transaction, then once I was happy with it, I coded it into an electronic prototype to be tested by users.

![Coded design](/portfolio/assets/images/appointment-workflow/update_attendance.png "Conditionally revealing options based on user selections")
*Conditionally revealing options based on user selections.*

This design works more efficiently by guiding the user through the process of recording attendance. It prompts the user to answer two questions, displaying only the information that is relevant to the answer provided, rather than the drop down menu of 20+ options.

## Results

This design was an interesting conjunction between interaction design and data strategy. By removing or consolidating the options, this simplified the UI for the user, but has reduced their options and thus may have removed vital contextual information; probation practitioners may lose some of the detail behind absences. 

For example; previously they would have been able to record an acceptable absence against 'medical'. Whereas now they can't. Previously, three consecutive absences due to medical appointments may have been a cause for concern, but this information is now not immediately obvious. It was important to consider this on the next iteration of the design.
