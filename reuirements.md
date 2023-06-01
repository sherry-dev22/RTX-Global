## COMPLETE WEBSITE + PAYMENT SYSTEM REQUIREMENTS

*Project:* RXT Global Solutions
*Legal Entity:* RXT Global BPO & Marketing Inc. (Canada)

---

# 1. WEBSITE PURPOSE (CLEAR DIRECTION)

This website must function as:

* A *professional B2B business services website*
* A *centralized billing & payment platform*
* A *corporate umbrella presence for multiple brands*

It should NOT look like:
❌ A random payment page
❌ A freelance site
❌ A marketplace

It MUST look like:
✅ A real company website with structured services

---

# 2. FULL HOME PAGE CONTENT (DETAILED)

## 🔹 HERO SECTION

*Title:*
RXT Global Solutions

*Subtitle:*
Business Support & B2B Solutions Across Canada

*Text:*
RXT Global Solutions is a business services platform operating under RXT Global BPO & Marketing Inc., a registered Canadian company. We provide structured business-to-business (B2B) support services through our internal brands and service divisions.

---

## 🔹 ABOUT SECTION

We help businesses improve efficiency, client acquisition, and operational performance through reliable and scalable service solutions.

Our structure allows us to work with multiple industries while maintaining centralized management, billing, and service quality standards.

---

## 🔹 SERVICES SECTION (DETAILED)

We offer the following services:

* Appointment Booking Services
  We connect businesses with qualified prospects through structured outreach.

* Lead Generation Support
  We assist in identifying and engaging potential clients.

* Virtual Assistant Services
  Remote administrative and operational support for businesses.

* Marketing & Outreach Support
  Helping businesses expand their reach and improve conversions.

* Business Operations Support
  Improving workflows and backend processes.

---

## 🔹 INDUSTRIES WE SERVE

We provide services to:

* Real estate professionals
* Transportation & cab companies
* Service-based businesses
* Small and medium-sized enterprises (SMEs)
* Other B2B organizations

---

## 🔹 HOW WE OPERATE (IMPORTANT)

RXT Global Solutions operates as a multi-division business structure.

Services are delivered through specialized internal brands and teams, while all billing, administration, and client coordination are managed centrally under RXT Global BPO & Marketing Inc.

---

# 3. 💳 PAYMENT SYSTEM (VERY DETAILED)

## 🔹 MAIN BUTTON

Add:
👉 “Make a Payment”

---

## 🔹 PAYMENT PAGE STRUCTURE

### OPTION A — FIXED PACKAGES

Display selectable options:

* $3,600
* $6,600
* $8,999
* $10,800

Each should have:
👉 “Pay Now” button

---

### OPTION B — CUSTOM AMOUNT (MANDATORY)

Field:
👉 “Enter Your Amount”

User flow:

1. User enters amount
2. Clicks “Proceed to Payment”
3. Goes to payment gateway

---

# 4. 🔌 PAYMENT GATEWAY INTEGRATION (TECHNICAL)

## YES — Multiple gateways CAN be added ✅

### Recommended setup:

#### Option 1 (BEST):

* Primary: *Stripe*
* Secondary: *Moneris*

---

## 🔹 UI FLOW

User sees:

👉 Pay with Card (Stripe)
👉 Pay via Moneris

---

## 🔹 BACKEND LOGIC

* If Stripe selected → redirect to Stripe Checkout
* If Moneris selected → redirect to Moneris hosted payment page

---

## 🔹 IMPORTANT RULE

Do NOT:
❌ Process payments manually
❌ Store card details on website

ONLY use:
✅ Hosted checkout (Stripe / Moneris)

---

## 🔹 STRIPE TECHNICAL

Use:

* Stripe Checkout (hosted page) OR Payment Links

For custom amount:

* Dynamic amount field → pass to Stripe API

---

## 🔹 MONERIS TECHNICAL

* Use Moneris Hosted Tokenization / Hosted Pay Page
* Redirect user securely

---

# 5. ⚖️ TERMS OF SERVICE (DETAILED CONTENT)

Create a full page with:

### Include:

* Services are B2B only
* Payments are for agreed services
* Refund policy (customizable by company)
* No guarantee of results unless stated
* Client responsible for cooperation
* Disputes handled under Canadian law

---

### IMPORTANT LINE:

RXT Global Solutions operates as a billing and administrative division of RXT Global BPO & Marketing Inc. Services may be delivered through affiliated brands or service providers.

---

# 6. 🔒 PRIVACY POLICY (DETAILED CONTENT)

Include:

* What data is collected:

  * Name
  * Email
  * Payment info (via third-party processors)

* How data is used:

  * Service delivery
  * Communication
  * Billing

* Third-party sharing:

  * Payment processors (Stripe, Moneris)

* Data protection statement

---

# 7. ⚠️ DISCLAIMER (IMPORTANT)

Add on site:

Services are delivered by respective affiliated brands or service providers.
RXT Global Solutions acts as the centralized billing and administrative entity.

---

# 8. FOOTER (MANDATORY)

Include:

RXT Global BPO & Marketing Inc.
All Rights Reserved

RXT Global Solutions is an operating division of RXT Global BPO & Marketing Inc.

Links:

* Terms of Service
* Privacy Policy

---

# 9. DESIGN REQUIREMENTS

* Clean corporate design
* Mobile responsive
* Fast loading
* Minimal but professional
* Trust-focused layout

---

# 10. FINAL OBJECTIVE

The website must:

* Look like a legitimate Canadian company
* Clearly explain services
* Provide secure payment options
* Support multiple brands under one system
* Pass payment gateway verification easily