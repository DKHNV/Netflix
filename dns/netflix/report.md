# Netflix DNS Maintenance Report

Generated: `2026-08-21T23:42:46Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 178 |
| Pending | 112 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 160 |
| Unknown | 18 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **178**
Average stability: **89.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 2 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 2 |
| `api-user.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 2 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 2 |
| `api.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 2 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 2 |
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 4 |
| `control.tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 4 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 4 |
| `internationalbenefits.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 3 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 3 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 4 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 4 |
| `nm.push.sandbox.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 3 | TIMEOUT | 18.214.127.164, 3.81.194.156, 34.224.54.49 | 0.0 | 3 |
| `obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 3 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 3 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 4 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 4 |
| `tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 4 |
| `tlscontrol.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 4 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 4 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 4 |
| `useast.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 3 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 3 |
| `uswest.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 3 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 3 |

## Discovery

Discovery state updated: `2026-08-21T23:42:46Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
