# Netflix DNS Maintenance Report

Generated: `2026-08-28T08:40:35Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 1 |
| Suspect | 53 |
| Quarantine | 55 |
| Excluded | 172 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 0 |
| Suspect | 10 |
| Dead | 7 |

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
| `api-global.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 35 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 35 |
| `api-user.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 35 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 35 |
| `api.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 35 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 35 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 37 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `internationalbenefits.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 36 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 36 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 36 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 36 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 37 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 37 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 37 |
| `useast.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 36 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 36 |
| `uswest.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 36 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 36 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 31 | TLS_CERT_ERROR | 3.214.91.176, 3.219.54.248, 3.234.191.246 | 0.0 | 31 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 31 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 31 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 31 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 31 |

## Discovery

Discovery state updated: `2026-08-28T08:40:35Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
