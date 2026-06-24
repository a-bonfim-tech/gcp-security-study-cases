# Security Policy

## Scope

This repository documents Google Cloud security study cases for portfolio and
learning purposes. The material should remain audit-friendly, sanitized, and
limited to environments owned by the author or explicitly authorized for study.

The repository should not contain:

- Active Google Cloud credentials, service-account keys, API keys, or tokens
- Project IDs that expose private environments
- Customer, employer, or third-party data
- Live infrastructure endpoints that are not intentionally public
- Screenshots exposing secrets, billing data, private IAM members, or personal
  data

## Reporting a Concern

Open a GitHub issue if you identify:

- Exposed secrets or credentials
- Sensitive cloud identifiers
- Unsafe configuration guidance without context
- Evidence that should be sanitized
- Incorrect claims about Google Cloud controls or security behavior

Do not include active secrets or private identifiers in public issue text.
Reference the affected file path and describe the issue category.

## Triage Process

Reports are handled in this order:

1. Preserve the report and affected file path.
2. Confirm whether the evidence or guidance is sensitive, unsafe, or inaccurate.
3. Remove or redact exposed material.
4. Update the relevant case study or evidence note.
5. Record the correction in commit history.

## Intended Use

The cases are intended for cloud security learning, architecture discussion,
and recruiter-facing evidence. They are not production hardening baselines and
do not replace official Google Cloud documentation.
