# InvoiceShield: Contractor Research & Hybrid Pricing Model
**Date:** April 8, 2026

---

## PART 1: WHAT TOOLS DO CANADIAN CONTRACTORS ACTUALLY USE?

### The Reality (Not What Tech People Assume)

Most small contractors do NOT use Stripe, Wave, or sophisticated invoicing platforms. The industry is far less digitized than assumed.

| Tool | Market Share | Who Uses It | Notes |
|------|-------------|-------------|-------|
| **QuickBooks** | ~47% of small businesses | Established firms with a bookkeeper | Most common. Has basic reminder feature but no AI escalation. |
| **Jobber** | Growing fast | Field service contractors (HVAC, plumbing, electrical, landscaping) | Built for scheduling + invoicing. Popular with trades. |
| **Joist** | Popular with solo trades | Small renovation, roofing, painting contractors | Free tier popular. Estimate-focused. |
| **Sage** | Enterprise-leaning | Mid-size construction firms (10-50 employees) | Overkill for solos but common in established firms. |
| **Excel / Google Sheets** | ~20-30% of micros | Solo operators, 1-3 person shops | No automation at all. Manual everything. |
| **Paper / Nothing** | ~44% of micro firms | Handshake-deal contractors | Construction is the 2nd least digitized sector. 44% use NO software. |
| **FreshBooks** | Small share | Creative freelancers more than trades | Toronto-born but not construction-focused. |
| **Wave** | Small share | Solopreneurs on a budget | Free but basic. Being sunset/changed. |

### Key Insight: The 44% Gap

44% of micro construction firms use NO invoicing software at all. They send handwritten invoices, Word docs, or verbal agreements. These are the hardest to onboard but also the most desperate for help collecting.

### Integration Priority for InvoiceShield

| Priority | Integration | Why | Difficulty |
|----------|-------------|-----|-----------|
| **#1** | CSV / Email Upload | Works for EVERYONE, including the 44% with no software | Easy (already built) |
| **#2** | QuickBooks API | 47% market share. OAuth connection. Well-documented API. | Medium |
| **#3** | Jobber API | Growing fast in trades. REST API available. | Medium |
| **#4** | Joist | Popular with solos. API access may be limited. | Hard (may need scraping) |
| **#5** | Sage | Enterprise. Lower priority for our target (micro firms). | Medium |

---

## PART 2: WHY CONSTRUCTION IS #1 TARGET

### The Data

| Metric | Value | Source |
|--------|-------|--------|
| Late payment rate | **91%** of construction businesses | BCCA Survey |
| On-time payment rate | Only **5%** of subcontractors | DocJoist 2026 |
| Average wait after submitting | **56 days** (extremes of 120 days) | CCA |
| Unpaid after 30 days | **$46 billion** outstanding | Canadian Construction Association |
| Withdraw from personal savings | **1 in 3** subcontractors | BCCA |
| Not paid at all for completed work | **69%** experienced this | BCCA |
| Self-employed in construction | **356,900+** | Statistics Canada 2023 |

### Regulatory Tailwind

Canada's Prompt Payment legislation (federal Dec 2023, plus ON, AB, SK, MB, NT) creates urgency. Contractors now have legal backing but need tools to enforce timely payment.

### Why They'll Pay for InvoiceShield

1. **Pain is extreme** -- 91% deal with late payments, 1 in 3 dip into savings
2. **Current solutions are expensive** -- Collection agencies take 20-25%, factoring companies take 2.5-8%
3. **No AI-powered alternative exists** in Canada at our price point
4. **Digital adoption is low** -- they need something simple, not another complex SaaS
5. **Average invoice sizes are large** -- $5K-$50K per job, so even 3% recovery fee is a bargain vs. not getting paid

---

## PART 3: UPDATED HYBRID PRICING MODEL

### Why We Changed from Flat Pricing

**Old model:** $0 / $9 / $19 per month (flat)
**Problem:** A contractor waiting 60 days for a $10K invoice only pays $19/mo to recover $10K. That's massively underpriced.

**Benchmarks that justify hybrid pricing:**
- Collection agencies: 20-25% of recovered amount
- Invoice factoring: 2.5-8% of invoice value
- Trade credit insurance: 0.5-2% of sales volume
- Carrying cost of late payment on $10K invoice: ~$1,400/year in interest + opportunity cost

### New Hybrid Pricing

| Plan | Monthly Fee | Recovery Fee | Invoice Limit | Target Customer |
|------|------------|-------------|---------------|-----------------|
| **Starter** | $29/mo | 3% of recovered | Up to 20 invoices | Solo contractors, testing the tool |
| **Pro** | $49/mo | 2.5% of recovered | Up to 100 invoices | Busy contractors, small firms |
| **Shield** | $99/mo | 1.5% of recovered | Unlimited | Growing firms, agencies, fleet owners |

### What Each Plan Includes

**Starter ($29/mo + 3%)**
- AI reminder sequences (friendly > firm > final notice)
- Email reminders
- CSV / email upload
- Basic reporting

**Pro ($49/mo + 2.5%)** -- Most Popular
- Everything in Starter
- SMS reminders
- Client Payment Scores
- QuickBooks integration
- Priority support

**Shield ($99/mo + 1.5%)**
- Everything in Pro
- Jobber + Sage integrations
- Custom branding on reminders
- Dedicated account manager
- API access

**All plans:** No long-term contract. Cancel anytime. Recovery fee only charged when money actually lands in your account.

### Revenue Comparison: Old vs New

**Scenario:** Contractor recovers $10,000 in late invoices per month

| Model | Monthly Revenue per Customer |
|-------|------------------------------|
| Old ($19/mo flat) | $19 |
| New Pro ($49 + 2.5%) | $49 + $250 = **$299** |
| New Shield ($99 + 1.5%) | $99 + $150 = **$249** |

**15x revenue increase per customer** while still being 10x cheaper than a collection agency ($2,000-$2,500 on $10K).

### How We Pitch the Price

> "A collection agency charges 20-25% of what they recover. That's $2,500 on a $10K invoice. We charge under 3%. On that same $10K, you pay about $300 total. You keep $9,700 instead of $7,500. And we don't burn the client relationship."

### The Math That Sells Itself

| Recovery Amount | Collection Agency (25%) | InvoiceShield Pro (2.5% + $49) | You Save |
|----------------|------------------------|-------------------------------|----------|
| $5,000 | $1,250 | $174 | **$1,076** |
| $10,000 | $2,500 | $299 | **$2,201** |
| $25,000 | $6,250 | $674 | **$5,576** |
| $50,000 | $12,500 | $1,299 | **$11,201** |

---

## PART 4: COMPETITIVE POSITIONING

| Competitor | Price | AI-Powered | Canada-Born | Construction Focus | Recovery Fee Model |
|-----------|-------|-----------|-------------|-------------------|-------------------|
| Chaser | $45+/mo | No | No (UK) | No | No |
| Paidnice | $30+/mo | No | No (NZ) | No | No |
| InvoiceSherpa | $49+/mo | No | No (US) | No | No |
| FreshBooks | $22+/mo | No | Yes (Toronto) | No | No |
| Collection Agency | 20-25% | No | Varies | Some | Yes (expensive) |
| **InvoiceShield** | **$29-99/mo + 1.5-3%** | **Yes** | **Yes** | **Yes** | **Yes (affordable)** |

**Our unique position:** Only Canadian-born, AI-powered payment recovery tool with hybrid pricing. 10x cheaper than collection agencies. Built for contractors who use Jobber, Joist, or nothing at all.

---

## PART 5: PROVINCIAL LAUNCH PRIORITY

| Province | Small Businesses | Delinquency YoY | Construction Self-Employed | Launch Order |
|----------|-----------------|-----------------|---------------------------|-------------|
| **Ontario** | 410,154 | +18.85% | Largest pool | #1 |
| **British Columbia** | 170,512 | +19.93% | BCCA data source | #2 |
| **Alberta** | 137,182 | +8.90% | Oil & gas crossover | #3 |
| **Quebec** | 228,622 | +13.31% | Needs French support | #4 |

---

*All data sourced from: Statistics Canada, BCCA, CCA, DocJoist 2026, Equifax Canada Q1-Q2 2025, Atradius 2024, Freelance.ca 2026*
