# Netflix DNS Maintenance Report

Generated: `2026-09-11T15:04:11Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 188 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 186 |
| Excluded | 95 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 171 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **188**
Average stability: **91.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 91 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 54 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 91 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 54 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 91 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 54 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 54 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 54 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 92 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 54 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 54 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 54 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 92 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 54 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 54 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 54 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 93 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 54 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 92 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 54 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 92 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 54 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 87 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.131.252.91 | 0.0 | 54 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 87 | TLS_CERT_ERROR | 107.22.243.248, 18.221.239.141, 3.131.250.78 | 0.0 | 54 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 87 | TLS_CERT_ERROR | 18.119.26.28, 18.221.239.141, 3.131.250.78 | 0.0 | 54 |

## Discovery

Discovery state updated: `2026-09-11T15:04:11Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
