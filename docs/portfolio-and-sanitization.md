# Portfolio and Sanitization

## Safe evidence

- generic architecture and workflow diagrams;
- mock dashboards populated with demo data;
- home-screen layouts with placeholder widgets;
- completion percentages and generalized lessons learned;
- policy, checklist, and mode documentation;
- cropped device photos with identifying details removed.

## Never publish

- credentials, tokens, keys, certificates, cookies, QR codes, or recovery codes;
- internal URLs, hostnames, addresses, ports, SSIDs, or real topology;
- IMEI, serial number, MAC address, phone number, or account identifiers;
- notifications, calendars, contacts, messages, family details, faces, or locations;
- live alert content, security findings, or identifiable device lists;
- raw backups, diagnostics, logs, or authenticator exports.

## Screenshot release checklist

- [ ] Demo or mock data is used.
- [ ] Status bar contains no identifying carrier, VPN, or notification detail.
- [ ] Account avatars, names, email addresses, and profile photos are absent.
- [ ] Network and device identifiers are absent.
- [ ] Browser history, tabs, bookmarks, and address bar are safe.
- [ ] Image metadata has been removed.
- [ ] Full-resolution inspection is complete.
- [ ] A second-person review is complete.
- [ ] Source and licensing are documented for non-original assets.

## Suggested portfolio narrative

Describe the problem, threat model, device-role separation, least-privilege approach, NetWatch one-action design, recovery testing, and measurable outcomes. Avoid claiming that documentation alone proves implementation; distinguish designed, configured, and validated controls.

