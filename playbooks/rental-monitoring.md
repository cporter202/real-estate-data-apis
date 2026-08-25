# Rental monitoring workflow

1. Collect listing URLs or search results from the [Apify catalog](../catalog/README.md).
2. Normalize address, price, beds, baths, square footage, availability, and listing timestamps.
3. Store a first-seen and last-seen record so price and availability changes are measurable.
4. Add a location or geocoding step only after the source data is clean.
5. Send threshold alerts to a dashboard, email, or webhook.

Useful outputs include rent changes, new listings, removed listings, time on market, and neighborhood-level supply snapshots.

