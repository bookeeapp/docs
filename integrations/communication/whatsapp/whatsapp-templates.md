---
description: Create, approve, and manage WhatsApp templates for outbound messaging.
---

# WhatsApp Templates

WhatsApp templates are **pre-approved messages** you can send **anytime**.

Use templates when:

* The customer has not messaged you in the last 24 hours.
* You want to message first.
* You want to automate messages in Journeys.

{% hint style="info" %}
You can still chat normally (free-form) inside the 24-hour window. Templates are for starting or restarting conversations.
{% endhint %}

### What makes a template different

Templates are:

* Reviewed by WhatsApp.
* Reusable across your team.
* Built with safe placeholders (variables) like `{{first_name}}`.

Templates are not:

* A place for free-form back-and-forth.
* Editable after submission in most setups.

### Creating Your First Template

Templates are your secret weapon for staying connected with customers. Here's how to create them:

#### Step 1: Create Your Template

* [ ] Go to **Settings** → **WhatsApp Templates** → **Create Template**
* [ ] Give your template a clear, descriptive name
* [ ] Choose the right **category** (UTILITY or MARKETING)
* [ ] Write your message in the **Body** field

**Good template names:**

* ✅ "Appointment Reminder"
* ✅ "Order Confirmation"
* ✅ "Welcome Message"
* ✅ "Follow-Up After Service"
* ❌ "Template 1" (too vague)
* ❌ "Message" (not descriptive)

**Category guide:**

| Category      | Use For                | Examples                                               |
| ------------- | ---------------------- | ------------------------------------------------------ |
| **UTILITY**   | Transactional messages | Appointments, orders, updates, confirmations, receipts |
| **MARKETING** | Promotional messages   | Sales, offers, announcements, newsletters, campaigns   |

{% hint style="info" %}
**Naming tip:** Use clear, descriptive names. You'll thank yourself later when you have multiple templates and need to find the right one quickly.
{% endhint %}

#### Step 2: Add Personalization (Make It Personal)

Make your templates feel personal by adding these variables:

| Variable          | What It Does                  | Example Output    |
| ----------------- | ----------------------------- | ----------------- |
| `{{first_name}}`  | Inserts customer's first name | "Sarah"           |
| `{{last_name}}`   | Inserts customer's last name  | "Johnson"         |
| `{{client_name}}` | Inserts your business name    | "Downtown Clinic" |

**Example template:**

```
Hi {{first_name}}, your appointment at {{client_name}} is confirmed for tomorrow at 2 PM. We're looking forward to seeing you!
```

**What the customer receives:**

```
Hi Sarah, your appointment at Downtown Clinic is confirmed for tomorrow at 2 PM. We're looking forward to seeing you!
```

See how it automatically fills in Sarah's name and your business name? That's the power of personalization!

<details>

<summary>💡 Template examples for different use cases</summary>

**Appointment Confirmation (UTILITY):**

```
Hi {{first_name}}, your appointment at {{client_name}} is confirmed for {{date}} at {{time}}. We'll see you then!
```

**Order Shipped (UTILITY):**

```
Hi {{first_name}}, great news! Your order from {{client_name}} has shipped. Track it here: {{tracking_link}}
```

**Welcome Message (MARKETING):**

```
Welcome to {{client_name}}, {{first_name}}! We're excited to have you. Use code WELCOME20 for 20% off your first order.
```

**Follow-Up (UTILITY):**

```
Hi {{first_name}}, how was your recent visit to {{client_name}}? We'd love to hear your feedback!
```

</details>

#### Step 3: Submit for Approval

* [ ] Review your template one more time to make sure everything looks good
* [ ] Click **"Submit for Approval"**
* [ ] Wait for approval (usually takes a few minutes, but can take up to 24 hours)
* [ ] You'll receive a notification when your template is approved or if any changes are needed

**Approval status timeline:**

| Status          | What It Means      | Typical Time            |
| --------------- | ------------------ | ----------------------- |
| 🟡 **Pending**  | Waiting for review | 2-5 minutes             |
| 🟢 **Approved** | Ready to use!      | 5-30 minutes            |
| 🔴 **Rejected** | Needs changes      | Immediate (with reason) |

{% hint style="info" %}
**Approval timeline:** Most templates are approved within a few minutes. If it takes longer, don't worry—this is normal. You'll get notified either way.
{% endhint %}

***

### Common Template Mistakes (And How to Avoid Them)

We've seen these mistakes happen often. Learn from them so your templates get approved the first time!

#### ❌ Mistake #1: Mixing Marketing Language with Utility Templates

**What's wrong:**

```
🎉 Special offer! Book now and save 20%!
```

_(Using this in a UTILITY template)_

**What's right:**

```
Your appointment is confirmed for January 15th at 2 PM.
```

**Why it matters:** UTILITY templates are for transactional messages only. Save the promotions for MARKETING templates.

#### ❌ Mistake #2: Starting or Ending with a Placeholder

**What's wrong:**

```
{{first_name}}, your order is ready!
```

**What's right:**

```
Hi {{first_name}}, your order is ready!
```

**Why it matters:** Templates must start and end with actual text, not variables. Always add a greeting or closing.

#### ❌ Mistake #3: Placing Placeholders Right Next to Each Other

**What's wrong:**

```
Hello {{first_name}}{{last_name}}, welcome!
```

**What's right:**

```
Hello {{first_name}} {{last_name}}, welcome!
```

_(Notice the space between them)_

Or even better:

```
Hello {{first_name}}, welcome to {{client_name}}!
```

**Why it matters:** Variables need to be separated by text. This makes the message more natural and readable anyway.

#### ❌ Mistake #4: Overusing Emojis or Special Characters

**What's wrong:**

```
🎉🎊🎈🎁🎂🎀 Special offer!!! Book NOW and SAVE!!! 🎉🎊🎈
```

**What's right:**

```
Special offer: Book now and save 20% on your next appointment.
```

**Why it matters:** Keep it professional. One or two emojis are fine, but excessive use can get your template rejected.

#### ❌ Mistake #5: Choosing the Wrong Category

**UTILITY templates should:**

* ✅ Be transactional and informative
* ✅ Focus on appointments, orders, updates, confirmations
* ✅ Not include promotional content
* ✅ Be clear and direct

**MARKETING templates should:**

* ✅ Clearly indicate promotional content
* ✅ Include opt-out options when required
* ✅ Follow WhatsApp's marketing guidelines
* ✅ Be engaging but compliant

**Quick decision guide:**

```
Are you trying to sell something?
├─ YES → MARKETING category
└─ NO → UTILITY category

Are you informing about a transaction?
├─ YES → UTILITY category
└─ NO → MARKETING category
```

***

### What to Do If Your Template Gets Rejected

Don't worry—template rejections happen, and they're easy to fix! Here's your action plan:

#### Step 1: Read the Rejection Reason

WhatsApp will tell you exactly why your template was rejected. Common reasons include:

| Rejection Reason     | What It Means                                      | How Common     |
| -------------------- | -------------------------------------------------- | -------------- |
| Wrong category       | Used UTILITY for marketing content (or vice versa) | 🔴 Very common |
| Placeholder issues   | Placeholders at start/end or adjacent              | 🟡 Common      |
| Promotional language | Sales language in UTILITY template                 | 🔴 Very common |
| Formatting problems  | Unsupported characters or URLs                     | 🟢 Less common |

#### Step 2: Fix the Issue

Based on the rejection reason, make these common fixes:

* **Wrong category?** → Change it to the correct one (UTILITY vs MARKETING)
* **Promotional language?** → Remove sales language from UTILITY templates
* **Placeholder issues?** → Make sure placeholders aren't at the start/end and aren't adjacent
* **Formatting problems?** → Remove unsupported characters or fix URL formatting

#### Step 3: Create a New Template

You can't edit rejected templates, so create a new one with:

* A slightly different name (e.g., "Appointment Reminder v2")
* The fixes applied
* All the same content, just corrected

#### Step 4: Resubmit

Submit your corrected template for approval again. Most templates get approved on the second try once you fix the issues.

{% hint style="info" %}
**Pro tip:** Keep a simple note of what got rejected and why. This helps you avoid repeating the same mistake. Most rejections are due to category mismatches or placeholder placement—both easy to fix!
{% endhint %}

<details>

<summary>📋 Template rejection checklist</summary>

Use this checklist when fixing a rejected template:

* [ ] Read the rejection reason carefully
* [ ] Check if category is correct (UTILITY vs MARKETING)
* [ ] Verify no promotional language in UTILITY templates
* [ ] Ensure placeholders aren't at start or end
* [ ] Check placeholders aren't adjacent to each other
* [ ] Remove excessive emojis or special characters
* [ ] Verify URLs are properly formatted (if used)
* [ ] Create new template with fixes
* [ ] Use slightly different name
* [ ] Resubmit for approval

</details>
