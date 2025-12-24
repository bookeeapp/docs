---
title: "Form Setup"
description: "Learn how to create and automate embedded and activity-based forms in Kenko"
keywords: "forms,activity-based forms,embedded forms,form automation"
sidebar_label: "Form Setup"
---

import { Steps, Step, AccordionGroup, Accordion, CardGroup, Card } from "@/components/ui"

# Setting up Forms in Kenko

Kenko allows you to collect structured information from clients via digital forms. Whether you're capturing lead details, onboarding new members, or collecting health disclosures, forms help streamline client experiences and internal operations.

## Types of Forms

Kenko supports two types of forms, both using the same form builder but differing in how they are delivered.

| Feature                  | Shareable / Embedded Form            | Activity-Based Form                      |
| ------------------------ | ------------------------------------ | ---------------------------------------- |
| Requires login           | No                                   | Yes                                      |
| Delivery method          | Manual sharing / Embedded on website | Triggered via signup or purchase actions |
| Automation supported     | No                                   | Yes                                      |
| Use cases                | Lead capture, feedback forms         | Onboarding, Health declarations          |
| Customizable fields      | Yes                                  | Yes                                      |
| Connected to CRM/contact | Optional                             | Always synced to contact                 |

> Both form types use the same layout and field options — the only difference is that activity-based forms have a powerful automation layer.

## Creating a Form

<Steps>
  <Step title="Go to Setup → Forms">
    In your Kenko admin dashboard, navigate to **Setup → Forms**.\
    Click **Create form** in the top-right corner.

    ![Screenshot2025 05 14at5 01 53PM Pn](/images/Screenshot2025-05-14at5.01.53PM.png)
  </Step>
  <Step title="Select Form Type">
    Choose between

    - **Shareable / Embedded Form**: Forms that can be shared via a public URL or embedded on a website.
    - **Activity-Based Form**: Forms triggered automatically during client activity (e.g., signup or purchase).

    ![Screenshot2025 05 14at5 02 01PM Pn](/images/Screenshot2025-05-14at5.02.01PM.png)
  </Step>
  <Step title="Build the Form">
    Use the drag-and-drop builder to add fields

    - Text inputs (single-line or multi-line)
    - Email, phone, number, dropdowns
    - Date pickers
    - Checkboxes and headers

    You can also bind fields to existing or new contact properties.

    ![Screenshot2025 05 14at5 02 42PM Pn](/images/Screenshot2025-05-14at5.02.42PM.png)
  </Step>
  <Step title="Save and Embed (for Shareable)">
    If using a shareable/embedded form

    - Click **Save**
    - Use the **Get Embed Code** button to copy the iframe or direct URL for use on your website or landing page

    ![Screenshot2025 05 14at5 03 03PM Pn](/images/Screenshot2025-05-14at5.03.03PM.png)
  </Step>
  <Step title="Configure Automation (for Activity-Based)">
    If using an activity-based form

    - Enable **automation**
    - Set when to trigger the form (e.g., on signup, after purchase)
    - Define which **locations** or **regions** the rule applies to
    - Configure **email timing** and **reminders**

    ![Screenshot2025 05 14at5 04 42PM Pn](/images/Screenshot2025-05-14at5.04.42PM.png)

    ![Screenshot2025 05 14at5 04 50PM Pn](/images/Screenshot2025-05-14at5.04.50PM.png)

    Currently Activity-Based Forms can only be sent via email after the trigger. You can customize the email through which the form will be sent.
  </Step>
  <Step title="Form Responses" icon="users">
    You can access the form responses by navigating to Settings \> Forms \> Particular Form \> Download responses.

    ![Screenshot2025 05 14at6 53 02PM Pn](/images/Screenshot2025-05-14at6.53.02PM.png)

    _Additional options here are Preview and Delete form._
  </Step>
</Steps>

## Use Case Examples

<CardGroup cols={2}>
  <Card title="Lead Capture" icon="user-plus">
    Use an embedded form on your website to collect interest from potential clients. No login required.
  </Card>
  <Card title="Medical History Intake" icon="stethoscope">
    Use an activity-based form that is sent immediately after someone purchases a membership or course.
  </Card>
  <Card title="Waiver Agreement" icon="file-check">
    Trigger this on first login or at the time of booking. Automatically includes e-signature field.
  </Card>
  <Card title="Challenge Signup" icon="flag">
    Ask participants to complete a short form with goals or disclaimers when joining a studio challenge.
  </Card>
</CardGroup>

## Best Practices

<AccordionGroup>
  <Accordion title="Name Forms Clearly" icon="pen">
    Use names that reflect both purpose and trigger. For example, “Signup Health Form” or “Pole Party Lead Form”.
  </Accordion>
  <Accordion title="Use as Few Fields as Possible" icon="file-waveform">
    Only ask for what you really need. Long forms reduce completion rates.
  </Accordion>
  <Accordion title="Test Embeds on Mobile" icon="mobile">
    If embedding a form, check how it renders on small screens and ensure scroll/zoom works correctly.
  </Accordion>
  <Accordion title="Use Reminders for Activity-Based Forms" icon="lightbulb">
    Set up automated reminders every few days until a form is completed to reduce manual follow-up.
  </Accordion>
  <Accordion title="Link to CRM Properties" icon="link">
    Always map form responses to contact fields when the data will be used in follow-ups, segmentation, or reporting.
  </Accordion>
</AccordionGroup>