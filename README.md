# Papa (papa)

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
