---
title: "Introduction to Appointments"
description: "Get an overview of how Appointments work inside Kenko CRM"
---

import { AccordionGroup, Accordion } from "@/components/mdx/accordion"
import { CardGroup, Card } from "@/components/ui/card"
import { Callout } from "@/components/mdx/callout"

# Appointments in Kenko

Appointments in Kenko allow for **1-on-1 or small group services** to be booked with instructors across flexible time slots. Whether it's personal training, physiotherapy, massage, assessments, or coaching — appointments are designed to be service-specific, staff-availability-driven, and highly customizable.

## What Makes Appointments Unique?

Unlike classes, which are scheduled on fixed days and times, **appointments work off Instructor or Facility availability**. They are **dynamic**, **real-time**, and rely on the system's ability to check:

- Service durations
- Buffers before/after
- Instructor working hours
- Facility usage

Customers see only time slots that satisfy all conditions.

## Core Appointment Concepts

<AccordionGroup>
  <Accordion title="Service-Based Configuration" icon="gear">
    Appointments are created as **individual services** (e.g., "30-Min Physio", "60-min Massage", "1:1 Assessment").

    Each service has:

    - A fixed **duration**
    - Allowed **instructors**
    - Optional **facility**
    - Pricing (credits or free)
    - Custom cancellation policy

    Services are then grouped into categories for discoverability in the booking interface.
  </Accordion>
  <Accordion title="Instructor-Driven Availability" icon="user">
    Appointment booking times are based on:

    - Instructor's **working hours**
    - Existing bookings
    - Service-level duration \+ buffers

    If an instructor is unavailable or has time blocked off (e.g., meetings, personal breaks), those slots won't appear.

    Each instructor can also specify:

    - Days they are available for appointments
    - Maximum number of appointments per day
    - Auto-approval or manual approval preferences
  </Accordion>
  <Accordion title="Buffer Management & Flexibility" icon="clock">
    Buffers help ensure smooth transitions between sessions.

    - You can define buffer time **before and/or after** a session.
    - These buffers are invisible to the customer but respected in calendar logic.
    - Example: A 60-min massage with a 15-min post-buffer will block 75 mins total in the instructor's calendar.
  </Accordion>
  <Accordion title="Recurring Appointments" icon="repeat">
    Customers can optionally book recurring appointments (e.g., every Tuesday at 3 PM).

    - Recurrence depends on availability across all requested dates.
    - If any slot is unavailable, the system notifies the customer before confirming.
  </Accordion>
  <Accordion title="Booking for Someone Else & Dependencies" icon="user-plus">
    Customers can book appointments on behalf of:

    - Family members
    - Children
    - Other saved profiles (e.g., athletes, patients)

    The system shows eligibility and credits for the selected contact, and appointment confirmations reflect their name.
  </Accordion>
  <Accordion title="Visibility, Eligibility & Rules" icon="eye">
    - Appointments can be public or visible only via direct links
    - Booking restrictions include:
      - Credit pack requirements
      - Membership eligibility
      - Tag-based visibility (e.g., only for "Gold" members)
    - Custom cancellation & no-show rules can be applied per service
  </Accordion>
  <Accordion title="Integration Behavior" icon="plus">
    Appointment bookings via **Gympass** and **MyClubs** are **auto-assigned** to instructors based on availability.

    - These platforms do not allow customers to pick a specific instructor
    - Only services enabled for these integrations will show up on their platforms
    - Reporting and payout logic flows through your existing aggregator contract
  </Accordion>
</AccordionGroup>

## Use Cases

<CardGroup cols="2">
  <Card title="Personal Training" icon="dumbbell">
    Offer 1-on-1 or small group coaching sessions tailored to fitness goals, form correction, or strength building.
  </Card>
  <Card title="Body Composition Analysis" icon="child">
    Book assessment slots for measuring body fat, muscle mass, and other fitness metrics using tools like InBody or calipers.
  </Card>
  <Card title="Physiotherapy & Recovery" icon="spa">
    Enable injury recovery, mobility improvement, or corrective therapy through licensed professionals.
  </Card>
  <Card title="Nutrition Consults" icon="salad">
    Allow customers to book appointments with certified nutritionists for diet planning or supplementation.
  </Card>
  <Card title="Goal Planning / 1-on-1 Check-ins" icon="bullseye">
    Use appointment slots to set personal goals, review progress, or create structured accountability with coaches or mentors.
  </Card>
  <Card title="Massage & Relaxation" icon="spa">
    Schedule massage therapy, recovery-focused bodywork, or relaxation appointments to complement training.
  </Card>
</CardGroup>

### Appointments vs. Classes: Key Differences

| Feature                  | **Appointments**                                                                                  | **Classes**                                                                             |
| ------------------------ | ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **Scheduling Logic**     | Based on **real-time instructor availability**, service duration, buffer time, and facility usage | Admin-defined fixed schedule (e.g., Mon/Wed/Fri at 6 PM)                                |
| **Booking Flow**         | Customer chooses **service → time → (optionally) instructor**                                     | Customer picks from a **predefined list of group sessions**                             |
| **Facility Integration** | Yes - Can be tied to **specific rooms or service zones** (e.g., massage rooms, PT bays)           | Yes - Assigned to studios or halls (e.g., Yoga Studio, Spin Room)                       |
| **Group Size**           | Designed for **1-on-1** or very small groups (1–3 people max)                                     | Suitable for medium to large groups (typically 5–30\+ participants)                     |
| **Instructor Logic**     | Instructor is either auto-assigned or customer-selected (if allowed)                              | Instructor is **pre-set** at creation; cannot be changed per session by customer        |
| **Recurrence Model**     | Optional — customers can set up recurring sessions if availability allows                         | Set by admin; uses recurring patterns (e.g., weekly, bi-weekly, ends after 10 sessions) |
| **Buffers Supported**    | Yes — supports pre/post session buffers for recovery, setup, or transition time                   | No buffer support — sessions run on exact start-end time                                |
| **Booking Restrictions** | Can be configured with credit packs, memberships, or tag-based rules                              | Same eligibility model as appointments, but applied at the class level                  |
| **Use Case Examples**    | - Personal Training, Physiotherapy , Massage , Nutrition Consults , 1:1 Assessments               | -Yoga , Spin , Dance , Pilates , Strength Classes , HIIT Group                          |
| **Customer Experience**  | Personalized, dynamic booking with **live slot availability**                                     | Predictable, schedule-based flow; **customer books into predefined time blocks**        |
| **Best Suited For**      | Wellness, private coaching, recovery, diagnostics, consultations                                  | Group fitness, community sessions, recurring structured programs                        |

## Summary

Appointments in Kenko give you the power to offer flexible, high-touch services with real-time availability logic, detailed control over scheduling rules, and smooth integration into your studio's customer experience.

Whether you're a coach, therapist, or wellness studio — appointments help you scale 1:1 engagement while maintaining structure and simplicity.