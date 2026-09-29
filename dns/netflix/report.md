# Netflix DNS Maintenance Report

Generated: `2026-09-29T02:36:07Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 191 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 4 |
| Excluded | 97 |
| Expired | 182 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 174 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **191**
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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 160 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 55 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 160 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 55 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 160 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 55 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_CERT_ERROR | 52.211.238.216, 54.217.127.99, 99.80.13.184 | 0.0 | 55 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 55 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 161 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 55 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 55 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 55 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 161 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 55 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 55 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 55 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 162 | TLS_CERT_ERROR | 52.211.238.216, 54.217.127.99, 99.80.13.184 | 0.0 | 55 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 161 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 55 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 161 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 55 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 156 | TLS_CERT_ERROR | 34.252.42.104, 34.255.15.69, 46.137.170.241 | 0.0 | 55 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 156 | TLS_CERT_ERROR | 34.252.42.104, 46.137.170.241, 54.195.169.127 | 0.0 | 55 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 156 | TLS_CERT_ERROR | 34.255.15.69, 52.211.179.103, 52.31.11.242 | 0.0 | 55 |

## Discovery

Discovery state updated: `2026-09-29T02:36:07Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
