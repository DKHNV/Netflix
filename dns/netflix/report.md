# Netflix DNS Maintenance Report

Generated: `2026-09-01T01:51:32Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 186 |
| Pending | 0 |
| Suspect | 1 |
| Quarantine | 185 |
| Excluded | 95 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 169 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **186**
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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 49 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 49 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 49 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 49 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 49 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 49 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 51 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 51 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 50 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 50 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 51 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 51 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 50 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 50 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 51 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 51 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 51 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 51 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 50 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 50 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 50 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 50 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 45 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 45 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 45 | TLS_CERT_ERROR | 18.209.154.243, 3.234.191.246, 35.171.10.11 | 0.0 | 45 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 45 | TLS_CERT_ERROR | 107.22.243.248, 3.214.91.176, 3.219.54.248 | 0.0 | 45 |

## Discovery

Discovery state updated: `2026-09-01T01:51:32Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
