---
title: "Payment Methods"
description: "Configure and manage payment options for your fitness business"
---

# Payment Methods Configuration in Kenko

Offering flexible payment options is essential for providing a smooth experience for your members. Kenko supports multiple payment methods and helps you manage them securely.

## Supported Payment Methods

Kenko allows you to accept various payment types:

<CardGroup cols="2">
  <Card title="Credit & Debit Cards" icon="credit-card">
    Accept all major credit and debit cards including Visa, Mastercard, American Express, and Discover.
  </Card>
  <Card title="Bank Transfers (ACH)" icon="building">
    Direct transfers from members' bank accounts for recurring payments (US only).
  </Card>
  <Card title="Digital Wallets" icon="wallet">
    Support for Apple Pay, Google Pay, TWINT (Switzerland), and other mobile payment options.
  </Card>
  <Card title="Manual Payments" icon="money-bill">
    Record cash, check, or other offline payment methods.
  </Card>
</CardGroup>

## Setting Up Payment Processing

Before accepting payments, you need to configure your payment processing settings.

<Steps>
  <Step title="Access Payment Settings">
    Navigate to **Admin Settings** \> **Billing & Payments** \> **Payment Processing**.
  </Step>
  <Step title="Connect Payment Processor For Members">
    <Check>
      Connect Stripe or Adyen before processing online payments and enabling payment options from there
    </Check>
    Follow the integration steps for your chosen processor.

    _You can choose any payment method that the Payment Processing Getway supports for your Members._

    <Note>
      See our [Stripe Connection Guide](../../integrations/stripe/account-connection) for detailed setup instructions for our recommended processor.
    </Note>
  </Step>
  <Step title="Configure Payment Settings">
    Set your payment preferences

    - Default payment methods to accept
    - Auto-billing settings
    - Failed payment handling
    - Receipt and invoice customization
  </Step>
  <Step title="Test Your Configuration">
    Run a test transaction to ensure everything is working properly

    1. Enable test mode
    2. Process a test payment
    3. Verify it appears correctly in your payment processor dashboard
    4. Disable test mode when complete
  </Step>
</Steps>

## Enabling Apple Pay

Apple Pay is currently supported only on branded customer apps. Here's how to enable it via Stripe

<Steps>
  <Step title="Enable Apple Pay in Stripe">
    1. Log in to your Stripe Dashboard
    2. Navigate to **Settings** \> **Payment Methods**
    3. Under **Wallets**, toggle Apple Pay ON
  </Step>
  <Step title="Register Your Domain">
    1. Navigate to the Apple Pay section in Stripe and click **Add New Domain**
    2. Download and verify the domain using the CSR file
    3. Send the CSR to our support team at [support@bookeeapp.com](mailto:support@bookeeapp.com)
  </Step>
  <Step title="App Setup & Completion">
    The Kenko team will:

    - Register your merchant ID
    - Upload certificates to Stripe
    - Build and release the updated app version
    - Enable Apple Pay
  </Step>
</Steps>

## Enabling TWINT

TWINT is a Swiss mobile payment solution available only on the website version of Kenko (not in the app).

<Steps>
  <Step title="Enable TWINT in Stripe">
    1. Log into your Stripe Dashboard
    2. Go to **Settings** \> **Payments** \> **Payment Methods**
    3. Locate **TWINT** and toggle ON
  </Step>
  <Step title="Complete Setup if Required">
    You may be asked for additional compliance documents or business details. Provide them as needed to complete activation.
  </Step>
  <Step title="Check Activation Status">
    Monitor if the status is **Pending**. If it doesn't activate automatically, contact Stripe Support.
  </Step>
</Steps>

## Managing Member Payment Methods

### Adding Payment Methods for Members

<AccordionGroup>
  <Accordion title="During Member Registration" icon="user-plus">
    When creating a new member account:

    1. Go to the payment section of the form
    2. Click **Add Payment Method**
    3. Enter the details or let the member enter them
    4. Set it as default if applicable
  </Accordion>
  <Accordion title="For Existing Members" icon="user">
    1. Open the member's profile
    2. Navigate to the **Billing** tab
    3. Add and save a new payment method
  </Accordion>
  <Accordion title="Member Self-Service" icon="user-check">
    1. Members log into the member portal
    2. Go to **Account Settings** \> **Payment Methods**
    3. Add and manage their own payment methods

    <Note>
      All forms are PCI-compliant and secure.
    </Note>
  </Accordion>
</AccordionGroup>

### Managing Multiple Payment Methods

1. A default method is used for auto-payments
2. Members may choose different methods for one-time purchases
3. Default method can be changed at any time—either by staff or the member

## Handling Failed Payments

Kenko provides automated tools to help manage payment failures.

<Steps>
  <Step title="Configure Retry Settings">
    Navigate to **Admin Settings** \> **Billing & Payments** \> **Failed Payment Handling**
  </Step>
  <Step title="Set Retry Schedule">
    Customize the timing, number of retries, and intervals
  </Step>
  <Step title="Configure Notifications">
    Set up:

    - Failed payment alerts
    - Retry attempt alerts
    - Final reminders

    <Note>
      Manage templates in **Communications** \> **Email Templates**
    </Note>
  </Step>
  <Step title="Define Account Actions">
    Decide how to handle multiple failed payments:

    - Suspend access
    - Auto-cancel after threshold
    - Treat long-term members differently
  </Step>
</Steps>

### Manual Payment Resolution

1. Go to **Billing** \> **Failed Payments**
2. Select an issue and choose from:
   - Contacting the member
   - Retrying a new method
   - Creating a payment plan
   - Recording a manual payment

## Payment Security and Compliance

<CardGroup cols="2">
  <Card title="PCI Compliance" icon="shield">
    Kenko maintains PCI DSS compliance for secure card handling.
  </Card>
  <Card title="Data Protection" icon="lock">
    Payment data is encrypted and stored via Stripe/Square.
  </Card>
  <Card title="Fraud Prevention" icon="user-shield">
    Tools like AVS, CVV match, and fraud scores are built-in.
  </Card>
  <Card title="Secure Access" icon="key">
    Role-based access ensures sensitive data is only visible to authorized staff.
  </Card>
</CardGroup>

<Warning>
  Never store full credit card numbers in notes, emails, or chat. Kenko only shows the last four digits for reference.
</Warning>

## 