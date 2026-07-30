# Security Baseline

Validate setting names against the installed Android and One UI versions.

## Identity and unlock

- Use a unique PIN of at least six digits; prefer a longer PIN or password.
- Enroll only required biometrics and review them periodically.
- Disable convenience unlock features that weaken the boundary.
- Protect Google, Samsung, password-manager, and primary email accounts with phishing-resistant MFA where supported.
- Store recovery codes offline and away from both Apollo devices.
- Require reauthentication for password manager, VPN administration, and sensitive applications.

## Updates and integrity

- Enable automatic Android, Google Play system, Samsung, and application updates.
- Review update status monthly and after security advisories.
- Install applications only from approved stores or a documented, verified source.
- Do not unlock the bootloader or root production devices.
- Keep Play Protect and supported Samsung/Knox integrity controls enabled.

## Lock screen and physical access

- Lock automatically after a short idle period.
- Lock immediately with the side key.
- Hide sensitive notification content.
- Disable lock-screen access to sensitive controls where practical.
- Configure remote locate, lock, and erase; test access from another trusted device.
- Record serial and purchase details in a private inventory, never this repository.

## Network

- Never expose NetWatch or administrative dashboards directly to the internet.
- Use the approved VPN or zero-trust access path outside the trusted network.
- Disable automatic connection to unknown Wi-Fi.
- Prefer encrypted DNS where compatible with the private environment.
- Turn off unused wireless discovery and sharing features.
- Restrict USB data access while locked; use charge-only accessories in untrusted locations.

## Applications and permissions

- Apply least privilege to location, microphone, camera, contacts, files, nearby devices, and accessibility access.
- Allow background operation only when required for alerts, VPN, backup, or device-finding.
- Remove unused applications and review special access quarterly.
- Separate personal, work, and administrative data using supported profiles or containers when available.

## Administrative access

- Use separate monitoring and administrative accounts.
- Prefer short-lived sessions and key-based SSH with protected keys.
- Do not save administrative passwords in browsers.
- Require VPN connectivity before opening internal tools.
- Log out of sensitive dashboards after use and avoid unattended active sessions.

## Validation record

Record completion date, software version, tester, exceptions, and next review in a private register. Publish only aggregate or redacted status.

