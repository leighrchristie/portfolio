---
layout: post
title:  "Job listing pattern for HMPPS"
date:   2023-09-27
category: website builder
categories: moj web mobile
---

## Background
Recruitment and retention of HMPPS frontline staff is a major priority and the department’s greatest risk. 

On 30 November 2022, the Prisons and Probation Minister announced to MPs that an emergency contingency plan called Operation Safeguard had been triggered because of an “acute and sudden increase in the prison population”. Prison staffing is a contributing factor.

MoJ Communications planned an HMPPS brand campaign that launched in September 2023.
 
The campaign uses TV and online video, social media and digital audio to drive awareness and consideration of prison and probation jobs. 

## Task
Our role as part of this campaign was to create a new HMPPS jobs website that fit in with the brand campaign look & feel, as well as serving the users' need to find a job that suits them.

This topic had been looked at previously a number of times, so there was a wealth of previous research to look at.

![Previous research](/portfolio/assets/images/hmpps-jobs/previous_research.png "An image of two previous sources of research findings from 2017 and 2018")
*An image of two previous sources of research findings from 2017 and 2018.*

### User needs
There were many user needs identified as part of the various discovery projects into this area, which we consolidated into 10 epics;

![Ten user research epics](/portfolio/assets/images/hmpps-jobs/ur_epics.png "The ten themes of user needs we identified")
*The ten themes of user needs we identified.*

Originally, the jobs listing pattern was attempting to address the user needs within 'Current vacancies', 'Immediate next steps' and 'Can I apply?'

## Design: version one

This version was created using the research we had accumulated through the various research decks. It was put together using the existing blocks available on the Hale theme in WordPress to test whether it was possible to meet user needs using the features already available.

![Version one collapsed](/portfolio/assets/images/hmpps-jobs/version1.png "Jobs listing using the columns and card blocks in WordPress")
*Jobs listing using the columns and card blocks in WordPress.*


![Version one expanded](/portfolio/assets/images/hmpps-jobs/version1_expanded.png "When the link of the card was clicked, it would open more information about the role")
*When the link of the card was clicked, it would open more information about the role.*

### Findings
Initially we were trying to solve the user needs around the epic 'Immediate next steps' with these screens, but realised that this information would be duplicated on our site as well as the site that applicants use to apply for the role. The jobs pattern needed to be the minimum amount of information that the user would need to judge whether they were interested in finding out more about the role, so it was deemed as not necessary while the applicant journey uses two sites. These user needs can be met elsewhere on the site within the specific role pages.

![Immediate next steps needs](/portfolio/assets/images/hmpps-jobs/version1_nextsteps.png "Immediate next steps needs")
*Immediate next steps needs, met elsewhere in the user journey.*

## Design: version two
These versions took inspiration from existing GOV.UK patterns on job listings as well as other leading job sites, such as LinkedIn, Google, Indeed and others.

![Desk research](/portfolio/assets/images/hmpps-jobs/version2_examples.png "Desk research")
*Different versions inspired by desk research.*

We ran a design critique on this design (as well as some other options) and came away with decisions that would create the MVP design. I kept a design history of the recorded changes I needed to make for the third version.

![Design crit](/portfolio/assets/images/hmpps-jobs/version2_crit.png "Design crit")
*Design crit findings with the team.*

The chosen version included a link to the application site for the role, key information about the role including salary, contract type and location as well as filters and keyword searches to help the user identify the specific roles they were interested in applying for.

![Version two](/portfolio/assets/images/hmpps-jobs/version2.png "Version two")
*Version two*

### Findings
- Remove the keyword search as there is no clear user need at this point
- Update the button content to be more consistent with other government job sites; “Update results”
- Remove the summary of the job description as there is no clear user need for this and it was not clear if this data would be useful or available. It may also have been duplicated across similar roles
- Where possible we should include the specific salary, not just the salary range in the job description
- Remove the reference from the job summary as there is no user need for it; it is hypothesised that this is an internal only data point

## Design: version three

This version implemented the identified changes in Figma and built out a full user journey for testing. This journey included a content for when a user searches for a job but there are no matches.

![Version three](/portfolio/assets/images/hmpps-jobs/version3.png "Version three")
*Version three, with filters for role, region and salary*

![Version three](/portfolio/assets/images/hmpps-jobs/version3_noresults.png "Version three, no results")
*Content for when there are no matching roles after searching for jobs*

These designs were tested in a round of research using participants that had used the previous site to apply for a role at HMPPS.

### Findings
- Users want to build on their results, use a filter, check what comes up, then add another filter and so on without “clearing”
- Additional filters for grade or contract type may be useful
- Region seemed to be the most popular filter. The regions are still quite big
- Users would note the address and look at Google Maps to check location as Prison name won’t always relate to them
- All 5 users felt a different way to select pay ranges might be easier, such as selecting multiple options or a slider, or possibly ‘up to £X amount’

## Design: version four

Due to the quality of the data that we are receiving from the job feed in Oleeo, some technical solutions were required to support requirements from the business around surfacing jobs for the user.

One requirement was to add in a keyword search that will allow users to search the job titles in the current vacancies and allow the business to create pre-filtered search results. This meant a design change, but the initial design for this was removed from version three for MVP as there was no clear user need at the time.
s
Functionality to note;
- The ‘update results’ button will need to be pressed for searching and/or filtering
- The search term will persist in the search box after the ‘update results’ button has been pressed
- Additional filters can be added along with the search term and apply to the search (e.g. “youth” + minimum salary £30,000)

![Version four](/portfolio/assets/images/hmpps-jobs/version4.png "Version four")
*Version four*

## Results
Overall the jobs listing design has tested very well, with users understanding the functionality of the filters and search.

The site launched on the 18th of September 2023 and in the first week, the job listing design had over 100,000 unique visitors. It will continue to be monitored, observing users behaviour post launch to check for things we might want to consider, such as;
- Do we need to include some way of identifying women’s prisons, or prison specific jobs?
- Would users like to be able to sort the search results?
- Would users like to be able to narrow the location down further?
