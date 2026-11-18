# Netflix DNS Maintenance Report

Generated: `2026-11-18T20:40:44Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 193 |
| Pending | 1 |
| Suspect | 0 |
| Quarantine | 82 |
| Excluded | 103 |
| Expired | 97 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 176 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **193**
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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 312 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 31 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 312 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 31 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 312 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 31 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 31 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 31 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 313 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 31 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 31 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 31 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 313 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 31 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 31 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 31 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 314 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 31 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 313 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 31 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 313 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 31 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 308 | TLS_CERT_ERROR | 35.165.30.1, 44.235.227.192, 54.184.157.35 | 0.0 | 31 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 308 | TLS_CERT_ERROR | 44.225.17.85, 44.229.178.197, 44.235.228.33 | 0.0 | 31 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 308 | TLS_CERT_ERROR | 34.214.209.123, 35.165.30.1, 44.229.178.197 | 0.0 | 31 |

## Discovery

Discovery state updated: `2026-11-18T20:40:44Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
