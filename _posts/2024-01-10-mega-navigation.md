---
layout: post
title:  "Expanding our navigation offering"
date:   2024-01-10
tags: [moj, mobile, designing interfaces, designing for digital]
---

## Background
In April 2023 we conducted user research into how we might expand our navigation offering on the WordPress Hale theme offered to our users, as well as address some user frustrations about how the secondary navigation interacted with user’s typical cursor behaviour. 

I solved the issue with secondary navigation by [changing the orientation to vertical](https://leighrchristie.github.io/portfolio/2023/04/20/secondary-navigation.html) in August 2023.

We have become aware that in the near future, there will be a need to transform more complex websites, with more complex content. We are therefore carrying out research and design to explore what the navigation might look like to cater for these more complex websites.

### User needs
The main findings were;
- Providing users with the option to use search bar or navigation is important to cater to different styles of navigating content
- Ensure there is a consistent navigation pattern across site
- Continue to allow for the user to click on main nav headings and go directly to landing pages
- Use plain english throughout
- If using hover, include a vertical list of menu options
- Be explicit about where the user is in the journey; e.g. through the use of breadcrumbs

### Business needs
The main business need identified was to enable the team to onboard sites with more complex information structures which will expand our options for potential sites and support them as they grow.

## Task: Problem statement
> How might we enable more complex structured sites to more easily use navigation on the Hale theme?

## Version one
Version one of the mega navigation used categorised columns across the full width of the page to increase the amount of options within the drop down area, as opposed to just one column. There were some questions regarding whether the category title (South West, for example) and whether that would be a link to its own page.

![Version one](/portfolio/assets/images/mega-navigation/version1.png "Version one")
*Version one.*

### Findings
I ran a design critique into this option (as well as some others) and this was the chosen mega-navigation design to pursue.

![Crit](/portfolio/assets/images/mega-navigation/crit.png "Crit details")
*Screenshot of the crit on this design.*

The main things to consider for the second version were;
- This could become quite busy
- Wrapping will be needed for long menu items
- How will this translate for different screen sizes?
- Should this cover or push the page down?

## Version two
This version needed to solve a few problems that had been identified as part of the previous rounds, but most importantly ‘How does the navigation respond to different screen sizes?’

The first idea was that we could increase our maximum page width on the screen so that we could get more options in by default. It is currently at 960px, but could be increased to 1,256px. However, the design would still need to work from anything from 1,256px – 769px (the point at which it changes to tablet/mobile view).

I took inspiration from one of the sites we tested during user research; the BBC News site. This site uses a ‘More’ menu item that includes menu items that disappear as the screen size gets smaller.

This means that the items are still available as the screen adjusts, but that some thought will need to go into the order of items in the nav bar if editors don’t want items to be pushed into ‘More’.

This is my version of that design in Figma;

![BBC more design](/portfolio/assets/images/mega-navigation/bbc.png "BBC 'more' design in Figma")
*BBC 'more' design in Figma.*

As with the BBC site, as the screen gets smaller the last item on the right of the primary navigation would disappear once it had hit a critical break point. With our design, I wanted to ensure that our editors could have as many items in the nav bar as they would like (the most we have at present is 7). To do this, I set each nav item to have a minimum and maximum width it could expand or contract to before moving into ‘More’. This worked out at having 8 items at a maximum, with ‘More’ as the 9th. If the navigation item was particularly long, it would wrap onto two lines and the other items would centre with it.

### 'More' expanded
This example is what the ‘More’ menu would look like with items from the primary navigation in it. It would only take up as much of the horizontal space of the screen as the width of the items that have been moved into it (see examples). The order would remain the same as it was in the primary nav, so new items appear to the left of the existing items. This maintains their position as more items are added, so users should recognise positions regardless of screen size.

![My 'more' menu](/portfolio/assets/images/mega-navigation/more.png "My 'more' menu")
*The 'more' menu using one of our sites as an example in Figma*

### Findings
This design wasn’t tested with users, but shared with various members of the team for feedback first;
- the distinction between navigation levels could be visually clearer on the ‘More’ and mega-navigations
- what happens if the ‘More’ menu has so many items it needs to wrap?

## Version three
Tol solve one of the issues, I added in line breaks into the ‘More’ and mega-navigation to improve the visual distinction for users. 

![Version 3](/portfolio/assets/images/mega-navigation/version3.png "An example of primary, secondary and tertiary navigation within the ‘More’ menu")
*An example of primary, secondary and tertiary navigation within the ‘More’ menu*

## Results

Once the initial proof of concept had been coded, I decided to make some changes to how the ‘More’ menu worked when the user interacted with it, which was much easier to test in a real environment vs theory in Figma. It will now only open/close when clicked on. This will hopefully prevent the same issue we had with the horizontal secondary navigation; where the user’s mouse was leaving the target area. 

This 'more' design has been in place on the https://magistrates.judiciary.uk/ site since March 2024. It activates when the screen size makes the primary navigation too small for all the items.

This has given our stakeholders the flexibility yo have as many primary navigation items as they want, without worrying about screen size restrictions.

![Live version](/portfolio/assets/images/mega-navigation/live_version.png "The Magistrates site live Sept 2024")
*The Magistrates site live Sept 2024.*