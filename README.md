# steam-prices

Fetches CS2 case prices from the Steam Community Market and saves them to `prices.json`.

## Setup

```
uv sync
```

## Usage

```
uv run fetch_prices.py
```

Outputs `prices.json` with median/lowest prices and volume for each item.

## Output format

```json
{
  "updated_at": "2026-03-15T12:00:00+00:00",
  "prices": [
    {
      "name": "Chroma Case",
      "median_price": "0,03€",
      "lowest_price": "0,03€",
      "volume": "12345"
    }
  ]
}
```
