# Workday Payroll (workday-payroll)

Workday Payroll provides comprehensive APIs for managing payroll operations, employee compensation, tax calculations, and payment processing within the Workday platform.

**Tags:** Compensation, Enterprise, Human Resources, Payroll, SaaS, Tax

**Modified:** 2026-05-03

## APIs

### Workday Payroll API
Core API for managing payroll processes including payroll calculations, employee pay data, deductions, earnings, and payroll runs.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll/v1`

**Tags:** Compensation, Deductions, Earnings, Pay Runs, Payroll

#### Properties
- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-openapi.yml)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)

### Workday Payroll Results API
API for retrieving payroll calculation results, payment details, payslip data, and historical payroll information.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll-results/v1`

**Tags:** History, Payments, Payroll Results, Reporting

#### Properties
- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-results-openapi.yml)

### Workday Payroll Input API
API for submitting and managing payroll input data including one-time payments, adjustments, supplemental earnings, and batch submissions.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/payroll-input/v1`

**Tags:** Adjustments, One-Time Payments, Payroll Input, Supplemental Earnings

#### Properties
- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-payroll-input-openapi.yml)

### Workday Tax API
API for managing payroll tax calculations, tax withholdings, W-4 elections, and tax filing information.

**Human URL:** [https://www.workday.com/en-us/products/payroll-management.html](https://www.workday.com/en-us/products/payroll-management.html)

**Base URL:** `https://api.workday.com/tax/v1`

**Tags:** Compliance, Tax, Tax Filing, Withholdings

#### Properties
- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [OpenAPI](openapi/workday-payroll-tax-openapi.yml)

## Common Properties

- [Developer Portal](https://community.workday.com/)
- [Getting Started](https://doc.workday.com/developer/studio/en-us/getting-started.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/authentication/authentication.html)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Status](https://status.workday.com/)
- [Security](https://www.workday.com/en-us/why-workday/security.html)

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|---|---|
| [workday-payroll-payroll-openapi.yml](openapi/workday-payroll-payroll-openapi.yml) | Core payroll management: pay runs, pay groups, worker earnings/deductions |
| [workday-payroll-payroll-results-openapi.yml](openapi/workday-payroll-payroll-results-openapi.yml) | Payroll results: payslips, payments, payment elections |
| [workday-payroll-payroll-input-openapi.yml](openapi/workday-payroll-payroll-input-openapi.yml) | Payroll inputs: one-time payments, adjustments, supplemental earnings, batches |
| [workday-payroll-tax-openapi.yml](openapi/workday-payroll-tax-openapi.yml) | Tax withholdings, elections, calculations, and filings |

### JSON Schemas
| Schema | Description |
|---|---|
| [workday-payroll-pay-run-schema.json](json-schema/workday-payroll-pay-run-schema.json) | JSON Schema for PayRun objects |
| [workday-payroll-payslip-schema.json](json-schema/workday-payroll-payslip-schema.json) | JSON Schema for Payslip objects |

### JSON Structures
| Structure | Description |
|---|---|
| [workday-payroll-pay-run-structure.json](json-structure/workday-payroll-pay-run-structure.json) | Documented structure for PayRun |
| [workday-payroll-payslip-structure.json](json-structure/workday-payroll-payslip-structure.json) | Documented structure for Payslip |

### JSON-LD
| Context | Description |
|---|---|
| [workday-payroll-context.jsonld](json-ld/workday-payroll-context.jsonld) | Linked data context for Workday Payroll entities |

### Examples
| Example | Description |
|---|---|
| [workday-payroll-list-pay-runs-example.json](examples/workday-payroll-list-pay-runs-example.json) | List pay runs with filters |
| [workday-payroll-get-worker-payslip-example.json](examples/workday-payroll-get-worker-payslip-example.json) | Get a detailed worker payslip |
| [workday-payroll-create-one-time-payment-example.json](examples/workday-payroll-create-one-time-payment-example.json) | Submit a one-time bonus payment |

### Spectral Rules
| Ruleset | Description |
|---|---|
| [workday-payroll-rules.yml](rules/workday-payroll-rules.yml) | Spectral rules enforcing Workday Payroll API conventions |

### Naftiko Capabilities
| Capability | Description |
|---|---|
| [payroll-processing.yaml](capabilities/payroll-processing.yaml) | Unified payroll processing workflow combining all 4 payroll APIs |

**Shared Definitions:**
- [payroll.yaml](capabilities/shared/payroll.yaml) — Core payroll API
- [payroll-results.yaml](capabilities/shared/payroll-results.yaml) — Payroll results API
- [payroll-input.yaml](capabilities/shared/payroll-input.yaml) — Payroll input API
- [payroll-tax.yaml](capabilities/shared/payroll-tax.yaml) — Tax API

### Vocabulary
| Vocabulary | Description |
|---|---|
| [workday-payroll-vocabulary.yml](vocabulary/workday-payroll-vocabulary.yml) | Payroll domain vocabulary covering compensation, deductions, tax, and payments |

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
