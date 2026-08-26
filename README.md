# 📉 DropCurve

> **Real Street Resale Rates. Zero Lowballers.**  
> A lightweight, zero-dependency valuation engine for the Indian second-hand market (Smartphones, Vehicles, and Laptops).

---

## ⚡ Overview

Selling or buying used goods in India on platforms like OLX, Cashify, and Facebook Marketplace involves extreme price ambiguity, relentless lowballing, and buyer/seller scams. 

**DropCurve** solves this by calculating fair street valuations using empirical depreciation decay curves, component-level diagnostic deductions, and regional RTO/tax adjustments.

---

## 🚀 Key Features

* **🔍 Buyer's Radar (Fair-Deal Checker):**
  * Audits asking prices against fair market value.
  * Classifies listings into **Steal Deal**, **Fair Deal**, **Overpriced**, or **Total Rip-Off**.
  * Recommends a **Max Safe Offer Cap** to avoid overpaying.

* **🏷️ Seller Mode (3-Tier Output Engine):**
  * **🎯 Fair Market Value:** Realistic walk-away cash price for direct peer-to-peer deals.
  * **🛡️ OLX Listing Quote:** Built-in +12% bargaining cushion to absorb buyer haggling.
  * **⚡ Instant Cash Floor:** Liquidation benchmark for doorstep services (Cashify / Spinny).

* **⚙️ Granular Diagnostic Penalties:**
  * **Smartphones:** Non-linear decay curves (Apple vs. Flagship Android vs. Budget), battery capacity degradation, non-OEM replacement screen penalties, and AMOLED green-line deductions.
  * **Vehicles:** Mileage-per-year ratios, ownership count deductions, and state tax premiums.
  * **Laptops:** Apple Silicon retention vs. Windows gaming/ultrabook thermal degradation.

* **🛡️ Anti-Scam & Negotiation Tools:**
  * 1-click dynamic counter-offer generator for WhatsApp and OLX chats.
  * Security alerts for UPI QR code frauds and escrow scams.

---

## 🛠️ Tech Stack & Design Philosophy

* **100% Native:** Built with pure HTML5, CSS3, and Vanilla JavaScript.
* **Zero External Dependencies:** No frameworks, CDN dependencies, or tracking scripts.
* **Fast & Self-Contained:** Runs entirely client-side inside a single `index.html` file.
* **Responsive Dark UI:** Mobile-first layout with high-contrast accessibility.

---

## 📦 Local Setup & Deployment

Since DropCurve is built without a build step, running it locally or deploying takes seconds:

### Run Locally
```bash
# Clone the repository
git clone [https://github.com/](https://github.com/)<YOUR_USERNAME>/dropcurve.git

# Navigate to the folder and open index.html in any browser
cd dropcurve
open index.html # Or double-click index.html
