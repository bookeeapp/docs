---
title: "Waivers Setup"
description: "A step-by-step guide to creating, customizing, and applying digital waivers in Kenko to protect your studio and streamline onboarding."
keywords: "waivers,liability,forms,legal,agreements,studio policies"
sidebar_label: "Creating Waivers"
---

import { Steps, Step, AccordionGroup, Accordion } from "@/components/ui"

# Creating Waivers in Kenko

Waivers are one of the most essential pieces of your studio's legal infrastructure. Whether it’s for general liability, minors, or a specialized program — a properly signed waiver ensures protection for both your business and your clients.

Kenko makes it easy to create, automate, and collect digital waivers — with e-signatures, tracking, and flexible triggers.

## How to Access and Create Waivers

<Steps>
  <Step title="Access Waivers">
    Go to **Settings → Agreements**.\
    This is your central hub for managing all Waivers

    ![Screenshot2025 05 14at3 47 28PM Pn](/images/Screenshot2025-05-14at3.47.28PM.png)

    _You can also edit waivers from here._

    <Note>
      You cannot delete a Waiver. Although it is possible to Replace it with a new version or Pause the waiver.
    </Note>
  </Step>
  <Step title="Click 'Add New Form'">
    Select **Add New Agreement**, then choose **Waiver** as the form type.
  </Step>
  <Step title="Enter Title & Description">
    Give your waiver a clear internal title (e.g., “General Liability Waiver”).\
    Optionally add a short description so staff understand its purpose.

    ![Screenshot2025 05 14at3 37 31PM Pn](/images/Screenshot2025-05-14at3.37.31PM.png)
  </Step>
  <Step title="Choose Trigger Rules">
    Decide when this waiver should be shown to clients

    - On **first login/signup**
    - Before purchasing a specific **membership**
    - When booking **certain classes or appointments**
    - Linked to **intro offers**, **minors**, or **challenges**

    <Note>
      Waivers can be set Business wide, at Region level or at Location level.
    </Note>
    ![Screenshot2025 05 14at3 37 45PM Pn](/images/Screenshot2025-05-14at3.37.45PM.png)

    Furthermore, Agreements can be either sent via email after Purchase or during the Checkout Process before the Purchase.

    <Note>
      In-flow waivers are mandatory for purchase and have a high-rate of completion. While waivers sent via e-mail do not have a high completion rate. For essential waivers, Kenko recommends setting it to be in-flow.
    </Note>
    You can also set how frequently the waiver email should be sent to the customer if it is triggered via email.

    ![Screenshot2025 05 14at3 37 55PM Pn](/images/Screenshot2025-05-14at3.37.55PM.png)
  </Step>
  <Step title="Write the Waiver Body">
    Enter the full legal content of the waiver.\
    You can use headers, paragraphs, and bullet points to structure your content.

    > Make sure to include liability terms, cancellation/refund conditions, and any age or health disclaimers.

    ![Screenshot2025 05 14at3 38 37PM Pn](/images/Screenshot2025-05-14at3.38.37PM.png)

    You can use Variable Tags that automatically populate based on the Contact's details.
  </Step>
  <Step title="Signature Requirement">
    **Digital Signature** Tag is a required Tag to enforce e-signature collection at the time of submission. You can put other tags as well along with the mandatory tag.

    ![Screenshot2025 05 14at3 38 45PM Pn](/images/Screenshot2025-05-14at3.38.45PM.png)
  </Step>
  <Step title="Preview and Publish">
    Use the Preview to check formatting and signature flow.\
    Once you're ready, click **Publish** — the waiver is now active and will trigger based on your setup.
  </Step>
  <Step title="Draft E-mail Body">
    Incase the waiver is being sent over email, you can also customize the e-mail body with Variable Tags.

    ![Screenshot2025 05 14at3 39 09PM Pn](/images/Screenshot2025-05-14at3.39.09PM.png)

    Some Custom Tags include the following

    ![Screenshot2025 05 14at3 39 16PM Pn](/images/Screenshot2025-05-14at3.39.16PM.png)
  </Step>
</Steps>

## When Should You Use Waivers?

| **Use Case**                    | **When to Trigger**                          |
| ------------------------------- | -------------------------------------------- |
| General Studio Liability        | First login or first booking                 |
| Underage Participation (Minors) | At sign-up or booking if date of birth \< 18 |
| Event/Challenge Waivers         | Attached to the challenge or course start    |
| Special Services (e.g. Massage) | Before booking the specific service          |
| Medical Declarations            | First session or recurring per visit         |

You can link waivers to services, memberships, or customer types — and Kenko handles the rest.

## Best Practices for Studio Waivers

<AccordionGroup>
  <Accordion title="Use Simple, Legally-Sound Language" icon="scale-unbalanced">
    Avoid legal jargon overload. Clients should understand what they’re signing. If unsure, consult your local legal advisor.
  </Accordion>
  <Accordion title="Trigger Waivers Intelligently" icon="bolt">
    Only ask for what’s necessary. Don’t force all clients to sign every waiver. Use contextual triggers (e.g., first booking vs. membership purchase).
  </Accordion>
  <Accordion title="Keep Copies for Compliance" icon="file-check">
    Kenko stores all signed waivers under the client profile, so you're always audit-ready.
  </Accordion>
  <Accordion title="Make It Mobile-Friendly" icon="mobile">
    Most users will sign from their phones. Preview on mobile and keep content scrollable but readable.
  </Accordion>
  <Accordion title="Update Annually or When Policies Change" icon="pen">
    Whenever you update terms or add new disclaimers, duplicate the waiver, edit it, and re-trigger it for affected members.
  </Accordion>
</AccordionGroup>