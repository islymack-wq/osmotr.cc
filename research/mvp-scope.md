# MVP Scope & Operations

## MVP Product (Customer-facing)
- **Direct Telegram Communication:** Primary channel for inquiries and support.
- **Simple Landing Page:** Focus on Trust, Speed, and Coverage (EU countries).
- **Inquiry Process:** Brand, Model, City, Link to listing (AutoScout/Mobile.de) sent via Telegram.
- **Payment Link:** Stripe/PayPal integration for upfront payment.
- **Status Tracking:** Direct updates from the manager/bot in Telegram.

## Operations (Internal/Backend)
- **Telegram-first Communication:** All communication with clients and inspectors via Telegram for speed.
- **Expert Network Management:** Database of contractors with location, rating, and tool availability.
- **SLA Management:** Target 2 business days for report delivery.
- **QC (Quality Control):** Manual review of photos and findings by a lead expert before sending to the client.

## Standard Operating Procedures (SOPs)
1. **Intake:** Customer sends link + payment via Telegram.
2. **Matching:** Assign inspector based on proximity to the car.
3. **Scheduling:** Inspector calls seller to arrange time.
4. **Execution:** Inspector performs check using thickness gauge.
5. **Reporting:** Full Photo/Video report and notes sent to HQ via Telegram.
6. **Delivery:** HQ delivers final report and answers follow-up questions via Telegram.

## Refund & Quality Policy
- **Standardized Checklist:** Report must cover all points in the mandatory checklist.
- **Missing Data:** If critical photos (e.g., VIN, engine) are missing without explanation -> partial refund.
- **Major Miss:** If a major defect (welded frame, engine knock) is missed that was "visible" -> full refund of the service fee.
- **Seller Refusal:** If seller refuses inspection -> refund minus a small "travel/call fee" for the inspector.
