# Mom Ka Nuska — Website Design Templates

> Section-by-section specs for Home, About, Products, and Product Detail pages

---

## DESIGN SYSTEM (Shared Across All Pages)

### Navigation Bar
```
┌────────────────────────────────────────────────────────┐
│  [Logo]   Home   Shop   About   Recipes   Contact  🛒 │
└────────────────────────────────────────────────────────┘
```
- Background: Warm Cream `#FDF5E6`
- Logo: Icon badge on left
- Links: Playfair Display, `#3D2B1F`, hover → `#B85C38`
- Cart icon: badge with item count
- Sticky on scroll (becomes slightly transparent)
- Mobile: hamburger menu left, logo center, cart right

### Footer
```
┌──────────────────────────────────────────────────────────┐
│  [Logo]     Quick Links     Contact       Social Media   │
│             Home            📞 +91-XXXXX  📷 Instagram   │
│  मॉम का     Shop            📧 hello@     🎵 YouTube     │
│  नुस्खा     About           📍 Una, HP    💼 LinkedIn     │
│             Recipes                                      │
│             FAQ              Newsletter: [email] [→]     │
│                                                          │
│  © 2026 Mom Ka Nuska | Made with ❤️ on our farm          │
└──────────────────────────────────────────────────────────┘
```
- Background: `#B85C38` (terracotta)
- Text: `#FDF5E6` (cream)
- Newsletter input: rounded, cream bg, terracotta submit button

---

## PAGE 1: HOMEPAGE

![Homepage design with hero section, trust badges, products, story, and testimonials](file:///media/atom/01DC59D4D8122980/f2c/brand-identity/page-homepage.png)

### Section 1: Hero
- **Type:** Full-width image with overlay
- **Image:** Anjula ji making pickle in farm kitchen (real photo, warm lighting)
- **Overlay:** Semi-transparent gradient from left (dark) to right (clear)
- **Heading:** "मॉम का नुस्खा" (Yatra One, 64px, cream)
- **Subheading:** "Authentic Indian Homemade" (Playfair Display, 24px)
- **CTA:** "Shop Now" button (terracotta bg, cream text, rounded, 18px)
- **Height:** 80vh desktop, 60vh mobile
- **Animation:** Subtle parallax scroll on the background image

### Section 2: Trust Badges
- **Layout:** 4 badges in a row, centered
- **Background:** Cream with subtle kraft texture
- **Padding:** 40px top/bottom

| Icon | Text |
|------|------|
| 🚫 (hand-drawn) | Zero Preservatives |
| 🌿 | Farm Fresh |
| 👐 | Handmade with Love |
| 📦 | Pan India Delivery |

- Each: hand-drawn icon (terracotta/mustard) + Outfit 14px text
- Mobile: 2x2 grid

### Section 3: Featured Products
- **Heading:** "Featured Products" (Playfair Display, 36px, centered)
- **Layout:** 4 product cards in a row
- **Each card:**
  - Product image (square, cream bg, slight shadow)
  - Product name Hindi first: "आम का अचार" (Noto Sans, 16px bold)
  - English: "Mango Pickle" (Outfit, 14px)
  - Price: "₹229" (Playfair Display, 20px, terracotta)
  - "Add to Cart" button (terracotta outline, hover fills)
- **Mobile:** Horizontal scroll / 2-column grid

### Section 4: Our Story (Split)
- **Layout:** 50/50 split — image left, text right
- **Image:** Farm landscape with green fields (rounded corners)
- **Heading:** "Our Story" (Playfair Display, 32px)
- **Text:** 2-3 paragraphs about Anjula ji's journey (Outfit, 16px, `#3D2B1F`)
- **CTA:** "Read More →" (terracotta text link)
- **Background:** Cream
- **Mobile:** Stacks vertically — image on top, text below

### Section 5: "Mom's Favorites" Banner
- **Type:** Full-width, mustard gold background
- **Content:** "₹499 se upar FREE delivery! 🚚" (announcement style)
- **Purpose:** Push AOV above free-shipping threshold

### Section 6: Testimonials
- **Heading:** "Kya kehte hain humare customers" (Playfair, 32px)
- **Layout:** 3 testimonial cards, carousel on mobile
- **Each card:**
  - Large quotation marks (mustard gold, decorative)
  - Review text (Outfit, 15px italic)
  - Customer photo (small circle, 40px)
  - Name + city (Outfit, 13px)
  - Star rating
- **Background:** Slight kraft texture

### Section 7: Instagram Feed
- **Heading:** "Follow our journey @momkanuska"
- **Layout:** 6 latest Instagram posts in a row (auto-pulled or manual)
- **Each:** Square image, hover shows like count
- **CTA:** "Follow on Instagram" button

---

## PAGE 2: ABOUT US

![About page with story hero, Anjula Ji section, farm photos, process flow, values, and team](file:///media/atom/01DC59D4D8122980/f2c/brand-identity/page-about.png)

### Section 1: Hero Banner
- **Image:** Anjula ji standing in front of farmland, smiling
- **Overlay text:** "हमारी कहानी" (Yatra One, 56px) + "Our Story" (Playfair, 28px)
- **Height:** 50vh
- **Style:** Same gradient overlay as homepage hero

### Section 2: Meet Anjula Ji
- **Layout:** Large circular photo left (300px), text block right
- **Photo:** Anjula ji in kitchen or with products
- **Heading:** "Meet Anjula Ji" (Playfair, 36px)
- **Content:**
  ```
  30 saalon se Anjula ji apne parivaar ke liye wahi achar, 
  chatni aur masale bana rahi hain jo unki maa ne unhe sikhaye the.

  Aaj woh yeh swaad aapke ghar tak pahuncha rahi hain — 
  bina kisi preservative ke, apni farm se, seedha aapki kitchen tak.

  "Mera nuskha simple hai — achhe ingredients, 
  dheeraj aur bahut saara pyaar."
  ```
- **Background:** Cream
- **Mobile:** Photo stacks above text (centered, 200px)

### Section 3: Our Farm
- **Type:** Full-width photo strip (parallax)
- **Image:** Panoramic 2-acre farm shot — green fields, mountains, Una HP
- **Caption overlay:** "Our 2-Acre Farm, Una, Himachal Pradesh"
- **Height:** 40vh

### Section 4: Our Process
- **Layout:** 4 steps in a horizontal flow with connecting dotted line
- **Background:** Cream

| Step | Icon (hand-drawn) | Heading | Description |
|------|--------------------|---------|-------------|
| 1 | Basket of ingredients | **Source** | Fresh ingredients from our farm and trusted local farmers |
| 2 | Hands cooking | **Prepare** | Anjula ji personally prepares every batch with traditional recipes |
| 3 | Glass jars | **Pack** | Hand-packed in glass jars, sealed for freshness |
| 4 | Delivery box | **Deliver** | Shipped pan-India, from our farm to your kitchen |

- Dotted line connecting icons: `#D4A84B` (mustard)
- Mobile: Vertical stack with line going down

### Section 5: Our Values
- **Layout:** 3 cards, equal width
- **Each card:**
  - Terracotta circle icon (64px)
  - Heading: "Zero Preservatives" / "Farm to Kitchen" / "Mother's Love"
  - Description: 2 lines (Outfit, 14px)
- **Background:** Very light mustard tint

### Section 6: The Family
- **Heading:** "The Family Behind the Brand" (Playfair, 32px)
- **Layout:** 3 team member cards, centered

| Photo | Name | Role |
|-------|------|------|
| Circular, 150px | **Vibhor Singh** | Founder & CEO — "Yeh sab maa ki wajah se hai" |
| Circular, 150px | **Anjula Singh** | Head Chef & CPO — "30 saal ka anubhav, har jar mein" |
| Circular, 150px | **Srishti Singh** | Brand & Marketing — "Maa ki kahani duniya tak" |

---

## PAGE 3: PRODUCTS (Shop All)

![Products page with category filters, product grid, and bundle banner](file:///media/atom/01DC59D4D8122980/f2c/brand-identity/page-products.png)

### Section 1: Page Header
- **Heading:** "हमारी रसोई से" (Yatra One, 48px) + "All Products" (Playfair, 24px)
- **Background:** Cream with product collage on right (decorative)
- **Height:** 25vh

### Section 2: Category Filters
- **Style:** Pill-shaped toggle buttons, horizontal row, centered
- **Categories:** All | Achar (Pickles) | Chutneys | Snacks | Gift Boxes
- **Active state:** Terracotta bg, cream text
- **Inactive:** Cream bg, terracotta border/text
- **Behavior:** Filter products instantly (no page reload)

### Section 3: Product Grid
- **Layout:** 4 columns desktop, 2 columns tablet, 2 columns mobile
- **Gap:** 24px
- **Each product card:**

```
┌─────────────────────┐
│                     │
│   [Product Image]   │  ← Square, cream bg, hover: slight zoom
│                     │
├─────────────────────┤
│  आम का अचार        │  ← Hindi name (Noto Sans Bold, 15px)
│  Mango Pickle | Jar │  ← English + format (Outfit, 13px, gray)
│                     │
│  ₹229    ₹249       │  ← Price (Playfair 18px terracotta) + MRP strikethrough
│                     │
│  [  Add to Cart  ]  │  ← Terracotta button, full-width
└─────────────────────┘
```

- **Hover:** Card lifts slightly (box-shadow increase), image zooms 1.05x
- **Badge (top-right):** "Bestseller" (terracotta) or "New" (mustard) or "Limited" (red)

### Section 4: Bundle & Save Banner
- **Background:** Mustard gold gradient
- **Layout:** Heading left + 3 combo cards right
- **Heading:** "BUNDLE & SAVE" (Playfair, 32px, white)
- **Combos:**
  - "Achar Combo" (3 pickles) — ₹599 (save 13%)
  - "Chutney Duo" (2 chutneys) — ₹319 (save 10%)
  - "Snack Feast" (3 snacks) — ₹379 (save 12%)
- **CTA:** "Shop Combos" button (cream bg, terracotta text)

### Section 5: "Free Shipping" Sticky Banner
- **Position:** Fixed bottom of screen (mobile only)
- **Content:** "₹499 se upar FREE delivery! Aapka cart: ₹XXX — ₹YYY aur add karein"
- **Background:** Terracotta, cream text

---

## PAGE 4: PRODUCT DETAIL

![Product detail page with image gallery, pricing, tabs, reviews, and related products](file:///media/atom/01DC59D4D8122980/f2c/brand-identity/page-product-detail.png)

### Section 1: Breadcrumb
- "Home > Products > Mango Pickle" (Outfit, 13px, gray)
- Each segment clickable

### Section 2: Product Main (Split Layout)

**LEFT (50%) — Image Gallery:**
- Main image: Large product photo (500x500, rounded corners)
- Thumbnails below: 4 images (100x100 each)
  - Thumb 1: Jar front view
  - Thumb 2: Ingredients spread
  - Thumb 3: Mom making the pickle
  - Thumb 4: Pickle served on plate with roti
- Click thumbnail → swaps main image
- Mobile: Full-width swipeable carousel

**RIGHT (50%) — Product Info:**
```
आम का अचार                          ← Yatra One, 36px
Mango Pickle                         ← Playfair, 20px, gray
⭐⭐⭐⭐⭐ 4.8 out of 5 (124 reviews)  ← Stars + count

₹229  250g jar                       ← Playfair, 32px, terracotta
                                      
Size: [250g ₹229] [500g ₹399]       ← Toggle selector (active = terracotta)

"Made with raw Himachali mangoes,     ← Outfit, 15px, description
cold-pressed mustard oil, and 
Mom's secret 12-spice blend"

Quantity: [—] [1] [+]                ← Stepper

[       Add to Cart       ]          ← Large terracotta button
[     Buy Now — ₹229      ]          ← Outline button below

🚫 Zero Preservatives   👐 Handmade   🌿 Farm Fresh
                                      ← 3 trust badges inline
```

### Section 3: Product Tabs
- **Tabs:** Description | Ingredients | How to Use | Reviews
- **Active tab:** Terracotta underline
- **Tab content height:** Auto (expands)

**Description Tab:**
```
Anjula ji ka mango pickle — 30 saalon purana nuskha.

Kacche Himachali aam, kacchi ghani ka sarson tel, aur 12 
masaalon ka secret blend. Koi preservative nahi, koi shortcut 
nahi — bas maa ke haath ka swaad.

🥭 Himachali Raw Mangoes (sourced from Una, HP)
🫒 Cold-pressed Mustard Oil
🌶️ 12-spice secret blend
☀️ Sun-dried for 3 days for perfect texture

Best paired with: paratha, dal-chawal, curd rice, or straight 
from the jar (we won't judge! 😄)
```

**Ingredients Tab:**
```
Raw Mangoes, Cold-Pressed Mustard Oil, Salt, Fenugreek 
Seeds, Mustard Seeds, Fennel Seeds, Red Chilli Powder, 
Turmeric, Asafoetida (Heeng), Nigella Seeds (Kalonji), 
Cumin Seeds, Black Pepper

Allergen Info: Contains mustard
Storage: Store in a cool, dry place. Use dry spoon.
Shelf Life: 12 months from manufacturing date
```

**How to Use Tab:**
```
🍽️ With Meals: 1-2 teaspoons alongside dal-chawal, 
   paratha, or any Indian meal

🥙 In Wraps: Mix with mayo for a desi sandwich spread

🥗 In Salads: Add tangy kick to any salad

📹 Watch Mom's serving tips → [QR code / video link]
```

**Reviews Tab:**
- Star distribution bar chart (5★: 80%, 4★: 12%, etc.)
- Individual reviews with: stars, name, date, text, photo (optional)
- "Write a Review" CTA

### Section 4: You May Also Like
- **Layout:** 4 product cards (same style as Products page)
- **Logic:** Show products from same category + one cross-category
- **Example:** Lemon Pickle, Mixed Pickle, Garlic Pickle, Pudina Chutney

### Section 5: Recently Viewed
- **Layout:** Horizontal scroll of 6 products (smaller cards)
- **Shows:** Products the user has browsed before

---

## RESPONSIVE BEHAVIOR

| Element | Desktop | Tablet | Mobile |
|---------|---------|--------|--------|
| Nav | Full menu | Full menu | Hamburger + cart |
| Hero | 80vh, text left | 70vh | 60vh, text centered |
| Product grid | 4 columns | 3 columns | 2 columns |
| Split sections | 50/50 side-by-side | 50/50 | Stack vertically |
| Trust badges | 4 in row | 4 in row | 2x2 grid |
| Testimonials | 3 cards | 2 + carousel | 1 + carousel |
| Footer | 4 columns | 2x2 | Single column stack |

---

## KEY UX ELEMENTS

### Sticky "Add to Cart" (Mobile)
- On product detail page, once user scrolls past the main CTA
- Fixed bottom bar: Product name + price + "Add to Cart" button
- Background: cream, slight top shadow

### WhatsApp Chat Widget
- Fixed bottom-right: WhatsApp green icon
- Opens pre-filled message: "Hi! I'd like to order from Mom Ka Nuska"
- Available on all pages

### Exit Intent Popup
- Trigger: Mouse moves toward browser close (desktop only)
- Content: "Ruko! Pehle order pe 10% OFF 🎁" + email input
- Code: "MAA10" auto-applied
- Design: Terracotta bg, cream text, close X

### Free Shipping Progress Bar
- Shows on cart page/drawer
- "₹150 aur add karo for FREE delivery!"
- Progress bar fills from cream to terracotta as cart value increases

---

## TECH STACK RECOMMENDATION (Not Shopify)

Since you're not keen on Shopify, here are better-fit options:

| Option | Best For | Cost | Self-Hosted |
|--------|----------|------|-------------|
| **WooCommerce (WordPress)** | Simplest, most plugin options | ₹0 (self-hosted) | ✅ Yes |
| **Next.js + Saleor** | Modern, fast, headless commerce | ₹0 (open source) | ✅ Yes |
| **Medusa.js** | Dev-friendly headless commerce | ₹0 (open source) | ✅ Yes |
| **Next.js + custom backend** | Full control, your VPS | ₹0 | ✅ Yes |

**Recommended: WooCommerce on your VPS** (34.0.4.47)
- Self-hosted on your existing server
- Razorpay/PhonePe payment gateway (Indian-first)
- WhatsApp order integration
- No monthly platform fees
- Full design control with custom theme
