# SuperTokens (supertokens)

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

SuperTokens is an open source authentication solution providing session management, social login, email/password auth, and passwordless flows for web and mobile apps. It is an open source alternative to Auth0, Firebase Auth, and AWS Cognito. SuperTokens exposes a Core Driver Interface (CDI) HTTP API for backend SDKs to communicate with the supertokens-core service, as well as a Frontend Driver Interface (FDI) for frontend SDK interaction. Available SDKs cover Node.js, Python, Go, Java, React, Flutter, iOS, and Android.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml)

## Tags

- Authentication
- Open Source
- Session Management
- Social Login
- Passwordless
- Identity
- Authorization
- Multi-Tenancy
- Node.js
- Self-Hosted

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-30

## APIs

### SuperTokens Core Driver Interface

The Core Driver Interface (CDI) is the REST API exposed by the supertokens-core HTTP service. Backend SDKs (Node.js, Python, Go) communicate with the core via this API to perform authentication operations including session creation, verification, refresh, user sign-up/sign-in, email verification, password reset, multi-tenancy, and user metadata management.

- **Human URL:** [https://github.com/supertokens/core-driver-interface](https://github.com/supertokens/core-driver-interface)
- **Base URL:** `https://{supertokens-core-host}:{port}`

#### Tags

- Authentication
- Session Management
- Core API
- Identity
- Open Source

#### Properties

- [Documentation](https://supertokens.com/docs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/openapi/supertokens-core-driver-interface-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/supertokens/supertokens-core)
- [A P I  Specification](https://github.com/supertokens/core-driver-interface)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-schema/supertokens-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-structure/supertokens-session-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-ld/supertokens-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/rules/supertokens-cdi-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/vocabulary/supertokens-vocabulary.yml)
- [Postman Collection](collections/supertokens-core-driver-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/supertokens-core-driver-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/supertokens)
- [Website](https://supertokens.com)
- [Documentation](https://supertokens.com/docs)
- [GitHub Organization](https://github.com/supertokens)
- [GitHub Repository](https://github.com/supertokens/supertokens-core)
- [S D K  Node.js](https://github.com/supertokens/supertokens-node)
- [S D K  Python](https://github.com/supertokens/supertokens-python)
- [S D K  Go](https://github.com/supertokens/supertokens-golang)
- [S D K  React](https://github.com/supertokens/supertokens-web-js)
- [S D K  Flutter](https://github.com/supertokens/supertokens-flutter)
- [Changelog](https://github.com/supertokens/supertokens-core/blob/master/CHANGELOG.md)
- [Issues](https://github.com/supertokens/supertokens-core/issues)
- [Features](undefined)
- [M C P Server](https://github.com/supertokens/mcp-plugin)
- [L L Ms Txt](https://supertokens.com/llms.txt)
- [Review](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/review.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
