---
title: "Roles and Privileges"
description: "Set up secure, scalable access control for your team using roles and privileges in Kenko."
keywords: "roles,permissions,admin,access control,staff setup"
sidebar_label: "Roles & Privileges"
---

import { Steps, Step, AccordionGroup, Accordion, CardGroup, Card } from "@/components/ui"

# Setting Up Roles and Privileges

Kenko gives you fine-grained control over who can access what in your studio. By setting up roles and privileges, you ensure your team sees only the features and data they need — no more, no less.

## Why Roles and Privileges Matter

<AccordionGroup>
  <Accordion title="Protect Sensitive Information" icon="lock">
    Restrict access to billing, CRM, and admin settings to ensure that only authorized users handle sensitive operations.
  </Accordion>
  <Accordion title="Streamline Staff Workflows" icon="layer-group">
    Give staff access only to the tools they need. Instructors see their schedule, front desk sees the calendar and check-ins, and admins control the backend.
  </Accordion>
  <Accordion title="Support Team Growth" icon="users">
    Use prebuilt roles or create custom ones to scale team onboarding while keeping permissions secure and organized.
  </Accordion>
  <Accordion title="Avoid Operational Errors" icon="triangle-exclamation">
    Prevent accidental changes or unauthorized actions by clearly defining what each role is allowed to do.
  </Accordion>
</AccordionGroup>

## How to Set Up Roles

<Steps>
  <Step title="Navigate to Roles and Privileges">
    Go to **_Admin Settings → Roles and Privileges_** from your Kenko dashboard.

    ![Screenshot2025 05 15at4 29 31PM Pn](/images/Screenshot2025-05-15at4.29.31PM.png)
  </Step>
  <Step title="Create or Edit a Role">
    Click **Add Role** to create a new role, or select Edit next to an existing one to customize permissions.

    ![Screenshot2025 05 15at4 29 55PM Pn](/images/Screenshot2025-05-15at4.29.55PM.png)
  </Step>
  <Step title="Set Name and Permissions">
    Give the role a clear name like “Instructor” or “Front Desk”, then toggle access to different sections

    - Contacts & POS
    - Operations (Calendar, Tasks, Reports)
    - Admin (Setup, Attendance, Billing)
    - Inbox
    - Website Builder
    - Business App

    ![Screenshot2025 05 15at4 30 12PM Pn](/images/Screenshot2025-05-15at4.30.12PM.png)
  </Step>
  <Step title="Save Changes">
    Click Save Changes to activate the role configuration.
  </Step>
  <Step title="Assign to Staff">
    Go to Staff → Edit Staff and assign the appropriate role from the dropdown. Else while adding a Staff assign them a role.
  </Step>
</Steps>

## Common Role Use Cases

<CardGroup cols={2}>
  <Card title="Instructor" icon="user">
    Sees only their calendar and task assignments. Cannot access CRM or reports.
  </Card>
  <Card title="Receptionist" icon="badge-check">
    Can manage check-ins, POS, and client bookings, but cannot view billing or change global settings.
  </Card>
  <Card title="Studio Admin" icon="user">
    Full access to scheduling, staff, attendance, reports, and customer profiles. No billing access.
  </Card>
  <Card title="Finance Manager" icon="credit-card">
    Can view and export financial reports, but doesn’t access the CRM or calendar.
  </Card>
</CardGroup>

## Best Practices

<AccordionGroup>
  <Accordion title="Use Templates for Common Roles" icon="list">
    Create standard roles like “Instructor”, “Sales”, and “Manager” so you can apply them consistently when onboarding new team members.
  </Accordion>
  <Accordion title="Review Roles Every Quarter" icon="rotate">
    As your studio grows, check permissions to make sure staff access matches their responsibilities.
  </Accordion>
  <Accordion title="Don’t Over-Permission" icon="eye">
    Give each team member the minimum access required to do their job well. This protects your data and reduces mistakes.
  </Accordion>
  <Accordion title="Combine with Attendance & Tasks" icon="circle-check">
    Use role access to control who can view attendance logs, complete internal tasks, and access operations data.
  </Accordion>
</AccordionGroup>

Need help planning your roles and team structure? Contact [support@kenko.com](mailto:support@kenko.com) — we’re happy to advise based on your business model.