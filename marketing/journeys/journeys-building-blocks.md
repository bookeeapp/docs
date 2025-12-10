---
title: 'Journeys: Building Blocks'
description: >-
  Understand the core components used to build customer journeys in Kenko, and
  how to best use each.
---

# Journeys Building Blocks

Kenko Journeys are powered by a **drag-and-drop builder** that lets you visually map out automated workflows across different communication channels. These workflows, called Journeys, are composed of **Blocks** — the foundational units that define actions, logic, and content inside a journey.

This guide explains each type of block, how they work, and how to use them to build powerful, personalized automation workflows.

## Types of Journey Blocks

Use a combination of these blocks to create sophisticated, contextual journeys for maximum client engagement. Rule blocks are the \*\*logic engines\*\* of your journey — they determine who qualifies for the journey or which path they follow next.

```
Use filters such as:

- Membership status
- Pricing options purchased
- Tags assigned to contact
- Visit or class count

![Rules Block](/images/Block\(3\).png)

<Info>
  You can also set timing conditions like "wait X days after purchase" or "trigger if no booking in 7 days."
</Info>
```

Use drag-and-drop tools to craft branded emails that drive engagement and action.

```
- Personalize content with variables (name, service, etc.)
- Track open, click, and delivery performance
- Add fallback channels if the email goes unopened

![Email Block](/images/Block\(4\).png)

<Tip>
  Great for newsletters, onboarding sequences, milestone check-ins, and upsell offers.
</Tip>
```

SMS is powerful for quick, timely messages — high open rates, instant delivery.

```
- Perfect for reminders, confirmations, and flash promos
- Add personalization with name, session info, and more
- Supports fallback if not delivered

<Tip>
  Keep messages short, actionable, and compliant with opt-in regulations.
</Tip>
```

Push blocks allow you to send in-app messages to users of your branded mobile app.

```
- Alert members about class spots, new videos, or offers
- Ideal for re-engagement without email/SMS costs
- Set conditions for timing and frequency

<Tip>
  Use these sparingly for important updates or time-sensitive nudges.
</Tip>
```

Wait blocks delay the next step in your journey.

```
- Fixed delay: “Wait 3 days”
- Conditional delay: “Wait until booking is made”
- Timed delay: “Wait until 9 AM on a weekday”

![Wait Block](/images/Block\(5\).png)

<Tip>
  Use this to pace out messages and avoid overwhelming clients.
</Tip>
```

Tags allow dynamic segmentation and logic within your journey.

```
- Apply or remove tags based on user actions
- Trigger automations or eligibility based on tags
- Use tags to power audience-specific campaigns

![Tag Block](/images/Block\(6\).png)

<Tip>
  Use tags to track trial completion, drop-offs, referrals, or engagement levels.
</Tip>
```

## Connecting Blocks

Select a block from the left-side menu in the Journey Builder and drop it onto the canvas. Click on the arrow from one block and drag it to another. This creates a directional flow.

```
![Connect Block Pn](/images/ConnectBlock.png)

<div className="flex justify-center" />
```

Kenko supports \*\*parallel paths\*\* — clients can continue down two flows simultaneously if configured that way.

## Understanding Rule Matching

Rule blocks define conditional logic. Here's how matching behavior works:

| Behavior        | Explanation                                                                                                        |
| --------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Matched**     | Contact satisfies the rule's condition (e.g., purchased a plan, completed a visit). Moves down the "matched" path. |
| **Not Matched** | Contact doesn't meet the rule's condition. Moves down an alternate (fallback) path or exits the journey.           |

Fallbacks ensure that even if a user doesn't match a rule, they still experience a meaningful journey.

## Advanced Features

Implicit waits are handled by rule blocks with a time window (e.g., wait 3 days to see if they take an action). If a user doesn’t meet the rule condition, fallback paths can be used to send them a different message or exit them from the journey. Each journey defines how customers enter, proceed, exit, or achieve a goal. Pause, resume, duplicate, or delete journeys at any time. Pausing prevents new contacts from entering, but existing ones still progress.

## Journey Analytics

Monitor journey health, engagement, and conversion rates with **Journey Analytics**.

![Screenshot2025 05 05at6 56 09PM Pn](../../.gitbook/assets/Screenshot2025-05-05at6.56.09PM.png)

| Metric           | Meaning                                                |
| ---------------- | ------------------------------------------------------ |
| Audience Entered | Number of contacts who started the journey             |
| Conversion Rate  | % of contacts who completed the journey goal           |
| Drop-off Rate    | % who exited midway or disengaged                      |
| Email Metrics    | Open rates, click-through rates, bounces, unsubscribes |

Review Analytics every week to refine entry rules, wait times, and messaging. Want a visual walkthrough? Watch \[this YouTube guide]\(https://www.youtube.com/watch?v=NTku6XyPTew) to see how Kenko Journeys work step-by-step.

## Common Use Cases

Entry Rule: Bought intro plan → Email → Wait 3 days → Check if first visit done → Send next message accordingly. Entry Rule: Last visit \\> 30 days → Send re-engagement email → Offer incentive → Tag or exit. Entry Rule: Total visits = 10 → Send Congratulations email → Apply milestone tag.

## Journey Performance

Kenko tracks the journey lifecycle in real time:

| Status       | Meaning                                               |
| ------------ | ----------------------------------------------------- |
| Started      | Contact entered based on the entry rule               |
| In Progress  | Contact is currently going through the journey        |
| Finished     | Contact completed all blocks                          |
| Exited       | Contact left early (rule-based exit)                  |
| Disengaged   | Contact removed due to bounce, spam, or rule mismatch |
| Goal Reached | Contact achieved the defined journey goal             |

You can view real-time analytics on block performance (email opens, clicks, deliveries) and contact progression using \*\*Journey Analytics\*\*.

## Why Kenko Journeys Are Best-in-Class

* **Drag-and-Drop Interface**: Build complex logic with zero code.
* **Multi-Channel Automation**: (Email now, SMS & Push coming soon).
* **Contextual Messaging**: Based on real-time customer data.
* **Smart Conditions**: Use wait timers, fallback paths, and tags for precision.
* **Re-entry & Throttling Control**: Limit how often and when users re-enter.
* **Visual Analytics**: Get granular insights at block and contact levels.

## Usage Guidelines

\- 10,000 audience entries per month (token-based) - Up to 5 live journeys at once - Max 5 rule blocks & 5 wait blocks per journey - Rule evaluations every 6 hours - Contact data refreshes hourly - Analytics updates every 5 minutes - Minimum 24 hours wait before re-entry - Customer must finish, exit, or disengage to re-enter Clear titles for each block help with team collaboration and analytics readability.

## Before You Go Live

* ✅ All blocks should be connected
* ✅ Entry & exit rules must be configured
* ✅ Goal should be defined (optional but recommended)
* ✅ Review fallback paths for every rule block

Once live, you can monitor performance in **Journey Analytics** and iterate based on actual behavior.

Need help building your first Journey? Start with the \[Intro Offer Journey Template]\(https://help.bookeeapp.com/en/articles/9973499-setting-up-journey-template-intro-offer).
