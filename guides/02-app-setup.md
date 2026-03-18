# Guide 02 — Essential App Installation & Configuration

## App 1: Judge.me Product Reviews

**Purpose**: Collect and display customer reviews on product pages.

### Installation
1. Go to Shopify Admin > **Apps > Shopify App Store**
2. Search "Judge.me Product Reviews"
3. Click "Add app" and approve permissions

### Configuration
1. After install, open Judge.me dashboard
2. Go to **Settings > Widget**
   - Review widget style: **Stars + Review Count**
   - Star color: `#D4A574` (matches PawLux accent)
   - Font: leave as default (inherits from theme)
3. Go to **Settings > Emails**
   - Enable "Review request email" — set delay to 14 days after fulfillment
   - Customize email template with PawLux branding (logo, green header)
4. Go to **Display > Review Widget**
   - Enable on product pages
   - Position: below product description
5. Go to **Display > Preview Badge**
   - Enable star rating on collection pages

### Testing
- Open any product page and confirm the review widget appears below the description
- Star rating badge should appear on collection page product cards

---

## App 2: Shopify Search & Discovery

**Purpose**: Improve search functionality, add filters, and recommend related products.

### Installation
1. Apps > Shopify App Store > search "Search & Discovery" (by Shopify)
2. Click "Add app"

### Configuration
1. Open the app > **Filters**
   - Add filters: Product type, Price, Availability
   - Enable on collection pages
2. Go to **Recommendations**
   - Enable "Related products" on product pages
   - Enable "You may also like" section
3. Go to **Search**
   - Add synonyms: "bed" = "mattress", "harness" = "leash"
   - Enable search suggestions

---

## App 3: Shopify Bundles

**Purpose**: Create product bundles for higher average order value.

### Installation
1. Apps > Shopify App Store > search "Shopify Bundles" (by Shopify)
2. Install the app

### Configuration
1. Open app > Create Bundle
2. Suggested bundle: "Complete Walk Kit"
   - Adjustable No-Pull Dog Harness + Waterproof Dog Jacket
   - Bundle discount: 10% off when purchased together
3. Suggested bundle: "Comfort Essentials"
   - Orthopedic Memory Foam Dog Bed + Natural Calming Dog Treats
   - Bundle discount: 15% off

---

## App 4: Shopify Marketplace Connect

**Purpose**: Connect with marketplace channels for multi-channel selling.

### Installation
1. Apps > Shopify App Store > search "Marketplace Connect" (by Shopify)
2. Install and follow the onboarding flow

### Configuration
1. Review marketplace options (Amazon, eBay, Walmart)
2. For a dev store, simply install and review the interface
3. Actual marketplace connection requires a live store with a paid plan

---

## App 5: Shopify Subscriptions

**Purpose**: Enable recurring subscription orders (ideal for consumable products like treats).

### Installation
1. Apps > Shopify App Store > search "Shopify Subscriptions" (by Shopify)
2. Install the app

### Configuration
1. Open app > Create Subscription Plan
2. Apply to: **Natural Calming Dog Treats**
3. Frequency options: Every 30 days, Every 60 days
4. Discount: 10% off subscription price
5. Enable "Subscribe & Save" badge on the product page

---

## App 6: Labeler — Product Labels & Badges

**Purpose**: Add visual labels like "Best Seller," "Sale," "New" to product images.

### Installation
1. Apps > Shopify App Store > search "Labeler - Product Labels & Badges"
2. Install the app

### Configuration
1. Open app > Create Label
2. Create labels:
   - **Best Seller** — Gold (#D4A574) background, white text
   - **Sale** — Red (#DC2626) background, white text
   - **New** — Green (#1B4332) background, white text
3. Assign labels:
   - "Best Seller" to products tagged "bestseller"
   - "Sale" to products with compare-at price
4. Position: Top-left corner of product image
5. Preview and save

---

## Post-Installation Checklist

- [ ] Judge.me review widget visible on product pages
- [ ] Star ratings visible on collection pages
- [ ] Search filters working on collection pages
- [ ] Product recommendations appearing on product pages
- [ ] Bundle options displaying correctly
- [ ] Subscription option visible on calming treats product page
- [ ] Product labels showing on appropriate products

## Common Mistakes

- Installing too many apps at once without testing each individually
- Not customizing app colors to match your brand (default styles clash with the theme)
- Forgetting to enable widgets after installation (apps install in disabled state)
- Not testing on mobile after enabling app widgets (layout shifts)
