---
title: "General Payments Settings"
description: "Configure payment modes, retry logic, enrollment eligibility, and global trial pack limits in Kenko"
---

# General Payment Settings in Kenko

Kenko offers flexible and powerful payment configuration tools to manage customer transactions efficiently. This guide walks you through how to customize payment modes, set retry and cancellation logic, configure enrollment fees, and control trial pack limits.

## Payment Modes

You can select the methods through which payments will be accepted at your studio.

<AccordionGroup>
  <Accordion title="Available Payment Modes" icon="credit-card">
    - **Credit/Debit Card (External)** (Default)
    - **Cash** (Default)

    The sole purpose of adding payment methods here is to mark any sale made from POS against the used payment method.

    This helps in keeping track of the payments in a more structured manner.

    You can enable or disable any method and remove custom ones.

    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at11.46.57AM.png"
      alt="Payment Modes"
      className="rounded-xl max-w-[700px] w-full shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Create a Custom Payment Mode" icon="circle-o">
    You can define new payment methods with custom icons.

    **Steps:**

    1. Click **Create a custom payment mode**
    2. Enter method name
    3. Upload an icon image (supports JPG, JPEG, PNG up to 2MB)

    <Note>
      Custom Payment methods appear while making any Sale from the POS or the Floating POS in Calendar
    </Note>
    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at11.47.05AM.png"
      alt="Create Custom Payment Mode"
      className="rounded-xl max-w-[500px] w-full shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Payment Types

<Accordion title="Pay Later" icon="clock">
  <Note>
    Enabling **Pay Later** lets members defer payments, which may lead to billing issues if not managed correctly.
  </Note>
  While booking a member from Kenko' platform into a Class or Appointment, Pay Later option will appear which can be later cleared off by the Member from the CRM or the Website and App.

  <div className="flex justify-center my-4">
  <img
    src="/images/Screenshot2025-04-24at11.47.19AM.png"
    alt="Pay Later Option"
    className="rounded-xl max-w-[700px] w-full shadow-sm"
  />

  </div>

  <Note>
    The Outstanding payment will appear in the Member's profile under the **Payments \> Order** Tab
  </Note>
</Accordion>

## Membership Cancellation Criteria

You can define what happens when a member's payment fails:

<AccordionGroup>
  <Accordion title="Cancel Immediately on Failure" icon="triangle-exclamation">
    Membership will be cancelled right after a failed attempt, following 3 retry attempts over 7 days.

    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at12.57.31PM.png"
      alt="Cancel Immediately"
      className="rounded-xl max-w-[700px] w-full shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Cancel After X Failures" icon="n">
    Set a specific number of failures (e.g., 2, 99) before cancellation.

    <Note>
      For each cycle, there will be 3 tries over the course of 7 days. For X cycle, there will be 3\*X tries before the membership is finally cancelled
    </Note>
    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at1.30.38PM.png"
      alt="Cancel After Failures"
      className="rounded-xl max-w-[700px] w-full shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Suspend Then Cancel" icon="pause">
    You can first suspend the member after a failure and cancel after a set number of days (e.g., 10 days).

    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at1.36.12PM.png"
      alt="Suspend Then Cancel"
      className="rounded-xl max-w-[700px] w-full shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Smart Retry Settings with Stripe

Kenko uses Stripe’s Smart Retry to retry failed payments at optimal times.

<Note>
  Do not modify Stripe’s retry settings unless necessary. Make sure the default status is **“leave the subscription as-is”**.
</Note>

Kenko uses **Stripe's Smart Retry** feature to handle failed payments efficiently. For every billing cycle, Stripe will retry the card **three times over seven days** using machine learning to pick the best times based on user behavior and device signals.

If **all retries fail**, Kenko:

- Will attempt this retry cycle up to **X times** (As configured).
- Adds an **unpaid due** tag and logs the customer in the **Amount Dues report**.
- Sends notifications to both the business and optionally, the customer.
- **Cancels the membership** only after all retries fail.

<Info>
  To ensure this works correctly, set your Stripe subscription status to **"leave the subscription as-is"** when retries fail. This prevents premature cancellation by Stripe.
</Info>

## Enrollment Fee Settings

You can charge enrollment fees based on whether the customer is new or returning.

<AccordionGroup>
  <Accordion title="New Customers" icon="user-plus">
    New customers will be charged an enrollment fee upon purchase of a Subscription
  </Accordion>
  <Accordion title="Existing Customers" icon="repeat">
    You can define a threshold (in months) after which returning customers are again considered eligible for enrollment fees.

    <div className="flex justify-center my-4">
    <img
      src="/images/Screenshot2025-04-24at11.49.45AM.png"
      alt="Enrollment Fees for Existing Customers"
      className="rounded-xl max-w-[700px] w-full shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Global Trial Pack Setting

Limit how frequently customers can purchase Trial Packs.

<Info>
  This is different from Trial Membership toggle in Credit Packs and only applies to the global purchase restriction.
</Info>

<div className="flex justify-center my-4">
<img
  src="/images/Screenshot2025-04-24at11.49.51AM.png"
  alt="Global Trial Pack Setting"
  className="rounded-xl max-w-[700px] w-full shadow-sm"
/>
</div>
Learn more about Intro Packs here

## Best Practices

<CardGroup cols="2">
  <Card title="Enable Pay Later Judiciously" icon="clock">
    Only allow Pay Later for trusted members. Monitor dues regularly to avoid cashflow issues.
  </Card>
  <Card title="Use Smart Retry Defaults" icon="rotate">
    Let Stripe optimize retry attempts to reduce failures. Avoid manual tweaks.
  </Card>
  <Card title="Limit Trial Pack Abuse" icon="shield-check">
    Define location- or business-level limits on trial packs to prevent repeated use.
  </Card>
  <Card title="Clarify Enrollment Fees" icon="info">
    Communicate eligibility and timing clearly to avoid customer confusion.
  </Card>
</CardGroup>

---