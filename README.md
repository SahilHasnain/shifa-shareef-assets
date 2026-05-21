# Shifa Shareef Assets

Static asset repository for remote page delivery used by the `shifa-shareef` app.

## Purpose

This repo hosts:

- page images by language and volume
- manifest files consumed by the app

It is intended to be served through a CDN layer such as jsDelivr.

## Structure

```text
pages/
  urdu/
    volume1/
    volume2/
  roman-urdu/
    volume1/

manifests/
  urdu.json
  roman-urdu.json
```

## Naming

- pages should use zero-padded names like `page-001.webp`
- folder paths should follow `pages/<languageId>/<volumeId>/`

## Delivery

Recommended public delivery:

- `https://cdn.jsdelivr.net/gh/<github-user>/<repo>@main/pages/...`

## Initial Plan

Start by pushing:

- `roman-urdu/volume1`

Then wire that volume first in the app for remote delivery.
