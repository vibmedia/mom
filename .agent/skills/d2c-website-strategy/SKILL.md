---
name: d2c-website-strategy
description: >
  When the user wants to plan a D2C food website with location-first UX, geo-targeted
  product display, or regional product catalog. Also use when the user mentions
  "website strategy," "location-first," "geo targeting," "product catalog," "D2C website,"
  "Shopify," or "e-commerce for food brand."
metadata:
  version: 1.0.0
  profile: shared
  category: fmcg-marketing
---

# D2C Website Strategy

> Location-first UX — show regional products before national bestsellers.

## Core Framework

### Location-First UX Flow

```
Step 1: Landing Page
  → "Namaste! Aap kahan se hain?" (Where are you from?)
  → State/City dropdown OR auto-detect via geolocation

Step 2: Regional Catalog
  → Show products matching user's state/region FIRST
  → "Popular in [State]" section
  → Regional hero products featured

Step 3: National Catalog
  → "Bestsellers Across India" section below regional
  → Cross-regional discovery ("Try South India's famous Avakaya")

Step 4: NRI Detection
  → If international IP detected, show NRI bundle page
  → International shipping info prominent
  → Festival gifting hampers featured
```

### Tech Stack Decision

| Option | Cost | Complexity | Best For |
|--------|------|-----------|----------|
| **Shopify** | ₹2-5K/month | Low | Quick launch, proven for D2C |
| **Shopify + Custom Theme** | ₹20-50K one-time + monthly | Medium | Custom UX, location logic |
| **Custom (Next.js + Headless)** | ₹1-3L one-time | High | Full control, long-term |
| **WooCommerce** | ₹5-15K setup | Medium | Budget, self-hosted |

> **Recommendation for Phase 3:** Start with Shopify, migrate to custom in Phase 4.

### Essential Pages

| Page | Purpose | Priority |
|------|---------|----------|
| Home (with location selector) | First impression, regional routing | P0 |
| Product listing (by region) | Browse and purchase | P0 |
| Product detail | Buy specific product | P0 |
| Cart + Checkout | Purchase flow | P0 |
| About / Our Story | Brand trust, Mom's story, farm | P0 |
| Our Farm | Photo/video tour of the farm | P1 |
| Recipes | Use our products in recipes | P1 |
| Blog | SEO content, food stories | P1 |
| Gift Hampers | Curated gift sets | P2 |
| Subscription | Monthly box signup | P2 |
| B2B / Wholesale | HoReCa inquiry form | P3 |

### State-wise Product Catalog Logic

| State/Region | Featured Products | Flavor Profile |
|-------------|-------------------|---------------|
| **UP, Delhi, Haryana** | Mango pickle, Mathri, Besan ladoo | Spicy, rich |
| **Rajasthan** | Ker sangri pickle, Mirchi vada mix | Tangy, spicy |
| **Gujarat** | Thepla mix, Fafda, Sweet pickle | Sweet-spicy |
| **Maharashtra** | Thecha, Puran poli mix | Tangy, coconut |
| **Tamil Nadu, AP** | Avakaya, Podi, Murukku | Tangy, sesame |
| **Kerala** | Naranga achar, Banana chips | Coconut, curry leaf |
| **Bihar, Jharkhand** | Sattu mix, Litti masala, Mango pickle | Mustard-forward |
| **Bengal** | Kasundi, Tok dal mix | Mustard, subtle |
| **Punjab** | Mixed pickle, Pinni, Gur | Rich, ghee-heavy |

## Common Mistakes

- ❌ Showing all 50+ SKUs to every visitor (overwhelms, reduces conversion)
- ❌ No mobile optimization (70%+ of D2C food traffic is mobile)
- ❌ Missing trust signals (FSSAI badge, customer reviews, founder story)
- ❌ Complex checkout (should be 2-step max)
- ❌ No WhatsApp ordering option (huge in India, especially Tier 2/3)
