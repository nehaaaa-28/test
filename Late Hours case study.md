Late Hours

[Summary](#summary)[Problem](#problem)[Discovery](#discovery)[Store](#store)[Checkout](#checkout)[Scarcity](#scarcity)[States](#states)[System](#system)[Tradeoffs](#tradeoffs)

9 min read

Late HoursSwiggy Instamart · case study

Night mode · open 11 PM – 4 AM

# A night store for the person awake at 1 AM

A smaller store for someone who already knows what they need. It tells the truth about stock and closing time, and it never wakes anyone up.

[Read the case study](#summary)[See the screens](#preview)

![](img/01-kitchens-closed.webp)

![](img/03-product-sheet.webp)

![](img/02-storefront.webp)

*☾*

**Storefront**1:12 AM · 25 min delivery

Summary

## Same app at 1 AM as at noon. I made it fit the moment.

01Problem

At night Instamart shows the full daytime store: bright banners, forty categories, thousands of products. The person opening it is tired, in bed, and wants two or three things.

02Solution

A distinct night mode: 32 items in 5 categories, actions in thumb reach, perks in one warm colour, honest stock counts, a calm 4 AM wind-down, and discovery placed where the app would otherwise fail people.

03Outcome

A design system extension, not a new app: 4 entry points, 4 states, 2 components with full state sets, and every night text colour at AAA contrast.

ProductSwiggy Instamart

RoleProduct designer

PlatformAndroid

ScopeDiscovery to checkout

TypeDesign exercise

Design outcomes

## A smaller store, found at the right moment, that never manufactures urgency.

This is a design exercise, so these are properties of the design, not shipped results. What I'd measure after launch is at the end.

32items

Five categories, down from the day store's 4,000 products and forty-tile grid.

4entry points

Each one matched to a moment the person is already in, from 10:30 PM to 1 AM.

0late pushes

No uninvited notification after 10 PM. Reminders only when asked for.

7/7AAA

Every night text token passes AAA contrast, lowest 5.1:1.

Product preview

## Three moments: finding it, choosing, and an item that's nearly gone.

![Swiggy home at 1:12 AM with the Late Hours tab and intro card](img/01-kitchens-closed.webp)

**Found where it lives.**At 11 PM the Instamart tab turns into Late Hours, with a one-time card.

![Late Hours storefront at 1:12 AM](img/02-storefront.webp)

**Read at the top, act at the bottom.**Perks in amber, categories in the nav, the cart bar in thumb reach.

![Product sheet for a nearly sold out brownie](img/03-product-sheet.webp)

**Scarcity with context.**A real batch size, a per-order cap and the restock time.

The problem

## The night user is a different person. The app treats them the same.

Who opens the app at 1 AM?

Someone in bed, screen brightness low, phone in one hand, ordering for themselves. Not browsing, not comparing. They want two or three things and they want to be done.

Who doesn't know it exists?

A traveller in a Bengaluru hotel who mostly orders food on Swiggy. Back late, no socks for tomorrow morning. Their instinct is Amazon, delivered tomorrow. They never think of opening Instamart.

What does the business need?

A distinct night mode with a small curated range, a slower 25-minute promise (10 in the day), and a few night-only items that genuinely run out. Late orders should feel worth it, not just possible.

What can't change?

Instamart's design system. Night had to extend it, not replace it, and feel like the same product.

The hard constraint: scarcity and closing time are real, and anything that manufactures panic fails.

Discovery

## People at 1 AM recognise features. They don't discover them.

So I placed discovery earlier in the evening, or exactly where the app would otherwise let someone down. Each entry point is matched to a moment the person is already in.

01 / 0410:30 PM

### Evening teaser

A slim strip in the day store: opens at 11, tonight's batches, and an opt-in reminder. It plants the idea while people are awake.

02 / 0411:00 PM

### The tab becomes Late Hours

For regulars, the Instamart tab itself turns into the night store, with a one-time card explaining the smaller range and the 4 AM close.

03 / 041:12 AM

### Kitchens are closed

The Food list is mostly closed. One honest row says medicines, essentials and snacks still deliver in about 25 minutes.

04 / 0411:42 PM

### "socks" has no restaurants

Instead of "no results", search shows Late Hours: tonight in about 25 minutes, not tomorrow. This is the line that beats Amazon.

![Instamart day home with the Late Hours teaser](img/e3-evening-teaser.webp)

**10:30 PM · Evening teaser**Planted in the day store, with an opt-in reminder.

![Swiggy Food tab with most restaurants closed and a Late Hours card](img/e1-food-tab.webp)

**1:12 AM · Kitchens closed**The Food tab offers what still delivers.

![Lock screen notification for a traveller](img/n1-new-city.webp)

**9:48 PM · New city**One silent note when a hotel address is saved.

![Lock screen cancellation with a Late Hours fallback](img/n2-cancelled.webp)

**12:41 AM · Order cancelled**The fallback rides inside the alert they must see.

Rejected

### A push at 11 PM to everyone

Reaches people while they're winding down, before any need exists. Most recipients don't need it tonight, and each ignored push raises the chance they mute Swiggy entirely, including order tracking.

Chosen

### Notifications only with a reason they'd agree with

A silent note before 10 PM when a rare user saves a hotel address, once per trip. And if a late food order is cancelled, the cancellation alert they must see anyway offers Late Hours as the fallback.

Swiggy · now

**Midnight Biryani Co. cancelled your order**

**Still need something tonight?**\
Late Hours: snacks, meals and medicines in \~25 min.

**Decision**

No uninvited pushes after 10 PM. I accepted slower awareness in exchange for never interrupting someone's night.

Where it lives

## I put Late Hours where the people who don't know it already are.

24.7Mvs8.2M

Weekly users, Swiggy app against the standalone Instamart app, May 2025 (Sensor Tower data via CLSA). Swiggy doesn't publish its order split.

Instamart has two front doors. The Swiggy app is likely the bigger one, especially for food-first users like the traveller, so the Food-side entry points (kitchens closed, search, the cancelled-order alert) live there. In the standalone Instamart app, the whole app simply switches to Late Hours at 11 PM; those users are already grocery-first.

**Decision**

Design in the Swiggy app first. The standalone app gets the switch and the one-time card.

The store

## I moved every action into the bottom quarter of the screen.

**The thumb does the work.** Categories move into the bottom nav. Every add button sits bottom-right of its tile at 40px (32 in the day app). The cart bar and the pay button live in the lowest quarter.

**One warm colour.** On a cool, dim screen, amber is reserved for perks. Offers catch the eye through colour alone: no motion, no pop-ups, no size jump.

**Perks that are worth it.** Free delivery from ₹99 (₹149 in the day), free cookies from ₹249, no surge after midnight. The cart bar shows progress to the next one.

Live components

☾ NIGHT PERK**Free delivery above ₹99**Day minimum is ₹149

TonightHealthCareDailyBabySnacks

Free delivery on · ₹134 more for free cookies

**2 items · ₹115**Arrives \~1:37 AM

First direction

### A comfort-food night menu

Snacks, sweets, drinks and instant meals. It served the craving, but not the traveller who forgot socks or the parent who ran out of diapers.

Shipped direction

### Essentials as first-class categories

Health, Personal care, Daily needs, Baby and Munchies. The range answers "what do I need before morning", and the Health page says up front that prescription medicines aren't sold at night.

**Decision**

32 items across five categories, with food as one of them, not the whole store.

Checkout

## I made the bag explain the slower promise before anyone asks.

![Checkout screen at 1:14 AM](img/04-checkout.webp)

**Checkout, full scroll**25 minutes with the reason, quiet drop-off on by default, free delivery applied.

![Order placed confirmation](img/05-order-placed.webp)

**Order placed**Arrival time, a rider who texts instead of ringing, and the 4 AM rule.

**The honest promise.** "25 min tonight · 10 min in the day", with one line on why: fewer riders are out at night.

**Quiet by default.** After 11 PM, "Leave at door" is already selected, with "Don't ring the bell" one tap away. The rider texts instead.

**Perks applied, not hunted.** Free delivery shows up in the bill on its own, struck through against the usual fee, so the night perk is visible without a coupon.

**A calm confirmation.** A rider card with message first and call second, a short timeline, and a note that orders placed before 4 AM are always delivered.

**Decision**

Every night-specific rule shows up in the bag itself, so nothing about the night order is a surprise.

Scarcity and closing time

## I let real numbers do the work that timers usually do.

Common pattern

### "Only 3 left!" and a countdown

Familiar from every sale page. It works once.

→

Why it fails at 1 AM

### It reads as a trick

A tired person can't tell real scarcity from sales pressure, so they discount both. Next time, "3 left" means nothing.

→

What I designed

### The count, with its context

The batch size, a per-order cap with its reason, the restock time. No product timers, no "people viewing", no red.

Product sheet

**3 left of tonight's 40**Max 2 per order

Next batch tomorrow, 11 PM. We cap orders so more people get one tonight.

Header from 3:30 AM

Closes in 20 min · last orders 3:55 AM

**We're winding down for the night**Orders placed by 3:55 are still delivered. Not finishing? Your bag is saved for the 6 AM store.

**One clock, the store's.** The only countdown is the store closing, in the header from 3:30, with the last-order time and what happens to your bag.

**Sold out is explained where it happened.** If an item sells out while it's in the bag, the row dims into a note: removed, not charged, back at 11 PM. If that drops the bag below a perk, it says exactly how much to add.

**The slower promise says why.** "25 min tonight · 10 min in the day. Fewer riders are out at night, so we give ourselves a little more time and keep the promise."

**Decision**

Show the truth about stock and time, and let that be enough. Trust is the habit at 1 AM.

States and motion

## I designed the same screen for when things go wrong.

![Late Hours closed state in the day](img/s1-closed.webp)

**10:02 AM · Closed**Says when it opens and offers the day store or a reminder.

![Closing soon state at 3:40 AM](img/s2-closing-soon.webp)

**3:40 AM · Closing soon**A calm countdown in the header; the bag is saved.

![Checkout with an item that sold out](img/s3-sold-out.webp)

**1:14 AM · Sold out in the bag**The row becomes a note; totals update in place.

![Loading state with skeleton cards](img/s4-loading.webp)

**1:12 AM · Loading**Header and bag from cache; only the catalogue shimmers.

Motion · 600 ms

### Day → Late Hours

The header and tab dim into night together, so you know the store changed, not just the colours.

Motion · after 1.2 s · 450 ms

### Sold out in the bag

The row dims and totals recount in place, so the change is explained where it happened.

System

## I derived every night colour from its day pair.

Same components, same token names; only values change. The rule: keep the hue, invert the lightness, lower the saturation. Surfaces get lighter as they rise, because shadows don't read on dark.

| Token | Day | Night | Contrast at night | Rule |
| --- | --- | --- | --- | --- |
| bg/page | #FFFFFF | #0B0F1C | — | Deep navy, not black: reads as Instamart blue at night |
| text/primary | #1A1D26 | #E7E9F1 | 15.8:1 AAA | 90% white, not 100%: no glare at low brightness |
| text/secondary | #5F6373 | #A3A8BA | 8.1:1 AAA | Meta and body text |
| action/primary | #1F4BFF | #8AA0FF | 7.8:1 AAA | Same blue hue, lighter; text on it flips to dark |
| perk/fg | #B35A00 | #F5C46B | 11.8:1 AAA | The only warm hue at night, reserved for perks |
| caution/fg | #B4421C | #F3A27A | 9.2:1 AAA | Low stock and closing: soft coral, never alarm red |
| positive/fg | #138A5B | #63CF9C | 9.9:1 AAA | Discounts and savings |

25 minsDisplay 22/28

Night-only, small batchesTitle 17/22

Free delivery above ₹99Subtitle 15/20

Search medicines, socks, snacksBody 14/20

Open till 4:00 AMCaption 12/16

3 LEFT TONIGHTMicro 11/14

### One-handed, low-light rules

- Nothing below 11px; meta text gets bolder rather than smaller
- Add button 40×40, icon buttons 44×44, primary actions at least 48 high and full width
- Cart bar and pay row in the bottom quarter
- Add button states: add, loading, added, limit reached, in bag, sold out
- Product card states: default, low stock, in bag, sold out, skeleton

**Decision**

Night is a mode of Instamart's system, not a new one, so every future screen inherits night for free.

Tradeoffs

## The biggest call: one honest small store over full choice.

Not chosen

### A toggle between night store and full catalogue

Keeps every option open, but brings back the noon app at 1 AM: two stores, a decision before every order, and a delivery promise that changes with the toggle.

Chosen

### Auto-switch to one small store

Clear and fast. The cost is the person who needs something outside the 32; search can show "available from 6 AM" and let them save it to the bag.

Gave up

### Short-term conversion on night-only items

Real counts convert a little less than timers. They earn trust that the next "3 left" is true.

Gave up

### Bigger single orders

A cap of 2 lowers the ceiling per basket and spreads scarce stock across more people.

Gave up

### First-week reach

No late pushes means slower discovery. The evening teaser carries the cold start instead.

What I'd measure

## Faster orders at night, without eroding trust.

Planned metrics, not results.

### Night conversion

Sessions from 11 PM to 4 AM that end in an order, against the old all-day store at the same hours.

### Time to order

Seconds from open to placed. The night store should be faster, not just darker.

### Non-food share

Share of night orders from Health, Care, Daily and Baby.

### Notification opt-outs

Must stay flat. A rise means the notes feel like spam.

### Sold-out-in-bag rate

Must stay low, or stock counts aren't fresh enough for honest copy.

### Promise kept

Share of night orders delivered within 25 minutes.

Lessons

## What I'd carry into the next project.

01

### Design for the moment, not the feature.

The same person at 1 AM needs fewer choices, bigger targets and plainer words than at noon.

02

### Put discovery where the product would otherwise fail.

A closed-kitchens list and an empty search are better entry points than any banner.

03

### Honest constraints persuade better than invented ones.

A real batch size, a reasoned cap and a stated restock time do the job urgency tricks try to do.

Assumptions

- Late Hours runs 11 PM–4 AM, closed 4–6 AM to restock, day store from 6 AM
- About 32 products in 5 categories; night-only items baked in batches of 40
- No prescription medicines at night
- Android 360×800; Plus Jakarta Sans stands in for Swiggy's typeface

Process and tools

Designed in Figma on top of Instamart's existing patterns, using screenshots of the live app as reference. AI accelerated the build: tokens, components and frames from my direction, contrast checks, unbranded product photos, and copy drafts I edited. The brief interpretation, flows, scarcity rules and visual decisions are mine.

Late Hours · a design exercise for Swiggy Instamart. Not affiliated with Swiggy. Neha · [nehans.framer.website](https://nehans.framer.website)