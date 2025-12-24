---
title: Courses & Workshop Setup
description: >-
  Learn how to create, configure, and price courses in Kenko with group
  structure, scheduling, and installment options.
---

# Courses Setup

Kenko’s **Courses** module is designed to support structured, multi-session programs such as certifications, workshops, or progressive skill tracks. Unlike classes or appointments, courses have defined start/end dates, consistent instructors, and fixed batch sizes.

This guide walks through the full lifecycle: grouping, configuring, and scheduling courses.

## Course Lifecycle

Courses in Kenko can be created via

Navigating to the side \*\*Nav-bar → Setup → Courses & Workshops\*\*

From here, you will be able to

* **Create Groups**: Organize multiple related courses under one umbrella
* **Create Courses**: Define the sessions, price, and rules for each course
* **Edit or Delete**: Modify future courses or clean up test versions

![Courses and Workshops dashboard](../../../.gitbook/assets/Screenshot2025-04-16at5.59.36PM.png)## Configuration and Setup of Courses

Course creation is split into **3 stages**

### Basic Details

Select a group under which this course will live. Then give it a meaningful name (e.g., “Teacher Training – Level 1” or “6-Week Strength Bootcamp”).

```
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.04.37PM.png"
    alt="Course group and name"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Upload a banner image under 2MB to represent the course. Add a description that clearly explains the purpose and structure of the program.

```
<Info>
  Adding images is very important for Flagship courses.
</Info>
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.06.46PM.png"
    alt="Upload image and category"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Assign one or more instructors and choose the facility where the course takes place. Optionally toggle if it’s an online course.

```
<Info>
  Incase it is an online course, You will get the option to choose whether to Add Zoom Link or add links to the session manually.
</Info>
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.09.33PM.png"
    alt="Instructor and course type"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Toggle visibility to customers and optionally highlight as a featured course.

```
Featured courses highlight the course to your customers.

<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.13.55PM.png"
    alt="Visibility and featured toggles"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Define when the course will run. All session logic and enrollments will be restricted to this date range.

```
<Note>
  Additional sessions can be added to the Course past its end date after it's creation. This does not change the Course' end date across CRM and Customer facing interfaces.
</Note>
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.12.25PM.png"
    alt="Start and end dates"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Pick a color to easily distinguish this course in the calendar.

```
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.14.58PM.png"
    alt="Color tag selector"
    className="max-w-[300px] w-full rounded-lg shadow-sm"
  />
</div>
```

### Schedule

Choose the frequency at which course sessions repeat (e.g., every 1 week).

```
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.16.47PM.png"
    alt="Recurring schedule"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

Select one or more weekdays for sessions to occur. Then define start and end times for each day.

```
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.17.15PM.png"
    alt="Time slots setup"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

### Pricing

You can set a one-time payment amount and customers can pay the entire amount upfront to get access to all the sessions and benefits of the Course.

```
<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.19.42PM.png"
    alt="One-time payment"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

This enables Customers to pay the Course fee in installments over a period of time.

```
The components include:
- **Total Amount**
- **Initial Payment**
- **Number of Installments**

This is perfect for longer, high-value programs.

<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.21.35PM.png"
    alt="Installment plan"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>

**Time of Installments**: Define the cycle of the Payment Plan.

_e.g. - Charge $80 every 1 month/week/day after the initial payment._

Once this is entered, the System will automatically show you how the Customer's payment cycle will look like.

<div className="flex justify-center mt-4">
  <img
    src="/images/Screenshot2025-04-16at6.22.36PM.png"
    alt="Installment breakdown"
    className="max-w-[600px] w-full rounded-lg shadow-sm"
  />
</div>
```

## Best Practices

Group related courses under intuitive names like "Wellness Tracks" or "Martial Arts Levels" to help admins stay organized. Courses work best when led by consistent instructors to ensure continuity and build learner rapport. Cap participant limits to preserve attention and quality in training-heavy formats. For expensive programs, use the payment plan option to increase accessibility. Use colors to distinguish programs (e.g., Green for Rehab, Purple for Yoga). Boost visibility of new or seasonal courses by marking them as Featured.

***
