---
title: Products Setup
keywords: products,POS,variants,inventory,retail,merch,pickup
sidebar_label: Product Setup
description: >-
  Step-by-step guide to creating and managing sellable products in Kenko,
  including variants, inventory, and in-studio pickup.
---

# Setup Products

import { Steps, Step, AccordionGroup, Accordion } from "@/components/ui"

## Setting Up Products in Kenko

From water bottles and whey protein to branded tees and yoga mats — Kenko lets you sell products right from your studio dashboard. Whether you're selling behind the desk or via your branded app, Kenko tracks inventory, supports variant options, and simplifies checkout.

> Kenko does not currently support logistics, delivery, or shipping. All products are for **on-site collection** only.

### What Can You Sell via Kenko?

Kenko’s product engine supports all kinds of physical items commonly sold in fitness and wellness studios

| **Category**       | **Examples**                                          |
| ------------------ | ----------------------------------------------------- |
| Apparel            | T-shirts, tank tops, leggings, jackets                |
| Gear & Equipment   | Yoga mats, foam rollers, resistance bands             |
| Consumables        | Protein bars, smoothies, electrolytes, bottled drinks |
| Accessories        | Towels, bags, bottles, socks                          |
| Studio Merchandise | Branded mugs, notebooks, challenge kits               |
| Seasonal Specials  | Gift boxes, holiday bundles, exclusive drops          |

### How to Create a Product

Navigate to \*\*Setup → Products\*\*. You’ll see a full list of all products created across your studio locations, including draft and active items.

```
![Screenshot2025 05 14at12 11 04PM Pn](/images/Screenshot2025-05-14at12.11.04PM.png)
```

Click \*\*Add Product\*\* to create something new.\ Or hit \*\*Edit\*\* to update an existing product. Add a \*\*Title\*\*, optional \*\*Brand\*\*, and a brief \*\*Description\*\*.\ The status can be \*\*Draft\*\* (invisible) or \*\*Active\*\* (available for sale).

```
> To add a new brand, just start typing in the **Brand** field. Kenko auto-creates it and adds it to your global brand list.

![Screenshot2025 05 14at12 11 31PM Pn](/images/Screenshot2025-05-14at12.11.31PM.png)
```

If your product has variations (like size or color), enable \*\*This product has multiple options\*\*.

```
![Screenshot2025 05 14at12 13 04PM Pn](/images/Screenshot2025-05-14at12.13.04PM.png)

Then enter values like

- Size → S, M, L, XL
- Color → Black, Blue, Green
- Material → Cotton, Synthetic

![Screenshot2025 05 14at12 14 04PM Pn](/images/Screenshot2025-05-14at12.14.04PM.png)

Kenko will auto-generate all combinations for setup.

![Screenshot2025 05 14at12 14 16PM Pn](/images/Screenshot2025-05-14at12.14.16PM.png)
```

For each variant

```
- Add **Price** and optional **Compare at price**
- Upload **Product images**
- Define a **SKU** for inventory tracking
- Check “Charge tax” if applicable

![Screenshot2025 05 14at12 17 02PM Pn](/images/Screenshot2025-05-14at12.17.02PM.png)

> **What’s a SKU?**\
> SKU stands for Stock Keeping Unit — a unique identifier like `TSHIRT-BLU-M`.\
> It helps you track stock, reorder efficiently, and avoid mix-ups.
```

Add available quantities for each \*\*studio location\*\* you operate in.\ If the product isn't available somewhere, just leave the quantity at zero.

```
> Products are only shown at POS or app **in the locations where stock exists.**

![Screenshot2025 05 14at12 17 11PM Pn](/images/Screenshot2025-05-14at12.17.11PM.png)
```

Click \*\*Save Changes\*\* to finalize the product.\ If marked active and stock is available, it will be ready for purchase at checkout or via the mobile app.

### How Do Customers Receive Products?

All products are set up for **physical pickup only**. Once a customer purchases through POS or the app

* The product is marked as “purchased”
* The front desk or staff hands it over in-studio
* Inventory automatically updates based on the pickup location

There is no home delivery or courier support built into Kenko at this time.

### Product Fulfillment

Once products are sold and received by the Customer, they have to be marked as "Fulfilled" for tracking and report management.

To fulfill an order, Navigate to Contact `Profile -> Payments`. When a Product is purchased, Mark as fulfilled options pops-up.

![Screenshot2025 05 14at1 06 48PM Pn](../../../.gitbook/assets/Screenshot2025-05-14at1.06.48PM.png)

### **Best Practices**

A product with no image is easy to skip. Use tools like \*\*PicCopilot\*\* or \*\*GPT-powered generation\*\* to create clean, on-brand mockups fast. Use a consistent format like \`TOP-BLK-S\` for t-shirts or \`YOGA-GRN-L\` for gear. This makes inventory reporting and troubleshooting easier later. Stick to conventional values like S/M/L and primary color names. Avoid complex abbreviations that confuse customers or staff. Visit the inventory screen regularly to restock top sellers and archive out-of-stock variants if needed. Always double-check that you've entered quantities by location. Otherwise, a product won't appear at POS or app for those customers.
