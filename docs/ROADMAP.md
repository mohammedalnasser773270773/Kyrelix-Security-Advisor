# Development Roadmap

> **Planning document:** These items describe intended work, not guaranteed features, delivery dates, or proof of completed production security testing.

## Current Development Areas

- **Account Security Advisor:** Clear findings, evidence sources, and next-step recommendations.
- **Official provider integrations:** Authorized checks only where provider APIs permit them. GitHub functionality is undergoing development and testing.
- **Password Advisor:** On-device suggestions, optional memory hints, and secure generation methods.
- **Passkeys and device guidance:** Links to official settings, with an explicit distinction between supported checks and inaccessible data.
- **Kyrelix account sessions:** Appwrite session reporting without treating multiple sessions as unique physical devices.
- **Android user experience:** Accessibility, localization, error handling, and consistent security-status colors.

## Work Planned Before Production Release

1. Security-event history and appropriate notifications.
2. Review and strengthen Appwrite integration, access controls, auditing, and data retention.
3. End-to-end Android testing, regression tests, privacy review, and security hardening.
4. Migrate eligible paid in-app subscriptions to Google Play Billing and official promotional mechanisms, while preserving legitimate existing entitlements and audit history.
5. Final release validation, public documentation, support information, and verified distribution links.

## Commitments and Limitations

The project intends to preserve existing authenticator functionality and user data throughout development.

No single OAuth authorization provides full access to every provider's 2FA, passkeys, password, or device settings. Kyrelix must clearly identify inaccessible information instead of inferring a vulnerability or inventing a device count.

The roadmap may be adjusted in response to testing, provider limitations, security requirements, and release readiness.
