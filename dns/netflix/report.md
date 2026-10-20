# Netflix DNS Maintenance Report

Generated: `2026-10-20T01:54:26Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 193 |
| Pending | 0 |
| Suspect | 4 |
| Quarantine | 56 |
| Excluded | 113 |
| Expired | 110 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 176 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **193**
Average stability: **91.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| MULTIPLE | 1 |
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 8 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 231 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 47 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 231 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 47 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 231 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 47 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 47 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 47 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 232 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 47 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 47 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 47 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 232 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 47 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 47 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 47 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 233 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 47 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 232 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 47 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 232 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 47 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 227 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 47 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 227 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.132.172.84 | 0.0 | 47 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 227 | MULTIPLE | 3.131.252.91, 3.131.81.23, 3.133.239.80 | 0.0 | 47 |

## Discovery

Discovery state updated: `2026-10-20T01:54:26Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
