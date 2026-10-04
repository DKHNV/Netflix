# Netflix DNS Maintenance Report

Generated: `2026-10-04T15:49:45Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 191 |
| Pending | 3 |
| Suspect | 0 |
| Quarantine | 0 |
| Excluded | 102 |
| Expired | 178 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 174 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **191**
Average stability: **91.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| MULTIPLE | 2 |
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 8 |
| TLS_ERROR | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 180 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 53 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 180 | MULTIPLE | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 53 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 180 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 53 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 53 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 53 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 181 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 53 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 53 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | MULTIPLE | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 53 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 181 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 53 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 53 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 53 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 182 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 53 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 181 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 53 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 181 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 53 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 176 | TLS_CERT_ERROR | 3.214.91.176, 3.219.54.248, 52.87.23.187 | 0.0 | 53 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 176 | TLS_CERT_ERROR | 107.22.243.248, 18.119.26.28, 3.132.172.84 | 0.0 | 53 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 176 | TLS_CERT_ERROR | 18.209.154.243, 3.234.191.246, 35.171.10.11 | 0.0 | 53 |

## Discovery

Discovery state updated: `2026-10-04T15:49:45Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
