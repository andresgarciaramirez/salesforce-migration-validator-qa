# Changelog

## 0.1.0 — first public version

- Reconcile a source file (CSV/TSV/JSON) against an object in an org authenticated in the Salesforce
  CLI. No credentials are requested or stored.
- Mapping editor with suggestions (names, labels, external ID as key, date format and decimal
  separator from samples), composite keys, one-level relationship paths and simple transformations
  (trim, case, ignore case, date format, decimal separator, value map).
- Checks: counts, missing/extra records, duplicate keys, field-by-field comparison with type-aware
  normalisation, lookups (empty, wrong parent, parent not migrated), truncation, length, type and
  picklist values.
- Reads with SOQL (REST) or Bulk API 2.0 (automatic above 10,000 records, with daily-limit check).
- Report view plus Markdown/HTML/CSV export. English and Spanish.
- Read-only, 100% local: no backend, no telemetry; record values are never logged or persisted.
