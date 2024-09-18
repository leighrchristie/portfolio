---
layout: post
title:  "Search and filter functionality to allow users to efficiently find information"
date:   2022-04-22
categories: moj interventions web
---

## Background
The team had to introduce pagination onto a screen because the page was becoming too big and impacting service stability.

On paginated pages, this would affect users who will no longer be able to use their browser to search across the paginated pages. 

A survey with users revealed that many used browser functionality Ctrl-F on the page to pinpoint an intervention or group of interventions. This would no longer work adequately when pagination was introduced.

### User needs
The user need here was clear; 

> As a user I want to be able to quickly identify a case within a list so that I can complete my tasks associated with that case.

## Exploring different design options
I created five designs in Figma, ranging in complexity and confidence level, using established search patterns from within the HMPPS community and adapting them to suit our requirements.

![Designs](/assets/images/search-filter/three_designs.png "Three of the five designs I created to resolve the user need")
*Three of the five designs I created to resolve the user need.*

I wanted to get feedback from the whole user experience side of the team so invited interaction design, content design, user research and service design team members to critique the design. I created a rough agenda for the 45 minute slot; it was not much time to get through a lot of information, but I stuck to time and planned the session well ahead of time, so it ran smoothly and finished on time.

> "In a recent crit, she produced a very structured meeting format, ran the session tightly and accumulated useful feedback as a result." - feedback from a Content Designer

## Testing the feasibility of the design
Once we'd decided on the best design, I ran the developers through the design to judge the technical feasibility of it. Unfortunately, the data that we required was being pulled from various locations, meaning that although we’d chosen the most simple interaction, the technical feasibility of this was not simple and wouldn’t satisfy the user need of being able to search the whole list.

![Initial search function design](/assets/images/search-filter/initial_design.png "Initital search function design")
*Initial search function design before reviewing with the team.*

Based on the developers feedback, I made some changes to the design which narrowed down where in the data the user was searching, while still maintaining the simplicity of the design.

![Revised search function design](/assets/images/search-filter/final_design.png "Revised search function design")
*Resvised search function design for testing.*

I then created a full journey prototype in Figma for this new design which would test how users interact with a search in user research.

## Results
We tested the prototyped journey with five participants, four of which were able to complete the task of finding a probation practitioner’s cases with no prompts. 

Users were generally excited when first seeing the search box, as it was a desired feature of the product.

The crit provided the team with clear design direction and confidence for a feature that was tested with users. The feedback from the user testing excellent and didn’t result in any changes to the design. It was decided that it should be implemented and monitored with users, perhaps released to only a few before a national roll-out.
