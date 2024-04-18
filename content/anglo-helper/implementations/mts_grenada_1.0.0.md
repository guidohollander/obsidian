---
implementation_name: mts_grenada_1.0.0
component_version: 1.0.0
release_date: 2023-01-15
solution: mts
country: grenada
customer_code: gd_ird
---

# `= this.implementation_name`

## internals
CONTINUOUS_DELIVERY
Cash register portal
..

## externals
[[sc-account-trunk]]
[[dsc_business_license_trunk]]
[[sc_additional_tax_period_trunk]]

## components
This implementation thereby uses  the following (general) components:
```dataview
table without id link(component_name) as "Component" from outgoing([[]])
sort component_name asc
```