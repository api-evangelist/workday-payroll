# Workday Payroll (workday-payroll)

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

Workday Payroll provides comprehensive APIs for managing payroll operations, employee compensation, tax calculations, and payment processing within the Workday platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml)

## Tags

- Compensation
- Enterprise
- Human Resources
- Payroll
- SaaS
- Tax

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Workday Payroll API

Core API for managing payroll processes including payroll calculations, employee pay data, deductions, earnings, and payroll runs.

- **Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)
- **Base URL:** `https://api.workday.com/payroll/v1`

#### Tags

- Compensation
- Deductions
- Earnings
- Pay-Runs
- Payroll

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-payroll-payroll.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-payroll-payroll.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)
- [A P I Console](https://community.workday.com/api-console)
- [Rate Limits](https://doc.workday.com/admin-guide/en-us/api-reference/api-rate-limiting.html)
- [JSON-LD](json-ld/workday-payroll-payroll-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/payroll-calculation-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-create-pay-run-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-deduction-code-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-deduction-code-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-deduction-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-deduction-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-deduction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-earning-code-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-earning-code-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-earning-code-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-earning-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-earning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-group-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-group-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-period-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-run-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-pay-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-update-pay-run-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-worker-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-worker-payroll-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-worker-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/payroll-calculation-status-structure.json)
- [JSON Structure](json-structure/payroll-create-pay-run-request-structure.json)
- [JSON Structure](json-structure/payroll-deduction-code-collection-structure.json)
- [JSON Structure](json-structure/payroll-deduction-code-ref-structure.json)
- [JSON Structure](json-structure/payroll-deduction-code-structure.json)
- [JSON Structure](json-structure/payroll-deduction-collection-structure.json)
- [JSON Structure](json-structure/payroll-deduction-structure.json)
- [JSON Structure](json-structure/payroll-earning-code-collection-structure.json)
- [JSON Structure](json-structure/payroll-earning-code-ref-structure.json)
- [JSON Structure](json-structure/payroll-earning-code-structure.json)
- [JSON Structure](json-structure/payroll-earning-collection-structure.json)
- [JSON Structure](json-structure/payroll-earning-structure.json)
- [JSON Structure](json-structure/payroll-pay-group-collection-structure.json)
- [JSON Structure](json-structure/payroll-pay-group-ref-structure.json)
- [JSON Structure](json-structure/payroll-pay-group-structure.json)
- [JSON Structure](json-structure/payroll-pay-period-structure.json)
- [JSON Structure](json-structure/payroll-pay-run-collection-structure.json)
- [JSON Structure](json-structure/payroll-pay-run-structure.json)
- [JSON Structure](json-structure/payroll-update-pay-run-request-structure.json)
- [JSON Structure](json-structure/payroll-worker-collection-structure.json)
- [JSON Structure](json-structure/payroll-worker-payroll-details-structure.json)
- [JSON Structure](json-structure/payroll-worker-ref-structure.json)
- [Example](examples/payroll-calculation-status-example.json)
- [Example](examples/payroll-create-pay-run-request-example.json)
- [Example](examples/payroll-deduction-code-collection-example.json)
- [Example](examples/payroll-deduction-code-example.json)
- [Example](examples/payroll-deduction-code-ref-example.json)
- [Example](examples/payroll-deduction-collection-example.json)
- [Example](examples/payroll-deduction-example.json)
- [Example](examples/payroll-earning-code-collection-example.json)
- [Example](examples/payroll-earning-code-example.json)
- [Example](examples/payroll-earning-code-ref-example.json)
- [Example](examples/payroll-earning-collection-example.json)
- [Example](examples/payroll-earning-example.json)
- [Example](examples/payroll-pay-group-collection-example.json)
- [Example](examples/payroll-pay-group-example.json)
- [Example](examples/payroll-pay-group-ref-example.json)
- [Example](examples/payroll-pay-period-example.json)
- [Example](examples/payroll-pay-run-collection-example.json)
- [Example](examples/payroll-pay-run-example.json)
- [Example](examples/payroll-update-pay-run-request-example.json)
- [Example](examples/payroll-worker-collection-example.json)
- [Example](examples/payroll-worker-payroll-details-example.json)
- [Example](examples/payroll-worker-ref-example.json)
- [Example](examples/workday-payroll-list-pay-runs-example.json)

### Workday Payroll Results API

API for retrieving payroll calculation results, payment details, and historical payroll data.

- **Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)
- **Base URL:** `https://api.workday.com/payroll-results/v1`

#### Tags

- History
- Payments
- Payroll-Results
- Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-results-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-payroll-payroll-results.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-payroll-payroll-results.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/workday-payroll-payroll-results-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/payroll-results-pay-period-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-pay-run-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payment-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payment-election-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payment-election-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payslip-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payslip-deduction-line-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payslip-earning-line-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payslip-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-payslip-tax-line-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-worker-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-worker-result-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-results-worker-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/payroll-results-pay-period-structure.json)
- [JSON Structure](json-structure/payroll-results-pay-run-result-structure.json)
- [JSON Structure](json-structure/payroll-results-payment-collection-structure.json)
- [JSON Structure](json-structure/payroll-results-payment-election-collection-structure.json)
- [JSON Structure](json-structure/payroll-results-payment-election-structure.json)
- [JSON Structure](json-structure/payroll-results-payment-structure.json)
- [JSON Structure](json-structure/payroll-results-payslip-collection-structure.json)
- [JSON Structure](json-structure/payroll-results-payslip-deduction-line-structure.json)
- [JSON Structure](json-structure/payroll-results-payslip-earning-line-structure.json)
- [JSON Structure](json-structure/payroll-results-payslip-structure.json)
- [JSON Structure](json-structure/payroll-results-payslip-tax-line-structure.json)
- [JSON Structure](json-structure/payroll-results-worker-ref-structure.json)
- [JSON Structure](json-structure/payroll-results-worker-result-collection-structure.json)
- [JSON Structure](json-structure/payroll-results-worker-result-structure.json)
- [Example](examples/payroll-results-pay-period-example.json)
- [Example](examples/payroll-results-pay-run-result-example.json)
- [Example](examples/payroll-results-payment-collection-example.json)
- [Example](examples/payroll-results-payment-election-collection-example.json)
- [Example](examples/payroll-results-payment-election-example.json)
- [Example](examples/payroll-results-payment-example.json)
- [Example](examples/payroll-results-payslip-collection-example.json)
- [Example](examples/payroll-results-payslip-deduction-line-example.json)
- [Example](examples/payroll-results-payslip-earning-line-example.json)
- [Example](examples/payroll-results-payslip-example.json)
- [Example](examples/payroll-results-payslip-tax-line-example.json)
- [Example](examples/payroll-results-worker-ref-example.json)
- [Example](examples/payroll-results-worker-result-collection-example.json)
- [Example](examples/payroll-results-worker-result-example.json)
- [Example](examples/workday-payroll-get-worker-payslip-example.json)

### Workday Payroll Input API

API for submitting and managing payroll input data including one-time payments, adjustments, and supplemental earnings.

- **Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)
- **Base URL:** `https://api.workday.com/payroll-input/v1`

#### Tags

- Adjustments
- One-Time-Payments
- Payroll-Input
- Supplemental-Earnings

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-input-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-payroll-payroll-input.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-payroll-payroll-input.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/workday-payroll-payroll-input-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/payroll-input-adjustment-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-adjustment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-create-adjustment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-create-input-batch-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-create-one-time-payment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-create-supplemental-earning-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-create-time-off-input-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-input-batch-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-input-batch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-input-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-one-time-payment-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-one-time-payment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-supplemental-earning-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-supplemental-earning-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-time-off-input-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-time-off-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-update-one-time-payment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/payroll-input-worker-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/payroll-input-adjustment-collection-structure.json)
- [JSON Structure](json-structure/payroll-input-adjustment-structure.json)
- [JSON Structure](json-structure/payroll-input-create-adjustment-request-structure.json)
- [JSON Structure](json-structure/payroll-input-create-input-batch-request-structure.json)
- [JSON Structure](json-structure/payroll-input-create-one-time-payment-request-structure.json)
- [JSON Structure](json-structure/payroll-input-create-supplemental-earning-request-structure.json)
- [JSON Structure](json-structure/payroll-input-create-time-off-input-request-structure.json)
- [JSON Structure](json-structure/payroll-input-input-batch-collection-structure.json)
- [JSON Structure](json-structure/payroll-input-input-batch-structure.json)
- [JSON Structure](json-structure/payroll-input-input-record-structure.json)
- [JSON Structure](json-structure/payroll-input-one-time-payment-collection-structure.json)
- [JSON Structure](json-structure/payroll-input-one-time-payment-structure.json)
- [JSON Structure](json-structure/payroll-input-supplemental-earning-collection-structure.json)
- [JSON Structure](json-structure/payroll-input-supplemental-earning-structure.json)
- [JSON Structure](json-structure/payroll-input-time-off-input-collection-structure.json)
- [JSON Structure](json-structure/payroll-input-time-off-input-structure.json)
- [JSON Structure](json-structure/payroll-input-update-one-time-payment-request-structure.json)
- [JSON Structure](json-structure/payroll-input-worker-ref-structure.json)
- [Example](examples/payroll-input-adjustment-collection-example.json)
- [Example](examples/payroll-input-adjustment-example.json)
- [Example](examples/payroll-input-create-adjustment-request-example.json)
- [Example](examples/payroll-input-create-input-batch-request-example.json)
- [Example](examples/payroll-input-create-one-time-payment-request-example.json)
- [Example](examples/payroll-input-create-supplemental-earning-request-example.json)
- [Example](examples/payroll-input-create-time-off-input-request-example.json)
- [Example](examples/payroll-input-input-batch-collection-example.json)
- [Example](examples/payroll-input-input-batch-example.json)
- [Example](examples/payroll-input-input-record-example.json)
- [Example](examples/payroll-input-one-time-payment-collection-example.json)
- [Example](examples/payroll-input-one-time-payment-example.json)
- [Example](examples/payroll-input-supplemental-earning-collection-example.json)
- [Example](examples/payroll-input-supplemental-earning-example.json)
- [Example](examples/payroll-input-time-off-input-collection-example.json)
- [Example](examples/payroll-input-time-off-input-example.json)
- [Example](examples/payroll-input-update-one-time-payment-request-example.json)
- [Example](examples/payroll-input-worker-ref-example.json)
- [Example](examples/workday-payroll-create-one-time-payment-example.json)

### Workday Tax API

API for managing payroll tax calculations, tax withholdings, and tax filing information.

- **Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)
- **Base URL:** `https://api.workday.com/tax/v1`

#### Tags

- Compliance
- Tax
- Tax-Filing
- Withholdings

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-tax-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-payroll-tax.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-payroll-tax.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/workday-payroll-tax-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tax-create-tax-election-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-election-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-election-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-filing-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-filing-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-jurisdiction-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-jurisdiction-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-jurisdiction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-result-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-withholding-collection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-tax-withholding-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-update-tax-withholding-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-worker-ref-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tax-worker-tax-summary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tax-create-tax-election-request-structure.json)
- [JSON Structure](json-structure/tax-tax-election-collection-structure.json)
- [JSON Structure](json-structure/tax-tax-election-structure.json)
- [JSON Structure](json-structure/tax-tax-filing-collection-structure.json)
- [JSON Structure](json-structure/tax-tax-filing-structure.json)
- [JSON Structure](json-structure/tax-tax-jurisdiction-collection-structure.json)
- [JSON Structure](json-structure/tax-tax-jurisdiction-ref-structure.json)
- [JSON Structure](json-structure/tax-tax-jurisdiction-structure.json)
- [JSON Structure](json-structure/tax-tax-result-collection-structure.json)
- [JSON Structure](json-structure/tax-tax-result-structure.json)
- [JSON Structure](json-structure/tax-tax-withholding-collection-structure.json)
- [JSON Structure](json-structure/tax-tax-withholding-structure.json)
- [JSON Structure](json-structure/tax-update-tax-withholding-request-structure.json)
- [JSON Structure](json-structure/tax-worker-ref-structure.json)
- [JSON Structure](json-structure/tax-worker-tax-summary-structure.json)
- [Example](examples/tax-create-tax-election-request-example.json)
- [Example](examples/tax-tax-election-collection-example.json)
- [Example](examples/tax-tax-election-example.json)
- [Example](examples/tax-tax-filing-collection-example.json)
- [Example](examples/tax-tax-filing-example.json)
- [Example](examples/tax-tax-jurisdiction-collection-example.json)
- [Example](examples/tax-tax-jurisdiction-example.json)
- [Example](examples/tax-tax-jurisdiction-ref-example.json)
- [Example](examples/tax-tax-result-collection-example.json)
- [Example](examples/tax-tax-result-example.json)
- [Example](examples/tax-tax-withholding-collection-example.json)
- [Example](examples/tax-tax-withholding-example.json)
- [Example](examples/tax-update-tax-withholding-request-example.json)
- [Example](examples/tax-worker-ref-example.json)
- [Example](examples/tax-worker-tax-summary-example.json)

## Common Properties

- [Developer Portal](https://community.workday.com/)
- [Getting Started](https://doc.workday.com/developer/studio/en-us/getting-started.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Status Page](https://status.workday.com/)
- [Security](https://www.workday.com/en-us/why-workday/security.html)
- [JSON-LD](json-ld/workday-payroll-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/workday-payroll-pay-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-payroll-payslip-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/workday-payroll-pay-run-structure.json)
- [JSON Structure](json-structure/workday-payroll-payslip-structure.json)
- [Example](examples/workday-payroll-pay-run-example.json)
- [Example](examples/workday-payroll-payslip-example.json)
- [Spectral Rules](rules/workday-payroll-spectral-rules.yml)
- [Vocabulary](vocabulary/workday-payroll-vocabulary.yml)
- [Tools](https://github.com/Workday/raas-python)
- [Tools](https://github.com/Workday/everywhere)
- [Tools](https://github.com/Workday/asor)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
