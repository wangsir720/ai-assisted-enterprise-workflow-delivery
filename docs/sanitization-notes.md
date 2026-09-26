# Sanitization Notes

## Removed from the Public Version

- Private network addresses and environment URLs
- Tenant names, tenant keys, profiles, and account identifiers
- User IDs and object IDs for applications, forms, workflows, nodes, and links
- Cookies, tokens, credentials, and authentication instructions
- Real employee names, department names, and department codes
- Customer, employer, and product names that are not explicitly approved for publication
- Internal command names, private package names, and script names
- Local filesystem paths and internal filenames
- Raw command output and unredacted screenshots
- Internal assessment of previous reports
- Internal delivery-team commentary

## Kept in the Public Version

- Anonymized business modules and delivery scale
- Configuration and verification methodology
- Generalized problem categories and resolutions
- Public-safe workflow screenshots
- Readback outcomes without raw IDs or commands
- Reusable templates, checklists, and delivery lessons

## Public Naming Rules

- Use `enterprise low-code platform` instead of the vendor or product name.
- Use `private deployment environment` instead of a URL, IP address, or tenant name.
- Use `approver A`, `approver B`, or role names instead of real personnel names.
- Replace object IDs with `[ID redacted]`.
- Replace internal commands with `configuration operation` or `verification operation`.

## Review Before Publishing

Run a final search for:

```text
http://
https://
192.168
10.
172.
userId
tenantId
workflowId
formId
nodeId
token
cookie
vendor or product name
internal tool names
real personnel names
```

Do not publish any file containing an unreviewed result from this search.
