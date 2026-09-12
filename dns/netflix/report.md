# Netflix DNS Maintenance Report

Generated: `2026-09-12T14:13:12Z`

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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 95 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 98.85.45.78 | 0.0 | 55 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 95 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 34.208.235.84 | 0.0 | 55 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 95 | TLS_CERT_ERROR | 100.28.105.134, 13.216.189.215, 34.208.235.84 | 0.0 | 55 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_CERT_ERROR | 100.28.13.17, 34.217.204.82, 44.234.6.167 | 0.0 | 55 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 55 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 96 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 55 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 55 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 55 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 96 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 55 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 55 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 55 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 97 | TLS_CERT_ERROR | 100.28.13.17, 34.217.204.82, 44.234.6.167 | 0.0 | 55 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 96 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 55 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 96 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 55 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 91 | TLS_CERT_ERROR | 18.209.154.243, 3.214.91.176, 3.219.54.248 | 0.0 | 55 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 91 | TLS_CERT_ERROR | 107.22.243.248, 35.165.30.1, 35.168.39.97 | 0.0 | 55 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 91 | TLS_CERT_ERROR | 107.22.243.248, 18.209.154.243, 35.168.39.97 | 0.0 | 55 |

## Discovery

Discovery state updated: `2026-09-12T14:13:12Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
