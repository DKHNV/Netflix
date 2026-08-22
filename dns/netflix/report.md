# Netflix DNS Maintenance Report

Generated: `2026-08-22T11:40:04Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 245 |
| Pending | 138 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 225 |
| Unknown | 20 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **245**
Average stability: **91.8%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 6 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 4 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 4 |
| `api-user.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 4 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 4 |
| `api.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 4 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 4 |
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 6 |
| `control.tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 6 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 6 |
| `internationalbenefits.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 5 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 5 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 6 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 6 |
| `nm.push.sandbox.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 5 | TIMEOUT | 18.214.127.164, 3.81.194.156, 34.224.54.49 | 0.0 | 5 |
| `obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 5 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 5 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 6 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 6 |
| `tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 6 |
| `tlscontrol.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 6 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 6 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 6 |
| `useast.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 5 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 5 |
| `uswest.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 5 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 5 |
| `ws.push.test.netflix.com` | unknown | `2026-08-22T05:46:48Z` | 2 | TIMEOUT | 3.210.189.6, 34.194.215.122, 54.91.223.156 | 0.0 | 2 |
| `ws.test.netflix.com` | unknown | `2026-08-22T11:40:04Z` | 1 | TIMEOUT | 3.210.189.6, 34.194.215.122, 54.91.223.156 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-22T11:40:04Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
