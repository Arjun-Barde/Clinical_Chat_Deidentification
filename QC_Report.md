# De-Identification QC Report
## Dataset: Counsel Chat (nbertagnolli/counsel-chat)
## Tool: Microsoft Presidio | Date: 2026-05-04

---

## Summary

| Metric | Value |
|--------|-------|
| Total records processed | 200 |
| Records with PII detected | 161 |
| Records with no PII | 39 |
| PII detection rate | 80.5% |

---

## PII Entities Detected

| Entity Type | Count |
|-------------|-------|
| DATE_TIME | 214 |
| URL | 91 |
| PERSON | 22 |
| LOCATION | 8 |
| US_DRIVER_LICENSE | 4 |
| PHONE_NUMBER | 2 |
| NRP | 2 |
| US_BANK_NUMBER | 1 |

---

## Notes
- 200-record sample of the Counsel Chat dataset
- Presidio NLP engine: spaCy en_core_web_lg
- False positives possible for ambiguous patterns