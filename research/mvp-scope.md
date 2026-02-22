# MVP Scope & Operations

## MVP Product (Web/Customer-facing)
- **Simple Landing Page:** Focus on Trust, Speed, and Coverage (EU countries).
- **Inquiry Form:** Brand, Model, City, Link to listing (AutoScout/Mobile.de), Phone (WhatsApp).
- **Payment Link:** Stripe/PayPal integration for upfront payment or deposit.
- **Status Tracking:** Simple "Order Received" -> "Inspector Assigned" -> "Inspection Scheduled" -> "Report Sent".

## Operations (Internal/Backend)
- **WhatsApp-first Communication:** All communication with clients and inspectors via WhatsApp/Telegram groups for speed.
- **Expert Network Management:** Database of ~50 contractors with location, rating, and tool availability.
- **SLA Management:** Target 2 business days for report delivery.
- **QC (Quality Control):** Manual review of photos and findings by a lead expert before sending to the client.

## Standard Operating Procedures (SOPs)
1. **Intake:** Customer sends link + payment.
2. **Matching:** Assign inspector based on proximity to the car.
3. **Scheduling:** Inspector calls seller to arrange time.
4. **Execution:** Inspector performs check using thickness gauge + scanner (if possible).
5. **Reporting:** Photos and brief notes sent to HQ via WhatsApp.
6. **Delivery:** HQ compiles final report and sends it to the customer via WhatsApp.

## Refund & Quality Policy
- **Standardized Checklist:** Report must cover all points in the mandatory checklist.
- **Missing Data:** If critical photos (e.g., VIN, undercarriage) are missing without explanation -> partial refund.
- **Major Miss:** If a major defect (welded frame, engine knock) is missed that was "visible" -> full refund of the service fee.
- **Seller Refusal:** If seller refuses inspection -> refund minus a small "travel/call fee" for the inspector.
