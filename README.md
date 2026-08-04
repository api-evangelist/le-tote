# LE TOTE

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
