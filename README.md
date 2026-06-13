# Cat Facts API — APIs.json Profile

This repository contains the [APIs.json 0.19](https://apisjson.org/) profile for the **Cat Facts API** (`catfact.ninja`), catalogued by [API Evangelist](https://apievangelist.com).

## About

The Cat Facts API is a free, open REST API providing random cat facts, breed information, and cat-related trivia. No authentication or API key is required. CORS is enabled, making it suitable for browser-based applications and learning projects.

**Base URL:** `https://catfact.ninja`

### Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/fact` | Returns a single random cat fact |
| GET | `/facts` | Returns a paginated list of cat facts |
| GET | `/breeds` | Returns a list of cat breeds |

### Query Parameters

- `max_length` — filter facts by maximum character length
- `limit` — number of results per page
- `page` — page number for paginated endpoints

## Files

| File | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider index |
| `plans/catfact-plans-pricing.yml` | Pricing and plan details (free) |
| `rate-limits/catfact-rate-limits.yml` | Rate limit documentation |
| `finops/catfact-finops.yml` | FinOps cost and optimization notes |

## Links

- API Website: https://catfact.ninja/
- Source Repository: https://github.com/alexwohlbruck/cat-facts
- API Evangelist: https://apievangelist.com

## Maintainer

Kin Lane — kin@apievangelist.com
