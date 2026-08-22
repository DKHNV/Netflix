# Netflix DNS Maintenance Report

Generated: `2026-08-22T17:40:12Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 266 |
| Pending | 177 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 241 |
| Unknown | 25 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **266**
Average stability: **90.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 6 |
| TLS_CERT_ERROR | 14 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 5 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 5 |
| `api-us.test.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 1 | TLS_CERT_ERROR | 52.201.21.64, 52.54.24.236, 54.167.128.47 | 0.0 | 1 |
| `api-user.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 5 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 5 |
| `api.netflix.com` | unknown | `2026-08-21T17:49:18Z` | 5 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 5 |
| `api.test.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 1 | TLS_CERT_ERROR | 52.201.21.64, 52.54.24.236, 54.167.128.47 | 0.0 | 1 |
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 7 |
| `control.tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 7 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 7 |
| `internationalbenefits.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 6 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 6 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 7 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 7 |
| `nm.push.sandbox.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 6 | TIMEOUT | 18.214.127.164, 3.81.194.156, 34.224.54.49 | 0.0 | 6 |
| `obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 6 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 6 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 7 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 7 |
| `tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 7 |
| `tlscontrol.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 7 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 7 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 7 |
| `useast.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 6 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 6 |
| `uswest.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 6 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 6 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 1 | TLS_CERT_ERROR | 18.119.26.28, 3.131.252.91, 3.131.81.23 | 0.0 | 1 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 1 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.131.252.91 | 0.0 | 1 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | unknown | `2026-08-22T17:40:12Z` | 1 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 18.221.239.141 | 0.0 | 1 |
| `ws.push.test.netflix.com` | unknown | `2026-08-22T05:46:48Z` | 3 | TIMEOUT | 3.210.189.6, 34.194.215.122, 54.91.223.156 | 0.0 | 3 |
| `ws.test.netflix.com` | unknown | `2026-08-22T11:40:04Z` | 2 | TIMEOUT | 3.210.189.6, 34.194.215.122, 54.91.223.156 | 0.0 | 2 |

## Discovery

Discovery state updated: `2026-08-22T17:40:12Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
