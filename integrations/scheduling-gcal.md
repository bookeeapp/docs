---
title: "Google Calendar Integration"
description: "Sync Kenko classes, appointments, and courses with your instructors’ Google Calendars for seamless scheduling."
---

# Sync Google Calendar with Kenko

Google Calendar integration allows your **instructors and staff** to automatically sync their classes, appointments, and courses from Kenko into their personal Google Calendars — ensuring everyone is always in the loop.

<Note>
  This integration enhances instructor visibility and reduces scheduling conflicts by ensuring events created in Kenko reflect in their connected personal calendar.
</Note>

## Why Use Google Calendar Integration?

<CardGroup cols={2}>
  <Card title="Personalized Schedules" icon="calendar">
    Instructors see their daily Kenko schedule directly in their personal calendar.
  </Card>
  <Card title="Reduce No-Shows" icon="bell">
    Improve punctuality with native calendar notifications and reminders.
  </Card>
  <Card title="Easy Access" icon="mobile">
    Events are visible across all devices via Google Calendar.
  </Card>
  <Card title="Real-Time Sync" icon="sync">
    Classes, courses, and appointments update instantly on staff calendars.
  </Card>
</CardGroup>

## Supported Events

The Google Calendar integration supports the following event types

- Classes
- Appointments
- Courses

Whenever one of these is scheduled for a staff member, it will automatically appear in their connected Google Calendar.

## Where to Set This Up?

<Steps>
  <Step title="Navigate to Integrations">
    Go to **Admin Settings** → **Integrations** → **Google Calendar**.
  </Step>
  <Step title="Install Integration">
    Click on the **Google Calendar** tile and press **Install**.

    ![Screenshot2025 05 12at5 12 04PM Pn](/images/Screenshot2025-05-12at5.12.04PM.png)
  </Step>
</Steps>

<Info>
  The integration only needs to be installed once per business. Individual staff must authorize calendar sync from their own profiles.
</Info>

## Connecting Individual Staff Calendars

After the admin has enabled Google Calendar in Kenko, staff must connect their individual calendars.

<Steps>
  <Step title="Log into Kenko">
    Staff should log into their Kenko web account.
  </Step>
  <Step title="Go to Google Calendar Integration">
    Navigate to **Admin Settings** → **Integrations** → **Google Calendar**.
  </Step>
  <Step title="Click 'Connect Google Cal'">
    Next to their name in the staff list, click **Connect Google Cal**.

    ![Screenshot2025 05 12at5 12 19PM Pn](/images/Screenshot2025-05-12at5.12.19PM.png)

    <div className="flex justify-center" />
  </Step>
  <Step title="Authorize Access">
    Staff will be redirected to log into Google and authorize access to their calendar. This grants Kenko permission to push events to their account.
  </Step>
</Steps>

<Note>
  You can revoke access anytime by clicking **Remove** in the integration settings.
</Note>

## What Happens After Connection?

Once connected, any scheduled class, appointment, or course that is assigned to the staff will:

- Appear automatically on their Google Calendar
- Include title, timing, and facility
- Be updated in real-time if edited in Kenko

## Sync Behavior and Use Cases

<AccordionGroup>
  <Accordion title="Do staff see personal events inside Kenko?" icon="user-secret">
    No, the integration is one-way. Kenko pushes events to Google Calendar, but staff personal events are not visible in Kenko.
  </Accordion>
  <Accordion title="What if a session is rescheduled in Kenko?" icon="clock-rotate-left">
    The calendar event is automatically updated on Google Calendar for the respective instructor.
  </Accordion>
  <Accordion title="Can staff disconnect anytime?" icon="link-slash">
    Yes. Each staff can disconnect their calendar by navigating back to the Google Calendar integration settings and clicking **Remove**.
  </Accordion>
</AccordionGroup>

## Best Practices for Google Calendar Integration

<CardGroup cols={2}>
  <Card title="Encourage All Staff to Connect" icon="user-plus">
    The integration is most effective when all instructors have synced calendars.
  </Card>
  <Card title="Regularly Reauthorize Access" icon="key">
    Google may revoke access after long inactivity. Ask staff to reconnect if events stop syncing.
  </Card>
  <Card title="Avoid Double-Booking" icon="ban">
    While personal events aren't visible in Kenko, staff should mark personal conflicts to avoid clashes.
  </Card>
  <Card title="Test Sync With a Sample Event" icon="flask">
    Create a test class and verify it appears on the instructor's Google Calendar after sync.
  </Card>
</CardGroup>

## Troubleshooting

If staff experience issues syncing

- Ensure Google Calendar is connected under the right email
- Confirm permissions were granted during authorization
- Check if the staff is assigned to the event in Kenko
- Revoke and reconnect the integration if sync breaks

For help, contact [Kenko Support](mailto:support@gokenko.com).

<Info>
  Stay organized, eliminate scheduling gaps, and empower your team — all with the power of Google Calendar \+ Kenko.
</Info>