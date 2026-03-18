# Guide 05 — Final QA Checklist

## Store Configuration

- [ ] Store name displays as "PawLux"
- [ ] Currency is set to USD
- [ ] Timezone is correct
- [ ] Password protection is enabled (dev store)
- [ ] Contact email is set
- [ ] Sender email is configured

## Branding

- [ ] Logo appears in header at correct size
- [ ] Favicon is uploaded
- [ ] Colors match brand guide (Primary: #1B4332, Secondary: #F5E6CC, Accent: #D4A574)
- [ ] Heading font is Outfit
- [ ] Body font is Inter
- [ ] Custom CSS is loaded and applying correctly

## Homepage

- [ ] Announcement bar displays and rotates messages
- [ ] Hero banner shows with heading, subheading, and CTA button
- [ ] Featured collection (Best Sellers) loads correct products
- [ ] USP/Benefits section shows all 4 columns
- [ ] Image with Text section appears (brand story)
- [ ] Testimonials display correctly
- [ ] Newsletter signup section renders and form submits
- [ ] Footer shows all columns with correct links
- [ ] Social media links point to correct URLs (or placeholder)
- [ ] Payment icons display in footer

## Navigation

- [ ] Main menu has all items: Shop All, Best Sellers, Collections (dropdown), New Arrivals, About, Contact
- [ ] Collection dropdown expands on hover (desktop) and tap (mobile)
- [ ] Footer menu has all policy and help links
- [ ] All menu links lead to correct pages (no 404s)
- [ ] Breadcrumbs display on product and collection pages
- [ ] Mobile hamburger menu works correctly

## Products

- [ ] All 5 products are imported and visible in the store
- [ ] Each product has: title, description, images, variants, pricing, SKU
- [ ] Compare-at prices show with strikethrough
- [ ] Product tags are assigned correctly
- [ ] Products appear in correct collections
- [ ] Variant selectors (size, color) work on product pages
- [ ] Add to cart button functions
- [ ] Inventory tracking is enabled

## Product Pages

- [ ] Product images load cleanly (no blurry or stretched images)
- [ ] Trust badges display below the add-to-cart button
- [ ] Sticky add-to-cart bar appears when scrolling past the form
- [ ] Review widget (Judge.me) appears on product pages
- [ ] Product recommendations appear at the bottom
- [ ] Product labels (Best Seller, Sale) display on tagged products
- [ ] Subscription option appears on calming treats
- [ ] SEO meta title and description are set

## Collections

- [ ] "Shop All" shows all products
- [ ] "Best Sellers" filters products with "bestseller" tag
- [ ] Each category collection shows correct products
- [ ] Filters (type, price, availability) work
- [ ] Star rating badges appear on product cards
- [ ] Product count is correct

## Content Pages

- [ ] About Us page content renders correctly
- [ ] Contact Us page has a working contact form
- [ ] FAQ page displays all questions and answers
- [ ] Shipping & Returns page has shipping table + return info
- [ ] Privacy Policy page is complete
- [ ] Terms of Service page is complete

## Cart & Checkout

- [ ] Products can be added to cart from product pages
- [ ] Products can be added from collection pages (quick add)
- [ ] Cart page shows correct items, quantities, and prices
- [ ] Cart updates correctly when quantity changes
- [ ] Discount code field is visible at checkout
- [ ] WELCOME15 applies 15% off
- [ ] BUNDLE20 applies $20 off on $120+ orders
- [ ] Free shipping applies automatically on $75+ orders
- [ ] BOGOTREATS applies 50% off second treat item
- [ ] Shipping rates display correctly
- [ ] Checkout flow completes in test mode (no real payment)

## Apps

- [ ] Judge.me review widget visible and styled
- [ ] Search & Discovery filters working
- [ ] Product recommendations appearing
- [ ] Bundles displaying on product pages
- [ ] Subscription option on calming treats
- [ ] Product labels (Labeler) showing correctly

## Email Popup

- [ ] Popup appears after 5 seconds on first visit
- [ ] Popup does not reappear after dismissal (cookie-based)
- [ ] Close button works
- [ ] Clicking outside the popup closes it
- [ ] Email form submits correctly
- [ ] Popup styling matches brand

## SEO

- [ ] Every page has a unique meta title
- [ ] Every page has a unique meta description
- [ ] H1 tags are present on every page
- [ ] Images have alt text
- [ ] URLs are clean (no trailing parameters or broken characters)
- [ ] Sitemap is accessible at /sitemap.xml

## Mobile Responsiveness

- [ ] Homepage renders correctly on mobile (375px width)
- [ ] Product pages are usable on mobile
- [ ] Cart page works on mobile
- [ ] Navigation is accessible via hamburger menu
- [ ] Buttons are large enough to tap (minimum 44px height)
- [ ] Text is readable without zooming
- [ ] No horizontal scroll on any page
- [ ] Sticky add-to-cart adapts to mobile layout
- [ ] Trust badges stack vertically on mobile
- [ ] Newsletter form stacks on mobile

## Visual Consistency

- [ ] Button styles are consistent across all pages
- [ ] Spacing and padding are uniform
- [ ] No orphaned text or widows in paragraphs
- [ ] No placeholder "Lorem ipsum" content anywhere
- [ ] Images are optimized (aim for under 200KB each)
- [ ] No broken images or missing assets

## Performance

- [ ] Pages load within 3 seconds on 4G connection
- [ ] No JavaScript errors in browser console
- [ ] No layout shifts during page load
- [ ] Images use proper formats (WebP preferred, JPEG fallback)
