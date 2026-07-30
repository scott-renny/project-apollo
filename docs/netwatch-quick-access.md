# NetWatch v2.0 Quick Access

NetWatch v2.0 is the centerpiece of the Galaxy Tab S11 operations experience. The goal is one action from an unlocked tablet to the network dashboard.

## Home-screen design

```text
┌──────────────────────────────────────────────────────┐
│ Calendar       Tasks       Weather       VPN status │
├──────────────────────────────────────────────────────┤
│              NETWATCH v2.0 — PRIMARY                │
├──────────────────────────────────────────────────────┤
│ Argus          Wazuh       Homepage       Pi-hole    │
├──────────────────────────────────────────────────────┤
│ Athena         Hestia      Git hosting    Runbooks   │
├──────────────────────────────────────────────────────┤
│ NetWatch | Browser | VPN | SSH | Notes | Files       │
└──────────────────────────────────────────────────────┘
```

Use a large shortcut or trusted web-app shortcut. Do not expose the internal URL in screenshots or public documentation.

## Launch sequence

1. Confirm the device is on a trusted network or the approved secure tunnel is connected.
2. Open NetWatch from the home screen, dock, or Network Operations mode.
3. Authenticate with a monitoring-only account where possible.
4. Escalate to administrative tools only when required.

## Network Operations mode

- Prefer landscape orientation.
- Connect the approved secure tunnel when outside the trusted network.
- Extend display timeout for the active session.
- Silence entertainment notifications.
- Allow required background operation for the tunnel and alerting tools.
- Prepare split-screen pairs: NetWatch + notes, NetWatch + SSH, NetWatch + runbook.
- Restore normal timeout, notification, and battery settings when the mode ends.

## Optional deep links

If NetWatch v2.0 officially supports stable deep links, create validated shortcuts for Network Health, Server Status, Offline Devices, Active Alerts, and Historical Graphs. Do not invent or publish internal routes. Record tested links in a private configuration file excluded by `.gitignore`.

## Failure behavior

- If the tunnel fails, do not bypass it by exposing the service publicly.
- If authentication fails, use the documented recovery process rather than cached or shared credentials.
- If the dashboard contains sensitive data, do not screen-share or capture it outside the sanitized demonstration workflow.

