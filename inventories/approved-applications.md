# Approved Applications Inventory

Replace placeholders in a private working copy. The public repository should normally show capability categories, not the full operational stack.

| Capability | Phone status | Tablet status | Selection | Required permissions | Data class | Review date |
|---|---|---|---|---|---|---|
| Password manager | Required | Required | `<APP>` | Network, biometrics | Restricted | `<DATE>` |
| Authenticator/passkey provider | Required | Limited | `<APP>` | Camera only for enrollment | Restricted | `<DATE>` |
| Secure tunnel | Required | Required | `<APP>` | VPN, background operation | Confidential | `<DATE>` |
| NetWatch v2.0 | Quick status | Primary | `<APP_OR_PWA>` | Network | Confidential | `<DATE>` |
| Secure browser | Required | Required | `<APP>` | Network | Internal | `<DATE>` |
| SSH/remote administration | Emergency | Approved | `<APP>` | Network, secure storage | Restricted | `<DATE>` |
| Notes/documentation | Capture | Authoring | `<APP>` | Files as needed | Internal | `<DATE>` |
| Git hosting | Optional | Recommended | `<APP_OR_BROWSER>` | Network | Internal | `<DATE>` |
| Device finding | Required | Required | `<SERVICE>` | Location, background | Confidential | `<DATE>` |
| Encrypted backup | Required | Required | `<SERVICE>` | Files as scoped | Confidential | `<DATE>` |
| Household controls | Quick actions | Console | `<APP_OR_PWA>` | Network, nearby devices as needed | Confidential | `<DATE>` |

## Inventory rules

- Document publisher, version, source, owner, purpose, permissions, backup behavior, and removal plan privately.
- Do not list credentials, account names, tenant names, server names, URLs, or identifiers.
- Remove applications that no longer have an approved purpose.

