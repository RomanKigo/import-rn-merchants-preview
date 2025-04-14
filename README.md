# Database Schema Documentation for RN Merchant Integration

## Tables

- [merchant.merchants](./merchant.merchants.md)
- [merchant.asset](./merchant.asset.md)
- [merchant.categories](./merchant.categories.md)
- [merchant.commodity](./merchant.commodities.md)
- [merchant.corporate_names](./merchant.corporate_names.md)
- [merchant.dba_names](./merchant.dba_names.md)
- [merchant.locations](./merchant.locations.md)

## Interactive Mapping Tool

To better understand which fields from the incoming JSON data map to which target table columns, you can use the interactive web application:

👉 [Open Mapping UI](https://romankigo.github.io/import-rn-merchants-preview/)

This tool allows you to:

- View raw incoming `RN.merchant` JSON on the left
- View a single target table and its field comments on the right
- Automatically highlight matching fields or references from the table comments
- Navigate through tables and switch between different JSON files
