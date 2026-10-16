# Meter

Track AI and API usage per customer and turn it into accurate bills.

> **Status: in development.** I'm building this in public. Follow along here or on the project page:
> **https://jacksonkojoosei.com/projects/meter**

## What it does

Record every metered event, such as tokens, API calls or documents processed, roll it up per customer and billing period, and send it to Stripe usage-based billing. Late or corrected events update the bill without double-counting.

## Why

Usage billing breaks in quiet ways: events counted twice, events arriving after the invoice, and no audit trail when a customer disputes a bill.

## Planned features

- [ ] Idempotent event ingestion
- [ ] Per-customer, per-period roll-ups
- [ ] Re-rating when late events arrive
- [ ] Stripe usage-based billing sync
- [ ] Audit trail for every invoice line

## Stack

TypeScript, Node.js, PostgreSQL, Stripe

## Author

Built by **[Jackson Kojo Osei](https://jacksonkojoosei.com)**, CTO in Accra, Ghana.
[LinkedIn](https://www.linkedin.com/in/jackson-kojo-osei-740846189) · [All projects](https://jacksonkojoosei.com/projects)

## License

MIT
