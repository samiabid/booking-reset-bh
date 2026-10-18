# The Booking Reset — Bahrain

A narrow, fixed-price landing page for a 48-hour WhatsApp booking-conversion pilot for Bahrain field-service businesses.

## Offer

- **BD 115**, one time
- WhatsApp Business message map and quick replies
- One lightweight quote/booking intake path
- Click-to-WhatsApp entry points
- Tomorrow-job confirmation checklist
- 30-minute handover and seven days of small fixes

The offer deliberately does **not** promise a full CRM, WhatsApp API chatbot, or replacement booking platform. It improves the existing customer path first.

## Local preview

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Then open `http://127.0.0.1:4173`.

## Lead handling

The landing page uses a prefilled `mailto:` request to `hello@samiabid.com`. Before paid traffic or outbound, replace it with a controlled intake and payment method (for example, a booking link plus BenefitPay/bank-transfer instructions after the fit check).
