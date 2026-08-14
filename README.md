<h1 align="center">Project Apollo</h1>

<p align="center">
<b>Secure Mobile Command Environment for Samsung Galaxy S25 and Galaxy Tab A11</b>
</p>

<p align="center">

![Status](https://img.shields.io/badge/Status-Planning-orange?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-v1.0.0-0078D6?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Devices](https://img.shields.io/badge/Devices-Galaxy%20S25%20%2B%20Tab%20A11-1428A0?style=for-the-badge&logo=samsung&logoColor=white)
![License](https://img.shields.io/github/license/scott-renny/project-apollo?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/scott-renny/project-apollo?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/scott-renny/project-apollo?style=for-the-badge)

</p>

---

## Overview

Project Apollo standardizes a phone and tablet as secure, coordinated extensions of a home cyber-operations environment. The Galaxy S25 is the alert, authentication, communication, and rapid-response device. The Galaxy Tab A11 is the portable operations console, with NetWatch v2.0 as its primary network-monitoring experience.

> **Device baseline:** The Galaxy Tab A11 is the current tablet baseline. Any future tablet replacement will be documented as a separate migration decision and must not be represented as deployed before validation.

> This public repository is a documentation and design reference. It intentionally contains no credentials, private addresses, device identifiers, recovery codes, personal notifications, family information, or live infrastructure screenshots.

## Project goals

- Establish distinct roles for the phone and tablet.
- Apply a repeatable mobile security and privacy baseline.
- Make NetWatch v2.0 available from the tablet in one action.
- Define modes and routines separately for each device.
- Standardize approved applications, backup, recovery, and loss response.
- Extend the shared Hermes–Cerberus–Apollo visual identity to mobile.
- Produce sanitized, portfolio-safe evidence of planning and implementation.

## Device roles

| Device | Role | Primary use |
|---|---|---|
| Galaxy S25 | Mobile Command Device | Alerts, authentication, communication, quick status checks, emergency response |
| Galaxy Tab A11 | Portable Operations Console | NetWatch v2.0, dashboard analysis, documentation, remote administration, study, DeX |

See [Device Roles](docs/device-roles.md) for the operating boundaries.

## Repository map

```text
project-apollo/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── .gitignore
├── SECURITY.md
├── docs/
│   ├── project-overview.md
│   ├── device-roles.md
│   ├── security-baseline.md
│   ├── privacy-standard.md
│   ├── application-standard.md
│   ├── synchronization-policy.md
│   ├── netwatch-quick-access.md
│   ├── backup-and-recovery.md
│   ├── visual-identity-standard.md
│   ├── portfolio-and-sanitization.md
│   ├── implementation-roadmap.md
│   └── github-publishing.md
├── modes/
│   ├── phone-modes.md
│   └── tablet-modes.md
├── checklists/
│   ├── phone-build-checklist.md
│   ├── tablet-build-checklist.md
│   ├── monthly-security-review.md
│   └── lost-device-response.md
├── inventories/
│   └── approved-applications.md
└── assets/
    ├── README.md
    ├── logos/.gitkeep
    ├── wallpapers/.gitkeep
    ├── lockscreens/.gitkeep
    ├── screenshots/.gitkeep
    └── diagrams/.gitkeep
```

## Quick start

1. Read the [privacy standard](docs/privacy-standard.md) before capturing evidence.
2. Confirm each [device role](docs/device-roles.md).
3. Complete the [phone](checklists/phone-build-checklist.md) and [tablet](checklists/tablet-build-checklist.md) checklists.
4. Configure [NetWatch quick access](docs/netwatch-quick-access.md).
5. Implement the separate [phone](modes/phone-modes.md) and [tablet](modes/tablet-modes.md) modes.
6. Test [backup and recovery](docs/backup-and-recovery.md) and rehearse the [lost-device response](checklists/lost-device-response.md).
7. Publish only evidence that passes the [sanitization checklist](docs/portfolio-and-sanitization.md).

When ready to publish, follow the [GitHub Publishing Guide](docs/github-publishing.md).

## Security model

Apollo assumes that a mobile device may be lost, stolen, observed in public, or connected through an untrusted network. Access to internal services must use an approved encrypted path, strong authentication, least privilege, and short sessions. Administrative interfaces must never be exposed directly to the public internet for convenience.

This repository does not prescribe a particular VPN, password manager, authenticator, SSH client, or mobile-device-management product. Record the selected tools locally, then publish only generic categories or sanitized names.

## Visual identity

Hermes, Cerberus, and Apollo use the exact same master wallpaper composition, color palette, typography, icon language, lighting, and lock-screen treatment. Only the official project emblem changes:

- Hermes: winged helmet
- Cerberus: three-headed guardian
- Apollo: stylized **A**

These emblems are the official project logos moving forward. Binary logo and wallpaper files must be added only when the owner has verified the source files and rights. See [Visual Identity Standard](docs/visual-identity-standard.md).

## Status

Documentation baseline: **v1.0.0-ready**

Device-specific settings should be validated against the software version installed on each device before implementation.
