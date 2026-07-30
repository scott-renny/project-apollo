# Contributing

Contributions should improve clarity, repeatability, security, or accessibility without exposing the private environment.

## Before making a change

1. Open an issue or describe the intended change.
2. Confirm that no secret, personal data, internal address, device identifier, or live operational detail is included.
3. Keep product-specific instructions version-aware; mobile settings can change between Android and One UI releases.
4. Prefer categories and placeholders over private tool configuration.

## Documentation style

- Use clear Markdown headings and short, testable steps.
- Mark optional controls as optional.
- Separate phone and tablet behavior.
- Use `<INTERNAL_SERVICE_URL>`, `<VPN_PROFILE>`, and similar placeholders.
- Never include credentials, tokens, recovery codes, serial numbers, IMEIs, MAC addresses, public IP addresses, private DNS names, or QR codes.

## Validation

- Test internal links.
- Review every image at full resolution.
- Confirm screenshots contain no notification previews, account names, faces, locations, or infrastructure identifiers.
- Record behavioral changes in `CHANGELOG.md`.

## Suggested pull-request title

`docs: describe the user-visible change`

