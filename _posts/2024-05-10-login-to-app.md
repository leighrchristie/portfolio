---
layout: post
title:  "Allowing users to more easily log in to GOV.UK One Login"
date:   2024-05-10
tags: [gds, mobile, designing interfaces, designing for digital, designing with data]
---

## Situation: Background
There is a GDS-wide ambition to develop a single GOV.UK app, which aims to offer a personalised experience for users and provide easy access to government services and information.

Through the development of this app we want to leverage the existing One Login capabilities of authentication, user account data, and identity verification (IDV), to enable: 
- Access to government services (where IDV is required) 
- A more personalised experience of GOV.UK (that may or may not be reliant on having a verified identity, but would require being ‘logged in’) in the app

By integrating login into the app journey, we believe we can enhance the overall journey user experience. 

### User needs
We have observed a certain percentage dropout on every question in the current web triage flow. Some of this is valid, with users not meeting criteria (e.g. don't have a smartphone or relevant ID document), but currently, the length and complexity of the journey may be deterring some users from continuing. We also have had feedback in app store reviews on the overall length and complexity of the journey, so believe steps towards simplifying the web triage journey will also benefit our successful users.

## Task: What hypotheses do we want to test? 
> Users find triage flow journey easy to understand and simple to use (for mobile or desktop versions)

> Users understand the benefits of using the app and they are encouraged to try

> Users understand they can change their mind any point in the triage flow

While working to streamline the login process when accessing the new GOV.UK One Login app, I needed to consider the handover process from desktop to app and back again, as well as mobile browser to app and back again.

## Action: Iterations
To ensure as many users as possible are able to prove their identity in the GOV.UK One Login app, there had to be different ways to access the service. As there are different technologies used in the desktop and mobile versions, I have been designing interfaces for each version that perform the same task, but are distinct from one another based on the functionality of each device. 

The mobile version was easier to iterate quickly, but the desktop version required the user to navigate between their desktop and phone, so needed iterating a few times.

### Version one
Initial findings were telling me that users were getting distracted with the transition from desktop to mobile, and not readng the content on the page. To combat this, I tried implementing some friction into the process, asking the user to confirm they had downloaded the app before continuing. 

![The design](/portfolio/assets/images/login-to-app/version1_desktop.png "The first version with a checkbox")
*The first version with a checkbox.*

However, when tested users failed to click the checkbox, preferring to follow the instuctions on their mobile, then becoming confused when returning to this page. The content on the next page that explained the steps in the app was obsolete by this point, as most users had already passed this point in their journey.

### Version two
This desktop version combines the step by step approach of the first iteration with the original QR code a to guide the user through downloading the app on their mobile on one page. 

![The design](/portfolio/assets/images/login-to-app/version2_desktop.png "The step by step process")
*The step by step process.*

The spinner will help to indicate to users something is happening while they complete the steps on their phone, and that they need to return to this page afterwards.

The content on desltop is essentially the same as the mobile version so each user has all the information they need, with a few differences as appropriate to the channel.

![The mobile design](/portfolio/assets/images/login-to-app/version2_mobile.png "The mobile version, linking to app store")
*The mobile version, linking to app store.*

### Findings
This version is going live in January 2025, with some aspects of the streamlined triage journey going live in Autumn 2024 to enable users to benefit from a shorter journey before this date.

## Results
Each design takes into account the requirements for different channels and how the journeys may differ based on the device you are using. Users are able to choose which technology they want to use to access the service which fits with their personal preference as what is easy for one user may be inconvenient for another; that could be mobile, desktop or a face to face route if they prefer not to complete the ID check online.