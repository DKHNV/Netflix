# Netflix DNS Maintenance Report

Generated: `2026-09-04T14:59:54Z`

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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 63 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 63 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 63 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 63 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 63 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 63 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 63 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 64 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 64 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 63 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 63 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 65 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 63 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 64 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 63 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 64 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 63 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 59 | TLS_CERT_ERROR | 18.119.26.28, 3.132.172.84, 3.133.172.165 | 0.0 | 59 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 59 | TLS_CERT_ERROR | 18.119.26.28, 3.132.172.84, 3.133.172.165 | 0.0 | 59 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 59 | TLS_CERT_ERROR | 107.22.243.248, 18.119.26.28, 18.217.99.125 | 0.0 | 59 |

## Discovery

Discovery state updated: `2026-09-04T14:59:54Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
