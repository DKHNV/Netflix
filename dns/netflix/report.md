# Netflix DNS Maintenance Report

Generated: `2026-09-06T14:13:48Z`

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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 71 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 63 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 71 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 63 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 71 | TLS_CERT_ERROR | 3.13.134.191, 3.143.109.83, 3.148.32.134 | 0.0 | 63 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_CERT_ERROR | 34.217.204.82, 44.234.6.167, 52.89.219.164 | 0.0 | 63 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_ERROR | 107.20.175.192, 18.236.7.30, 204.236.236.127 | 0.0 | 63 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 72 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 63 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 63 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 63 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 72 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 63 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_ERROR | 18.236.7.30, 34.218.19.240, 44.226.113.145 | 0.0 | 63 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 63 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 73 | TLS_CERT_ERROR | 18.221.229.140, 3.129.196.255, 3.16.62.20 | 0.0 | 63 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 72 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 63 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 72 | TIMEOUT | 44.252.221.210, 44.253.81.170, 54.71.10.136 | 0.0 | 63 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 67 | TLS_CERT_ERROR | 18.221.239.141, 3.131.250.78, 3.15.91.90 | 0.0 | 63 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 67 | TLS_CERT_ERROR | 34.214.209.123, 35.165.30.1, 44.235.227.192 | 0.0 | 63 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 67 | TLS_CERT_ERROR | 18.217.99.125, 3.132.231.15, 3.132.253.101 | 0.0 | 63 |

## Discovery

Discovery state updated: `2026-09-06T14:13:48Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
