# Manifest Spec

Each language manifest should describe the available volumes and remote asset paths.

## Example

```json
{
  "languageId": "roman-urdu",
  "title": "Roman Urdu",
  "version": "2026-05-21-1",
  "volumes": [
    {
      "id": "volume1",
      "version": "2026-05-21-1",
      "totalPages": 306,
      "deliveryMode": "remote",
      "baseUrl": "https://cdn.jsdelivr.net/gh/<user>/shifa-shareef-assets@main/pages/roman-urdu/volume1",
      "filePattern": "page-{page}.webp",
      "extension": "webp"
    }
  ]
}
```
