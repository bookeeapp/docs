---
title: "Optimize Your Journey Filters"
description: "Learn how to use goal and exit filters effectively to measure success and manage contacts in Kenko Journeys."
---

import { Callout, CardGroup, Card } from '@mintlify/components'

# Mastering Goal and Exit Filters to Optimize Your Journeys

In journeys, the ability to track and manage user behavior is critical to measure its success. Two key concepts that help achieve this are **Goals** and **Exit Criteria**. While they might seem similar, they serve different functions that can dramatically impact your journey’s effectiveness.

## What is a Goal?

A _Goal_ is used to measure the success of a journey by tracking whether contacts complete specific desired actions, like purchasing a membership or booking a class. It allows businesses to assess how well a journey is achieving its intended outcomes.

- **Purpose:** Measure the journey’s success by tracking key actions taken by contact.
- **How It Works:** This works by monitoring contact behavior to see if they meet the defined goal (as per the segment you have created via the filters), such as purchasing a membership or completing a visit.

For example, let’s say your journey is designed to encourage contacts to purchase an intro offer at your studio. _Goal_ tracks how many contacts successfully purchase that intro offer. This not only shows how effective your journey is but also allows you to assess the revenue generated from the journey.

<Info>
  Use a Goal Filter — "Pricing Option Purchased" — to track memberships purchased. Set the purchase date to start from when the journey goes live to accurately measure how many memberships were bought as a result of the journey.
</Info>

## What is an Exit Criteria?

_Exit_ is used to automatically remove contacts from a journey once they meet certain conditions, ensuring they stop receiving communications that are no longer relevant to them.

- **Purpose:** Exit contacts from the journey when certain conditions are met, stopping further messaging or interactions.
- **How It Works:** It identifies contacts who should no longer be part of the journey, either because they’ve completed the desired action or taken another action that makes the journey irrelevant for them.

Some examples to understand the use cases of Exit Filters:

- Example 1: In a journey promoting subscriptions, if a contact purchases a credit pack, the Exit Filter removes them from the journey to prevent them from receiving further irrelevant messages.
- Example 2: In a journey prompting contacts to leave a Google review, once a contact completes the review, they are exited from the journey, stopping any further nudges.

Sometimes, the Exit Filter overlaps with the goal being met. For example, if the goal of your journey is to get a contact to complete a booking, once that action is done, they also exit the journey as there’s no need for further communication.

<Info>
  Use an Exit Filter — "Pricing Option Name" — to remove contacts who purchased a credit pack when the intended journey was to promote a subscription. This ensures they no longer receive subscription-related messages, keeping your communication relevant.
</Info>

## When to Use Goal Filters vs. Exit Filters

These concepts work together to ensure that journeys are both goal-oriented and respectful of the contact’s needs. Here’s a quick breakdown of when to use each:

| Goal Filter                                                                                         | Exit Filter                                                                                         |
| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Use to measure success by tracking whether contacts complete key actions (e.g., purchases, visits). | Use to remove contacts from the journey once they no longer need to receive further communications. |

## How Goal and Exit Filters Complement Each Other

While these concepts have distinct purposes, they often work hand-in-hand within a journey. For instance, a Goal Filter might track how many contacts successfully book a service, while an Exit Filter ensures that contacts who completed the booking early on are no longer receiving promotional emails.

By using both filters together, you create a more seamless and efficient journey, ensuring that your communications are effective without overwhelming or spamming contacts.

---