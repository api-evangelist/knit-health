# Knit Health

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

Knit Health Technologies, Inc. is a healthcare AI company spun out of the University of California, Berkeley, building a Large Clinical Behavior Model (LCBM) — a healthcare-native intelligence layer trained on the real decision patterns of practicing clinicians captured in EMR data, rather than on medical text alone. The model is trained on Truveta EMR data representing more than 130 million patients across 30 U.S. health systems, then fine-tuned to an individual health system's own practice patterns.

Knit sells to health systems as an enterprise intelligence platform spanning intelligent specialist routing, predictive patient flow, optimized care team allocation, clinical variation insight, and proactive care recommendations.

- Website: https://www.knit.health/
- Technology: https://www.knit.health/ai
- Blog: https://www.knit.health/blog

Backed by: Uncork Capital and Frist Cressey Ventures (seed, $11.6M, May 2026); Moxxie Ventures and Coalition Operators (pre-seed).

## API surface

Knit publishes **no public API, developer portal, API documentation, SDK, CLI, or MCP server** as of 2026-07-19. The company states that its engineers work alongside customer teams to design and deploy APIs tailored to each health system, so the integration surface is bespoke and contractual rather than self-serve. No public GitHub organization or first-party package on npm/PyPI was found.

Note: `knithealth.com` belongs to an unrelated, defunct consumer baby-sleep-monitor company of the same name (2015–2019). This profile covers the 2025-founded clinical AI company at `knit.health` (`knithealth.ai` redirects there).

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/knit-health-domain-security.yml` | probed |
| Well-known probe | `well-known/knit-health-well-known.yml` | searched (no surface published) |
| llms.txt | `llms/knit-health-llms.txt` | generated |
