# OLTA — Phishing Analysis Workbench

A safe, methodical workbench for dissecting real phishing emails: header analysis, link deconstruction, IOC (indicator of compromise) extraction, and one-page analyst reports.

## Workflow

1. **Ingest** — suspicious email isolated (headers preserved, attachments never executed on host)
2. **Analyze** — sender authentication (SPF/DKIM/DMARC), URL expansion and reputation checks, attachment metadata
3. **Extract** — IOCs: URLs, domains, IPs, file hashes
4. **Report** — one-page analyst write-up per case (personal data redacted)

## Case reports

Each case is a short, structured report: what arrived, what it tried to do, how it was identified, IOCs.

## Status

🛠️ Planned — first cases from the operator's own spam folder.

> **Note:** Educational lab. All samples are handled safely; no live phishing infrastructure is touched.
