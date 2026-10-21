# Valmo RTO · Working Prototype · Team Shooters, IIT Kanpur

**Live:** https://chitts28.github.io/Meesho-DICE-Challenge-3.0/

Meesho DICE Challenge 3.0, Business Track, Valmo RTO. Our two solutions, Commit-to-COD and Sure-Meet, built into the Meesho app and the Valmo partner apps.

## What you can do
- **Guided demo:** four stories, each one order end to end on two synced phones. A side panel explains every step, what it looks like today vs with our fix, and the survey number behind it. Use **Auto-play** to watch it run, **Back** to undo a step, and the **What if** buttons to take a different path at any decision.
- **Free play:** the fifth button next to the four stories, also on the Overview. No script and no hints. Pick a normal buyer or a repeat refuser, with or without a saved backup receiver, then drive both phones yourself: shop any product, choose COD, Pay Online or a Valmo Point, answer the 8 am WhatsApp, and decide at the door on the rider phone. The order follows whatever you tap.
- **All scenarios:** a colour-coded map of every path for both solutions. Click any ending to jump straight into it on the phones.
- **Impact model:** six assumption sliders, each with a tick at our deck's base case, Cautious, Base and Strong presets, where Cautious and Strong move the two biggest levers 10 points down or up from the deck, a waterfall from gross saving to net value, a stress test table, and live net value, RTO rate, cost per delivered order, break-even and payback.
- **Control tower:** a simulated 90-day pilot, 2 pilot hubs against 2 matched controls. Drag or play the pilot day from 1 to 90 and watch the KPIs, the weekly RTO chart, the kill switches and the event log move with it.

The phones are labelled by role: customer, delivery partner, backup receiver, Valmo Point shop and hub. Nearly every control on them responds: wishlist, sizes, add to cart, price details, change address, help, masked calls, run-sheet stops, the Valmo Point code pad and more.

Every story shows the same building blocks a real buyer gets: the optional "someone else can receive" and "collect from a Valmo Point" choices at checkout, the WhatsApp order confirmation, and one day-of WhatsApp with every option: keep, change time, someone trusted, Valmo Point and cancel free. Valmo Point orders are always prepaid.

Highlights: order any product, with price, sizes and the 20% advance following it, add a new address, a backup receiver saved as a secondary address who confirms on WhatsApp, every day-of option on WhatsApp, refused orders listed in My Orders with a "raise a query" option, and attempt checks that run in the background so the rider never sees them.

Money rules shown in the prototype:
- The 20% advance for a flagged COD buyer is always paid online, by UPI or a family pay-link. There is no cash advance.
- Any refund on an order with a COD advance goes to the buyer's Meesho wallet, never the bank. That includes a refusal at the door, a free cancel and a wrong or damaged item. The money is not kept as a fee; it stays hers for her next order.
- A fully paid order, prepaid online or paid in full on delivery, chooses where its refund goes: bank account or Meesho wallet.

The rider has one door screen: call the customer at least 3 times before marking not available, send "I'm at the door", slide to deliver, customer refused, or customer not available, so a buyer who misses the call but opens after a knock still gets her parcel. A refusal at the door reaches the buyer on WhatsApp with the rider's photo, time and reason; she confirms it or opens a dispute right there. A backup receiver who agrees on WhatsApp gets the one-time delivery code on her own WhatsApp. The buyer is only told it was sent.

After a failed attempt the buyer hears on WhatsApp: proof of the visit and "Did a rider come?". A No raises a dispute against the rider, not her. Then she picks Collect from Valmo Point or Try again tomorrow. If the day 2 attempt also fails, the order is cancelled for free and the parcel goes to a 48 h local resale; only if nobody nearby buys it does it go back to the seller.

Demo codes: backup receiver **7316**, Valmo Point **4821**.

## Tech
One self-contained `index.html`, HTML, CSS and JavaScript with images embedded. No backend, no tracking. Concept prototype with sample data only; no real payments, messages or calls. Not a Meesho product.
