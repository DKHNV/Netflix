# Netflix DNS Maintenance Report

Generated: `2026-08-28T17:28:39Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 0 |
| Suspect | 41 |
| Quarantine | 80 |
| Excluded | 160 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 0 |
| Suspect | 6 |
| Dead | 11 |

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
| `api-global.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 38 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 38 |
| `api-user.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 38 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 38 |
| `api.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 38 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 38 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_CERT_ERROR | 100.28.13.17, 34.217.204.82, 44.234.6.167 | 0.0 | 40 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 40 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 39 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 40 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 40 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 39 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 40 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 40 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 40 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 40 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 39 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 39 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 34 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 34 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 34 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 34 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 34 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 34 |

## Discovery

Discovery state updated: `2026-08-28T17:28:39Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
