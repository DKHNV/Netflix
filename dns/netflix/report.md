# Netflix DNS Maintenance Report

Generated: `2026-10-30T13:09:21Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 194 |
| Pending | 1 |
| Suspect | 1 |
| Quarantine | 111 |
| Excluded | 102 |
| Expired | 67 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 177 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **194**
Average stability: **91.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 268 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 51 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 268 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 51 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 268 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 3.13.134.191 | 0.0 | 51 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 51 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 51 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 269 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 51 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 51 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 51 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 269 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 51 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 51 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 51 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 270 | TLS_CERT_ERROR | 100.28.13.17, 18.221.229.140, 3.129.196.255 | 0.0 | 51 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 269 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 51 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 269 | TIMEOUT | 35.168.152.188, 44.252.221.210, 44.253.81.170 | 0.0 | 51 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 264 | TLS_CERT_ERROR | 18.217.99.125, 3.131.252.91, 3.131.81.23 | 0.0 | 51 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 264 | TLS_CERT_ERROR | 18.119.26.28, 18.217.99.125, 3.132.172.84 | 0.0 | 51 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 264 | TLS_CERT_ERROR | 3.131.252.91, 3.131.81.23, 3.133.239.80 | 0.0 | 51 |

## Discovery

Discovery state updated: `2026-10-30T13:09:21Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
