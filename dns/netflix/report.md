# Netflix DNS Maintenance Report

Generated: `2026-09-08T19:56:26Z`

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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 80 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 53 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 80 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 53 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 80 | TLS_CERT_ERROR | 34.208.235.84, 44.236.148.165, 54.189.73.148 | 0.0 | 53 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 53 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 53 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 81 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 53 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 53 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 53 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 81 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 53 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 53 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 53 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 82 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 53 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 81 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 53 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 81 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 53 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 76 | TLS_CERT_ERROR | 44.225.17.85, 44.229.178.197, 44.235.228.33 | 0.0 | 53 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 76 | TLS_CERT_ERROR | 35.165.30.1, 44.225.17.85, 44.229.178.197 | 0.0 | 53 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 76 | TLS_CERT_ERROR | 35.165.30.1, 44.225.17.85, 44.235.227.192 | 0.0 | 53 |

## Discovery

Discovery state updated: `2026-09-08T19:56:26Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
