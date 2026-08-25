# Netflix DNS Maintenance Report

Generated: `2026-08-25T23:42:37Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 3 |
| Suspect | 86 |
| Quarantine | 0 |
| Excluded | 192 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 0 |
| Suspect | 17 |
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
| `api-global.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 28 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 28 |
| `api-user.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 28 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 28 |
| `api.netflix.com` | suspect | `2026-08-21T17:49:18Z` | 28 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 28 |
| `appboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 30 |
| `dse.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 30 |
| `internationalbenefits.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 29 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 29 |
| `microstrategy.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 30 |
| `microstrategydev.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 30 |
| `obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 29 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 29 |
| `raven.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 30 |
| `secure.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 30 |
| `uiboot.netflix.com` | suspect | `2026-08-21T08:09:29Z` | 30 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 30 |
| `useast.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 29 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 29 |
| `uswest.obiwan.netflix.com` | suspect | `2026-08-21T11:46:08Z` | 29 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 29 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 24 | TLS_CERT_ERROR | 18.119.26.28, 3.131.252.91, 3.131.81.23 | 0.0 | 24 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 24 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 24 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | suspect | `2026-08-22T17:40:12Z` | 24 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.131.252.91 | 0.0 | 24 |

## Discovery

Discovery state updated: `2026-08-25T23:42:37Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
