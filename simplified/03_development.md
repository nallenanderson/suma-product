# Streamlined Development Process
*Ship Working Code Daily - Delete, Simplify, Deliver*

---

## Input Required
**From Definition:** 
- Tested prototype + customer validation
- 3 must-have features (customer-confirmed)
- 3 beta customers committed to weekly testing
- Week-by-week build plan

**If you don't have these 4 things, go back to Definition.**

---

## The Weekly Build Cycle

### Monday: Week Goal + Prototype Reference
**This Week's Outcome:** [One prototype screen/feature becomes working code]

**Success Test:** "Can beta customers complete [specific task from prototype] without breaking?"

**Prototype Reference:** Use Definition prototype as specification - build exactly what customers already validated

### Tuesday-Thursday: Build Against Prototype
**Daily Question:** "Does this work like the prototype customers approved?"

**Daily Rule:** Every engineer commits working code that matches prototype behavior

**Daily Demo:** Show yesterday's progress compared to prototype (5 minutes max)

### Friday: Customer Demo & Feedback
**Demo:** Show this week's working feature to beta customers (same ones who tested prototype)
**Ask:** "Does this work like you expected from the prototype?"
**Record:** Differences between prototype and working code that matter to customers
**Decide:** Keep building next prototype screen OR fix this week's work

---

## The Only Tracking That Matters

### Weekly Progress
**Prototype vs. Reality:** [Which prototype screen is now working code]
**Customer Feedback:** [What beta customers said about this week's work]
**Next Prototype Feature:** [Which prototype screen we build next week]

**That's it. No story points, no burn-down charts, no velocity tracking.**

### Quality Gates (Delete Everything Else)
**The 3 Gates:**
1. **Does it work?** [User can complete the core action]
2. **Is it secure?** [Financial data encrypted, no obvious exploits]
3. **Is it fast?** [<3 second response time]

**If all 3 = Yes:** Ship it
**If any = No:** Fix it

---

## Problem Resolution

### Daily Issues
**Problem:** [What broke today]
**Owner:** [One person fixes this]
**Fix by:** [End of day/tomorrow/this week]

**No issue tracking systems. No ticket priorities. One person owns it, fixes it quickly.**

### Weekly Retrospective (5 minutes)
**What slowed us down this week?** [One thing]
**How do we eliminate it next week?** [One action]
**Who owns the fix?** [One person]

---

## Code Standards (Minimum Viable)

### Definition of Working
- [ ] Feature works end-to-end for target user
- [ ] Another engineer has tested it
- [ ] Code doesn't break existing features
- [ ] Financial calculations are correct (for ERP/Payroll)

**No code review meetings. No architecture reviews. Just working code.**

### Security Minimums (Non-Negotiable)
- [ ] User data encrypted at rest and in transit
- [ ] Financial data uses AES-256 encryption
- [ ] API endpoints require authentication
- [ ] Input validation prevents SQL injection

### Performance Minimums
- [ ] API responses <3 seconds
- [ ] Page loads <5 seconds
- [ ] Database queries optimized for 1000+ users

---

## The Build-Ship Loop (Prototype-Driven)

### Week 1-2: First Prototype Screen → Working Code
**Build:** Most important prototype screen/workflow
**Test:** With same 3 beta customers who validated prototype
**Compare:** "Does the working version match what you expected from prototype?"
**Result:** Screen works like prototype OR we fix the differences

### Week 3-4: Second Prototype Screen → Working Code
**Build:** Next prototype screen/workflow
**Test:** Integration with week 1-2 work + beta customer feedback
**Compare:** "Can you complete the full workflow from prototype?"
**Result:** Workflow works end-to-end OR we simplify

### Week 5-8: Complete Prototype → Working Product
**Build:** Remaining prototype screens + integration
**Test:** Full user journey with beta customers
**Compare:** "Does this solve your problem like the prototype showed?"
**Result:** Beta customers use daily OR we iterate

### Week 9-12: Polish Based on Usage
**Build:** Fix what beta customers struggle with most
**Test:** Usage patterns and feedback
**Result:** Ready for full launch to all customers

---

## Customer Feedback Loop (Pre-Validated Customers)

### Weekly Customer Demo (Same Beta Customers from Definition)
**Show:** This week's working feature vs. prototype version
**Ask:** "Does this work like you expected? What's different?"
**Record:** Gaps between prototype and working code
**Decide:** Fix differences OR keep building (if gap doesn't matter to customers)

### Beta Customer Health (Validated Pipeline)
**Healthy:** Customer uses working features daily (matching prototype expectations)
**Warning:** Customer confused by differences from prototype
**Critical:** Customer says "this doesn't work like the prototype showed me"

**If Critical:** Stop building new features and fix the disconnect

---

## Team Coordination

### Daily Standup (5 minutes max)
**Yesterday:** What prototype feature I built working code for
**Today:** Which part of prototype I'm making work
**Blocker:** Gap between prototype and technical reality (or "none")

**No status updates. No planning discussions. Just prototype-to-code progress.**

### Weekly Planning (15 minutes max)
**Last week:** Did prototype screen work like customers expected? [Yes/No]
**This week:** Which prototype screen/workflow we're building
**Resources:** Who's working on which part of prototype

---

## Anti-Patterns to Delete

❌ **Sprint planning meetings** - Plan one week at a time
❌ **Story point estimation** - Build it and see how long it takes
❌ **Backlog grooming** - Work on most important feature first
❌ **Velocity tracking** - Ship working features or don't
❌ **Burndown charts** - Demo to customers instead
❌ **Issue management systems** - Fix problems immediately
❌ **Code review ceremonies** - Test each other's code quickly
❌ **Definition of done checklists** - Ship working code

---

## Success Metrics

### Only One Matters
**Are beta customers using the working version like they used the prototype?**

*Everything else is a vanity metric.*

### Weekly Health Check
**Prototype Fidelity:** Does working code match prototype behavior?
**Customer Usage:** [X]% of beta customers using working features daily
**Customer Feedback:** [Same as prototype/Better than prototype/Worse than prototype]
**Technical Health:** [No critical bugs/Some bugs/Broken]

---

## Emergency Procedures

### Production Issues
**Step 1:** One person owns the fix
**Step 2:** Fix within 4 hours or rollback
**Step 3:** Post-mortem in one paragraph: What broke + How we prevent it

### Customer Escalations
**Step 1:** Engineering lead talks to customer directly
**Step 2:** Fix their problem within 24 hours
**Step 3:** Build feature to prevent similar problems

---

## Development Complete

**Success:** Beta customers use the working product like they used the prototype
**Failure:** Working product doesn't match prototype behavior customers validated

**Build the prototype they already approved. Everything else is waste.**