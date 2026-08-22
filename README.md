# Vimeo (vimeo)

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

Vimeo is a video hosting, creation, and streaming platform for creators, businesses, and enterprises that provides ad-free video hosting, live streaming, video editing, analytics, and OTT distribution. The Vimeo REST API enables programmatic upload, management, embedding, and analytics of videos, albums, channels, groups, and users using Bearer token (OAuth 2.0) authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vimeo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vimeo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Video
- Streaming
- Video Hosting
- Live Streaming
- Media
- OTT

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Vimeo API

REST API for uploading, managing, and streaming videos along with albums, channels, groups, users, comments, captions, live events, and analytics. Authentication uses OAuth 2.0 Bearer tokens.

- **Human URL:** [https://developer.vimeo.com/api/reference](https://developer.vimeo.com/api/reference)
- **Base URL:** `https://api.vimeo.com`

#### Tags

- Video
- Upload
- Streaming
- Live Events
- Channels
- Analytics

#### Properties

- [Documentation](https://developer.vimeo.com/api/reference)
- [Getting Started](https://developer.vimeo.com/api/guides/start)
- [Authentication](https://developer.vimeo.com/api/authentication)
- [OpenAPI](https://github.com/vimeo/openapi/blob/master/api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I  Source](https://github.com/vimeo/openapi)
- [Postman Collection](collections/vimeo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vimeo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vimeo Webhooks

AsyncAPI 2.6 specification for Vimeo's documented webhook surface, covering the Vimeo OTT customer and subscription lifecycle topics (customer.created, customer.product.renewed, customer.tvod.created, and related events) delivered via HTTPS POST to a subscriber URL. Vimeo's standard API webhooks (App Webhooks) are configured per API app from the developer dashboard. Note: Vimeo's official documentation states the standard API does not currently emit a webhook on transcode completion; transcode status must be polled.

- **Human URL:** [https://help.vimeo.com/hc/en-us/articles/12427268063761-Supported-webhook-topics-and-what-they-indicate-on-Vimeo-OTT](https://help.vimeo.com/hc/en-us/articles/12427268063761-Supported-webhook-topics-and-what-they-indicate-on-Vimeo-OTT)
- **Base URL:** `https://api.vimeo.com`

#### Tags

- Webhooks
- Events
- OTT
- Subscriptions
- AsyncAPI

#### Properties

- [Documentation](https://help.vimeo.com/hc/en-us/articles/12427268063761-Supported-webhook-topics-and-what-they-indicate-on-Vimeo-OTT)
- [Payload  Reference](https://help.vimeo.com/hc/en-us/articles/12427295198609-Properties-of-a-webhook-payload-on-Vimeo-OTT)
- [Setup  Guide](https://help.vimeo.com/hc/en-us/articles/12427285998225-Create-a-Vimeo-OTT-webhook)
- [App  Webhook  Reference](https://developer.vimeo.com/api/reference/response/api-app-webhook)
- [Transcode  Status  Note](https://help.vimeo.com/hc/en-us/articles/12427776744593-Get-video-transcode-status-from-the-API)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/vimeo/refs/heads/main/openapi/vimeo-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/vimeo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vimeo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vimeo)
- [Website](https://vimeo.com)
- [Documentation](https://developer.vimeo.com/)
- [Developer  Portal](https://developer.vimeo.com/)
- [Sign Up](https://vimeo.com/join)
- [Pricing](https://vimeo.com/upgrade)
- [GitHub Organization](https://github.com/vimeo)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
