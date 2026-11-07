# Netflix DNS Maintenance Report

Generated: `2026-11-07T13:15:51Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 193 |
| Pending | 0 |
| Suspect | 3 |
| Quarantine | 116 |
| Excluded | 109 |
| Expired | 55 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 177 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **194**
Average stability: **91.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| MULTIPLE | 1 |
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 287 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 39 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 287 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 39 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 287 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 39 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 39 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 288 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | MULTIPLE | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 288 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 39 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 39 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 289 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 39 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 288 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 288 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 39 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 283 | TLS_CERT_ERROR | 107.22.243.248, 18.209.154.243, 35.168.39.97 | 0.0 | 39 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 283 | TLS_CERT_ERROR | 3.214.91.176, 3.219.54.248, 3.234.191.246 | 0.0 | 39 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 283 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 39 |

## Discovery

Discovery state updated: `2026-11-07T13:15:51Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
