---
title: "Introduction"
description: "Discover the core of scheduling and event management on the Kenko Platform"
---

import { CardGroup, Card, AccordionGroup, Accordion, Tabs, Tab } from '@mintlify/components'

# Scheduling & Management

The **Scheduling & Management** module is the backbone of daily operations for any fitness or wellness business using Kenko.

 From managing daily classes and bookings to providing instructors with schedule clarity and enabling smooth check-ins, this module is built to optimize time, resources, and user experience.

## Core Components

<CardGroup cols="2">
  <Card title="Classes" icon="user-ninja" iconType="solid">
    Recurring or one-time group sessions with specific instructors, time slots, and capacity.
  </Card>
  <Card title="Appointments" icon="calendar-check" iconType="solid">
    One-on-one or semi-private bookings with flexible durations and instructor-specific availability.
  </Card>
  <Card title="Courses" icon="layer-group" iconType="solid">
    Multi-session offerings bundled under a single course name — ideal for workshops or progressions.
  </Card>
  <Card title="Calendar" icon="calendar-days" iconType="solid">
    A centralized view of all sessions, instructors, and facilities to manage schedules and resolve conflicts.
  </Card>
</CardGroup>

## What This Module Helps You Manage

<AccordionGroup>
  <Accordion title="Class Scheduling" icon="calendar">
    Configure recurring or one-off group classes that form the backbone of your studio's offerings.

    _Key setup options include_

    - **Session title & type** (e.g., Yoga Basics, HIIT, Spin)
    - **Instructor(s)** assigned with visibility across shifts and subs
    - **Location/facility** selection with automated conflict prevention
    - **Capacity limits** and **Waitlist activation**
    - **Duration** settings (e.g. 45, 60, 90 mins)
    - **Recurrence rules**: weekly, daily, or custom (e.g. every Mon/Wed/Fri for 8 weeks)

    ✅ Built-in validations alert you for instructor double-bookings or overlapping sessions in the same room.

    ✅ Option to add internal-only sessions (e.g., staff meetings or rehearsal classes).

    ✅ Visibility settings allow you to make classes public, private (link-only), or members-only.
  </Accordion>
  <Accordion title="Appointment Scheduling" icon="calendar-days">
    Let customers book one-on-one or small-group sessions with instructors based on real-time availability.

    Features include

    - **Instructor-specific time slots** and location preferences
    - **Buffer times** before/after each session for smooth transitions
    - **Minimum & maximum durations** (e.g., 30 mins to 2 hrs)
    - **Booking cutoffs and cancellation windows**

    ✅ Great for personal training, physiotherapy, body assessments, or specialty coaching.

    ✅ Instructors can block personal time so they're not bookable during breaks or non-working hours.

    ✅ Customers can optionally select the instructor they prefer or book based on first availability.
  </Accordion>
  <Accordion title="Course Configuration" icon="calendar-lines-pen">
    Group multiple sessions into a structured program or workshop.

    Setup includes

    - **Course name and type** (e.g., Beginner Aerial Hoop — Level 1)
    - **Start & end dates**, fixed duration
    - **Linked sessions**: auto-create or attach existing classes to form the course
    - **Pricing flexibility**: fixed price (pay once) or drop-in (per session)
    - **Access rules**:
      - Full course required (no drop-ins)
      - Prerequisites (e.g., "must complete Level 1 first")
      - Seat reservation per course, not per class

    ✅ Courses show progress tracking for both admins and customers.

    ✅ Useful for teacher training programs, seasonal bootcamps, 4- or 6-week transformation challenges, etc.

    ✅ Attendance can be marked across the entire course or per session.
  </Accordion>
  <Accordion title="Central Calendar Management" icon="calendar-heart">
    Get a real-time, color-coded calendar view of everything scheduled.

    Calendar capabilities:

    - **Day / Week / Month views**
    - **Color-coded by class type, instructor, or booking status**
    - **Live filters**: view by location, format (class vs. appointment), instructor, or room
    - **Drag & drop rescheduling** for admins
    - **Instant conflict detection** if two classes or appointments overlap by instructor or facility
    - **Quick Add**: tap to schedule directly from calendar

    ✅ Great for front desk teams, ops managers, and instructors to stay aligned.

    ✅ Integrated with notifications for reschedules, cancellations, or overbooked slots.
  </Accordion>
  <Accordion title="Substitution & Visibility Controls" icon="user">
    Handle instructor absences smoothly with built-in substitution logic.

    - **Admins can assign subs manually** or instructors can request substitutes
    - **Notifications sent to subs** and confirmation logged
    - **Visibility**: updates reflected across calendars and customer-facing views in real-time
    - **Permissions**: Only designated roles can modify instructor details
    - **Class history** tracks original and substitute instructors for transparency

    ✅ Especially useful for studios with large rotating staff or contract instructors.

    ✅ Ensures customers always know who’s teaching and avoids last-minute confusion.
  </Accordion>
</AccordionGroup>

## Quick Glance on the Module offerings

<CardGroup cols="2">
  <Card title="Class Scheduling" icon="calendar" iconType="solid">
    Create, organize, and manage group classes with flexible time slots, levels, and instructor allocations.
  </Card>
  <Card title="Appointment Scheduling" icon="calendar-check" iconType="solid">
    Enable one-on-one or small-group appointments for personalized experiences across services.
  </Card>
  <Card title="Facility Scheduling" icon="building" iconType="solid">
    Allocate spaces like rooms, studios, or equipment for internal or customer-facing bookings.
  </Card>
  <Card title="Courses" icon="layer-group" iconType="solid">
    Group a set of sessions into a course — ideal for multi-week training programs or workshops.
  </Card>
  <Card title="Check-in Kiosk" icon="tablet-screen-button" iconType="solid">
    Offer a self-check-in experience through a kiosk or mobile to reduce front desk load.
  </Card>
  <Card title="Spot Booking" icon="person-seat" iconType="solid">
    Let customers reserve specific spots within a class — e.g. yoga mat location or spin bike.
  </Card>
  <Card title="Waitlist Management" icon="list-ol" iconType="solid">
    Automatically manage overflow by allowing customers to join waitlists with real-time updates.
  </Card>
  <Card title="Substitution Management" icon="people-arrows" iconType="solid">
    Allow seamless instructor substitution with internal visibility and approvals.
  </Card>
</CardGroup>

## Who Uses This Module?

<Tabs>
  <Tab title="Studio Owners">
    Monitor scheduling across classes, facilities, and staff with high visibility. Ensure everything runs smoothly while empowering your team to manage their work independently.
  </Tab>
  <Tab title="Admins & Managers">
    Handle bookings, setup waitlists, assign subs, and configure rules — all from a single dashboard.
  </Tab>
  <Tab title="Instructors">
    View upcoming classes, availability, assigned spots, and substitutions clearly. No more confusion or manual handovers.
  </Tab>
  <Tab title="Customers">
    Enjoy a frictionless experience while booking, checking in, or being notified about class status — even when you’re on a waitlist or there's a cancellation.
  </Tab>
</Tabs>

## Summary

The **Scheduling & Management** module is foundational to running a smooth and professional operation. It handles everything from the backend logic of scheduling and availability, to the customer-facing experience of booking and checking in.

Ready to dive deeper?

