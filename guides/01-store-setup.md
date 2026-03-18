# Guide 01 — Shopify Partner Account & Dev Store Setup

## Step 1: Create Shopify Partner Account

1. Go to https://partners.shopify.com
2. Click "Join now"
3. Use a fresh email address dedicated to this project
4. Fill in your name, email, and password
5. Complete the onboarding questions (select "Building stores for clients")
6. Verify your email

## Step 2: Create Development Store

1. In the Partner Dashboard, click "Stores" in the left sidebar
2. Click "Add store" > "Create development store"
3. Select "Create a store to test and build"
4. Enter store name: **pawlux** (this creates pawlux.myshopify.com)
5. Select the region and currency (USD)
6. Click "Create development store"

## Step 3: Enable Development Settings

1. In your new store admin (pawlux.myshopify.com/admin), go to **Settings** (bottom left)
2. Click **Plan** — confirm it shows "Development store" (no payments required for testing)
3. Go to **Settings > Online store > Preferences**
4. Under "Password protection," enable it and set password to: **Test@123**
5. This keeps the store private during development

## Step 4: Store Configuration

1. Go to **Settings > General**
   - Store name: **PawLux**
   - Store contact email: your business email
   - Sender email: noreply@pawlux.com (or your email)
2. Go to **Settings > General > Store currency**
   - Set to **USD — US Dollar**
3. Go to **Settings > General > Time zone**
   - Set to your local timezone
4. Go to **Settings > General > Unit system**
   - Set weight unit to **lb** (pounds)

## Step 5: Install Dawn Theme

1. Go to **Online Store > Themes**
2. Dawn should already be installed as the default theme
3. If not, click "Explore free themes" and install Dawn
4. Click **Customize** to open the theme editor

## Step 6: Basic Page Structure

Create these pages (go to **Online Store > Pages > Add page**):

| Page | Handle | Template |
|---|---|---|
| About Us | about-us | page |
| Contact Us | contact-us | page.contact |
| FAQ | faq | page |
| Shipping & Returns | shipping-returns | page |
| Privacy Policy | privacy-policy | page |
| Terms of Service | terms-of-service | page |
| Track Your Order | track-order | page |

For each page, paste the HTML content from the `content/` folder in this project.

## Step 7: Create Collections

Go to **Products > Collections > Create collection** for each:

| Collection | Type | Condition |
|---|---|---|
| All Products | Automated | All conditions |
| Best Sellers | Automated | Product tag is equal to "bestseller" |
| New Arrivals | Manual | Add newest products manually |
| Beds & Furniture | Automated | Product type is equal to "Dog Beds" |
| Walking Gear | Automated | Product type is equal to "Dog Harnesses" |
| Treats & Wellness | Automated | Product type is equal to "Dog Treats" |
| Apparel | Automated | Product type is equal to "Dog Apparel" |
| Toys & Enrichment | Automated | Product type is equal to "Dog Bowls" |

## Step 8: Upload Logo

1. Go to **Online Store > Themes > Customize**
2. Click the header section
3. Upload `brand/logo/pawlux-logo.png` as the logo
4. Set logo width to 120px

## Step 9: Add Custom CSS

1. Go to **Online Store > Themes > Customize**
2. Click the **gear icon** at the bottom left (Theme settings)
3. Scroll down to **Custom CSS**
4. Paste the entire contents of `theme/custom.css`
5. Click Save

## Step 10: Add Custom Liquid Snippets

For trust badges and sticky ATC:
1. Go to **Online Store > Themes > (...) > Edit code**
2. Under "Snippets," click "Add a new snippet"
3. Name it `trust-badges`
4. Paste contents of `theme/trust-badges.liquid`
5. Repeat for `sticky-add-to-cart` and `announcement-bar`
6. Include snippets in relevant templates using `{% render 'snippet-name' %}`

## Domain Notes

- **Shopify Domain**: pawlux.myshopify.com (free, always available)
- **Custom Domain**: Purchase from Shopify ($14/year for .com) or connect one from GoDaddy/Namecheap
- Custom domain setup: **Settings > Domains > Buy new domain** or **Connect existing domain**
- Shopify handles SSL certificates automatically for all domains

## Common Mistakes

- Forgetting to enable password protection (store becomes public prematurely)
- Not setting the correct timezone (affects order timestamps and analytics)
- Using the wrong template for the Contact page (must use page.contact for the form to appear)
- Not saving theme customizations after pasting CSS
