# Security Notes

This showcase repository intentionally excludes production source code, secrets, deployment settings, and environment-specific identifiers.

The production app follows these principles:

- Stripe secret keys and webhook signing secrets are kept server-side.
- Firebase service account credentials are kept server-side.
- The mobile app never writes paid orders directly after client-side payment success.
- Checkout totals are calculated and validated on the backend.
- Webhook fulfillment is idempotent to avoid duplicate orders.

If you are reviewing the project for hiring or collaboration, I can provide a guided code walkthrough or selected source excerpts privately.
