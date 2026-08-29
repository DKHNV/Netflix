# Netflix DNS Maintenance Report

Generated: `2026-08-29T11:41:29Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 0 |
| Suspect | 19 |
| Quarantine | 138 |
| Excluded | 124 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 0 |
| Suspect | 3 |
| Dead | 14 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **185**
Average stability: **90.8%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 40 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 40 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 40 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 40 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 40 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 40 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 42 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 42 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 41 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 41 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 42 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 42 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 41 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 41 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 42 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 42 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 42 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 42 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 41 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 41 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 41 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 41 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 36 | TLS_CERT_ERROR | 3.214.91.176, 3.219.54.248, 3.234.191.246 | 0.0 | 36 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 36 | TLS_CERT_ERROR | 107.22.243.248, 18.209.154.243, 3.234.191.246 | 0.0 | 36 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 36 | TLS_CERT_ERROR | 18.209.154.243, 3.234.191.246, 35.171.10.11 | 0.0 | 36 |

## Discovery

Discovery state updated: `2026-08-29T11:41:29Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
