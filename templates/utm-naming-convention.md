# UTM Naming Convention Guide

A standardized framework for naming UTM parameters across all marketing
campaigns to ensure clean, consistent, and reportable data in your CRM
and analytics tools.

---

## 🎯 Why UTM Naming Conventions Matter

- Prevents inconsistent data (e.g. "Email" vs "email" vs "EMAIL")
- Enables accurate attribution reporting
- Makes campaign performance easier to filter and compare
- Keeps CRM and Google Analytics data clean and trustworthy

---

## 🧱 UTM Parameter Structure

Every campaign URL should follow this format:
website.com/page?utm_source=SOURCE&utm_medium=MEDIUM&utm_campaign=CAMPAIGN&utm_content=CONTENT&utm_term=TERM
---

## 📐 Parameter Definitions & Rules

### General Rules
- Always use **lowercase**
- Use **hyphens** instead of spaces (e.g. `summer-sale` not `summer sale`)
- Be **consistent** — agree on values as a team and document them
- Never use special characters or abbreviations that aren't documented

---

### utm_source
Identifies where the traffic is coming from.

| Source | Value |
|---|---|
| Google Ads | `google` |
| LinkedIn | `linkedin` |
| Facebook | `facebook` |
| Newsletter | `newsletter` |
| Partner site | `partner-[name]` |

---

### utm_medium
Identifies the marketing channel.

| Channel | Value |
|---|---|
| Paid Search | `cpc` |
| Paid Social | `paid-social` |
| Email | `email` |
| Organic Social | `organic-social` |
| Banner Ad | `display` |

---

### utm_campaign
Identifies the specific campaign name.

Format: `[year]-[quarter]-[campaign-name]`

| Example | Value |
|---|---|
| Q1 2025 Lead Gen | `2025-q1-lead-gen` |
| Black Friday Promo | `2025-q4-black-friday` |
| Product Launch | `2025-q2-product-launch` |

---

### utm_content
Differentiates between ads or links within the same campaign.

| Example | Value |
|---|---|
| Blue banner ad | `banner-blue` |
| CTA button version A | `cta-button-a` |
| Top nav link | `nav-link-top` |

---

### utm_term
Used for paid search to identify keywords (optional for other channels).

---

## ✅ Full Example

Campaign: Q2 2025 LinkedIn paid ad promoting a free eBook

website.com/ebook?utm_source=linkedin&utm_medium=paid-social&utm_campaign=2025-q2-ebook-promo&utm_content=banner-blue

---

## 🚫 Common Mistakes to Avoid

- [ ] Mixing cases (`Email` vs `email`)
- [ ] Using spaces in values (`paid social` instead of `paid-social`)
- [ ] Skipping UTMs on paid campaigns
- [ ] Using vague campaign names (`campaign1`, `test`)
- [ ] Not documenting your convention anywhere (this file fixes that!)

---

## 📝 Notes

> This convention should be reviewed quarterly and updated as new
> channels or campaign types are added.
> Built from hands-on Marketing Operations experience.
























