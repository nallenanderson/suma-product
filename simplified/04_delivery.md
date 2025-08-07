## Pricing Integration Across Workflow

### Discovery Phase (Pricing Foundation)
**Key Questions:**
- "What would you pay to never deal with this problem again?"
- "How much does this problem cost you annually?"
- "What's your current budget for solving this?"

**Pricing Output:** Price range based on customer value ($[X] - $[Y])

### Definition Phase (Pricing Validation & Decision) ⭐
**During prototype testing:**
- "For this exact solution [show prototype], what would you expect to pay?"
- "At $[X]/month, would you purchase this?"
- "What price would make this a no-brainer vs. too expensive?"

**Pricing Output:** **VALIDATED PRICE DECISION** - $[X]/period with customer commitment

### Development Phase (Pricing Confirmation)
**During weekly demos:**
- "As this becomes real, is it still worth $[X] to you?"
- "Does the working version deliver the value you expected for this price?"

**Pricing Output:** Final price confirmation from active beta users

### Delivery Phase (Pricing Execution Only)
**Launch with pre-validated pricing:**
- Execute validated pricing strategy (no pricing decisions)
- Monitor conversion rates vs. beta validation
- Minor optimizations only if needed

**The key insight:** Price is DECIDED in Definition, CONFIRMED in Development, EXECUTED in Delivery.# Streamlined Delivery Process
*Ship to Customers Immediately - Delete, Simplify, Launch*

---

## Input Required
**From Development:** 
- Working product that matches validated prototype
- 3 beta customers already using it daily
- Validated pricing confirmed during development ($[X]/period)
- Usage data proving product-prototype match
- Customer feedback confirming it solves their problem AND is worth the price

**If beta customers aren't using the working product daily AND confirming pricing value, don't launch it.**

---

## The 3-Day Launch Process

### Day 1: Launch Decision (Pricing Already Set)
**Pricing Model Confirmation (From Definition Phase):**
- Validated pricing model from Definition: $[X]/[period] as [Add-on/Plan inclusion/Usage-based]
- Beta customer validation: [Y]/3 customers confirmed this model works for them
- Billing system ready: [Confirmed with Finance/Ops team]
- **No pricing model decisions needed** - model was validated with prototype and billing system prepped

**Launch Decision:** 
- Question: Are 3 beta customers using this daily AND still confirm the pricing model works for them?
- **Yes:** Launch to all customers immediately with validated pricing model
- **No:** Don't launch - fix product or pricing model issue first

### Day 2: Turn It On (Execute Validated Pricing Model)
**Morning:** Product + validated pricing model live for 100% of customers
**Pricing Communication:** 
- **If Add-on:** "New [feature name] add-on - $[price]/[period] - [benefit]"
- **If Plan inclusion:** "[Feature name] now included in [Plan Name] - [benefit]" 
- **If Usage-based:** "New [feature name] - $[price] per [unit] - [benefit]"
**Afternoon:** Monitor for usage and any pricing model confusion
**Evening:** Check adoption metrics and initial revenue/usage

### Day 3: Measure Success
**Usage:** [X]% of customers tried it
**Conversion:** [Y]% of triers became paying customers  
**Revenue:** $[Z] actual vs $[Expected] projected
**Problems:** Fix any pricing or product issues immediately

---

## The Only Launch Plan That Matters

### Before Launch (1 hour)
**Tell customers:** "New feature is live now - here's what it does"
**Tell support:** "Here's how the feature works + how to help customers"
**Tell engineering:** "Watch for these 3 things that could break"

### Launch Day (Monitor Only)
**Hour 1:** Are customers using it?
**Hour 4:** Any critical issues?
**End of day:** Success or rollback decision

### After Launch (1 week)
**Daily:** Fix any customer problems immediately
**Weekly:** Measure adoption rate
**Monthly:** Measure business impact

---

## Success Metrics (The Only 4 That Matter)

### 1. Customer Adoption
**Target:** [X]% of eligible customers try feature within 7 days
**Measure:** Feature activation rate
**Action:** If <50% adoption after week 1, fix product or messaging

### 2. Revenue Conversion  
**Target:** [Y]% of triers become paying customers within 14 days
**Measure:** Trial-to-paid conversion rate
**Action:** If <[expected]% conversion (based on beta validation), investigate disconnect

**Note:** Conversion rate target based on beta customer validation rate from Definition phase

### 3. Customer Problems
**Target:** <5 support tickets per 100 active users
**Measure:** Support ticket volume (product + pricing questions)
**Action:** Fix any problem affecting >10 customers immediately

### 4. Revenue Target Achievement
**Target:** $[X] incremental monthly revenue (from Discovery, validated in Definition)
**Measure:** Actual recurring revenue from feature
**Action:** If <80% of target after 30 days, investigate (pricing was pre-validated, so likely adoption issue)

**Everything else is vanity metrics.**

---

## Customer Communication (Minimum Viable)

### Launch Message (Send Once)
**Subject varies by pricing model:**

**If Add-on:** "[Feature Name] add-on now available - $[price]/[period]"
**If Plan inclusion:** "[Feature Name] now included in your [Plan Name]"  
**If Usage-based:** "[Feature Name] available - pay as you use ($[price]/[unit])"

**Content template:**
- What: [One sentence what it does]
- Why: [One sentence problem it solves + value delivered]
- Pricing: [Model-specific pricing explanation]
- How: [One click to start - varies by model]

**Send to:** [Targeted by pricing model - all customers, specific plan customers, etc.]

**Support Training (15 minutes)
**Tell support team:**
- What the feature does
- Pricing model: $[price]/[period] as [Add-on/Plan inclusion/Usage-based] - why this model
- How billing works: [Billing process for this model]
- 3 most likely customer questions (product + pricing model)
- Who to escalate complex issues to

**Pre-validated pricing model responses:**
- **Add-on questions:** "Why separate charge?" → "Beta customers preferred flexibility to add only if needed"
- **Plan inclusion questions:** "Why not available in Basic?" → "Pro customers validated this fits their workflow"  
- **Usage-based questions:** "How is usage calculated?" → [Specific usage definition from validation]
- **Billing questions:** [Process for their specific model - monthly, annual, per-usage, etc.]

---

## Problem Resolution

### Critical Issues (Fix Immediately)
**Critical = Any of these:**
- Feature doesn't work for >10% of users
- Feature breaks existing functionality
- Data corruption or security issue
- >20 angry customer emails

**Response:** Fix within 4 hours or rollback feature

### Non-Critical Issues (Fix This Week)
**Non-Critical = Everything else**
**Response:** Add to next week's development priorities

### Feature Rollback (Nuclear Option)
**Trigger:** Critical issue can't be fixed in 4 hours
**Process:** 
1. Turn off feature for all customers
2. Email customers: "Feature temporarily disabled - back soon"
3. Fix problem and re-launch when ready

---

## Launch Success Patterns

### Week 1: Adoption + Pricing Validation
**Success:** >50% try feature, conversion rate matches beta validation
**Warning:** Good adoption but lower conversion than beta (investigate pricing communication)
**Failure:** <20% adoption (product-market fit problem, not pricing)

### Week 2-4: Usage + Revenue Growth
**Success:** Daily usage >30% of adopters, revenue tracking to target
**Warning:** Good usage but revenue below target (pricing optimization needed)
**Failure:** <10% daily usage OR <10% conversion (fix or kill)

### Month 2+: Revenue Target Achievement
**Success:** Hit Discovery revenue target ($[X]/month)
**Warning:** 60-80% of revenue target (optimize conversion or pricing)
**Failure:** <60% of revenue target (major iteration or sunset)

---

## Anti-Patterns to Delete

❌ **Gradual rollouts and A/B tests** - Ship to everyone immediately
❌ **Launch planning meetings** - Just turn it on
❌ **Customer training programs** - Make features self-explanatory
❌ **Detailed launch documentation** - Write one email
❌ **Success celebration events** - Celebrate revenue impact instead
❌ **Post-launch retrospectives** - Fix problems immediately instead
❌ **Feature flag management** - Ship working features, not broken ones
❌ **Launch communication campaigns** - One email, then let usage speak

---

## The Customer Success Loop

### Daily Monitoring (5 minutes)
**Check:** Customer usage numbers
**Ask:** Any new support tickets about this feature?
**Act:** Fix problems same day

### Weekly Health Check (15 minutes)
**Usage trend:** Up, down, or flat?
**Customer feedback:** Happy, confused, or angry?
**Business impact:** Positive, neutral, or negative?

### Monthly Impact Review (30 minutes)
**Revenue impact:** $[X] incremental MRR
**Customer retention:** [Y]% improvement
**Feature fate:** Keep building, maintain, or sunset

---

## Launch Communication Templates

### Customer Launch Email
```
Subject: [Feature] is now live

Hi [Customer],

We just launched [Feature Name] - it [solves specific problem].

Try it now: [Direct link]

Questions? Hit reply.

Thanks,
[Team]
```

### Support Team Briefing
```
New feature: [Feature Name]
What it does: [One sentence]
How customers use it: [One sentence]
Common questions: [List 3]
Escalate to: [Name] for complex issues
```

### Internal Launch Announcement
```
[Feature Name] is live for all customers.
Watch for: [3 potential issues]
Success target: [X]% adoption in 7 days
Questions to: [Product Manager]
```

---

## Launch Decision Framework

### Ship It If:
- [ ] Beta customers use it daily
- [ ] Feature works end-to-end
- [ ] Solves real customer problem
- [ ] Support team knows how to help
- [ ] Can rollback if needed

### Don't Ship If:
- [ ] Beta customers stopped using it
- [ ] Major functionality broken
- [ ] No clear customer benefit
- [ ] Too complex to support
- [ ] Can't measure success

**One person decides. No committees.**

---

## Post-Launch Reality

### Week 1: Fire Fighting
**Focus:** Fix anything breaking customer workflows
**Success:** No angry customers, feature works
**Decision:** Continue or rollback

### Month 1: Adoption Drive
**Focus:** Help customers discover and use feature
**Success:** Target adoption rate hit
**Decision:** Invest more or pivot

### Month 3: Impact Measurement
**Focus:** Measure business results
**Success:** Clear ROI from development investment
**Decision:** Build more features or optimize existing

---

## Launch Complete

**Success:** Customers use feature daily + business impact achieved
**Failure:** Low adoption or no business impact

**The market decides if features succeed, not internal metrics.**

*Ship fast, measure impact, fix problems immediately.*