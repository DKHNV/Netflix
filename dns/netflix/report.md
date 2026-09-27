# Netflix DNS Maintenance Report

Generated: `2026-09-27T01:32:56Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 190 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 186 |
| Excluded | 96 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 173 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 17 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **190**
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
| `api-global.netflix.com` | dead | `2026-08-21T17:49:18Z` | 153 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 56 |
| `api-user.netflix.com` | dead | `2026-08-21T17:49:18Z` | 153 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 56 |
| `api.netflix.com` | dead | `2026-08-21T17:49:18Z` | 153 | TLS_CERT_ERROR | 176.34.94.213, 52.215.78.165, 54.76.212.68 | 0.0 | 56 |
| `appboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_CERT_ERROR | 52.211.238.216, 54.217.127.99, 99.80.13.184 | 0.0 | 56 |
| `dse.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 56 |
| `internationalbenefits.netflix.com` | dead | `2026-08-21T11:46:08Z` | 154 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 56 |
| `microstrategy.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 56 |
| `microstrategydev.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 56 |
| `obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 154 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 56 |
| `raven.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_ERROR | 107.20.175.192, 204.236.236.127, 50.17.247.9 | 0.0 | 56 |
| `secure.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_CERT_ERROR | 45.57.90.1, 45.57.91.1 | 0.0 | 56 |
| `uiboot.netflix.com` | dead | `2026-08-21T08:09:29Z` | 155 | TLS_CERT_ERROR | 52.211.238.216, 54.217.127.99, 99.80.13.184 | 0.0 | 56 |
| `useast.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 154 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 56 |
| `uswest.obiwan.netflix.com` | dead | `2026-08-21T11:46:08Z` | 154 | TIMEOUT | 35.168.152.188, 54.209.43.49, 98.85.207.205 | 0.0 | 56 |
| `venkman.cluster.eu-west-1.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 149 | TLS_CERT_ERROR | 34.252.42.104, 46.137.170.241, 52.211.179.103 | 0.0 | 56 |
| `venkman.cluster.us-east-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 149 | TLS_CERT_ERROR | 34.252.42.104, 34.255.15.69, 46.137.170.241 | 0.0 | 56 |
| `venkman.cluster.us-west-2.prod.cloud.netflix.com` | dead | `2026-08-22T17:40:12Z` | 149 | TLS_CERT_ERROR | 34.252.42.104, 34.255.15.69, 46.137.170.241 | 0.0 | 56 |

## Discovery

Discovery state updated: `2026-09-27T01:32:56Z`

## Notes

- Public active DNS file: `Netflix_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
