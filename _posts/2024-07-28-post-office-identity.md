---
layout: post
title:  "Enhancing the Post Office user journey so a user can prove their identity offline"
date:   2024-07-28
tags: [gds, offline journey, designing iteratively, designing for everyone]
---

## Situation: Background
From previous research, we found some users struggled with downloading, saving and transferring the customer letter given their low digital literacy. To mitigate this pain point, we want to provide the option to post the customer letter to them.

Printing customer letters is a key enabler for the Face-to-Face service with the Post Office. Our research has revealed that a significant number of our target users lack printers and smartphones, and therefore will require their customer letter to be printed. Using our integration with Notify, we will be able to have this posted to them, for a small cost.

## Task
I needed to amend our Post Office journey to enable users to opt to have their customer letter printed if they would like.

## Action
I added a screen into the prototype that asks the users if they would like their letter posted or by email only. There was added hint text to let users know how long they could expect to be waiting to receive the letter.

![The question](/portfolio/assets/images/post-office-identity/question.png "The question asking how they would like their letter")
*The question asking how they would like their letter.*

Their answer is then played back to them in a Check your answers screen.

![Check your answers](/portfolio/assets/images/post-office-identity/check-your-answers.png "Check your answers screen")
*Check your answers screen.*

## Results
When we tested this design with users, 6 out of 8 users chose “By Email and Post” over “By Email only”. They like to have options and a back-up (post) for a sense of security.

They are also unsure at this point of the journey if they will need to print out the letter later, hence they felt reassured to choose both. I decided that we should add in extra hint texts in the question screen that lets users know that they do not have to print their letter if they choose to download it.