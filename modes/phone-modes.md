# Galaxy S25 Modes

## Priority for v1

Daily, COC Alert, Work, Study, Travel, Sleep, and Incident Response.

## Daily

Normal communications, calendar, weather, camera, wallet, password manager, and authenticator access. Standard battery optimization remains enabled; COC tools are available but not dominant.

## COC Alert

Surfaces NetWatch, Wazuh, Argus, Pi-hole, Homepage, and secure-access shortcuts. Allows critical infrastructure alerts, mutes entertainment, verifies the approved secure tunnel before internal access, and extends timeout only for the active check.

## Work

Allows priority contacts, work apps, calendar, alarms, transportation, and weather. Mutes personal distractions, preserves battery, and limits COC alerts to high severity.

## Study

Surfaces training, notes, flashcards, browser, calendar, and timer. Enables focus controls, extends reading timeout, and permits only emergency and high-severity operational alerts.

## Home Command

Surfaces Athena controls, family calendar, Hestia media controls, household scenes, and a compact network-health view. Avoid exposing private household details on the lock screen.

## Travel

Uses the approved secure tunnel on untrusted networks, hides notification content, limits wireless discovery, restricts USB data, and surfaces maps, tickets, wallet, lodging details, and emergency contacts.

## Driving

Uses a simplified, voice-first interface. Navigation and hands-free communication are available; nonessential notifications are held and only critical COC alerts interrupt.

## Sleep

Enables Do Not Disturb, permits designated emergency contacts and critical alerts, reduces display activity, enables eye comfort, and maintains battery protection.

## Incident Response

Surfaces secure tunnel, NetWatch, Wazuh, Argus, approved administration, runbooks, communications, and incident notes. Temporarily relaxes battery restrictions for required tools and restores all normal settings when the incident ends.

## Implementation rule

Automations must fail safely: if secure connectivity, authentication, or a required control is unavailable, the mode must not expose or bypass protected services.

