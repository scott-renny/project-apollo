# Privacy Standard

## Data classes

| Class | Examples | Public repository |
|---|---|---|
| Public | Generic diagrams, placeholder layouts, policy text | Allowed |
| Internal | App choices, generic workflow notes, non-sensitive test results | Review first |
| Confidential | Private URLs, hostnames, user names, calendars, household details | Prohibited |
| Restricted | Credentials, tokens, recovery codes, keys, MFA material | Prohibited |

## Mobile privacy controls

- Show notification icons or generic summaries on the lock screen, not message content.
- Limit precise and background location to applications that require it.
- Disable advertising personalization and unnecessary diagnostics where appropriate.
- Review clipboard, screenshot, screen-recording, and sharing behavior.
- Remove photo location metadata before publishing.
- Keep personal and operations browser profiles separate.
- Avoid account names and personal photos in demonstration layouts.

## Evidence handling

Capture portfolio evidence with demo data whenever possible. Before publishing:

1. Close personal applications.
2. Enable Do Not Disturb and a sanitized demonstration mode.
3. Replace live dashboards with test or mock data.
4. Inspect the full-resolution image, including status and notification bars.
5. Remove metadata.
6. Ask a second reviewer to check the final asset.

Redaction is a fallback. Cropping or recreating an image with placeholders is safer than blurring a secret that may remain recoverable.

