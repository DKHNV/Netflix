# Netflix DNS Maintenance Report

Generated: `2026-08-21T08:09:29Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 71 |
| Pending | 55 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 61 |
| Unknown | 10 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **71**
Average stability: **85.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TLS_CERT_ERROR | 6 |
| TLS_ERROR | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `appboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 1 |
| `control.tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 1 |
| `dse.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 1 |
| `microstrategy.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 1 |
| `microstrategydev.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 1 |
| `raven.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 1 |
| `secure.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 1 |
| `tls.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 1 |
| `tlscontrol.develop.test.cloud.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 35.169.19.205, 52.203.123.59, 52.87.41.154 | 0.0 | 1 |
| `uiboot.netflix.com` | unknown | `2026-08-21T08:09:29Z` | 1 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-21T08:09:29Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
