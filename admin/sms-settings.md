---
title: "SMS Settings"
description: "Step-by-step guide to SMS setup in Kenko, including phone number configuration, US carrier compliance, and best practices."
---

import { Card, CardGroup, AccordionGroup, Accordion, Steps, Step, Callout } from '@mintlify/components'

# Configure numbers with Kenko

Kenko’s SMS Settings let you configure phone numbers, register with US carriers for compliance, and ensure reliable message delivery to your customers.

![Screenshot2025 05 17at1 05 49AM Pn](/images/Screenshot2025-05-17at1.05.49AM.png)

## Phone Number Configuration

<CardGroup cols={2}>
  <Card title="Unique Phone Number per Location" icon="phone">
    Each Kenko location requires a unique phone number. This number is the sender for SMS campaigns, journeys, and inbox messages for that location.\
    Using the same phone number for multiple locations will sync **all contacts and messages to just one location**, which may complicate communication management.
  </Card>
  <Card title="Compliance Status" icon="shield-check">
    Your phone number’s compliance status indicates if it’s registered and approved for sending SMS. Pending compliance means you need to complete US carrier registration before sending messages.
  </Card>
</CardGroup>

## US Carrier Registration

Kenko requires all virtual phone numbers sending SMS in the US to be A2P10DLC compliant. The registration process is handled via a wizard in Kenko’s SMS Settings.

<Steps>
  <Step title="Start Registration">
    Begin the wizard by providing your legal business name and tax ID to verify your business identity.

    ![Screenshot2025 05 17at1 06 00AM Pn](/images/Screenshot2025-05-17at1.06.00AM.png)
  </Step>
  <Step title="Provide Business Details">
    Enter your business type, registration numbers, and address. Accurate data here prevents application rejection.

    ![image.png](/images/image.png)

    ![image.png](/images/image.png)
  </Step>
  <Step title="Add Contacts">
    Submit authorized representative and technical contact information. These contacts handle compliance and technical communications.

    ![Screenshot2025 05 17at1 08 43AM Pn](/images/Screenshot2025-05-17at1.08.43AM.png)
  </Step>
  <Step title="Review and Submit">
    Confirm all information is correct and submit your registration for vetting by The Campaign Registry.
  </Step>
  <Step title="Messaging Details">
    Describe your typical SMS messages, campaigns, and opt-in processes. Providing clear, realistic examples improves approval chances.

    ![Screenshot2025 05 17at1 07 50AM Pn](/images/Screenshot2025-05-17at1.07.50AM.png)
  </Step>
</Steps>

<Info>
  Fees include a `$4 brand registration`, `$15 manual vetting`, and monthly `$1.50 maintenance`. Rejection incurs a `$15 resubmission fee`. Fees are billed to your credit card on file.
</Info>

## What Happens After Submission?

<AccordionGroup>
  <Accordion title="Application Review" icon="eye">
    The Campaign Registry reviews your submission for accuracy and compliance.
  </Accordion>
  <Accordion title="Approval or Request for More Information" icon="check">
    You will be notified if your registration is approved or if additional data is needed.
  </Accordion>
  <Accordion title="Maintaining Compliance" icon="gear">
    Keep your registration active by paying monthly fees and updating any changes in your business or messaging practices.
  </Accordion>
</AccordionGroup>

## International Considerations

Kenko currently requires US carrier compliance only. If you operate in other countries, please consult local regulations. Kenko will notify you if compliance requirements change.

## Best Practices for SMS Settings

<CardGroup cols={2}>
  <Card title="Use One Number per Location" icon="map-marker-alt">
    Avoid sharing phone numbers across locations to ensure accurate contact syncing and message routing.
  </Card>
  <Card title="Provide Complete and Accurate Info" icon="file-alt">
    During registration, provide all required business and messaging information thoroughly to avoid delays.
  </Card>
  <Card title="Keep Opt-in Records" icon="check-circle">
    Maintain records of customer consent to receive SMS to comply with laws and improve engagement.
  </Card>
  <Card title="Monitor Compliance Status" icon="eye">
    Regularly check your compliance status in Kenko and renew your registration when needed.
  </Card>
</CardGroup>

If you need help or have questions about SMS settings, please reach out to [Kenko Support](mailto:support@gokenko.com).