# framed-cars-feed

Auto-generated **public** data feed of in-stock die-cast **car** models, consumed by the
Framed Cars Shopify "request a framed model" feature.

- **File:** [`supplier_models.json`](./supplier_models.json)
- **CDN (used by the site):** `https://cdn.jsdelivr.net/gh/hzeroentity/framed-cars-feed@main/supplier_models.json`
- **Refreshed:** monthly, automatically (systemd timer on the OS Zero box → scrape → push here → purge jsDelivr).
- **Source:** baloccomodel.com (supplier catalog).

## Scope (what's included)
- In stock only.
- Scales **1:18 / 1:24 / 1:43**.
- **Cars only** — road, racing, rally, vintage, concept, F1, taxi, and movie cars.
  Excludes motorbikes, trucks, buses, commercial/agricultural/military vehicles, accessories, etc.
- **No price** is ever published.

## Format
```json
{
  "generated_at": "YYYY-MM-DD",
  "source": "baloccomodel.com",
  "count": 1164,
  "brands": ["Bburago", "Maisto", "Norev", "Solido"],
  "scales": ["1:18", "1:24", "1:43"],
  "models": [
    {
      "brand": "Norev",
      "article_code": "NV182805",
      "name": "FORD MUSTANG COUPE' 1966 BLUE METALLIC 1:18",
      "scale": "1:18",
      "category": "Auto Stradali",
      "image_url": "https://www.baloccomodel.com/images/thumbs/....jpg",
      "product_url": "https://www.baloccomodel.com/...."
    }
  ]
}
```

> Generated automatically — do not edit by hand; manual changes are overwritten on the next refresh.
