# Workday Payroll (workday-payroll)

Workday Payroll provides comprehensive APIs for managing payroll operations, employee compensation, tax calculations, and payment processing within the Workday platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/workday-payroll/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Compensation, Enterprise, Human Resources, Payroll, SaaS, Tax

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-03

## APIs

### Workday Payroll API
Core API for managing payroll processes including payroll calculations, employee pay data, deductions, earnings, and payroll runs.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll/v1`

#### Tags:

 - Compensation, Deductions, Earnings, Pay-Runs, Payroll

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-openapi.yml)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)
- [APIConsole](https://community.workday.com/api-console)
- [RateLimits](https://doc.workday.com/admin-guide/en-us/api-reference/api-rate-limiting.html)
- [Example](examples/workday-payroll-list-pay-runs-example.json)
- [NaftikoCapability](capabilities/shared/payroll.yaml)

### Workday Payroll Results API
API for retrieving payroll calculation results, payment details, and historical payroll data.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll-results/v1`

#### Tags:

 - History, Payments, Payroll-Results, Reporting

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-results-openapi.yml)
- [Example](examples/workday-payroll-get-worker-payslip-example.json)
- [NaftikoCapability](capabilities/shared/payroll-results.yaml)

### Workday Payroll Input API
API for submitting and managing payroll input data including one-time payments, adjustments, and supplemental earnings.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll-input/v1`

#### Tags:

 - Adjustments, One-Time-Payments, Payroll-Input, Supplemental-Earnings

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-input-openapi.yml)
- [Example](examples/workday-payroll-create-one-time-payment-example.json)
- [NaftikoCapability](capabilities/shared/payroll-input.yaml)

### Workday Tax API
API for managing payroll tax calculations, tax withholdings, and tax filing information.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/tax/v1`

#### Tags:

 - Compliance, Tax, Tax-Filing, Withholdings

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-tax-openapi.yml)
- [NaftikoCapability](capabilities/shared/payroll-tax.yaml)

## Common Properties

- [DeveloperPortal](https://community.workday.com/)
- [GettingStarted](https://doc.workday.com/developer/studio/en-us/getting-started.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)
- [TermsOfService](https://www.workday.com/en-us/legal.html)
- [PrivacyPolicy](https://www.workday.com/en-us/privacy.html)
- [StatusPage](https://status.workday.com/)
- [Security](https://www.workday.com/en-us/why-workday/security.html)
- [JSON-LD](json-ld/workday-payroll-context.jsonld)
- [JSONSchema](json-schema/workday-payroll-pay-run-schema.json)
- [JSONSchema](json-schema/workday-payroll-payslip-schema.json)
- [JSONStructure](json-structure/workday-payroll-pay-run-structure.json)
- [JSONStructure](json-structure/workday-payroll-payslip-structure.json)
- [SpectralRules](rules/workday-payroll-spectral-rules.yml)
- [NaftikoCapability](capabilities/payroll-processing.yaml)
- [Vocabulary](vocabulary/workday-payroll-vocabulary.yml)
- [Tools — Report-as-a-Service Python Client](https://github.com/Workday/raas-python)
- [Tools — Workday Everywhere SDK](https://github.com/Workday/everywhere)
- [Tools — Agent System of Record API](https://github.com/Workday/asor)

## Features

| Name | Description |
|------|-------------|
| Global Payroll Engine | Process payroll across multiple countries with configurable calculation logic, pay components, and statutory rules. |
| Pay Run Management | Create, schedule, and execute payroll runs with full visibility into calculation status and results. |
| Earnings and Deductions | Configure and apply earnings, deductions, accumulations, and balances per worker, organization, or pay group. |
| Tax Calculation and Withholding | Automated tax calculations and withholdings with support for federal, state, local, and international jurisdictions. |
| Payroll Input Processing | Submit one-time payments, retroactive adjustments, and supplemental earnings outside of scheduled pay runs. |
| Payslip Generation | Produce worker-facing payslips and pay statements with detailed breakdowns of earnings, deductions, and taxes. |
| Compliance Reporting | Generate statutory and compliance reports including tax filings, year-end forms, and audit trails. |
| Worker Self-Service | Surface pay history, payslips, and tax documents to workers via Workday Mobile and the Workday user experience. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Country Payroll Operations | Run payroll for a global workforce across regions while standardizing on a single platform and data model. |
| Payroll Cycle Automation | Schedule, execute, and audit recurring payroll runs end-to-end with minimal manual intervention. |
| One-Time Payments and Adjustments | Submit bonuses, retroactive pay, and corrections programmatically through the Payroll Input API. |
| Tax Filing and Compliance | Calculate withholdings and produce data feeds for statutory tax filings and year-end reporting. |
| Pay Data Integration | Sync payroll results into general ledger, banking, benefits, and analytics systems downstream of payroll runs. |
| Worker Pay Transparency | Provide workers with secure programmatic access to payslips, year-to-date totals, and tax forms. |

## Integrations

| Name | Description |
|------|-------------|
| Workday Human Capital Management | Integrated source of worker, organization, compensation, and time tracking data feeding payroll calculations. |
| Workday Financial Management | Posts payroll journal entries and accruals into the Workday general ledger. |
| Workday Time Tracking | Feeds approved time and absence data into payroll calculations. |
| Workday Benefits | Provides benefit elections and deductions consumed by payroll. |
| Workday Studio | Visual integration tool for building inbound and outbound payroll integrations. |
| Workday Cloud Connect for Third-Party Payroll | Pre-built integrations to third-party payroll providers and tax filing services. |
| Banking and Payment Networks | Generates ACH and international payment files for direct deposit and payroll disbursements. |

## Solutions

| Name | Description |
|------|-------------|
| Workday Payroll for the U.S. | Full-service payroll solution for U.S. employers including federal, state, and local tax calculation and filing support. |
| Workday Payroll for Canada | Payroll solution covering Canadian federal and provincial requirements. |
| Workday Payroll for the U.K. | U.K. payroll with HMRC reporting and statutory pay support. |
| Workday Payroll for France | French payroll covering DSN reporting and statutory rules. |
| Workday Cloud Connect for Third-Party Payroll | Connectors and data feeds for customers running payroll on a third-party provider while using Workday HCM. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Workday Payroll API](openapi/workday-payroll-payroll-openapi.yml)
- [Workday Payroll Results API](openapi/workday-payroll-payroll-results-openapi.yml)
- [Workday Payroll Input API](openapi/workday-payroll-payroll-input-openapi.yml)
- [Workday Tax API](openapi/workday-payroll-tax-openapi.yml)

### JSON Schema

**Workday Payroll API**

- [Calculation Status](json-schema/payroll-calculation-status-schema.json)
- [Create Pay Run Request](json-schema/payroll-create-pay-run-request-schema.json)
- [Deduction](json-schema/payroll-deduction-schema.json)
- [Deduction Code](json-schema/payroll-deduction-code-schema.json)
- [Deduction Code Collection](json-schema/payroll-deduction-code-collection-schema.json)
- [Deduction Code Ref](json-schema/payroll-deduction-code-ref-schema.json)
- [Deduction Collection](json-schema/payroll-deduction-collection-schema.json)
- [Earning](json-schema/payroll-earning-schema.json)
- [Earning Code](json-schema/payroll-earning-code-schema.json)
- [Earning Code Collection](json-schema/payroll-earning-code-collection-schema.json)
- [Earning Code Ref](json-schema/payroll-earning-code-ref-schema.json)
- [Earning Collection](json-schema/payroll-earning-collection-schema.json)
- [Pay Group](json-schema/payroll-pay-group-schema.json)
- [Pay Group Collection](json-schema/payroll-pay-group-collection-schema.json)
- [Pay Group Ref](json-schema/payroll-pay-group-ref-schema.json)
- [Pay Period](json-schema/payroll-pay-period-schema.json)
- [Pay Run](json-schema/payroll-pay-run-schema.json)
- [Pay Run Collection](json-schema/payroll-pay-run-collection-schema.json)
- [Update Pay Run Request](json-schema/payroll-update-pay-run-request-schema.json)
- [Worker Collection](json-schema/payroll-worker-collection-schema.json)
- [Worker Payroll Details](json-schema/payroll-worker-payroll-details-schema.json)
- [Worker Ref](json-schema/payroll-worker-ref-schema.json)

**Workday Payroll Input API**

- [Adjustment](json-schema/payroll-input-adjustment-schema.json)
- [Adjustment Collection](json-schema/payroll-input-adjustment-collection-schema.json)
- [Create Adjustment Request](json-schema/payroll-input-create-adjustment-request-schema.json)
- [Create Input Batch Request](json-schema/payroll-input-create-input-batch-request-schema.json)
- [Create One Time Payment Request](json-schema/payroll-input-create-one-time-payment-request-schema.json)
- [Create Supplemental Earning Request](json-schema/payroll-input-create-supplemental-earning-request-schema.json)
- [Create Time Off Input Request](json-schema/payroll-input-create-time-off-input-request-schema.json)
- [Input Batch](json-schema/payroll-input-input-batch-schema.json)
- [Input Batch Collection](json-schema/payroll-input-input-batch-collection-schema.json)
- [Input Record](json-schema/payroll-input-input-record-schema.json)
- [One Time Payment](json-schema/payroll-input-one-time-payment-schema.json)
- [One Time Payment Collection](json-schema/payroll-input-one-time-payment-collection-schema.json)
- [Supplemental Earning](json-schema/payroll-input-supplemental-earning-schema.json)
- [Supplemental Earning Collection](json-schema/payroll-input-supplemental-earning-collection-schema.json)
- [Time Off Input](json-schema/payroll-input-time-off-input-schema.json)
- [Time Off Input Collection](json-schema/payroll-input-time-off-input-collection-schema.json)
- [Update One Time Payment Request](json-schema/payroll-input-update-one-time-payment-request-schema.json)
- [Worker Ref](json-schema/payroll-input-worker-ref-schema.json)

**Workday Payroll Results API**

- [Pay Period](json-schema/payroll-results-pay-period-schema.json)
- [Pay Run Result](json-schema/payroll-results-pay-run-result-schema.json)
- [Payment](json-schema/payroll-results-payment-schema.json)
- [Payment Collection](json-schema/payroll-results-payment-collection-schema.json)
- [Payment Election](json-schema/payroll-results-payment-election-schema.json)
- [Payment Election Collection](json-schema/payroll-results-payment-election-collection-schema.json)
- [Payslip](json-schema/payroll-results-payslip-schema.json)
- [Payslip Collection](json-schema/payroll-results-payslip-collection-schema.json)
- [Payslip Deduction Line](json-schema/payroll-results-payslip-deduction-line-schema.json)
- [Payslip Earning Line](json-schema/payroll-results-payslip-earning-line-schema.json)
- [Payslip Tax Line](json-schema/payroll-results-payslip-tax-line-schema.json)
- [Worker Ref](json-schema/payroll-results-worker-ref-schema.json)
- [Worker Result](json-schema/payroll-results-worker-result-schema.json)
- [Worker Result Collection](json-schema/payroll-results-worker-result-collection-schema.json)

**Workday Tax API**

- [Create Tax Election Request](json-schema/tax-create-tax-election-request-schema.json)
- [Tax Election](json-schema/tax-tax-election-schema.json)
- [Tax Election Collection](json-schema/tax-tax-election-collection-schema.json)
- [Tax Filing](json-schema/tax-tax-filing-schema.json)
- [Tax Filing Collection](json-schema/tax-tax-filing-collection-schema.json)
- [Tax Jurisdiction](json-schema/tax-tax-jurisdiction-schema.json)
- [Tax Jurisdiction Collection](json-schema/tax-tax-jurisdiction-collection-schema.json)
- [Tax Jurisdiction Ref](json-schema/tax-tax-jurisdiction-ref-schema.json)
- [Tax Result](json-schema/tax-tax-result-schema.json)
- [Tax Result Collection](json-schema/tax-tax-result-collection-schema.json)
- [Tax Withholding](json-schema/tax-tax-withholding-schema.json)
- [Tax Withholding Collection](json-schema/tax-tax-withholding-collection-schema.json)
- [Update Tax Withholding Request](json-schema/tax-update-tax-withholding-request-schema.json)
- [Worker Ref](json-schema/tax-worker-ref-schema.json)
- [Worker Tax Summary](json-schema/tax-worker-tax-summary-schema.json)

**Cross-API**

- [Pay Run](json-schema/workday-payroll-pay-run-schema.json)
- [Payslip](json-schema/workday-payroll-payslip-schema.json)

### JSON Structure

**Workday Payroll API**

- [Calculation Status](json-structure/payroll-calculation-status-structure.json)
- [Create Pay Run Request](json-structure/payroll-create-pay-run-request-structure.json)
- [Deduction](json-structure/payroll-deduction-structure.json)
- [Deduction Code](json-structure/payroll-deduction-code-structure.json)
- [Deduction Code Collection](json-structure/payroll-deduction-code-collection-structure.json)
- [Deduction Code Ref](json-structure/payroll-deduction-code-ref-structure.json)
- [Deduction Collection](json-structure/payroll-deduction-collection-structure.json)
- [Earning](json-structure/payroll-earning-structure.json)
- [Earning Code](json-structure/payroll-earning-code-structure.json)
- [Earning Code Collection](json-structure/payroll-earning-code-collection-structure.json)
- [Earning Code Ref](json-structure/payroll-earning-code-ref-structure.json)
- [Earning Collection](json-structure/payroll-earning-collection-structure.json)
- [Pay Group](json-structure/payroll-pay-group-structure.json)
- [Pay Group Collection](json-structure/payroll-pay-group-collection-structure.json)
- [Pay Group Ref](json-structure/payroll-pay-group-ref-structure.json)
- [Pay Period](json-structure/payroll-pay-period-structure.json)
- [Pay Run](json-structure/payroll-pay-run-structure.json)
- [Pay Run Collection](json-structure/payroll-pay-run-collection-structure.json)
- [Update Pay Run Request](json-structure/payroll-update-pay-run-request-structure.json)
- [Worker Collection](json-structure/payroll-worker-collection-structure.json)
- [Worker Payroll Details](json-structure/payroll-worker-payroll-details-structure.json)
- [Worker Ref](json-structure/payroll-worker-ref-structure.json)

**Workday Payroll Input API**

- [Adjustment](json-structure/payroll-input-adjustment-structure.json)
- [Adjustment Collection](json-structure/payroll-input-adjustment-collection-structure.json)
- [Create Adjustment Request](json-structure/payroll-input-create-adjustment-request-structure.json)
- [Create Input Batch Request](json-structure/payroll-input-create-input-batch-request-structure.json)
- [Create One Time Payment Request](json-structure/payroll-input-create-one-time-payment-request-structure.json)
- [Create Supplemental Earning Request](json-structure/payroll-input-create-supplemental-earning-request-structure.json)
- [Create Time Off Input Request](json-structure/payroll-input-create-time-off-input-request-structure.json)
- [Input Batch](json-structure/payroll-input-input-batch-structure.json)
- [Input Batch Collection](json-structure/payroll-input-input-batch-collection-structure.json)
- [Input Record](json-structure/payroll-input-input-record-structure.json)
- [One Time Payment](json-structure/payroll-input-one-time-payment-structure.json)
- [One Time Payment Collection](json-structure/payroll-input-one-time-payment-collection-structure.json)
- [Supplemental Earning](json-structure/payroll-input-supplemental-earning-structure.json)
- [Supplemental Earning Collection](json-structure/payroll-input-supplemental-earning-collection-structure.json)
- [Time Off Input](json-structure/payroll-input-time-off-input-structure.json)
- [Time Off Input Collection](json-structure/payroll-input-time-off-input-collection-structure.json)
- [Update One Time Payment Request](json-structure/payroll-input-update-one-time-payment-request-structure.json)
- [Worker Ref](json-structure/payroll-input-worker-ref-structure.json)

**Workday Payroll Results API**

- [Pay Period](json-structure/payroll-results-pay-period-structure.json)
- [Pay Run Result](json-structure/payroll-results-pay-run-result-structure.json)
- [Payment](json-structure/payroll-results-payment-structure.json)
- [Payment Collection](json-structure/payroll-results-payment-collection-structure.json)
- [Payment Election](json-structure/payroll-results-payment-election-structure.json)
- [Payment Election Collection](json-structure/payroll-results-payment-election-collection-structure.json)
- [Payslip](json-structure/payroll-results-payslip-structure.json)
- [Payslip Collection](json-structure/payroll-results-payslip-collection-structure.json)
- [Payslip Deduction Line](json-structure/payroll-results-payslip-deduction-line-structure.json)
- [Payslip Earning Line](json-structure/payroll-results-payslip-earning-line-structure.json)
- [Payslip Tax Line](json-structure/payroll-results-payslip-tax-line-structure.json)
- [Worker Ref](json-structure/payroll-results-worker-ref-structure.json)
- [Worker Result](json-structure/payroll-results-worker-result-structure.json)
- [Worker Result Collection](json-structure/payroll-results-worker-result-collection-structure.json)

**Workday Tax API**

- [Create Tax Election Request](json-structure/tax-create-tax-election-request-structure.json)
- [Tax Election](json-structure/tax-tax-election-structure.json)
- [Tax Election Collection](json-structure/tax-tax-election-collection-structure.json)
- [Tax Filing](json-structure/tax-tax-filing-structure.json)
- [Tax Filing Collection](json-structure/tax-tax-filing-collection-structure.json)
- [Tax Jurisdiction](json-structure/tax-tax-jurisdiction-structure.json)
- [Tax Jurisdiction Collection](json-structure/tax-tax-jurisdiction-collection-structure.json)
- [Tax Jurisdiction Ref](json-structure/tax-tax-jurisdiction-ref-structure.json)
- [Tax Result](json-structure/tax-tax-result-structure.json)
- [Tax Result Collection](json-structure/tax-tax-result-collection-structure.json)
- [Tax Withholding](json-structure/tax-tax-withholding-structure.json)
- [Tax Withholding Collection](json-structure/tax-tax-withholding-collection-structure.json)
- [Update Tax Withholding Request](json-structure/tax-update-tax-withholding-request-structure.json)
- [Worker Ref](json-structure/tax-worker-ref-structure.json)
- [Worker Tax Summary](json-structure/tax-worker-tax-summary-structure.json)

**Cross-API**

- [Pay Run](json-structure/workday-payroll-pay-run-structure.json)
- [Payslip](json-structure/workday-payroll-payslip-structure.json)

### JSON-LD

- [Workday Payroll Context](json-ld/workday-payroll-context.jsonld)
- [Workday Payroll API Context](json-ld/workday-payroll-payroll-context.jsonld)
- [Workday Payroll Input API Context](json-ld/workday-payroll-payroll-input-context.jsonld)
- [Workday Payroll Results API Context](json-ld/workday-payroll-payroll-results-context.jsonld)
- [Workday Tax API Context](json-ld/workday-payroll-tax-context.jsonld)

### Examples

**Workday Payroll API**

- [Calculation Status](examples/payroll-calculation-status-example.json)
- [Create Pay Run Request](examples/payroll-create-pay-run-request-example.json)
- [Deduction](examples/payroll-deduction-example.json)
- [Deduction Code](examples/payroll-deduction-code-example.json)
- [Deduction Code Collection](examples/payroll-deduction-code-collection-example.json)
- [Deduction Code Ref](examples/payroll-deduction-code-ref-example.json)
- [Deduction Collection](examples/payroll-deduction-collection-example.json)
- [Earning](examples/payroll-earning-example.json)
- [Earning Code](examples/payroll-earning-code-example.json)
- [Earning Code Collection](examples/payroll-earning-code-collection-example.json)
- [Earning Code Ref](examples/payroll-earning-code-ref-example.json)
- [Earning Collection](examples/payroll-earning-collection-example.json)
- [Pay Group](examples/payroll-pay-group-example.json)
- [Pay Group Collection](examples/payroll-pay-group-collection-example.json)
- [Pay Group Ref](examples/payroll-pay-group-ref-example.json)
- [Pay Period](examples/payroll-pay-period-example.json)
- [Pay Run](examples/payroll-pay-run-example.json)
- [Pay Run Collection](examples/payroll-pay-run-collection-example.json)
- [Update Pay Run Request](examples/payroll-update-pay-run-request-example.json)
- [Worker Collection](examples/payroll-worker-collection-example.json)
- [Worker Payroll Details](examples/payroll-worker-payroll-details-example.json)
- [Worker Ref](examples/payroll-worker-ref-example.json)

**Workday Payroll Input API**

- [Adjustment](examples/payroll-input-adjustment-example.json)
- [Adjustment Collection](examples/payroll-input-adjustment-collection-example.json)
- [Create Adjustment Request](examples/payroll-input-create-adjustment-request-example.json)
- [Create Input Batch Request](examples/payroll-input-create-input-batch-request-example.json)
- [Create One Time Payment Request](examples/payroll-input-create-one-time-payment-request-example.json)
- [Create Supplemental Earning Request](examples/payroll-input-create-supplemental-earning-request-example.json)
- [Create Time Off Input Request](examples/payroll-input-create-time-off-input-request-example.json)
- [Input Batch](examples/payroll-input-input-batch-example.json)
- [Input Batch Collection](examples/payroll-input-input-batch-collection-example.json)
- [Input Record](examples/payroll-input-input-record-example.json)
- [One Time Payment](examples/payroll-input-one-time-payment-example.json)
- [One Time Payment Collection](examples/payroll-input-one-time-payment-collection-example.json)
- [Supplemental Earning](examples/payroll-input-supplemental-earning-example.json)
- [Supplemental Earning Collection](examples/payroll-input-supplemental-earning-collection-example.json)
- [Time Off Input](examples/payroll-input-time-off-input-example.json)
- [Time Off Input Collection](examples/payroll-input-time-off-input-collection-example.json)
- [Update One Time Payment Request](examples/payroll-input-update-one-time-payment-request-example.json)
- [Worker Ref](examples/payroll-input-worker-ref-example.json)

**Workday Payroll Results API**

- [Pay Period](examples/payroll-results-pay-period-example.json)
- [Pay Run Result](examples/payroll-results-pay-run-result-example.json)
- [Payment](examples/payroll-results-payment-example.json)
- [Payment Collection](examples/payroll-results-payment-collection-example.json)
- [Payment Election](examples/payroll-results-payment-election-example.json)
- [Payment Election Collection](examples/payroll-results-payment-election-collection-example.json)
- [Payslip](examples/payroll-results-payslip-example.json)
- [Payslip Collection](examples/payroll-results-payslip-collection-example.json)
- [Payslip Deduction Line](examples/payroll-results-payslip-deduction-line-example.json)
- [Payslip Earning Line](examples/payroll-results-payslip-earning-line-example.json)
- [Payslip Tax Line](examples/payroll-results-payslip-tax-line-example.json)
- [Worker Ref](examples/payroll-results-worker-ref-example.json)
- [Worker Result](examples/payroll-results-worker-result-example.json)
- [Worker Result Collection](examples/payroll-results-worker-result-collection-example.json)

**Workday Tax API**

- [Create Tax Election Request](examples/tax-create-tax-election-request-example.json)
- [Tax Election](examples/tax-tax-election-example.json)
- [Tax Election Collection](examples/tax-tax-election-collection-example.json)
- [Tax Filing](examples/tax-tax-filing-example.json)
- [Tax Filing Collection](examples/tax-tax-filing-collection-example.json)
- [Tax Jurisdiction](examples/tax-tax-jurisdiction-example.json)
- [Tax Jurisdiction Collection](examples/tax-tax-jurisdiction-collection-example.json)
- [Tax Jurisdiction Ref](examples/tax-tax-jurisdiction-ref-example.json)
- [Tax Result](examples/tax-tax-result-example.json)
- [Tax Result Collection](examples/tax-tax-result-collection-example.json)
- [Tax Withholding](examples/tax-tax-withholding-example.json)
- [Tax Withholding Collection](examples/tax-tax-withholding-collection-example.json)
- [Update Tax Withholding Request](examples/tax-update-tax-withholding-request-example.json)
- [Worker Ref](examples/tax-worker-ref-example.json)
- [Worker Tax Summary](examples/tax-worker-tax-summary-example.json)

**Cross-API**

- [Pay Run](examples/workday-payroll-pay-run-example.json)
- [Payslip](examples/workday-payroll-payslip-example.json)

**Operation Examples**

- [List Pay Runs](examples/workday-payroll-list-pay-runs-example.json)
- [Get Worker Payslip](examples/workday-payroll-get-worker-payslip-example.json)
- [Create One-Time Payment](examples/workday-payroll-create-one-time-payment-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Workday Payroll API](capabilities/shared/payroll.yaml) — 14 operations for payroll runs, pay groups, workers, earnings, and deductions
- [Workday Payroll Results API](capabilities/shared/payroll-results.yaml) — 8 operations for payroll calculation results, payslips, and payment history
- [Workday Payroll Input API](capabilities/shared/payroll-input.yaml) — 17 operations for one-time payments, adjustments, supplemental earnings, batches, and time-off inputs
- [Workday Tax API](capabilities/shared/payroll-tax.yaml) — 12 operations for tax withholdings, elections, jurisdictions, filings, and pay-run tax results

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Payroll Processing](capabilities/payroll-processing.yaml) | Payroll, Payroll Results, Payroll Input, Tax | 51 | HR Administrator / Payroll Specialist |

## Vocabulary

- [Workday Payroll Vocabulary](vocabulary/workday-payroll-vocabulary.yml) — Unified taxonomy mapping 24 resources, 7 actions, 5 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Workday Payroll Spectral Rules](rules/workday-payroll-spectral-rules.yml) — 63 rules across 13 categories enforcing Workday Payroll API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
