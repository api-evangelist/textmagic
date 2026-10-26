# Textmagic (textmagic)

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

Textmagic is a business text-messaging platform offering two-way SMS, bulk messaging, SMS marketing, and team inboxes. Its REST API (v2) lets developers send and receive messages, manage contacts and lists, schedule and template messages, and administer sender IDs and dedicated numbers programmatically over HTTPS.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/textmagic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/textmagic/refs/heads/main/apis.yml)

## Tags

- SMS
- Text Messaging
- Messaging
- Communications
- CPaaS

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Textmagic Messages API

Send single or templated SMS messages, list and search sent messages, preview and price messages, upload attachments, and delete outbound messages.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Messages
- SMS
- Send

#### Properties

- [Documentation](https://www.textmagic.com/docs/api/send-sms/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Bulk Messaging API

Track large send operations through bulk sessions and messaging sessions, retrieve session status, statistics, and the messages each session generated.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Bulk
- Sessions
- Campaigns

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Chats and Replies API

Manage two-way conversations - list, search, open, close, mute, and read chats - and retrieve, search, and delete inbound reply messages.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Chats
- Replies
- Inbound

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Contacts and Lists API

Create, read, update, delete, search, and import contacts; organize them into lists; and manage contact list membership, blocking, and unsubscribes.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Contacts
- Lists
- Address Book

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Templates API

Create, read, update, delete, and search reusable message templates for consistent outbound messaging.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Templates
- Reusable Content

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Scheduled Messages API

List, retrieve, search, and delete scheduled (future-dated) messages queued for delivery.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Schedules
- Scheduled Messages

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Textmagic Sender IDs and Numbers API

Apply for and manage alphanumeric sender IDs, find and purchase dedicated virtual numbers, and configure sender settings and available sources.

- **Human URL:** [https://docs.textmagic.com/](https://docs.textmagic.com/)
- **Base URL:** `https://rest.textmagic.com/api/v2`

#### Tags

- Sender IDs
- Dedicated Numbers
- Sender Settings

#### Properties

- [Documentation](https://docs.textmagic.com/)
- [API Reference](https://docs.textmagic.com/)
- [OpenAPI](openapi/textmagic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/textmagic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/textmagic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/textmagic)
- [LinkedIn](https://www.linkedin.com/company/textmagic)
- [Website](https://www.textmagic.com)
- [Documentation](https://docs.textmagic.com/)
- [Plans](plans/textmagic-plans-pricing.yml)
- [Rate Limits](rate-limits/textmagic-rate-limits.yml)
- [Fin Ops](finops/textmagic-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
