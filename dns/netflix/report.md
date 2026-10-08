# Netflix DNS Maintenance Report

Generated: `2026-10-08T12:05:45Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 192 |
| Pending | 14 |
| Suspect | 4 |
| Quarantine | 2 |
| Excluded | 127 |
| Expired | 136 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 175 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **192**
Average stability: **91.1%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_CERT_ERROR | 9 |
| TLS_ERROR | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 192 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 50 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 192 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 50 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 192 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 50 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 50 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 50 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 193 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 50 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 50 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 50 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 193 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 50 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 50 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 50 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 194 | TLS_CERT_ERROR | 100.28.13.17, 52.206.20.66, 54.224.145.4 | 0.0 | 50 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 193 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 50 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 193 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 50 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 188 | TLS_CERT_ERROR | 107.22.243.248, 18.209.154.243, 35.168.39.97 | 0.0 | 50 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 188 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 50 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 188 | TLS_CERT_ERROR | 107.22.243.248, 3.234.191.246, 35.168.39.97 | 0.0 | 50 |

## Discovery

Discovery state updated: `2026-10-08T12:05:45Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
