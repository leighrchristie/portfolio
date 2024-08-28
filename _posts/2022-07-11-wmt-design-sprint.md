---
layout: post
title:  "Design sprint: Redesigning the Workload Measurement Tool"
date:   2022-07-11
category: design sprint
categories: moj allocations web
---

## Background on WMT
The Workload Measurement Tool (WMT) was a third party supplied web based tool that was brought in house by the MoJ in 2022. In simple terms, the WMT measures work load and helps people to balance it.

The opportunity presented by the data available in WMT is greater than its current usage, with scope to improve further.

Myself and another Interaction Designer on the team decided to conduct a design sprint into the usage of WMT and how the data could be better used and presented, in a way that aligned with the users goals.

![A screenshot of the WMT national interface](/portfolio/assets/images/wmt-design-sprint/WMT.png "A screenshot of the WMT national interface, a table with rows for each region in England and Wales")
*A screenshot of the WMT National interface, a table with rows for each region in England and Wales.*

![A screenshot of the WMT caseload](/portfolio/assets/images/wmt-design-sprint/WMT_caseload.png "A screenshot of the WMT caseload interface, including statistics on caseload totals and a table breakdown")
*A screenshot of the WMT caseload interface, including statistics on caseload totals and a table breakdown.*

### User needs
To ensure we weren't reinventing the wheel, I looked back at previous research sessions where WMT had been discussed and noted down any important quotes and insights.

![Previous research into WMT](/portfolio/assets/images/wmt-design-sprint/WMT_research.png "A screenshot of the previous research done into WMT")
*A screenshot of the previous research done into WMT.*

In order to start working on potential designs, I decided we needed to analyse the existing research and assumptions to investigate where we had common threads of issues.

## Creating assumptions to test with designs
I gathered quotes from the research and began to affinity sort them into themes, making observations about these themes and turning those into assumptions about user behaviour and data quality.

> "[I'm] used to working in three or four different screens. You know, flicking between different screens to look it up. We have a measurement tool look up on an allocation spreadsheet." - Participant

I came up with 6 themes with associated assumptions we could test.

![Assumptions](/portfolio/assets/images/wmt-design-sprint/WMT_assumptions1.png "Three of the six themes; users are flicking between screens, confusion with the capacity % and that there is more to capacity than just the number")
*Three of the six themes; users are flicking between screens, confusion with the capacity % and that there is more to capacity than just the number.*

![Assumptions](/portfolio/assets/images/wmt-design-sprint/WMT_assumptions2.png "The last three of the six themes; users don't trust the data, users are misusing aspects of the system and that users can access more of the tool than necessary")
*The last three of the six themes; users don't trust the data, users are misusing aspects of the system and that users can access more of the tool than necessary.*

Using the research, analysis and assumptions I had created, I determined 9 - 10 distinct user journeys that were being done in WMT. I could see three key products that WMT could be broken down into;
- Caseload
- Workload Management
- Reporting

![Product map breakdown](/portfolio/assets/images/wmt-design-sprint/product_map.png "Ten distinct products that could be grouped into three different services; Caseloads, Workload Management and Reporting")
*Ten distinct products that could be grouped into three different services; Caseloads, Workload Management and Reporting.*

## Proof of concept designs
The next step of the design sprint was to pick an area to create a proof of concept. I chose to select the ‘view my team’ user journey, as this was key data that the tool was being used for, in order to support senior probation practitioners manage their team’s workload.

I extrapolated the data required for this journey (that already existed in WMT) and from analysis of the research, included some areas that might be beneficial new features.  Removing the data into it’s high level purpose, rather than looking at screens, helped me to remove the old product and focus on new ideas.

![WMT data points](/portfolio/assets/images/wmt-design-sprint/WMT_data_points.png "Sticky notes denoting data points to be included in the design")
*Sticky notes denoting data points to be included in the design.*

Using Miro, I took those high level data points and began to arrange them on a prototyped GOV.UK screen. Initially, I had gone straight into Figma to begin to create a prototype, but found that without a basic concept of what I wanted, I found it hard to choose appropriate components and visualise how I wanted the information architecture to be.

![View my team design in Miro](/portfolio/assets/images/wmt-design-sprint/miro_design.png "Miro sticky notes on a GOV.UK background to roughly layout the screens")
*Miro sticky notes on a GOV.UK background to roughly layout the screens.*

By taking a step back, I was actually able to save myself time by not diving in with too much complexity. From this design, I could then create a more realistic version in Figma.

![View my team design in Figma](/portfolio/assets/images/wmt-design-sprint/view_my_team.png "A more high fidelity design showing the proof of concept designs")
*A more high fidelity design showing the proof of concept designs.*

## Results
When I showed my design for the new ‘view my team’ screen, the team were very excited about it!

This initial first page only uses data currently available within WMT, but presents key information back in an easily digestible format. Users should be able to find a lot of their key team level information on this page with the option to drill down further only one click away in.

> "This is great! We could build this now, let’s do it!" - Technical architect

### Future considerations
As a proof of concept of what WMT is capable of, I think we succeeded in making the case for rethinking how powerful it could be. Work to improve the data in WMT was put onto the team’s roadmap.
