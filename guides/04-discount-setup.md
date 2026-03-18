# Guide 04 — Discount Code Setup

Go to **Shopify Admin > Discounts > Create discount**

---

## Discount 1: Welcome Offer (Percentage Off)

| Field | Value |
|---|---|
| Type | Percentage |
| Code | WELCOME15 |
| Discount Value | 15% |
| Applies to | All products |
| Minimum requirement | No minimum |
| Customer eligibility | All customers |
| Usage limit | 1 per customer |
| Start date | Immediately |
| End date | None (ongoing) |

---

## Discount 2: Free Shipping Threshold

| Field | Value |
|---|---|
| Type | Free shipping |
| Code | (automatic) |
| Minimum purchase | $75.00 |
| Countries | United States |
| Exclude shipping rates over | $50.00 |
| Start date | Immediately |

Set this as an **automatic discount** so it applies without a code.

---

## Discount 3: Bundle Discount (Fixed Amount)

| Field | Value |
|---|---|
| Type | Amount off order |
| Code | BUNDLE20 |
| Discount Value | $20.00 |
| Minimum requirement | $120.00 minimum purchase |
| Customer eligibility | All customers |
| Usage limit | No limit |
| Combines with | Product discounts |
| Start date | Immediately |

---

## Discount 4: BOGO (Buy One Get One)

| Field | Value |
|---|---|
| Type | Buy X Get Y |
| Code | BOGOTREATS |
| Customer buys | 1 item from "Treats & Wellness" collection |
| Customer gets | 1 item from "Treats & Wellness" collection at 50% off |
| Usage limit | 1 per customer |
| Start date | Immediately |

---

## Testing Discounts

1. Go to **Online Store** and start a test order
2. Add products to cart
3. Enter discount code at checkout
4. Verify:
   - Correct discount amount is applied
   - Discount does not stack with incompatible offers
   - Free shipping applies automatically when cart total exceeds $75
   - BOGO applies the correct 50% off the second item

## Common Mistakes

- Creating percentage discounts without usage limits (customers share the code indefinitely)
- Not testing discount stacking behavior (some discounts cannot combine)
- Forgetting to set the automatic discount for free shipping (customers will not know to enter a code)
- Setting BOGO on the wrong collection (discount applies to unexpected products)
