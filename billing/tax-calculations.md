---
title: "Tax Calculations"
description: "Configure inclusive and exclusive tax rates, apply taxes to services, and understand tax treatment in Kenko."
---

# Tax Calculations in Kenko

Kenko allows you to define, manage, and apply multiple tax rates to your offerings. You can choose between **inclusive** and **exclusive** tax handling, define custom rates, and apply them to subscriptions, services, and products.

## Inclusive vs. Exclusive Tax

Tax can be either **inclusive** (already included in the price) or **exclusive** (added on top of the price).

_Example of inclusive and exclusive tax_

A 25% tax applied to a $5 item would be handled differently depending on the tax type:

| Tax Type      | Subtotal | Tax Due                           | Total                   |
| ------------- | -------- | --------------------------------- | ----------------------- |
| 25% Exclusive | $5.00    | $1.25                             | $$6.25 ($$    5\+$1.25) |
| 25% Inclusive | $5.00    | $1.00 (already included in price) | $$5.00 ($$    4\+$1)    |

## ![Screenshot2025 04 24at2 49 00PM Pn](/images/Screenshot2025-04-24at2.49.00PM.png)

Add Custom Tax Rates

You can create new tax labels and define the rate in percentage.

**Steps**

1. Click **Add tax rate**
2. Enter a name like "Premium Service Fee"
3. Set the percentage (e.g., 12%)

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-24at2.49.39PM.png"
  alt="Tax Type Selection"
  className="max-w-[500px] w-full rounded-lg shadow-sm"
/>

</div>

Once added, tax rates appear under the **Tax rates** section

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-24at2.49.48PM.png"
  alt="Tax Type Selection"
  className="max-w-[500px] w-full rounded-lg shadow-sm"
/>

</div>

## Apply Tax Rates

You can assign tax rates to the following items, You can choose whether you want to apple single tax rate or multiple tax rates.

_Items Tax rate is applicable on_

Subscriptions, Credit and Top-up Packs, Courses, Products, Videos, Playlists, Appointments ( QuickPay ) and Enrollment Fee

<div className="flex justify-center mt-4">
<img
  src="/images/Screenshot2025-04-24at5.00.47PM.png"
  alt="Tax Type Selection"
  className="max-w-[500px] w-full rounded-lg shadow-sm"
/>

</div>

<Note>
  Each tax rate is calculated on the **base price of the appointment**, and then **added together**. Kenko **does not** calculate one tax on top of another — it applies them **independently** on the original price.
</Note>

### Example Calculation

| Tax Type        | Rate | Calculation             | Amount |
| --------------- | ---- | ----------------------- | ------ |
| Service Fee     | 15%  | 15% of $35.00           | $5.25  |
| Service Tax     | 10%  | 10% of $35.00           | $3.50  |
| **Total Tax**   |      |                         | $8.75  |
| **Final Price** |      | $$35.00 \\\+ $$    8.75 | $43.75 |

## Best Practices

<CardGroup cols="2">
  <Card title="Use Inclusive for Simplicity" icon="receipt">
    Use inclusive tax where pricing transparency matters, like in fitness classes or public packages.
  </Card>
  <Card title="Name Taxes Clearly" icon="tag">
    Give tax rates intuitive names like "VAT (5%)" or "Service Fee" so admins know exactly what they're applying.
  </Card>
  <Card title="Apply Relevant Taxes Only" icon="filter">
    Don’t overload services with multiple taxes. Match tax rates to specific services depending on locality and product type.
  </Card>
  <Card title="Review Monthly" icon="calendar">
    Periodically audit your applied tax rates for accuracy and compliance, especially after policy or price updates.
  </Card>
</CardGroup>

---