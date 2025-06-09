---
title: "Introduction to New Payment Settings"
description: "Learn how Kenko’s updated payment settings automate handling of failed payments using Stripe Smart Retry and streamline member billing workflows."
sidebar_position: "1"
---

import { Card, CardGroup, Accordion, AccordionItem } from '@mintlify/components'

# New Payment Settings in Kenko

Kenko introduces enhanced payment settings to help studio owners manage failed payments effectively. These settings leverage **Stripe’s Smart Retry** logic and automate actions like suspension, cancellation, and member notifications—ensuring clarity, reducing manual overhead, and improving customer retention.

## Overview of Settings

The new system offers three **mutually exclusive** options for handling payment failures.

<CardGroup cols={2}>
  <Card title="Immediate Cancellation on Failure" icon="ban" href="#immediate-cancellation">
    Membership is cancelled automatically after three failed Stripe retry attempts.
  </Card>
  <Card title="Cancellation After Multiple Failures" icon="x" href="#cancellation-after-multiple-failures">
    Membership is cancelled only after a predefined number of retries.
  </Card>
  <Card title="Suspension and Eventual Cancellation" icon="pause" href="#suspension-and-cancellation">
    Membership is suspended first; cancelled later if payment remains unresolved.
  </Card>
</CardGroup>

## Setting Details

<AccordionGroup>
  <Accordion title="Immediate Cancellation on Payment Failure" icon="ban">
    Kenko uses **Stripe Smart Retry** to attempt charging the card up to three times within a seven-day window.

    **If all attempts fail**

    - Membership is automatically cancelled
    - Customer is notified via email
    - An "Unpaid Due" tag is applied to the profile
    - Customer appears in the Amount Dues Report

    This setting is ideal for studio owners who want strict enforcement and minimal tolerance for payment lapses.
  </Accordion>
  <Accordion title="Cancellation After Multiple Failures" icon="x">
    This setting also uses Stripe Smart Retry but waits for a custom number of failures before canceling.

    **Use case**

    - Offers customers time to update payment info
    - Reduces involuntary churn
    - More customer-friendly approach for studios prioritizing retention

    Members receive alerts throughout the retry period to resolve their payment issues.
  </Accordion>
  <Accordion title="Suspension and Eventual Cancellation" icon="pause">
    In this mode

    - Upon the first payment failure, the membership is suspended
    - Member loses access to booking or attending classes
    - If the issue is unresolved within a defined window, the membership is cancelled

    All failed payments and resulting account changes are communicated via automated messages.
  </Accordion>
</AccordionGroup>

## Stripe Integration Setup

To ensure Kenko manages failed payment logic correctly, configure your Stripe account as follows:\\

**Navigate to**\
**Settings → Billing → Automatic Collection → If all retries fail: Leave subscription as-is**

This ensures Kenko's rules are applied instead of Stripe prematurely cancelling the membership.

If you set it to “Cancel the subscription,” Stripe will override Kenko’s settings and immediately cancel the membership on final failure.

[Open Stripe Billing Settings](https://dashboard.stripe.com/settings/billing/automatic)

## What Happens in Kenko

When one of these settings is enabled

- Stripe retries the payment automatically using Smart Retry
- Based on outcome, Kenko takes over and applies the chosen rule (suspend, cancel)
- The system automatically:
  - Sends emails
  - Updates tags
  - Reflects dues in reports
  - Blocks or restores access

This reduces manual tracking and ensures timely responses to payment failures.

## Best Practices

Choose the policy based on

- How tolerant you are toward late payments
- Member retention goals
- Staff workload and admin automation needs

Larger studios or chains often prefer suspension, while boutique or fast-growing studios may lean toward immediate cancellation for better financial predictability.

## Troubleshooting

- If members are being canceled earlier than expected, verify your Stripe setting for failed retries.
- Confirm only one payment policy is enabled per membership to avoid conflict.
- Always inform your staff of changes in cancellation logic to prevent customer confusion.

<Info>
  Need help setting this up? Contact our support team at [support@bookeeapp.com](mailto:support@bookeeapp.com)
</Info>