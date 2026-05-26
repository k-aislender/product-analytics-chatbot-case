# Chatbot Automation Analytics Case

**Domain:** Banking / Conversational AI  
**Type:** Product Analytics  
**Author:** Ksenia Aislender

---

## Business Context

A bank uses a chatbot for customer support automation.  
Current automation rate: **30%**  
Business goal: reach **60% automation** within 2 years without degrading service quality.

---

## What I Did

- Analyzed **25 categories of escalation reasons** with percentage breakdown
- Identified that the automation rate metric alone is misleading (can be gamed, excludes policy-based escalations)
- Proposed a **balanced metrics framework**: FCR, CSAT, Escalation Rate by category, Intent Accuracy
- Prioritized **top-3 root causes** by impact, manageability, and technical complexity
- Designed a **hypothesis testing methodology** (offline analysis - A/B test on 5–10% traffic - gradual rollout)
- Built an **8-month product roadmap** with expected outcome - automation rate ~60%

---

## Key Findings

| Priority | Issue | Escalation Share | Solution |
|----------|-------|-----------------|----------|
| #1 | Missing scenario branches | 10.0% | Analyze logs, build missing dialogue flows |
| #2 | Context loss between sessions | 5.4% | Implement conversation state tracking |
| #3 | Unknown / misclassified intents | 4.8% | Retrain on sentence embeddings + fallback intent |

---

## Why Automation Rate Is Not Enough

- Easy to game (a bot can "automate" a chat with a wrong answer)
- 9.6% of escalations are policy-based (VIP/debtors) - not bot failures
- Automated ≠ resolved - client may return with the same issue

---

## Metrics That Actually Matter

- **FCR** (First Contact Resolution) - was the problem solved without repeat contact?
- **CSAT** - did the client rate the interaction positively?
- **Escalation Rate by category** - where exactly is the bot failing?
- **Intent Accuracy** (precision/recall) - how well does the NLP classifier work?

---

## Files

- [`analytics_bank_chatbot.pdf`](./analytics_bank_chatbot.pdf) - full case document (Russian)

---

## Skills Demonstrated

`Product Analytics` `Metrics Design` `A/B Testing` `NLP / Intent Classification` 
`Prioritization Frameworks` `Roadmap Planning` `Banking Domain`
