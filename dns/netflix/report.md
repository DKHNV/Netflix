# Netflix DNS Maintenance Report

Generated: `2026-08-21T11:46:08Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 118 |
| Pending | 80 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 103 |
| Unknown | 15 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **118**
Average stability: **87.3%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |
| TLS_CERT_ERROR | 6 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 2 |
| `control.tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 2 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 2 |
| `internationalbenefits.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 1 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 1 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 2 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 2 |
| `nm.push.sandbox.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 1 | TIMEOUT | 18.214.127.164, 3.81.194.156, 34.224.54.49 | 0.0 | 1 |
| `obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 1 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 1 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 2 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 2 |
| `tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 2 |
| `tlscontrol.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 2 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 2 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 2 |
| `useast.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 1 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 1 |
| `uswest.obiwan.netflix.com` | unknown | `2026-08-21T11:46:08Z` | 1 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-21T11:46:08Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
