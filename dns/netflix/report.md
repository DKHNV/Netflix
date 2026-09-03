# Netflix DNS Maintenance Report

Generated: `2026-09-03T15:02:28Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 187 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 186 |
| Excluded | 95 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 170 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **187**
Average stability: **90.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 59 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 59 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 59 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 59 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 59 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 59 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 61 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 61 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 60 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 60 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 61 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 61 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 60 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 60 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 61 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 61 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 61 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 61 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 60 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 60 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 60 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 60 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 55 | TLS_CERT_ERROR | 18.217.99.125, 3.131.252.91, 3.131.81.23 | 0.0 | 55 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 55 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 55 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 55 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 55 |

## Discovery

Discovery state updated: `2026-09-03T15:02:28Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
