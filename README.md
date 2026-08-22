# Papa (papa)

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

Papa is a companion care company that pairs older adults and families with vetted, trained companions - called **Papa Pals** - for social support, errands, transportation, technology help, check-ins, and everyday assistance. Papa sells this as a tech-enabled social care benefit to Medicare Advantage, Medicaid, Special Needs, and commercial health plans and to employers, serving millions of members across roughly 70-100 health plan and employer partners. Members enroll by phone (or online for employer members) and use the **Papa Care** app to request and schedule visits; Papa Pals use the **Papa Pal** app to accept and complete them.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/papa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/papa/refs/heads/main/apis.yml)

## API Access Model — Honest Status

**Papa does not publish a public or self-serve developer API.** There is no public API reference, developer portal, API-key signup, OpenAPI document, or WebSocket endpoint for any Papa product as of this writing.

Papa is a business-to-business-to-consumer (B2B2C) service company, not an API product company. A health plan or employer integrates with Papa through a **sales and contracting relationship**, and the resulting data movement is handled privately:

- **Eligibility file exchange** — the health plan shares member eligibility data so Papa can identify, target, and onboard eligible members. This is a contract-governed data-file exchange, not a documented public API.
- **Enrollment and scheduling** — members are enrolled by phone (1-800-348-7951) or online (employer members), then use the Papa Care app. There is no public scheduling API.
- **Reporting dashboards** — Papa returns recurring dashboards covering program activity, utilization, identified gaps and referrals, member satisfaction, and outcomes. This is delivered as reporting, not as a queryable public API.

Logical capability areas a hypothetical Papa platform API *would* cover — **Members / Eligibility**, **Visits / Scheduling**, **Pals / Caregivers**, and **Reporting / Outcomes** — are described here only to characterize the business. **No endpoints are published, and none have been modeled or fabricated in this catalog entry.** This repository is maintained as an honest stub.

If Papa later exposes a partner or developer API, this entry should be updated with the real base URLs, an OpenAPI document under `openapi/`, and any plans, rate limits, and FinOps details.

## Tags

- Healthcare
- Social Care
- Companion Care
- Older Adults
- Medicare Advantage
- Medicaid
- Health Plans
- Aging
- No Public API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

None published. Papa exposes no public or partner developer API; see **API Access Model** above.

## Common Properties

- [Website](https://www.papa.com)
- [LinkedIn](https://www.linkedin.com/company/papainc)
- [GitHub Organization](https://github.com/joinpapa)
- [Health Plan Sign Up](https://www.papa.com/health-plans)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
