# Travel Buddy data

Public travel data (places, stays, rest stops, distances, warnings) used by the Travel Buddy app. All prices are estimates.

## Budget levels (data_version 2026.11.24.1, app v1.0.7)

- `tiers`: planning assumptions for four budget levels (budget-friendly, mid-range, upper mid-range, high-end): food per adult per day (veg / non-veg), tickets, activities, guides, local transport, shopping and snacks, plus the train / bus class and fare point each level uses. These are Travel Buddy estimates, not quoted prices.
- `stayTiers` (per destination): ₹ per room per night for each level, derived from that destination's researched `prices` (high-end is approx.).
- Older app versions ignore both fields (schema_version stays 1).
