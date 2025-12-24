---
title: "Discounts"
description: "Comprehensive guide to creating and applying discounts in POS and subscriptions"
---

# Everything You Need to Know About Discounts

Kenko allows you to set up powerful discount mechanisms to support promotions, retention strategies, and personalized pricing. This guide explains how to create, manage, and apply discounts through the POS or directly to customer subscriptions.

## Creating a Discount

To create a discount, follow these steps:

<Steps>
  <Step title="Navigate to Discounts">
    Go to `Setup > Discounts > Create Discount`
  </Step>
  <Step title="Setup Discount" icon="sparkles">
    <AccordionGroup>
      <Accordion title="Discount Name" icon="tag">
        Name of the discount using which you will be able to identify it.

        <img src="/images/Screenshot2025-04-25at5.37.35PM.png" className="rounded-lg" />
      </Accordion>
      <Accordion title="Discount Code" icon="gift">
        The discount code will be the code using which the Discount can be redeemed.

        <img src="/images/Screenshot2025-04-25at5.40.34PM.png" className="rounded-lg" />
      </Accordion>
      <Accordion title="Set Location" icon="location-pin">
        Set at which location the discount code can be used.

        <img src="/images/Screenshot2025-04-25at5.41.47PM.png" className="rounded-lg" />
      </Accordion>
      <Accordion title="Discount Type" icon="percent">
        Discount type can either be Percentage or Value.

        | Type             | Definition                                    | Example Use Case            | Sample Calculation                                            |
        | ---------------- | --------------------------------------------- | --------------------------- | ------------------------------------------------------------- |
        | **Percentage**   | Applies a % off the total item or cart amount | "10% OFF Yoga Mats"         | Cart total = $100 → 10% discount = $10 off → **Final = $90** |
        | **Fixed Amount** | Deducts a fixed dollar value from the total   | "$20 OFF First Class Pack" | Cart total = $100 → $20 discount → **Final = $80**           |

        ### When to Use

        - **Percentage Discount** is best when:
          - You want the offer to scale with cart size
          - Promoting site-wide sales or loyalty rewards
        - **Fixed Discount** is ideal when:
          - Offering set value deals like "$50 OFF"
          - Running specific service promotions (e.g. "$10 off Massage Session")

        <img src="/images/Screenshot2025-04-25at5.51.01PM.png" className="rounded-lg" />
      </Accordion>
      <Accordion title="Applies To" icon="balloon">
        Discounts apply to all purchase items in Kenko ( Purchase items are those that can be bought with money and not credits ).

        <img src="/images/Screenshot2025-04-25at5.52.16PM.png" className="rounded-lg" />

        The discount applied can further be modified based upon the item.

        For all purchase items the choices are "Apply to all" or "Apply to selected"

        Only for subscriptions, the choices are more exhaustive based upon the cycle.

        <img src="/images/Screenshot2025-04-25at5.54.18PM.png" className="rounded-lg" />
      </Accordion>
    </AccordionGroup>
  </Step>
  <Step title="Set Customer Eligibility">
    Configure the customer eligibility defining who can apply the discount and who cannot.

    <img src="/images/Screenshot2025-04-25at6.00.42PM.png" className="rounded-lg" />

    | Option                                | Description                                                                                | Use Case Example                                                  |
    | ------------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- |
    | **Everyone**                          | Discount can be applied by **any customer**                                                | Open promos like "WELCOME10" or seasonal campaigns                |
    | **Customers with select tags**        | Only customers tagged with specific labels (e.g., "VIP", "Returning") can use the discount | Targeted offers for loyalty or retention                          |
    | **Customers with select memberships** | Discount is limited to customers with specific membership plans                            | "10% off" for "Unlimited Monthly" holders                         |
    | **Customers with select emails**      | Discount is applicable only to specified email addresses                                   | Personal promo codes or compensation cases                        |
    | **Visible to customer**               | When enabled, the discount code appears on customer-facing platforms (website/app)         | Enable for discoverable promotions; disable for internal-only use |
  </Step>
  <Step title="Set Usage Limit">
    Set how many times the Discount Code can be used by the customes

    <img src="/images/Screenshot2025-04-25at6.04.58PM.png" className="rounded-lg" />
  </Step>
  <Step title="Set Active Dates">
    Set for how long the Discount will be Active for the usage of Customers

    <img src="/images/Screenshot2025-04-25at6.06.02PM.png" className="rounded-lg" />

    You can also set an end date, post which the Discount will become Inactive and will no longert be available for usage.
  </Step>
</Steps>

## Applying Discounts in POS

Discounts can be applied during checkout directly from the POS screen.

<AccordionGroup>
  <Accordion title="Apply a Custom Discount" icon="tag">
    1. Add items to cart
    2. Click **Apply Discount**
    3. Choose between flat amount (`$`) or percentage (`%`) or Search the Discount Code
    4. Enter/Select value and click **Apply**

    <img src="/images/Screenshot2025-04-25at6.09.24PM.png" className="rounded-lg" />
  </Accordion>
  <Accordion title="Improved Discount Code UX in POS" icon="sparkles">
    When using discount codes, only the ones applicable to the items in the cart are now shown.

    This saves time and reduces checkout errors.
  </Accordion>
</AccordionGroup>

## Applying Discounts to Subscriptions

Kenko allows discounts to be applied to upcoming subscription cycles after the plan has already been sold.

<Steps>
  <Step title="Create a Discount for Subscription">
    Navigate to `Setup > Discounts > Create Discount` and choose the relevant subscription plan.
  </Step>
  <Step title="Navigate to Member Profile">
    Go to **Customer Profile > Subscriptions**, and click on the `⋮` next to the plan.
  </Step>
  <Step title="Apply Discount">
    Choose **Apply Discount**, then pick from the available codes.

    - The amount and next billing charge will be updated accordingly.

    <img src="/images/Screenshot2025-04-25at6.15.29PM.png" className="rounded-lg" />
  </Step>
</Steps>

## Best Practices

<CardGroup cols="2">
  <Card title="Limit Discount Duration" icon="calendar-minus">
    For time-based campaigns, set an expiry or limit discount cycles to ensure revenue protection.
  </Card>
  <Card title="Use Percentage Discounts for Upsells" icon="percent">
    Great for encouraging upgrades or larger cart sizes.
  </Card>
  <Card title="Use Flat Discounts for Fixed Bundles" icon="dollar-sign">
    Ideal for applying value-based savings on packages or single services.
  </Card>
  <Card title="Preview Final Charge Before Payment" icon="eye">
    Ensure staff always verify the updated charge before confirming a payment.
  </Card>
</CardGroup>