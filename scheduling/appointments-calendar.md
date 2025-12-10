---
title: Managing Appointments via Calendar
description: >-
  Learn how to manage, schedule, and edit appointments directly from the
  calendar interface in Kenko
---

# Appointments Calendar

Kenko's calendar allows you to not only view all appointments but also schedule, modify, and manage them directly. This enables you to have full control over your appointments while providing flexibility for your customers.

This guide explains

* How to add an appointment from the calendar
* How recurring appointment scheduling works
* How to edit existing appointments
* Communication and attendance tools available

## Adding an Appointment from Calendar

You can add one-off or recurring appointment sessions directly from the calendar interface.

Navigate to the \*\*Calendar\*\* from the sidebar and click the \*\*Add Event\*\* button.

```
<Note>
  You can also click on a particular date and time to open the Add Event Panel with the selected date and time. 
</Note>
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.46.44PM.png"
  alt="Add Appointment Event"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Choose \*\*Appointment\*\* from the type options (Appointment, Class, Course, Blocked Time).

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.23.02PM.png"
  alt="Select Appointment Option"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

\- Select the appointment type (e.g., Physiotherapy, Massage, Nutrition Consult) - Assign an instructor or facility (whichever is applicable) - Pick the date and time slot

```
<Note>
  For appointments, the selection of either Instructor or Facility or both is essential as they are either Facility-led or Instructor-led
</Note>
You can also choose whether to or whether or not to send Notification about the appointment to the Customer(s)

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.26.14PM.png"
  alt="Appointment Details Input"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

- Set recurrence (optional)

You can also select whether to repeat an appointment with selected customers over a period of time.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.28.37PM.png"
  alt="Appointment Details Input"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Review the slot availability and click \*\*Add Appointment\*\* to finalize. The system will highlight any conflicts with another event incase the Facility or the Instructor are not available.

```
For recurring appointments, it will display all future events and their availability conflicts. You can still choose whether to proceed with the appointment creation.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.30.16PM.png"
  alt="Confirm Availability"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Select the customer for the appointment and select a membership for them from which they wish to deduct the credits from.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.32.43PM.png"
  alt="Confirm Availability"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

You can choose whether to charge with credits or charge later.

Quick-pay option is available too if it has been setup while creating the appointment in the setup module.
```

Appointments added from the calendar are \*\*detached instances\*\* — they don't follow the appointment type's default schedule unless explicitly made recurring.

## Editing and Managing Existing Appointments

Click on any existing appointment in the calendar to access specific management actions.

All quick actions can be accessed by navigating to:

_**Side Navbar > Calendar > Specific Appointment > Sidebar**_

![Booking a Customer](../.gitbook/assets/Screenshot2025-04-21at4.44.46PM.png)Incase the appointment allows for more than one customer to be booked ( As set during appointment creation ), more customers can be booked into the appointment.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.47.06PM.png"
  alt="Booking a Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

While booking a customer into an appointment from the calendar, the admin has several options available:

- **Charge with Credits**: Apply credits if the customer has a valid membership.
- **Charge Later**: Allows payment to be collected at a later time.
- **Single or Recurring Appointment**: You can choose to add the customer to a single appointment or recurring appointments. The recurrence will depend on the appointment setup, either from the Setup module or the Calendar setup.

<div className="flex justify-center" />

- **Choose a Membership**: If the customer has multiple memberships, you can select which one to deduct credits from.
- **Buy a New Membership**: If needed, purchase a new membership for the customer directly from the calendar.
```

You can send emails or text messages to customers who are booked directly from the appointment's calendar view.

```
_The "From" email address can be configured in the settings._

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.49.24PM.png"
  alt="Check-in Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<div className="flex justify-center" />
```

You can check-in customers directly from the appointment view in the calendar.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.58.54PM.png"
  alt="Check-in Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

You can also cancel or delete customer's booking from the appointment view in the calendar.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.51.31PM.png"
  alt="Cancellation Reason"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<div className="flex justify-center" />

You will be prompted to select a cancellation reason (optional) for both deletion and cancellation of the Customer's booking.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at5.34.39PM.png"
  alt="Cancellation Reason"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Appointment details can be edited if there are any changes to the schedule. This is useful if there are any updates required to the instructor, facility, or time.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at4.48.24PM.png"
  alt="Edit Appointment"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

In Kenko, you have the option to \*\*cancel\*\* or \*\*delete\*\* an appointment, depending on your needs. Here's how these two actions differ:

```
### Cancel Appointment:

- **Effect on Bookings**: All bookings will be marked as "free cancellations." The session will remain on the calendar but with a "cancelled" status.
- **Customer Notification**: You can choose whether or not to send a cancellation notification to customers.
- **Reason for Cancellation**: You must select a reason such as "Staff Emergency," "Client Emergency," "Staff Sickness," etc.
- **Impact on Future Occurrences**: Cancelling a single appointment will not affect future scheduled instances (if recurring). Only the specific instance will be marked as cancelled.

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at5.35.24PM.png"
  alt="Cancel Appointment Screenshot"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

### Delete Appointment:

- **Effect on Bookings**: Completely removes the appointment from the calendar, including all bookings. This action deletes the appointment entirely.
- **Customer Notification**: You can choose whether or not to send a deletion notification to customers.
- **Reason for Deletion**: You must select a reason such as "Staff Emergency," "Client Emergency," "Staff Sickness," etc.
- **Impact on Future Occurrences**: Deleting an appointment removes it entirely from the schedule, including any future occurrences if it's a recurring appointment.

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at5.36.02PM.png"
  alt="Delete Appointment Screenshot"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

You can attach the recording link of the appointment if it is an online session.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.46.26PM.png"
  alt="Recording Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

For online appointments, if Zoom integration setup is pending, a manual link still has to be added to the appointment.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.48.22PM.png"
  alt="Event Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

You can submit attendance once you check-in all the customers to the appointment after the appointment completion.

```
<Note>
  Customers should check-in before submitting the attendance else they will be marked as no-show. You can also enable auto-attendance submission from Booking settings.
</Note>
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at6.04.22PM.png"
  alt="Event Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

## Recurring Appointments Nuances

When creating an appointment from the calendar, you can set it to **repeat** on a weekly pattern (e.g., every Monday and Wednesday).

This generates a recurring series — but still allows you to edit or cancel individual occurrences later.

### Editing Recurring Series

* If you **edit the entire series**, changes apply to all future unbooked sessions
* If you only edit a single instance, it becomes **detached** and behaves independently

## When to Use Calendar vs Appointment Setup

| Use Case                                           | Best Module       |
| -------------------------------------------------- | ----------------- |
| One-off appointment / trial / holiday session      | Calendar          |
| Standard recurring appointment (e.g., "Mon 10 AM") | Appointment Setup |
| Special event or pop-up appointment                | Calendar          |
| Batch add 10+ appointments at once                 | Appointment Setup |

## Best Practices

Calendar will show warnings if your new appointment overlaps with another session using the same instructor or facility. Hide draft appointments from customers until you're ready to go live. You can toggle visibility anytime. Recurring appointments keep your calendar cleaner and save time. Messaging tools are great for reminding attendees, sharing pre-appointment prep, or cancellations. After customers are booked, avoid making significant changes to the schedule, as it may confuse them. Periodically check for appointment overlaps and resource conflicts to ensure a smooth schedule.

***
