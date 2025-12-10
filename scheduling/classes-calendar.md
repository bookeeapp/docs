---
title: Classes in Calendar
description: >-
  Learn how to manage, schedule, and edit class sessions directly from the
  calendar interface in Kenko.
---

# Classes Calendar

Kenko's calendar allows you to view, schedule, and modify class sessions directly. This flexibility streamlines managing your schedule and ensures a smooth booking process for both admins and customers.

This guide explains

* How to add a class event from the calendar
* How recurring scheduling works
* How to edit existing sessions
* When to use the calendar vs class setup
* Communication and attendance tools available

## Adding a Class from Calendar

You can add one-off or recurring class sessions directly from the calendar interface.

Navigate to the \*\*Calendar\*\* from the sidebar and click the \*\*Add Event\*\* button.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.46.44PM.png"
  alt="Add Class Event"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Choose \*\*Class\*\* from the type options (Appointment, Class, Course, Blocked Time).

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.47.12PM.png"
  alt="Select Class Option"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

\- Select a class from the classes created in the \*\*Class Setup\*\* (this is mandatory). - Assign an instructor and a facility (optional). - Pick the date and time slot.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.57.32PM.png"
  alt="Class Details Input"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

- Set recurrence (optional).

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.59.54PM.png"
  alt="Recurrence Option"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Review the slot availability and click \*\*Add Class\*\* to finalize. The system will highlight any conflicts with other events or if the class is outside of the facility's working hours.

```
For recurring classes, it will display all future events and their availability conflicts. You can still choose whether to proceed with the class creation.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.02.33PM.png"
  alt="Confirm Availability"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Classes added from the calendar are \*\*detached instances\*\* — they don't follow the class type's default schedule unless explicitly made recurring.

***

## Editing and Managing Existing Classes

Click on any existing class in the calendar to access specific management actions.

All quick actions can be accessed by navigating to:

_**Side Navbar > Calendar > Specific Class > Sidebar**_

![Calendar Class View](../.gitbook/assets/Screenshot2025-04-21at2.04.44PM.png)The integrated booking flow in the calendar allows you to book customers who have suitable memberships. For customers without memberships or with unsuitable memberships, there is a Purchase and Book flow.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.49.26PM.png"
  alt="Booking a Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

While booking a customer into a class from the calendar, the admin has several options available:

- **Charge with Credits**: Apply credits if the customer has a valid membership.
- **Charge Later**: Allows payment to be collected at a later time.
- **Single or Recurring Class**: You can choose to add the customer to a single class or recurring classes. The recurrence will depend on the class setup, either from the Setup module or the Calendar setup.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.53.42PM.png"
  alt="Charge with Credits or Book Later"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

- **Choose a Membership**: If the customer has multiple memberships, you can select which one to deduct credits from.
- **Buy a New Membership**: If needed, purchase a new membership for the customer directly from the calendar.
```

You can send emails or text messages to customers who are booked, waitlisted, or both, directly from the class's calendar view.

```
_The "From" email address can be configured in the settings._

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at2.21.16PM.png"
  alt="Send Group Message"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

You can check in customers directly from the class view in the calendar.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.58.54PM.png"
  alt="Check-in Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

You can also cancel a customer's booking from the class view in the calendar.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at2.01.28PM.png"
  alt="Cancel Booking"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

You will be prompted to select a cancellation reason (optional).

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at2.04.10PM.png"
  alt="Cancellation Reason"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Class details can be edited if there are any changes to the schedule. This is useful if there are any updates required to the instructor, facility, or time.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at2.23.19PM.png"
  alt="Edit Class"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

In Kenko, you have the option to \*\*cancel\*\* or \*\*delete\*\* a class, depending on your needs. Here’s how these two actions differ:

```
### Cancel Class:

- **Effect on Bookings**: All bookings will be marked as "free cancellations." The session will remain on the calendar but with a "cancelled" status.
- **Customer Notification**: You can choose whether or not to send a cancellation notification to customers.
- **Reason for Cancellation**: You must select a reason such as "Staff Emergency," "Client Emergency," "Staff Sickness," etc.
- **Impact on Future Occurrences**: Cancelling a single class will not affect future scheduled instances (if recurring). Only the specific instance will be marked as cancelled.

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.29.02PM.png"
  alt="Cancel Class Screenshot"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

### Delete Class:

- **Effect on Bookings**: Completely removes the class from the calendar, including all bookings. This action deletes the class entirely.
- **Customer Notification**: You can choose whether or not to send a deletion notification to customers.
- **Reason for Deletion**: You must select a reason such as "Staff Emergency," "Client Emergency," "Staff Sickness," etc.
- **Impact on Future Occurrences**: Deleting a class removes it entirely from the schedule, including any future occurrences if it's a recurring class.

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.30.35PM.png"
  alt="Delete Class Screenshot"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

You can attach the recording link of the class if it is an online class.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.46.26PM.png"
  alt="Recording Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

For online classes, if Zoom integration setup is pending, a manual link still has to be added to the class.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.48.22PM.png"
  alt="Event Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

An overview of customers who have booked into the class, are waitlisted, or have cancelled the class is shown in tabs in the class view of the calendar.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.50.27PM.png"
  alt="Customer Booking Status"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

## Recurring Classes Nuances

When creating a class from the calendar, you can set it to **repeat** on a weekly pattern (e.g., every Monday and Wednesday).

This generates a recurring series — but still allows you to edit or cancel individual occurrences later.

### Editing Recurring Series

* If you **edit the entire series**, changes apply to all future unbooked sessions
* If you only edit a single instance, it becomes **detached** and behaves independently

## When to Use Calendar vs Class Setup

| Use Case                                       | Best Module |
| ---------------------------------------------- | ----------- |
| One-off class / trial / holiday session        | Calendar    |
| Standard weekly class (e.g., "Wed 6 PM Zumba") | Class Setup |
| Special event class or pop-up format           | Calendar    |
| Batch add 10+ sessions at once                 | Class Setup |

## Best Practices

Calendar will show warnings if your new class overlaps with another session using the same instructor or facility. Hide draft classes from customers until you're ready to go live. You can toggle visibility anytime. Recurring sessions keep your calendar cleaner and save time. Messaging tools are great for reminding attendees, sharing pre-class prep, or cancellations. After customers are booked, try to avoid making significant changes to the schedule or instructor, as it may cause confusion. Periodically check for class overlaps and resource conflicts to ensure a smooth schedule.

***
