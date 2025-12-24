---
description: Use WhatsApp templates inside Journeys for automated reminders and follow-ups.
---

# WhatsApp in Journeys

### Using Templates in Journeys (Automation Made Easy)

Templates aren't just for manual messages—they're perfect for automated journeys that work while you sleep!

#### Setting Up a Journey with WhatsApp

* [ ] Go to **Journeys** → **Create Journey** (or edit an existing one)
* [ ] Add a **WhatsApp Node** to your journey flow
* [ ] Click on the WhatsApp node to configure it
* [ ] Select an **approved template** from the dropdown menu
* [ ] Save your journey

That's it! The template will automatically be used for all outbound messages in this journey step.

#### How Personalization Works in Journeys

The magic happens automatically. When you select a template in a journey:

| Variable          | Automatically Replaced With |
| ----------------- | --------------------------- |
| `{{first_name}}`  | Contact's first name        |
| `{{last_name}}`   | Contact's last name         |
| `{{client_name}}` | Your business name          |

**Real-world journey example:**

```
1. Trigger: Customer books an appointment online
   ↓
2. Journey starts automatically
   ↓
3. WhatsApp node sends: "Hi {{first_name}}, your appointment at {{client_name}} is confirmed!"
   ↓
4. Customer receives: "Hi Sarah, your appointment at Downtown Clinic is confirmed!"
```

**The best part:** You set it up once, and it works for every customer automatically. No manual work needed!

<details>

<summary>🎯 Journey setup best practices</summary>

**When to use WhatsApp in journeys:**

* ✅ Appointment reminders
* ✅ Order confirmations
* ✅ Follow-up messages after service
* ✅ Welcome messages for new customers
* ✅ Re-engagement campaigns

**Timing tips:**

* Send appointment reminders 24 hours before
* Send order confirmations immediately
* Send follow-ups 1-2 days after service
* Space out marketing messages appropriately

**Testing:**

* Always test your journey with a test contact first
* Verify personalization works correctly
* Check message timing and triggers

</details>
