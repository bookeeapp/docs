---
title: Courses in Calendar
description: Description of your new file.
---

# Courses Calendar

Kenko's calendar allows you to not only view all courses but also schedule, modify, and manage them directly. This enables full control over your courses while ensuring easy accessibility for both admins and customers.

Unlike Classes and Appointments, you can only add Course instances in the calendar.

This guide explains

* How to add a course instance from the calendar
* How to edit existing courses instances
* Communication and attendance tools available

## Adding a Course from Calendar

You can add one-off or recurring course sessions directly from the calendar interface.

Navigate to the \*\*Calendar\*\* from the sidebar and click the \*\*Add Event\*\* button.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at12.46.44PM.png"
  alt="Add Course Event"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

Choose \*\*Course\*\* from the type options (Appointment, Class, Course, Blocked Time).

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at7.53.09PM.png"
  alt="Select Course Option"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

\- Select a course group and course name from the already created courses in the Course Setup (this is mandatory). - Choose a facility for that particular course instance, A facility will pre-populate based on the initial course setup. - Pick the date and time slot for the course instance

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at7.53.23PM.png"
  alt="Course Details Input"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<Note>
  There is not recurrence in Course instances as Courses are itself recurring in nature. Addition of Course instances are important if any special event has to be added in the already setup course schedule.
</Note>
<div className="flex justify-center" />
```

Review slot availability and click \*\*Add Course\*\* \*\*instance\*\* to finalize. The system will highlight any overlapping with another event or whether the course is outside the facility’s working hours.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at7.53.38PM.png"
  alt="Course Details Input"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<div className="flex justify-center" />
```

Courses added from the calendar are \*\*detached instances\*\* — they don't follow the course type's default schedule unless explicitly made recurring.

## Editing and Managing Existing Courses

Click on any existing course in the calendar to access specific management actions.

All quick actions can be accessed by navigating to

_**Side Navbar > Calendar > Specific Course instance > Side panel**_

![Calendar Course View](../../../.gitbook/assets/Screenshot2025-04-21at8.40.07PM.png)When booking customers into a \*\*course\*\*, you're adding them to the \*\*entire course\*\* rather than individual sessions. This ensures that the customer is enrolled for all scheduled instances of that course.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at8.21.29PM.png"
  alt="Booking a Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

The entire Point of Sale opens in the calendar itself which enables the Admin to enroll customer to the entire course.
```

You can send emails or text messages to customers who are booked, waitlisted, or both, directly from the course's calendar view.

```
_The "From" email address can be configured in the settings._

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at8.35.42PM.png"
  alt="Send Group Message"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

You can check-in customers directly from the course view in the calendar.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at1.58.54PM.png"
  alt="Check-in Customer"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

You can also cancel a customer's booking from the course view in the calendar. If the customer's booking is cancelled, they will be removed from all instances of the course.

<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at2.01.28PM.png"
  alt="Cancel Booking"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
 <div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at8.42.29PM.png"
  alt="Cancel Booking"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<div className="flex justify-center" />
```

Course details can be edited if there are any changes to the schedule. This is useful if there are updates required to the instructor, facility, or time.

```
<div className="flex justify-center">
<img
  src="/images/Screenshot2025-04-21at8.39.27PM.png"
  alt="Edit Course"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

In Kenko, you have the option to \*\*delete\*\* a course, depending on your needs. Here’s how these two actions differ

```
### Delete Course

- **Effect on Bookings**: Completely removes the course from the calendar, including all bookings. This action deletes the course entirely.
- **Customer Notification**: You can choose whether or not to send a deletion notification to customers.
- **Reason for Deletion**: You must select a reason such as "Staff Emergency," "Client Emergency," "Staff Sickness," etc.
- **Impact on Future Occurrences**: Deleting a course removes it entirely from the schedule, including any future occurrences if it's a recurring course.

<div className="flex justify-center mt-4">
<img
  src="images/Screenshot2025-04-21at8.37.21PM.png"
  alt="Cancel Course Screenshot"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>

<div className="flex justify-center mt-4" />
```

You can attach the recording link of the course if it is an online course.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.46.26PM.png"
  alt="Recording Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

For online courses, if Zoom integration setup is pending, a manual link still has to be added to the course.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.48.22PM.png"
  alt="Event Link"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

An overview of customers who have booked into the course, are waitlisted, or have cancelled the course is shown in tabs in the course view of the calendar.

```
<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-21at2.50.27PM.png"
  alt="Customer Booking Status"
  className="max-w-[400px] w-full rounded-lg shadow-sm"
/>

</div>
```

## When to Use Calendar vs Course Setup

| Use Case                                       | Best Module  |
| ---------------------------------------------- | ------------ |
| One-off course / trial / holiday session       | Calendar     |
| Standard weekly course (e.g., “Mon 6 PM Yoga”) | Course Setup |
| Special event course or pop-up format          | Calendar     |
| Batch add 10+ courses at once                  | Course Setup |

***

## Best Practices

The calendar will show warnings if your new course overlaps with another session using the same instructor or facility. Hide draft courses from customers until you're ready to go live. You can toggle visibility anytime. Recurring courses help keep your calendar organized and save you time. Messaging tools are perfect for reminding attendees, sharing pre-course prep, or cancellations.
