# Project Overview

Project Apollo is the mobile layer of a broader engineering environment. It provides governed, secure access to communications, dashboards, documentation, authentication, and household systems without turning either mobile device into an unrestricted administrative endpoint.

## Scope

Apollo covers:

- device roles and ownership boundaries;
- account, screen-lock, update, permission, network, and physical-security baselines;
- approved application categories;
- home-screen layouts, modes, routines, and quick actions;
- synchronization, backup, restore, and loss response;
- NetWatch v2.0 access from the tablet;
- shared Hermes–Hydra–Apollo visual identity;
- portfolio-safe documentation.

Apollo does not publish live configurations, expose administrative services, store recovery material, replace vendor support, or guarantee that every setting exists on every software version.

## Design principles

1. **Secure by default:** encryption, strong authentication, prompt updates, private notifications.
2. **One device, one primary role:** the phone handles urgency; the tablet handles depth.
3. **One-action monitoring:** NetWatch v2.0 is immediately accessible on the tablet.
4. **Least privilege:** monitoring access is separated from administrative access where possible.
5. **Recoverable operation:** loss, replacement, and restore procedures are tested.
6. **Public/private separation:** portfolio evidence is intentionally sanitized.

## Success criteria

- Both devices pass their build checklist.
- Internal tools are unreachable without the approved secure access path.
- NetWatch opens from the tablet home screen or dock in one action.
- High-severity alerts reach the phone without exposing sensitive lock-screen content.
- Backup and restore tests are recorded privately.
- Lost-device actions can be performed from a separate trusted device.
- Public artifacts pass the sanitization review.

