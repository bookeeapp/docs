---
title: "Scheduling settings"
description: "Configure your calendar's appearance and global booking rules in the General settings."
---

# Global settings for Bookings

Kenko’s **Booking Settings** are divided into four categories, each controlling different aspects of how bookings are managed in the calendar. These categories are:

- **General Settings**
- **Classes Settings**
- **Appointments Settings**
- **Courses Settings**

We will explore each of these categories and dive deep into how each one functions.

## General Settings

The **General Settings** for scheduling allow you to control how the calendar is displayed, the cancellation and no-show policies, and other global configuration options that affect all event types (classes, appointments, and courses).

<AccordionGroup>
  <Accordion title="Calendar View" icon="calendar">
    Configure your calendar's weekly structure and preview window.

    - **Calendar shows up to**: Controls how many weeks of events are shown at once.
    - **My week starts on**: Choose the start day of the calendar week (e.g., Sunday).

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.54.39PM.png"
      alt="Calendar view setting"
      className="max-w-[500px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Cancellation policy" icon="ban">
    Define rules for cancellations and charges outside of free cancellation windows.

    - **Free Cancellation vs Window based cancellation fee**: Set whether you want to apply free cancellation for the policy or window based cancellation policy.
    - **Free window**: Set how far in advance a booking can be canceled before the Class or Appointments starts without a fee.
    - **Fee Structure**: Define charges for unlimited vs. limited credits, or QuickPay transactions.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.55.55PM.png"
      alt="Cancellation policy configuration"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.56.31PM.png"
      alt="Cancellation fee settings"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="No-show policy" icon="user-slash">
    Set how members are charged or penalized for missing a scheduled session without notice.

    The structure is very similar to that of the Cancellation policy.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.57.38PM.png"
      alt="No-show configuration"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.58.07PM.png"
      alt="No-show policy fee settings"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Policy Document" icon="file">
    Add a customer-facing description for the booking policy. The Policy combines Cancellation policy and No-show policy.

    You can make multiple policies for different Services.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-22at11.23.07AM.png"
      alt="Policy document section"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>

    <Note>
      A single policy consists of a Cancellation Policy, No-show Policy, and a Policy Document bundled together.
    </Note>
  </Accordion>
  <Accordion title="Service Category" icon="icons">
    Manage custom categories for services that help organize offerings. ( Classes and Appointments )

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-22at11.21.52AM.png"
      alt="Service category creation"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Classes Settings

The **Classes Settings** allow you to configure rules and policies specific to class bookings. These settings govern aspects such as booking limits, cancellations, and any restrictions based on class type.

<AccordionGroup>
  <Accordion title="Remaining Spots" icon="users">
    Set at what percentage of class's availability remaining spots should be shown to Customers to nudge urgency.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.49.33PM.png"
      alt="Remaining spots"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Booking Window" icon="clock">
    Set when the booking window opens and closes for Classes for Customer Bookings.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.50.10PM.png"
      alt="Booking window"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Auto-Submit Attendance" icon="check">
    Avoid manual submission of attendance by setting auto-submission of attendance.

    <Note>
      Customers should be checked-in before the attendance submission or they will be marked as No-Show.
    </Note>
    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.50.54PM.png"
      alt="Auto-submit attendance"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Book for Someone Else" icon="user-plus">
    Enable Book for someone else so that customers can book sessions for their related contacts.
    This is a good way to get more leads and ensure convenience for customers.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.51.51PM.png"
      alt="Book for someone else"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Waitlist Management" icon="user-clock">
    The **Waitlist Management** settings provide greater flexibility in handling overbooked classes and ensuring efficient use of available spots.

    Here are the key components of the waitlist configuration:

    - **Waitlist Activation**:\
      In the event a booking is canceled, the system can automatically book the first customer from the waitlist until the **waitlist auto-booking time** is reached. You can choose to:
      - **Automatically book the first person on the waitlist** until a set time (e.g., 2 hours before the class starts).
      - **Inform everyone on the waitlist when a spot becomes free** after the auto-booking time.

      This provides flexibility to either auto-assign customers or notify them of available spots.

      <div className="flex justify-center mt-4">
      <img
        src="/images/Screenshot2025-04-21at9.53.28PM.png"
        alt="Waitlist management"
        className="max-w-[600px] w-full rounded-lg shadow-sm"
      />

      </div>
    - **Maximum Waiting Spots**:\
      Define the maximum number of people that can be placed on the waitlist. If a class is fully booked, you can set a limit to ensure that the waitlist doesn’t become too large and is manageable. For example, you can set it to 5 waiting spots for a class.
    - **Waitlist Removal Window**:\
      This setting controls how long after the class ends a customer remains on the waitlist. You can specify how long the system will keep customers on the waitlist for future booking purposes before removing them. For instance, you can set it to "Immediately" after the class ends, meaning their waitlist status will be removed and they will be refunded their booking credit if applicable.
    - **Enable Public Access to Waitlist Information**:\
      When enabled, members and visitors can view the waitlist details of a class before and after booking. This transparency allows customers to see their position on the waitlist and how many others are ahead of them. It also helps in making informed decisions about booking classes or looking for alternate times.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.54.04PM.png"
      alt="Waitlist settings"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Forgive Late Cancellation" icon="money-bill">
    You can enable auto-forgive late-cancellation upto X times in Y year/month for customer's first few cancellations as a goodwill gesture.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.52.36PM.png"
      alt="Late cancellation"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Appointments Settings

The **Appointments Settings** control how individual appointment bookings are managed, including policies for cancellations, no-shows, and payment collection.

<AccordionGroup>
  <Accordion title="Booking Window" icon="clock">
    Define when the appointment booking window should open and close. For example, you can set a window for booking a session, ensuring customers don’t book too far in advance or at the last minute.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.48.28PM.png"
      alt="Appointment booking window"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Auto-Submit Attendance" icon="check">
    You can configure auto-submission of attendance, so no manual intervention is required. This ensures that attendees are recorded without any extra effort.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.48.01PM.png"
      alt="Auto-submit attendance"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Book For Someone Else" icon="user-plus">
    Allow customers to book appointments for other people, making it easier for them to manage their contacts.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.47.34PM.png"
      alt="Book for someone else"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Appointment Cancellation" icon="money-bill">
    You can enable whether or not a customer can cancel an appointment from app and website.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.46.55PM.png"
      alt="Appointment cancellation"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

## Courses Settings

The **Courses Settings** help you manage course bookings, especially when dealing with multi-session bookings, course limits, and payment structure.

<AccordionGroup>
  <Accordion title="Course Visibility" icon="eye">
    Control the visibility of your courses, deciding whether or not customers can see or book courses based on their availability or other rules.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.44.31PM.png"
      alt="Course visibility"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Auto-Submit Attendance" icon="check">
    Just like for classes and appointments, auto-submit attendance for courses ensures a seamless tracking experience.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.43.53PM.png"
      alt="Auto-submit attendance"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
  <Accordion title="Waitlist Management" icon="user-clock">
    For courses, similar waitlist management can be set, ensuring that you can manage full courses effectively, offering slots to people on the waitlist.

    <div className="flex justify-center mt-4">
    <img
      src="/images/Screenshot2025-04-21at9.43.18PM.png"
      alt="Course waitlist"
      className="max-w-[600px] w-full rounded-lg shadow-sm"
    />

    </div>
  </Accordion>
</AccordionGroup>

---

## Best Practices for Booking Settings

<CardGroup cols="2">
  <Card title="Review All Policies Regularly" icon="eye">
    Regularly review your cancellation, no-show, and payment policies to keep them aligned with customer expectations and business needs.
  </Card>
  <Card title="Use Waitlists for Fully Booked Classes" icon="list-ul">
    Maximize attendance by using waitlists when classes or appointments are full.
  </Card>
  <Card title="Consider Flexible Payment Options" icon="credit-card">
    Offering installment payments for courses or appointments can improve accessibility and reduce cancellations.
  </Card>
  <Card title="Set Realistic Booking Windows" icon="clock">
    Adjust booking windows to reflect your business model and customer behavior for better booking management.
  </Card>
  <Card title="Use Auto-Submit Attendance for Efficiency" icon="check">
    Enable auto-submit attendance to streamline the process and keep records accurate.
  </Card>
  <Card title="Segment Your Services" icon="filter">
    Organize your offerings into service categories to apply specific policies and rules for each service type.
  </Card>
  <Card title="Communicate Booking Policies Clearly" icon="bullhorn">
    Make sure customers understand your policies before booking to prevent confusion and conflicts.
  </Card>
  <Card title="Track Customer Behavior and Adjust" icon="chart-line">
    Monitor customer behavior around cancellations and no-shows to adjust your policies accordingly.
  </Card>
</CardGroup>

---