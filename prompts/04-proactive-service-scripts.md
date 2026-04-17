# Prompt 4 — Proactive Service Scripts Generator

---

## The Prompt

```
You are a customer success strategist who specializes in proactive outreach — contacting customers before they know there's a problem. Research shows proactive service reduces inbound support volume by 30-40% and increases customer retention by 15-25%.

Write a proactive customer service email for the following situation:

**Business:** [Business name and type]
**Customer name:** [First name, or "Customer" for batch templates]
**Outreach type:** [Select one:
  - ORDER DELAY — Their order will be late before they find out
  - SHIPPING ISSUE — Carrier problem detected (lost, damaged in transit, wrong address)
  - PRODUCT DEFECT BATCH — Quality issue discovered; some orders affected
  - POST-BAD-EXPERIENCE WIN-BACK — 24-72 hours after a negative interaction; repair the relationship
  - LOYALTY MILESTONE — Customer anniversary, order milestone, or spending threshold reached
  - NPS RECOVERY — Customer gave low NPS score; outreach before they churn]
**Situation details:** [Specific facts — new ETA, what the defect is, what their milestone is, etc.]
**Offer or gesture:** [What you're including — e.g., "Full refund + keep the order," "10% off next order," "Free upgrade," "Handwritten card + credit"]
**Tone:** [Warm and casual / Professional / Formal]

---

Generate the following based on the outreach type:

### ORDER DELAY:
1. Proactive delay notification email:
   - Subject line that doesn't bury the lede (they'll find out anyway — be first)
   - Immediate acknowledgment of what happened and the new ETA
   - Brief explanation (without over-explaining or making excuses)
   - Gesture of goodwill (discount, free upgrade, store credit)
   - Option to cancel if the new date doesn't work (shows confidence)
   - Close that thanks them for understanding
   - 3 subject line variants (transparent / empathetic / action-oriented)
   
2. Follow-up template: What to send when the order finally ships

### SHIPPING ISSUE:
1. Proactive shipping issue email:
   - Opens with the fact that you're watching their shipment
   - States the issue (lost / damaged / wrong routing)
   - Immediate resolution path (replacement shipped / refund processing / carrier claim filed)
   - No action required from them (important — make resolution effortless)
   - Timeline for resolution
   - Apology + gesture
   - 3 subject line variants

2. Replacement confirmation: Short email when replacement ships

### PRODUCT DEFECT BATCH:
1. Batch defect notification email:
   - Transparent subject line (don't hide the issue — they'll find out)
   - Clear description of the issue (what it is, what orders are affected)
   - Safety information if relevant
   - Resolution path (full refund, replacement, or both)
   - Instructions (what they need to do, or note that no action is required)
   - Commitment to quality improvement
   - 3 subject line variants (honest / action / empathy)

2. Internal communication template: Summary for your team before the emails go out

### POST-BAD-EXPERIENCE WIN-BACK:
1. 24-72 hour win-back email:
   - Reference the specific previous interaction (shows you tracked it)
   - Acknowledge what went wrong without re-litigating it
   - Statement of what changed or what you're doing differently
   - Meaningful gesture (not a generic discount — something tied to the original problem)
   - Soft ask: invite them back, not a hard sell
   - Direct contact for the customer going forward
   - 3 subject line variants

2. 7-day follow-up: If they don't respond to the first win-back (shorter, softer)

### LOYALTY MILESTONE:
1. Milestone celebration email:
   - Warm, personal acknowledgment of the milestone (1 year, 10th order, $500 spent, etc.)
   - What that milestone means to your business (make them feel valued, not just celebrated)
   - Reward: milestone-appropriate gesture (free item, significant discount, early access, upgrade)
   - Optional: "Tell us what you think" (reviews, referrals — but only if it feels natural here)
   - 3 subject line variants (celebration / gratitude / exclusive)

2. Social share version: Alternate subject + first paragraph for customers likely to share publicly

### NPS RECOVERY:
1. Low NPS follow-up email (sent within 24 hours of low score):
   - Subject: Never reference "NPS score" or "survey" — feels clinical
   - Open: Reference that they shared feedback (not that they gave a bad score)
   - Acknowledge: You heard them and you take it seriously
   - Ask: One specific question — what was the biggest issue? (open-ended, not leading)
   - Commit: What you're doing with their feedback
   - Gesture: Small goodwill offer as a thank-you for the honesty
   - Close: Direct line to a human if they want to talk
   - 3 subject line variants

2. Resolution confirmation: Short email to send after the issue is addressed

---

For all types, also provide:
- **Timing guidance:** When to send relative to the triggering event
- **Segmentation note:** Which customer segments need extra care (first-time buyers, high LTV, recent returners)
- **A/B test suggestion:** One variable to test in the first send
```

---

## Why Proactive Beats Reactive

| Metric | Reactive Support | Proactive Support |
|--------|-----------------|------------------|
| Inbound ticket volume | 100% | 60-70% (30-40% deflected) |
| Customer satisfaction | 4.1/5 average | 4.7/5 average |
| Churn rate after issue | 18% | 4% |
| Cost per resolution | $12-15/ticket | $2-4/proactive email |

Source: Gartner, 2024. Companies that shift 10% of reactive volume to proactive save $2M+ per year per 1M customers.

---

## When to Use This

- Carrier tracking API flags a delayed or lost package
- Quality control finds a defect in a batch before all customers notice
- Post-support survey comes back with a bad score
- Your CRM shows a customer's 1-year anniversary or 10th order milestone
- NPS response comes in below 7
- A difficult support interaction resolved — check in 24-48 hours later
