# Netflix DNS Maintenance Report

Generated: `2026-08-25T17:12:19Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 19 |
| Suspect | 70 |
| Quarantine | 0 |
| Excluded | 192 |
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
| `api-global.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 24 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 24 |
| `api-user.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 24 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 24 |
| `api.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 24 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 24 |
| `appboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 26 |
| `dse.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 26 |
| `internationalbenefits.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 25 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 25 |
| `microstrategy.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 26 |
| `microstrategydev.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 26 |
| `obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 25 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 25 |
| `raven.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 26 |
| `secure.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 26 |
| `uiboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 26 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 26 |
| `useast.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 25 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 25 |
| `uswest.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 25 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 25 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 20 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.131.252.91 | 0.0 | 20 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 20 | TLS_CERT_ERROR | 18.217.99.125, 3.132.231.15, 3.132.253.101 | 0.0 | 20 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 20 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 20 |

## Discovery

Discovery state updated: `2026-08-25T17:12:19Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
