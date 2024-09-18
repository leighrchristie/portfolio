---
layout: post
title:  "Allocation evidencing: influencing the design direction"
date:   2023-03-30
tags: [moj, designing information, working strategically, communicating and influencing]
---

## Situation
As part of a change to policy, probation practitioners will need to evidence their allocation decision for every allocation they make. Currently, practitioners only have to evidence their decision when that decision is made outside of policy guidance. Guidance is issued based on how much of a risk a person on probation is, affecting who can be allocated to which grade of probation practitioner.

## Task
I was asked to create designs in the Allocations service that would allow practitioners to evidence their allocation decisions. The new policy had not yet been written, but we had guidance from policy about what new additions would be included. This was a really crucial point of our service, as it meant that the evidence we gathered as part of testing these designs could be fed back and influence the policy. For our stakeholders in policy, the most important aspect of this design was that the allocation evidence should be written back to NDelius, the existing case management system, so that it was available for all users, not just those who were using our service in private beta.

## Action
My first action was to evaluate the current research findings with the user researcher and the policy with the business analyst. This allowed me to determine that there were four distinct user journeys for allocation evidence; the happy path, where the grade of practitioner meets the tier of person on probation, when a grade of practitioner is too low to manage the tier of person on probation, when a grade of practitioner is 'too high' (suggested) for the tier of the person on probation, or when the grade of practitioner is borderline for the tier of the person on probation. 

In line with current policy, when the tier of the practitioner is too low to manage the person on probation, I designed a hard stop so that no allocation could be completed. When I demonstrated these design concepts to policy, they were hesitant to include the hard stop within the designs, as there are edge cases when an allocation that breaks these rules must happen anyway. 

![Hard stop](/portfolio/assets/images/evidencing-allocation/hard_stop.png "Stopping a user from allocating against policy")
*Stopping a user from allocating against policy.*

Based on this feedback, I felt that it was important for us to influence the way the new policy was worded. To allow users to make the allocation when the policy is very strongly worded against it would make our service look like we were allowing the user to circumvent policy. I worked with the business analyst on the team to make sure this was not the case for the new policy and ensure the experience of the user was in line with policy wording.

My second action was to challenge where the evidence was written back to. As the team managing the Allocations service, and to contribute to moving away from legacy technology, I believed that the Allocations service should be the master source of this data, but policy were firm that it had to be written back to NDelius as a minimum. Their recommendation was that it be written back from our service into a contact called 'Management Oversight - General'. This contact is used for a varying number of activities in the management of a person on probation. Previously, there had been a separate contact for allocation evidence and so I made a strong recommendation that a new contact be set up that had the sole purpose of evidencing an allocation decision as then it would be much easier to find when a case audit is carried out. 

## Result
The business analyst has fed back our concerns about the policy wording and it is still currently being written. In the meantime, we have removed all policy guidance from the design so that it can still be rolled out but without affecting current practice. The new wording will allow for the situation where a lower grade practitioner must be allocated to a higher tier person on probation.

Policy accepted my recommendation that the evidence be written back to its own contact and the team is currently in the process of liaising with the NDelius team to get it created. It will be so much easier for an allocation to be audited because of this change.
