# Agile Delivery (agile-delivery)

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

A collection of resources, tools, and APIs related to agile delivery practices — the iterative approach to project management and software delivery that helps teams ship value faster through sprints, continuous feedback, and adaptive planning. Agile delivery frameworks emphasize cross-functional collaboration, working software over documentation, and responding to change over following a plan. This topic covers project management APIs, sprint planning tools, backlog management platforms, and delivery metrics services used to implement agile delivery at scale.

**URL:** [https://agilealliance.org/](https://agilealliance.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agile, Iterative Development, Project Management, Software Development, Sprint, Scrum

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## Common Properties

- [Portal](https://agilealliance.org/)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Sprint Schema](https://raw.githubusercontent.com/api-evangelist/agile-delivery/refs/heads/main/json-schema/agile-delivery-sprint-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agile-delivery/refs/heads/main/json-ld/agile-delivery-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agile-delivery/refs/heads/main/vocabulary/agile-delivery-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Sprint Planning and Tracking | APIs for managing sprint cycles, planning capacity, and tracking velocity across agile teams. |
| Backlog Management | Tools for creating, prioritizing, and refining product backlogs as part of agile delivery workflows. |
| Continuous Delivery Integration | Integration with CI/CD pipelines to support agile delivery principles of frequent, incremental software releases. |
| Delivery Metrics and Reporting | APIs for tracking key agile delivery metrics including velocity, cycle time, lead time, and burndown charts. |
| Retrospective Facilitation | Tools to facilitate sprint retrospectives and capture action items for continuous process improvement. |

## Use Cases

| Name | Description |
|------|-------------|
| Sprint Planning Automation | Use APIs to automatically populate sprint boards from product backlogs based on team capacity and story point estimates. |
| Delivery Metrics Dashboard | Aggregate sprint velocity, cycle time, and deployment frequency data to build agile delivery health dashboards. |
| Cross-Team Coordination | Synchronize agile delivery artifacts across multiple teams working on related products or platforms. |
| Release Planning | Use capacity and velocity data to forecast release dates and communicate delivery timelines to stakeholders. |

## Integrations

| Name | Description |
|------|-------------|
| Jira | Leading agile project management tool with comprehensive APIs for sprints, issues, and boards. |
| Linear | Modern issue tracking and project management tool built for agile software teams with a developer-friendly API. |
| GitHub Projects | Integrated project planning directly within GitHub for teams managing agile work alongside code. |
| Azure DevOps | Microsoft's agile planning tool with APIs for work items, sprints, and delivery pipelines. |
| Trello | Visual Kanban-based project management tool with APIs for cards, lists, and boards. |

## Artifacts

### JSON Schema

- [Sprint Schema](json-schema/agile-delivery-sprint-schema.json)

### JSON Structure

- [Sprint Structure](json-structure/agile-delivery-sprint-structure.json)

### JSON-LD

- [Agile Delivery Context](json-ld/agile-delivery-context.jsonld)

## Vocabulary

- [Agile Delivery Vocabulary](vocabulary/agile-delivery-vocabulary.yaml) — Taxonomy for sprint management, backlog, and delivery metrics

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
