# Guide 06 — Shopify Sidekick AI Usage

## What is Shopify Sidekick?

Shopify Sidekick (now called Shopify Magic) is an AI assistant built into the Shopify admin. It helps with content generation, layout suggestions, and store optimization directly inside your dashboard.

## How to Access

1. Log into your Shopify Admin
2. Look for the **Sidekick icon** (sparkle/star) in the bottom-right corner of any admin page
3. Click it to open the AI chat panel

## Task 1: Section Layout Suggestions

**Prompt to use:**
> "Suggest the best homepage section order for a premium pet accessories store targeting dog owners aged 25-45."

**What to expect:**
Sidekick will recommend a section sequence. Compare its suggestion against the layout in `content/homepage-sections.md` and adjust if the AI identifies a higher-converting arrangement.

**Prompt for collection page:**
> "What sections should I add to my collection pages to increase add-to-cart rate?"

## Task 2: Copy Improvements

Use Sidekick to refine product descriptions and page content.

**Product description prompt:**
> "Rewrite this product description to be more benefit-focused and conversion-optimized: [paste your description]"

**Hero banner prompt:**
> "Write 3 alternative hero section headlines for a premium dog accessories brand. The brand voice is warm, trustworthy, and premium."

**Email subject line prompt:**
> "Write 5 email subject lines for a welcome series offering 15% off the first order for a dog accessories brand called PawLux."

## Task 3: Navigation Optimization

**Prompt:**
> "Review my store navigation and suggest improvements. My main menu has: Shop All, Best Sellers, Collections (dropdown with 5 sub-items), New Arrivals, About, Contact."

**What to look for:**
- Whether the menu structure is too deep or too flat
- If "Shop All" and collection dropdown are redundant
- Missing calls-to-action in the navigation

## Task 4: SEO Description Generation

**Prompt:**
> "Write an SEO meta description (under 155 characters) for a product page selling an orthopedic memory foam dog bed priced at $89.99."

**Bulk generation prompt:**
> "Generate meta titles and meta descriptions for the following 5 products: [list your products]. Keep titles under 60 characters and descriptions under 155 characters."

Compare outputs against `seo/seo-meta.md` and use whichever version is stronger.

## Task 5: AI-Generated Sections

Shopify Magic can generate entire content sections. Use it for:

**Blog post ideas:**
> "Suggest 5 blog post topics for a dog accessories brand. Focus on SEO keywords related to dog health, walking, and home comfort."

**FAQ expansion:**
> "Generate 5 additional FAQ questions and answers for a dog accessories store that sells beds, harnesses, treats, jackets, and puzzle feeders."

**Social media captions:**
> "Write 5 Instagram captions promoting a natural calming dog treat product. Include relevant hashtags."

## Task 6: Store Analysis

**Prompt:**
> "Analyze my store and tell me what I should improve for better conversion rates."

Sidekick will scan your store pages, products, and settings, then provide actionable recommendations.

## Best Practices

1. Always review AI-generated content before publishing — it sometimes produces generic copy
2. Use AI output as a starting draft, then edit to match your brand voice
3. Run A/B tests if Sidekick suggests headline alternatives
4. Do not rely on AI for legal content (privacy policies, terms) — use the versions in `content/` which are properly structured
5. Save effective prompts in a document for reuse across products and campaigns

## Common Mistakes

- Accepting AI-generated descriptions without editing (they sound robotic and generic)
- Using Sidekick for legal pages (it produces vague, non-compliant text)
- Not comparing AI suggestions against your existing content (sometimes your version is already better)
- Overloading prompts with too many instructions (keep prompts focused on one task at a time)
