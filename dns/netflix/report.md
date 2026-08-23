# Netflix DNS Maintenance Report

Generated: `2026-08-23T15:57:31Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 184 |
| Pending | 88 |
| Suspect | 0 |
| Quarantine | 0 |
| Excluded | 190 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 167 |
| Unknown | 17 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **184**
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
| `api-global.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 10 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 10 |
| `api-user.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 10 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 10 |
| `api.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 10 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 10 |
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 12 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 12 |
| `internationalbenefits.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 11 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 11 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 12 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 12 |
| `obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 11 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 11 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 12 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 12 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 12 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 12 |
| `useast.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 11 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 11 |
| `uswest.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 11 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 11 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 6 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 6 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 6 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 6 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 6 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 6 |

## Discovery

Discovery state updated: `2026-08-23T15:57:31Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
