# Netflix DNS Maintenance Report

Generated: `2026-09-03T19:55:31Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 187 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 186 |
| Excluded | 95 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 170 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **187**
Average stability: **90.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 60 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 60 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 60 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 60 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 60 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 60 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 62 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 62 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 61 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 61 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 62 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 62 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 61 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 61 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 62 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 62 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 62 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 62 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 61 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 61 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 61 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 61 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 56 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 56 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 56 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 56 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 56 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 56 |

## Discovery

Discovery state updated: `2026-09-03T19:55:31Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
