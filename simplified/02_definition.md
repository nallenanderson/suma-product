# Streamlined Product Definition Process
*Build the Minimum Viable Solution - Delete, Simplify, Ship*

---

## Input Required
**From Discovery:** 
- Problem statement + Solution approach
- 3 beta customer contacts + Revenue target 
- Engineering timeline estimate

**If you don't have these 4 things, go back to Discovery.**

---

## The 5-Day Definition Sprint

### Day 1: Prototype Core Solution (6 hours)
**Morning (3 hours):**
Start with Discovery solution approach and build a clickable prototype:
- Sketch the 3-5 screen user journey
- Build working prototype (**[Figma Make](https://www.figma.com/make/), [Lovable](https://lovable.dev/), [AI Studio](https://aistudio.google.com/app/apps), [v0](https://v0.dev/), [Bolt](https://bolt.new/), [Replit](https://replit.com/)**, or even PowerPoint 🤯)
- Focus on core user action, ignore polish

**Afternoon (3 hours):**
Test prototype with 1-2 beta customers:
- "Here's how we think you'd solve [problem] - walk through this"
- Record what confuses them vs. what clicks
- Ask: "Would this solve your problem if it worked exactly like this?"

### Day 2: Minimum Feature Set (4 hours)
**Based on prototype feedback, define the absolute minimum:**

**The 3 Must-Have Features:**
1. [Feature that enables core user action from prototype]
2. [Feature that makes #1 possible]  
3. [Feature that makes #2 possible]

**Test with beta customers:** "If we only built these 3 things, would you use it daily?"

### Day 3: Technical Reality Check (6 hours)
**Morning (3 hours):**
Show prototype to engineering:
- "What's the fastest way to make this actually work?"
- Can we hack together existing systems?
- What's the biggest technical risk?

**Afternoon (3 hours):**
Refine timeline with engineering reality:
- Original Discovery estimate: [X] weeks
- Revised after seeing prototype: [Y] weeks
- If >12 weeks: Cut features or kill project

### Day 4: Beta Plan & Success Metrics (4 hours)
**Beta customer validation:**
- Confirm 3 beta customers will test in [Y] weeks
- Define success: "What needs to work for you to use this daily?"
- Schedule weekly check-ins during build phase

**Success measurement:**
- Primary metric: [Number that proves we solved the problem]
- Beta success: 2/3 customers use it daily after week 2

### Day 5: Build Plan (2 hours)
**Week-by-week build plan:**
- Week 1-2: [Specific prototype feature becomes working code]
- Week 3-4: [Next prototype feature becomes working code]  
- Week 5+: [Integration and beta testing]

**Resource confirmation:** [Y] engineers committed for timeline

---

## The Definition Output

### What We're Building
**Problem:** [Copy from Discovery]
**Solution:** [Refined from prototype testing]
**Pricing Model:** [Add-on/Plan inclusion/Usage-based] at $[X]/[period]
**Customer Validation:** [Y]/3 beta customers confirmed this model works for them
**Success:** [Primary metric + beta customer commitment to pay via this model]

### The Validated Feature Set
**Must Have (Validated by prototype + customers):**
1. [Feature] - Because [customers said this was essential in prototype test]
2. [Feature] - Because [enables #1 to work]
3. [Feature] - Because [enables #2 to work]

**Won't Have (Intentionally excluded):**
1. [Feature] - Because [customers didn't mention it OR engineering complexity too high]
2. [Feature] - Because [nice-to-have but not essential for core problem]
3. [Feature] - Because [can be added later if beta customers request it]

**Customer Quote:** "[Best quote from prototype testing showing they want this AND will pay for it]"

**Pricing Model Validation:** 
- **Model chosen:** [Add-on / Plan Inclusion / Usage or Volume Based/ Tiered]
- **Customer reasoning:** "[Why customers prefer this model - e.g., 'Add-on makes sense because we only need this occasionally']"
- **Budget/approval fit:** "[How this fits their procurement - e.g., 'Usage-based works because we can start small and scale']"

### Prototype-to-Code Plan
**Week 1-2:** [Prototype screen 1] becomes working feature
**Week 3-4:** [Prototype screen 2] becomes working feature
**Week 5-6:** [Integration] - features work together
**Week 7+:** Beta testing with actual customers

### Technical Approach (Post-Prototype)
**Stack:** [Frontend tech] + [Backend tech] + [Database]
**Integration:** [External systems needed]
**Biggest Risk:** [Technical challenge identified during prototype review]

**Final Timeline:** [Y] weeks (revised from Discovery estimate)
**Team:** [Y] engineers committed

### Beta Plan (Pre-Confirmed)
**Beta customers:** [3 names who saw prototype and committed]
**Success criteria:** 2/3 customers use daily after week 2
**Weekly demos:** Every Friday during build

---

## Go/No-Go Decision
**SHIP IT if ALL are true:**
- [ ] 2/3 beta customers said "yes, I'd use this daily" after seeing prototype
- [ ] Prototype demonstrates solution fits in <5 user steps
- [ ] Engineering confirms can build in revised timeline (<12 weeks)
- [ ] Technical risks are manageable
- [ ] Beta customers committed to weekly feedback during build

**KILL IT if ANY are true:**
- [ ] Beta customers weren't convinced by prototype
- [ ] Still takes >12 weeks after seeing what we're actually building
- [ ] Major technical risks discovered during prototype review
- [ ] Can't simplify user journey to <5 steps
- [ ] Beta customers won't commit to testing timeline

---

## The Build Phase Handoff

### Sprint 1 Goal (Week 1)
[One specific, demoable outcome]

### Week 2-4 Goal
[One specific, demoable outcome]

### Weeks 5-8 Goal
[One specific, demoable outcome]

### Weeks 9-12 Goal
[Working solution in beta]

**Success Tracking:**
- Weekly demo to beta customers
- Weekly metric check: [Primary metric]
- Weekly pricing value confirmation: "Still worth $[X] to you?"
- If metric doesn't improve OR pricing value questioned after 4 weeks: STOP and reassess

---

## Anti-Patterns to Delete

❌ **Detailed user stories with acceptance criteria** - Build and test instead
❌ **Technical architecture diagrams** - Start coding and refactor later
❌ **Risk matrices and mitigation plans** - Ship fast and fix problems
❌ **Multiple user personas** - Focus on one person's problem
❌ **Phase 2 and Phase 3 planning** - Ship Phase 1 first

---

## Definition Complete

**Decision:** SHIP IT or KILL IT
**If SHIP IT:** Development starts Monday with prototype as reference
**If KILL IT:** Archive prototype and pick next Discovery problem

**One person decides. No committees.**

*The best way to define a product is to prototype it and test with customers first.*