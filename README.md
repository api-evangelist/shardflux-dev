# Shardflux

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Shardflux provides serverless virtual machines for AI agents within products, offering a persistent per‑customer compute instance that is opened by a key, scales to zero when idle, and retains state. The platform enables developers to embed autonomous agents that require reliable, stateful compute without managing lifecycle code, simplifying deployment and reducing operational overhead for AI‑driven applications.

**Areas:** Serverless Compute · AI Agents · GPU Rendering · Developer Tools · Cloud Infrastructure

## Shardflux on APIs.io

Everything profiled for Shardflux is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/shardflux-dev/](https://apis.io/providers/shardflux-dev/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Shardflux Billing API](https://apis.io/apis/shardflux-dev/shardflux-dev-billing-api/) — The plan catalog and the organization’s subscription.
- [Shardflux Browser profiles API](https://apis.io/apis/shardflux-dev/shardflux-dev-browser-profiles-api/) — Write-only browser sessions scoped to a project or workspace.
- [Shardflux Client versions API](https://apis.io/apis/shardflux-dev/shardflux-dev-client-versions-api/) — The latest and the oldest supported version of every Shardflux client package.
- [Shardflux Egress policy API](https://apis.io/apis/shardflux-dev/shardflux-dev-egress-policy-api/) — Outbound network policy of a project or a workspace.
- [Shardflux Entitlements API](https://apis.io/apis/shardflux-dev/shardflux-dev-entitlements-api/) — The limits and features the organization’s plan grants.
- [Shardflux Feedback API](https://apis.io/apis/shardflux-dev/shardflux-dev-feedback-api/) — Send product feedback straight to the Shardflux team: what failed, confused you or is missing.
- [Shardflux Operations API](https://apis.io/apis/shardflux-dev/shardflux-dev-operations-api/) — Lifecycle operations (open, suspend, resume, fork, ...) and their progress.
- [Shardflux Organizations API](https://apis.io/apis/shardflux-dev/shardflux-dev-organizations-api/) — The organization an API key belongs to.
- [Shardflux Principal API](https://apis.io/apis/shardflux-dev/shardflux-dev-principal-api/) — The API key making the request: its organization, project and tool permissions.
- [Shardflux Projects API](https://apis.io/apis/shardflux-dev/shardflux-dev-projects-api/) — The project an API key belongs to.
- [Shardflux Secrets API](https://apis.io/apis/shardflux-dev/shardflux-dev-secrets-api/) — Project secrets, their versions, and the secrets bound to a workspace.
- [Shardflux Template builds API](https://apis.io/apis/shardflux-dev/shardflux-dev-template-builds-api/) — Build template versions from a recipe or an uploaded context, and look up packages and languages.
- [Shardflux Template drafts API](https://apis.io/apis/shardflux-dev/shardflux-dev-template-drafts-api/) — Draft templates: iterate on states and test instances, then publish a version.
- [Shardflux Templates API](https://apis.io/apis/shardflux-dev/shardflux-dev-templates-api/) — Published templates and their versions, files, recipes and diffs.
- [Shardflux Tool tokens API](https://apis.io/apis/shardflux-dev/shardflux-dev-tool-tokens-api/) — Short-lived tokens for the workspace tools (exec, PTY, files, git, browser) served at the workspace’s cell_endpoint, and agent sessions.
- [Shardflux Usage and spend API](https://apis.io/apis/shardflux-dev/shardflux-dev-usage-and-spend-api/) — Metered usage, estimates, grants and spend of an organization or a workspace.
- [Shardflux Volumes API](https://apis.io/apis/shardflux-dev/shardflux-dev-volumes-api/) — Persistent volumes shared between workspaces of a project.
- [Shardflux Workspaces API](https://apis.io/apis/shardflux-dev/shardflux-dev-workspaces-api/) — Open workspaces by key, and suspend, resume, snapshot, fork, reset or close them.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Shardflux Agentic Access](https://apis.io/agentic-access/shardflux-dev/shardflux-dev-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Operation](https://apis.io/schemas/shardflux-dev/shardflux-dev-operation/)
- [ResizeResult](https://apis.io/schemas/shardflux-dev/shardflux-dev-resize-result/)
- [SpendCap](https://apis.io/schemas/shardflux-dev/shardflux-dev-spend-cap/)
- [Template recipe v2 (shardflux.template-recipe.v2)](https://apis.io/schemas/shardflux-dev/shardflux-dev-template-recipe-v2/)
- [Volume](https://apis.io/schemas/shardflux-dev/shardflux-dev-volume/)
- [Workspace](https://apis.io/schemas/shardflux-dev/shardflux-dev-workspace/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Shardflux Dev Context](https://apis.io/jsonld/shardflux-dev/shardflux-dev-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Shardflux API Rules](https://apis.io/rules/shardflux-dev/shardflux-dev-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Shardflux Authentication](https://apis.io/security/shardflux-dev/shardflux-dev-authentication/)
- [Shardflux Domain Security](https://apis.io/security/shardflux-dev/shardflux-dev-domain-security/)
- [Shardflux Vulnerability Disclosure](https://apis.io/security/shardflux-dev/shardflux-dev-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Shardflux Plans Pricing](https://apis.io/plans/shardflux-dev/shardflux-dev-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://shardflux.dev/)
- [Documentation](https://docs.shardflux.dev/)
- [Getting started](https://docs.shardflux.dev/quickstart)
- [API reference](https://docs.shardflux.dev/reference/cli)
- [Support](https://shardflux.dev/security)
- [Security](https://shardflux.dev/security)
- [Terms of service](https://shardflux.dev/terms)
- [Privacy policy](https://shardflux.dev/privacy)
- [GitHub](https://github.com/shardfluxdev)

## API Evangelist rating

**Kin Score 56.6** — strong · rubric 0.28.0 · scored 2026-11-24

| Facet | Score |
|---|---|
| Discoverability | 76.8 |
| Contract quality | 60.3 |
| Contract governance | 79.1 |
| Operational transparency | 14.3 |
| Developer ergonomics | 61.2 |
| Access clarity | 40.0 |

**Agent readiness 54.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | — |
| MCP Tool Quality | na |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/shardflux-dev/](https://apis.io/providers/shardflux-dev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Shardflux: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/shardflux-dev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
