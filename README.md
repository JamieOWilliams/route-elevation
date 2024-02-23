# Elevation

Set the `GOOGLE_MAPS_API_KEY` environment variable to your Google Maps API key or
pass it as an argument to the `Route` class.

```python
from elevation import Route

route = Route(
    "Brewdog Bristol Bridge",
    "Merchant Venturers Building",
)

route.plot()
route.to_array()
```
