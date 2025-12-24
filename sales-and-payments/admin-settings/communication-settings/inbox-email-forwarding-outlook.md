---
title: "Email Forwarding in Outlook"
description: "Guide to routing your Outlook emails directly into your Kenko Inbox, with step-by-step instructions and admin-level setup."
---

import { Steps, Step, Callout } from '@mintlify/components'

# Forward Your Outlook Emails into Kenko

Want all your client emails to magically appear inside your **Kenko Inbox**? ✨\
You're in the right place. This guide walks you through setting up **email forwarding in Outlook**, specifically for **Microsoft 365 workspace accounts** — so all incoming emails land where your team already works.

> This setup involves a one-time admin-level configuration \+ a user-level tweak. After that, all Outlook emails flow straight into Kenko.

## Admin-Level Setup (Microsoft 365)

These steps must be done by someone with **Global Admin privileges** in your Microsoft workspace.

<Steps>
  <Step title="Log in to Microsoft 365 Security Settings">
    Go to [security.microsoft.com](https://security.microsoft.com) and sign in as a Global Admin.
  </Step>
  <Step title="Navigate to Email & Collaboration">
    In the left sidebar, head over to **Email & Collaboration** \> **Policies & Rules**.

    ![Screenshot2025 05 14at5 36 36PM Pn](/images/Screenshot2025-05-14at5.36.36PM.png)
  </Step>
  <Step title="Open Anti-Spam Policies">
    Select **Threat Policies** \> **Anti-spam policies**.

    ![Screenshot2025 05 14at5 38 13PM Pn](/images/Screenshot2025-05-14at5.38.13PM.png)

    ![Screenshot2025 05 14at5 39 36PM Pn](/images/Screenshot2025-05-14at5.39.36PM.png)
  </Step>
  <Step title="Edit the Default Policy">
    Click on the **Anti-spam outbound policy (Default)** to open settings.

    ![Screenshot2025 05 14at5 40 22PM Pn](/images/Screenshot2025-05-14at5.40.22PM.png)
  </Step>
  <Step title="Enable Forwarding">
    Under **Protection Settings**, look for **Automatic Forwarding Rules**

    ![Screenshot2025 05 14at5 41 13PM Pn](/images/Screenshot2025-05-14at5.41.13PM.png)

    .Set it to `On – Forwarding is enabled`, and click **Save**.

    ![Screenshot\+2025 05 14\+at\+5 42 19%E2%80%AFPM Pn](/images/Screenshot+2025-05-14+at+5_42_19%E2%80%AFPM.png)
  </Step>
</Steps>

<Info>
  This ensures all users in your organization are allowed to forward emails from Outlook to external inboxes like Kenko.
</Info>

## User-Level Setup (Outlook)

Now let’s configure forwarding for your specific Outlook mailbox.

<Steps>
  <Step title="Go to Outlook Settings">
    Open your Outlook account, click the ⚙️ icon, and go to **Settings** \> **Email** \> **Forwarding**.
  </Step>
  <Step title="Enable Email Forwarding">
    - Check **Enable forwarding**
    - Enter the email address from your Kenko Inbox email settings
    - (Optional) Tick “Keep a copy of forwarded messages” if you want a backup in Outlook
    - Click **Save**

    ![Screenshot2025 05 14at5 46 14PM 2 Pn](/images/Screenshot2025-05-14at5.46.14PM-2.png)
  </Step>
</Steps>

## You’re All Set\!

🎉 It’s a few steps, but once done, **every email** that hits your Outlook will also arrive in your Kenko Inbox. No more switching tabs or missing follow-ups — just unified messaging in one place.

If you get stuck or want help verifying your setup, just ping us at [support@spyn.co](mailto:support@spyn.co).

---