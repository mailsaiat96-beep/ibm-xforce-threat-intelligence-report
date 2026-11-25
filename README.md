# IBM X-Force Threat Intelligence Investigation Report

A consolidated cyber threat intelligence report prepared using **IBM X-Force Exchange**. It covers eight investigation tasks and turns the findings into practical defensive recommendations.

## Scope

| Task | Investigation area | Scope |
| --- | --- | --- |
| 1 | Domain investigations | 3 domains |
| 2 | Threat analysis reports | 2 reports |
| 3 | Threat group profiles | 3 groups |
| 4 | Malware investigations | 4 malware records |
| 5 | Phishing investigations | 3 reports |
| 6 | Spam-associated IP addresses | 10 IP addresses |
| 7 | Vulnerability investigations | 3 CVEs |
| 8 | Public malware hash collections | 3 file hashes |

## What the report covers

- Domain reputation, categorization, passive DNS and malware associations
- Threat campaigns, including activity targeting OT/ICS systems and internet-facing devices
- Threat group profiles and how they support adversary awareness
- Malware classifications, MD5 and SHA-256 hashes, and first-seen and last-seen dates
- Phishing indicators and email security checks (SPF, DKIM, DMARC)
- IP risk scores, category reliability, ASN and registration context
- CVE analysis using CVSS scores, affected versions, attack conditions and fixed versions

## Approach

- Reviewed X-Force report metadata, risk ratings, categories, DNS records, hashes and vulnerability descriptions
- Separated observed evidence from inference. An IP allocation, DNS association or threat group profile does not prove responsibility or compromise.
- Recommended defensive actions proportionate to the evidence: monitoring, patching, email controls, endpoint investigation, network hardening and incident response

## Limitations

- The X-Force account used had Freemium access, so some full threat analysis reports were not viewable. Supporting research is labeled as contextual, not presented as the complete IBM report.
- This is an intelligence assessment, not a forensic incident report. No malware was executed, reverse engineered or validated against live infrastructure.

## Tools and platforms

IBM X-Force Exchange

## Author

**Sai Siddarth P** | M.Tech Cybersecurity | Bengaluru, India
GitHub: [mailsaiat96-beep](https://github.com/mailsaiat96-beep)

## Disclaimer

For educational and defensive purposes only. Indicators are taken from public threat intelligence sources and should be validated against your own telemetry before blocking or attributing activity.
