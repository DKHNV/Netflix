# Netflix DNS Maintenance Report

Generated: `2026-08-30T15:22:16Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 185 |
| Pending | 0 |
| Suspect | 1 |
| Quarantine | 185 |
| Excluded | 95 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 168 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 44 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 44 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 44 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 44 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 44 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 44 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 46 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 46 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 45 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 45 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 46 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 46 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 45 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 45 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 46 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 46 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 46 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 46 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 45 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 45 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 45 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 45 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 40 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 40 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 40 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 40 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 40 | TLS_CERT_ERROR | 18.217.99.125, 18.221.239.141, 3.131.250.78 | 0.0 | 40 |

## Discovery

Discovery state updated: `2026-08-30T15:22:16Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
