# Netflix DNS Maintenance Report

Generated: `2026-11-08T22:15:07Z`

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
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 291 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 37 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 291 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 37 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 291 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 37 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 37 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 292 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 292 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 37 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 37 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 37 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 293 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 37 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 292 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 37 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 292 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 37 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 287 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 37 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 287 | TLS_CERT_ERROR | 18.119.26.28, 3.132.172.84, 3.133.172.165 | 0.0 | 37 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 287 | TLS_CERT_ERROR | 18.119.26.28, 3.132.172.84, 3.133.172.165 | 0.0 | 37 |

## Discovery

Discovery state updated: `2026-11-08T22:15:07Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
