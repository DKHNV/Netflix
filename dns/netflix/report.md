# Netflix DNS Maintenance Report

Generated: `2026-08-25T05:50:58Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 19 |
| Suspect | 69 |
| Quarantine | 0 |
| Excluded | 190 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 3 |
| Suspect | 14 |
| Dead | 0 |

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
| `api-global.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 17 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 17 |
| `api-user.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 17 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 17 |
| `api.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 17 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 17 |
| `appboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 19 |
| `dse.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 19 |
| `internationalbenefits.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 18 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 18 |
| `microstrategy.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 19 |
| `microstrategydev.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 19 |
| `obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 18 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 18 |
| `raven.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 19 |
| `secure.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 19 |
| `uiboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 19 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 19 |
| `useast.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 18 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 18 |
| `uswest.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 18 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 18 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 13 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 18.221.239.141 | 0.0 | 13 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 13 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.132.172.84 | 0.0 | 13 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 13 | TLS_CERT_ERROR | 18.119.26.28, 3.131.252.91, 3.131.81.23 | 0.0 | 13 |

## Discovery

Discovery state updated: `2026-08-25T05:50:58Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
