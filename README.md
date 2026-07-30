# LE TOTE

**Status: defunct.** Le Tote was an online women's clothing rental and subscription-box business founded in San Francisco in 2012 by Brett Northart and Rakesh Tondon (Y Combinator S13). It agreed to acquire Lord & Taylor from Hudson's Bay Company in August 2019, filed for Chapter 11 bankruptcy on 2 August 2020, and was sold to Saadia Group that October. Saadia Group was reported effectively shut down in March 2024 and the letote.com site went offline that spring.

Le Tote never published a public API or developer portal, so this profile carries no OpenAPI, MCP, skills, scopes, or conventions artifacts — those absences are accurate rather than gaps awaiting enrichment. What survives is the company's open-source engineering output.

## Artifacts

| Artifact | File |
|---|---|
| First-party packages (4 verified) | [`packages/le-tote-packages.yml`](packages/le-tote-packages.yml) |
| Company / API lifecycle | [`lifecycle/le-tote-lifecycle.yml`](lifecycle/le-tote-lifecycle.yml) |
| Probed domain security | [`security/le-tote-domain-security.yml`](security/le-tote-domain-security.yml) |
| llms.txt | [`llms/le-tote-llms.txt`](llms/le-tote-llms.txt) |

## Notes

- GitHub organization — https://github.com/LeToteTeam — 19 public repos, 5 first-party non-forks, last activity 2020.
- Published packages: `band` and `tm_mercury` (Hex), `unresponsys` (RubyGems), `Stardaze` (CocoaPods). These are internal engineering libraries, **not** client SDKs for a Le Tote API.
- letote.com is still registered with IONOS but returns `SERVFAIL`: it delegates to Route 53 nameservers that no longer host the zone — a dangling delegation.

Backed by: 500-global, a16z
