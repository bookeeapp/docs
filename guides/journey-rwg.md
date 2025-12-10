---
title: "Setting Up the Google Reviews Journey Template"
description: "Encourage customers to leave positive Google reviews through automated messaging using the Google Reviews Journey."
slug: "/journeys/templates/google-reviews"
category: "Journey Templates"
---

import { Callout, Info } from '@components'
import { Card } from '@components/ui/card'
import { Accordion, AccordionGroup } from '@components'

# Google Reviews Journey Template

The **Google Reviews Journey** helps you increase your studio's visibility by prompting loyal customers to leave positive reviews on Google. With Kenko, you can automate this process and gather social proof at scale.

<Info>
  Boost your online reputation by triggering smart reminders for happy customers to leave Google reviews.
</Info>

## Getting Started

<AccordionGroup>
  <Accordion title="Create a New Journey">
    Go to the **Journeys** tab in your Kenko dashboard. Click **New Journey** and select the **Get Google Reviews** template from the journey library.
  </Accordion>
  <Accordion title="Define Entry Rule">
    Identify which customers should be encouraged to leave a review. The template includes:

    - Users who visited once in the last 14 days
    - OR users with 5\+ total visits

    You can adjust these conditions to better suit your studio’s audience.
  </Accordion>
  <Accordion title="Customize Emails">
    Configure your email block by:

    - Choosing a sender email
    - Setting a relevant subject line
    - Personalizing the message body with your logo, studio visuals, and colors
    - Including a direct button to your Google review page

    Apply this configuration to each email in the journey to maintain consistency.
  </Accordion>
  <Accordion title="Adjust Wait Nodes">
    Update the timing between touchpoints. For example:

    - Wait 1 day after a visit before prompting for a review
    - Send a follow-up if no action is taken within 3 days
  </Accordion>
  <Accordion title="Add SMS Block (Optional)">
    Enhance your journey’s effectiveness by adding an SMS block:

    - Deliver the same message in a shorter format
    - Use it as a reminder if email engagement is low

    Multi-channel nudges improve conversion rates significantly.
  </Accordion>
</AccordionGroup>

## Example Setup

<Card>
  Ask for a Google Review after a positive customer experience

  - Entry rule: 1 visit in last 14 days OR 5\+ total visits
  - Wait: 1 day
  - Trigger email with review link
  - Optional: Send SMS reminder after 3 days
</Card>

## Best Practices

<AccordionGroup>
  <Accordion title="Keep Messaging Short and Direct">
    Make it easy for customers to act. Use direct language like:

    > "Loved your session? Leave us a quick review on Google\!"
  </Accordion>
  <Accordion title="Personalize by Visit History">
    Mention how many sessions they've completed. Recognition reinforces satisfaction and makes them more likely to share positive feedback.
  </Accordion>
  <Accordion title="Avoid Overcommunication">
    Don’t overdo it—set smart wait times between messages and avoid repeat triggers for customers who’ve already submitted reviews.
  </Accordion>
</AccordionGroup>

<Info>
  Have questions or want help setting up this journey? Reach out to [support@bookeeapp.com](mailto:support@bookeeapp.com).
</Info>