# Stellate FinOps

Source: https://stellate.co/pricing

## Cost Structure

Stellate uses a usage-based pricing model with a base plan fee plus optional add-ons and overages.

### Base Costs

| Plan       | Monthly Cost | Included Requests         |
|------------|-------------|---------------------------|
| Free       | $0          | 100,000 requests/month    |
| Business   | $249+       | 25,000,000 metrics requests/month |
| Enterprise | Custom      | Unlimited                 |

### Add-Ons (Business Plan)

| Feature       | Cost          |
|---------------|---------------|
| Edge Caching  | +$5/month     |
| Rate Limiting | +$5/month     |

### Overage Costs

| Usage Type        | Overage Rate                      |
|-------------------|-----------------------------------|
| Metrics Requests  | $10/month per 1,000,000 requests  |

## Cost Optimization

- **Edge Caching** reduces origin server traffic by up to 95%, which can lower backend infrastructure costs significantly.
- Stellate positions its caching as reducing infrastructure costs by up to 40% through reduced origin load.
- The Free plan supports up to 100,000 requests/month at no cost, suitable for development and low-traffic services.

## Billing Notes

- All billing is in US dollars.
- Business plan customers pay by credit card (VISA, Mastercard, AMEX).
- Enterprise customers may use wire transfer.
- Plans can be cancelled at any time; downgrade to Free is always available.
- Exceeding plan limits disables caching/rate-limiting features but does not block traffic or incur surprise overage charges (features simply stop processing until the next billing cycle or upgrade).

## Cost Visibility

- The Business plan includes 30 days of metrics retention, enabling teams to monitor and forecast usage for cost planning.
- The Free plan provides 1 day of retention, limiting historical cost analysis.
