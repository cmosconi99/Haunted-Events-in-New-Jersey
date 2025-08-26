# New Jersey Haunted Attractions · 2025 (v2)

**What’s new**
- Interactive **Map View** (Leaflet + OpenStreetMap)
- **Price filters** (min/max, based on typical estimated ranges)
- **This Weekend** list (auto-computed for Aug 26, 2025 weekend window: Aug 29–Aug 31)

## Use
Open `index.html` in any browser. Click **Map** to see markers. Use the search, region/type chips, and price filters to narrow results.

## Affiliate hooks
In `index.html` you’ll find an `AFFILIATE` object in the JS. Set `enabled: true` and add vendor mappings when you have IDs, e.g.
```js
const AFFILIATE = {
  enabled: true,
  // seatgeek: { param: 'aid', value: 'YOUR_ID' },
  // ticketmaster: { param: 'CAMEFROM', value: 'AFF_ID' },
};
```
This demo leaves links intact by default.
