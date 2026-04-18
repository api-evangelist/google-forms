# Google Forms (google-forms)
The Google Forms API is a RESTful interface that lets you create and modify Google Forms programmatically, read form responses, set up watches for notifications on form changes and new responses, and integrate forms with external applications.

**URL:** [Visit APIs.json URL](https://developers.google.com/forms/api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Collection, Forms, Google, Google Workspace, Questionnaires, Responses, Surveys

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Google Forms API v1
Create and modify Google Forms, read form responses and structure, set up watches for change notifications, and integrate forms with external applications via Cloud Pub/Sub.

**Human URL:** [https://developers.google.com/forms/api](https://developers.google.com/forms/api)

#### Tags:

 - Forms, Google, Questionnaires, Responses, Surveys, Watches

#### Properties

- [Documentation](https://developers.google.com/forms/api/reference/rest)
- [OpenAPI](openapi/google-forms-api.yaml)
- [JSONSchema](json-schema/google-forms-api-form-schema.json)
- [JSONSchema](json-schema/google-forms-api-form-response-schema.json)
- [JSONSchema](json-schema/google-forms-api-watch-schema.json)
- [JSONSchema](json-schema/google-forms-api-question-schema.json)
- [JSONStructure](json-structure/google-forms-api-form-structure.json)
- [JSONStructure](json-structure/google-forms-api-form-response-structure.json)
- [JSONStructure](json-structure/google-forms-api-watch-structure.json)
- [JSONStructure](json-structure/google-forms-api-question-structure.json)
- [Example](examples/google-forms-api-form-example.json)
- [Example](examples/google-forms-api-form-response-example.json)
- [Example](examples/google-forms-api-watch-example.json)
- [Example](examples/google-forms-api-question-example.json)
- [APIReference](https://developers.google.com/forms/api/reference/rest)
- [Quickstart](https://developers.google.com/forms/api/quickstart/python)
- [Authentication](https://developers.google.com/forms/api/guides/auth)

## Common Properties

- [Console](https://console.cloud.google.com/apis/library/forms.googleapis.com)
- [GettingStarted](https://developers.google.com/forms/api/guides)
- [Authentication](https://developers.google.com/identity/protocols/oauth2)
- [StatusPage](https://status.cloud.google.com/)
- [PrivacyPolicy](https://policies.google.com/privacy)
- [TermsOfService](https://policies.google.com/terms)
- [RateLimits](https://developers.google.com/forms/api/guides/quota)
- [Support](https://developers.google.com/forms/api/support)

## Features

| Name | Description |
|------|-------------|
| Form Creation | Programmatically create Google Forms with custom titles and descriptions. |
| Batch Updates | Apply multiple changes to a form in a single API call. |
| Response Collection | Read and analyze form responses programmatically. |
| Watch Notifications | Receive real-time notifications via Cloud Pub/Sub when forms change or responses are submitted. |
| Quiz Support | Create and grade quiz forms with correct answers and scoring. |
| Publish Settings | Control whether forms are published and accepting responses. |
| File Upload Questions | Support for file upload question types. |
| Rating Questions | Support for rating-style questions with customizable icons. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Survey Distribution | Create and distribute surveys programmatically as part of CRM or marketing workflows. |
| Response Analytics | Automatically collect and analyze form responses for reporting dashboards. |
| Event-Driven Processing | Trigger downstream workflows when new responses are submitted using watches. |
| Quiz and Assessment Automation | Build automated grading systems for educational quizzes. |
| Data Collection Pipelines | Integrate forms into data collection pipelines for research or operations. |

## Integrations

| Name | Description |
|------|-------------|
| Google Sheets | Automatically link form responses to Google Sheets for analysis. |
| Google Cloud Pub/Sub | Receive real-time notifications about form events via Pub/Sub topics. |
| Google Drive | Store file upload responses in Google Drive. |
| Google Workspace | Integrate with other Google Workspace apps for collaboration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Google Forms API](openapi/google-forms-api.yaml)

### JSON Schema

- [Form](json-schema/google-forms-api-form-schema.json)
- [FormResponse](json-schema/google-forms-api-form-response-schema.json)
- [Watch](json-schema/google-forms-api-watch-schema.json)
- [Question](json-schema/google-forms-api-question-schema.json)

### JSON Structure

- [Form](json-structure/google-forms-api-form-structure.json)
- [FormResponse](json-structure/google-forms-api-form-response-structure.json)
- [Watch](json-structure/google-forms-api-watch-structure.json)
- [Question](json-structure/google-forms-api-question-structure.json)

### JSON-LD

- [Google Forms API Context](json-ld/google-forms-api-context.jsonld)

### Examples

- [Form](examples/google-forms-api-form-example.json)
- [FormResponse](examples/google-forms-api-form-response-example.json)
- [Watch](examples/google-forms-api-watch-example.json)
- [Question](examples/google-forms-api-question-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Google Forms API](capabilities/shared/forms-api.yaml) — 11 operations for form, response, and watch management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Form Management](capabilities/form-management.yaml) | Google Forms API | 10 | Form Administrator, Data Analyst |

## Vocabulary

- [Google Forms Vocabulary](vocabulary/google-forms-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Google Forms Spectral Rules](rules/google-forms-spectral-rules.yml) — 24 rules across 8 categories enforcing Google Forms API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
