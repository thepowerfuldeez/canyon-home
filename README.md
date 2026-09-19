# Canyon home

An independent, image-led personal shopping guide. Ten collections, US product sources, detailed comparisons, and a local order tracker.

## Run locally

Serve this directory with any static web server, for example `python3 -m http.server 8080`, and open localhost:8080. There is no build step and no backend.

## Files

- `catalog.js`: public product research, image URLs and sources.
- `app.js`: filtering, product details, order list, local progress and CSV export.
- `style.css`: responsive visual system.

Progress is stored in browser localStorage and can be exported/restored as a JSON file. No checkout or subscription actions are performed. Product photography is remotely served by its source. No personal documents, receipts, account details, or addresses belong in this repository.

Prices are research snapshots, not live quotes. Delivery, availability, final configuration and return terms require confirmation with the retailer.

Revised 19 September 2026: rejected and duplicate products removed; existing pieces separated from new purchases; selected models compared with current alternatives. Replacement models use new IDs, and earlier saved selections remain in downloaded progress backups. Section notes retain unresolved layout and inventory decisions.
