# Plesk

Auto-provision Plesk from PeltyCMS orders

Official provisioning module for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Providers who sell hosting, VPS, game panels or cloud and need auto-create on payment.

## Features

- Create services on **Plesk** when the customer pays
- Suspend, unsuspend and terminate follow the Pelty service lifecycle
- Map Pelty products to packages / plans on the remote panel
- API tokens stay in Pelty secrets
- MythicCloud panel linking for authenticated installs

## How it works

1. Install **Plesk** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-plesk) inside Pelty Admin → Addons.
2. Open Pelty Admin → Products, map a product to the Plesk module, and save API credentials.
3. Customers hit checkout / login / order flow as usual — Plesk runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Plesk credentials
- Outbound HTTPS from your panel

## Get it

**[Plesk on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-plesk)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
