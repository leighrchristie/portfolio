---
layout: post
title:  "Improving the secondary navigation for users"
date:   2023-08-20
tags: [moj, mobile, designing interfaces, designing for digital]
---

## Background
In April 2023 we conducted user research into how we might expand our navigation offering on the WordPress Hale theme offered to our users, as well as address some user frustrations about how the secondary navigation interacted with user’s typical cursor behaviour. 

Users were finding the horizontal design of the secondary navigation hard to use due to the cursor moving out of the target area.

### User needs
The main findings were;
- Providing users with the option to use search bar or navigation is important to cater to different styles of navigating content
- Ensure there is a consistent navigation pattern across site
- Continue to allow for the user to click on main nav headings and go directly to landing pages
- Use plain english throughout
- If using hover, include a vertical list of menu options
- Be explicit about where the user is in the journey; e.g. through the use of breadcrumbs

## Task: Problem statement
My task was to work closely with the front end developer to create a scalable and accessible design for primary and secondary navigation.

> How might we enable more complex structured sites to more easily use navigation on the Hale theme?

> How might we improve user’s experience of using the secondary navigation for simpler sites?

## Action: Iterations
I iterated through 2 versions of the design before we got to a place we felt would satisfy the user needs, not depend on javascript to be implemented (achievable using only CSS) and degrade gracefully if needed. 

### Version one
This version was the version that was tested as part of the research round, on the IMB site.

![Version one](/portfolio/assets/images/secondary-navigation/version1.png "Example of the old navigation on the Public Defender Service site")
*Example of the old navigation on the Public Defender Service site.*

### Findings
Users felt like this was a bit frustrating when they hovered off the second level navigation and the menu disappeared. This was particularly an issue when trying to move diagonally across to a menu item, for example, trying to navigate from ‘Our solicitors’ to ‘Swansea’ leaves the menu area, making it disappear.

![Version one](/portfolio/assets/images/secondary-navigation/version1_demo.png "Example of how the old navigation might have come out of the target area")
*Example of how the old navigation might have come out of the target area.*

### Version two
After running a critique session on a variety of proposed designs to meet the identified needs, we decided as a team to focus on resolving the more simple problem first; how might we improve user’s experience of using the secondary navigation for simpler sites?

![Crit](/portfolio/assets/images/secondary-navigation/crit.png "This is the commentary on the Figma version of the design, after the critique")
*This is the commentary on the Figma version of the design, after the critique.*

The second version took on the feedback from the various rounds of research and changed the navigation to be vertical rather than horizontal. This meant that the target area was much easier to stay within.

![Version two](/portfolio/assets/images/secondary-navigation/version2.png "Feedback iterated design")
*Feedback iterated design.*

## Results
As this was a fairly low risk design change that we had high confidence in, we decided to test the changes “in the wild” and pushed the changes to live in July 2023.

Since then, we have only had positive reactions to the changes and there have been no further issues with users coming out of the target area.

### Future considerations
As we only addressed the issue regarding the hover target area, there is still work ongoing to enable us to support more complex sites using a mega-navigation structure.