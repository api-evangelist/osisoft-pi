# osisoft-pi (osisoft-pi)

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

OSIsoft PI System is a real-time data management platform used by industrial organizations to capture, analyze, and visualize operational data from sensors, devices, and applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### OSIsoft PI Web API

OSIsoft PI Web API (now part of AVEVA) provides a REST interface for accessing the PI System process historian. APIs enable real-time and historical time-series data retrieval, event frame queries, asset framework hierarchy navigation, and calculated data for industrial process monitoring.

- **Human URL:** [https://docs.aveva.com/bundle/pi-web-api-reference](https://docs.aveva.com/bundle/pi-web-api-reference)
- **Base URL:** `https://piwebapi.example.com/piwebapi`

#### Tags

- Energy
- Manufacturing
- Process Historian
- REST
- SCADA
- Time Series

#### Properties

- [Documentation](https://docs.aveva.com/bundle/pi-web-api-reference)
- [Reference](https://docs.aveva.com/bundle/pi-web-api-reference)
- [Getting Started](https://docs.aveva.com/bundle/pi-web-api-getting-started)
- [S D Ks](https://github.com/aveva/sample-pi_web_api-common_actions-python)
- [S D Ks](https://github.com/aveva/sample-pi_web_api-common_actions-angular)
- [OpenAPI](openapi/osisoft-pi-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/osisoft-pi-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osisoft-pi-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AVEVA CONNECT Data Services API

AVEVA CONNECT (formerly AVEVA Data Hub / OSIsoft Cloud Services) provides cloud-native REST APIs for industrial time-series data management, data views, event data, and secure cloud-based data sharing across operational technology environments.

- **Human URL:** [https://docs.aveva.com/bundle/aveva-data-hub-api-reference](https://docs.aveva.com/bundle/aveva-data-hub-api-reference)
- **Base URL:** `https://api.aveva.com`

#### Tags

- Cloud
- IoT
- Manufacturing
- REST
- Time Series

#### Properties

- [Documentation](https://docs.aveva.com/bundle/aveva-data-hub-api-reference)
- [Postman Collection](collections/osisoft-pi-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osisoft-pi-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OSIsoft PI AF SDK

OSIsoft PI Asset Framework SDK (AF SDK) is a .NET client library for programmatic access to the PI System asset hierarchy, time-series data, and event frames from on-premises PI servers.

- **Human URL:** [https://docs.aveva.com/](https://docs.aveva.com/)
- **Base URL:** `https://piwebapi.example.com/piwebapi`

#### Tags

- .NET
- Asset Framework
- Manufacturing
- SDK

#### Properties

- [Documentation](https://docs.aveva.com/)
- [S D Ks](https://github.com/aveva/sample-afsdk-getting_started-dotnet)
- [Postman Collection](collections/osisoft-pi-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osisoft-pi-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/osisoft)
- [Portal](https://docs.aveva.com/)
- [Documentation](https://docs.aveva.com/)
- [Getting Started](https://docs.aveva.com/bundle/pi-web-api-getting-started)
- [Website](https://www.aveva.com/)
- [Support](https://softwaresupport.aveva.com/)
- [Support](https://community.aveva.com/)
- [Documentation](https://learningacademy.aveva.com/)
- [GitHub Organization](https://github.com/aveva)
- [S D Ks](https://github.com/aveva)
- [OpenAPI](openapi/osisoft-pi-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/osisoft-pi-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/osisoft-pi-timed-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/osisoft-pi-context.jsonld)

## Maintainers

**Email:** kin@apievangelist.com
