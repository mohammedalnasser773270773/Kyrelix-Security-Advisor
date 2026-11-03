<div align="center">

# Kyrelix Security Advisor

**Account Security Guidance & Authenticator Tools for Android**

Android · Proprietary Software · In Development

[Project Overview](docs/OVERVIEW.md) · [Security](SECURITY.md) · [Privacy Information](docs/PRIVACY.md) · [Roadmap](docs/ROADMAP.md) · [Releases](docs/RELEASES.md)

</div>

## About Kyrelix

**Kyrelix Security Advisor** is an Android application designed to combine authentication tools with practical account security guidance. It helps users understand verified security findings, distinguish unavailable information from actual risks, and reach official provider settings when protective action is needed.

**This is the public information repository—not the application's source-code repository.** Flutter and Android source files, backend configuration, credentials, signing materials, and user data are not published here.

## Planned and Developing Capabilities

| Area | Description |
| --- | --- |
| Authenticator | TOTP/HOTP authentication tools and account enrollment using QR scanning, gallery QR import, or supported manual setup methods. |
| Account Security Advisor | Account summaries, verified security findings, status indicators, and practical recommendations. |
| Provider-Authorized Checks | Automatic retrieval of security facts where an official provider API and granted permissions support it. GitHub integration is under development and testing. |
| Password Advisor | On-device password suggestions and optional memory hints; the app does not claim to inspect existing passwords held by external providers. |
| Passkeys & Devices | Security guidance and direct links to provider settings when verified status or device counts cannot be retrieved. |
| Kyrelix Sessions | Appwrite-based account session information where available. Session counts do not necessarily equal the number of unique devices. |

### How to Interpret Security Findings

The advisor differentiates **verified protection**, **attention recommended**, **confirmed problems**, **permission/API access unavailable**, and **not assessed**.

An unavailable result must not be interpreted as proof that a security feature is disabled. A provider's consent screen does not automatically provide access to all 2FA, passkey, password, or device settings.

## Availability and Official Releases

Kyrelix is still in development. Feature availability may differ across versions and connected services. Official download links will be published only after a release has been approved and verified by the project owner.

Read the [release information](docs/RELEASES.md) and [development roadmap](docs/ROADMAP.md). Do not trust an APK or store listing based solely on a third-party claim of affiliation.

## Privacy and Vulnerability Reporting

The [privacy information](docs/PRIVACY.md) is a **draft for production review**, not a finalized legal privacy policy. It must be verified against the released application and its backend services.

To report suspected vulnerabilities, follow [SECURITY.md](SECURITY.md) and use a private reporting channel. Never publish credentials, authentication secrets, recovery codes, OAuth tokens, or personal data in public issues.

## Repository Scope and Licensing

This repository contains public documentation, project updates, and, if formally released, distribution information. **Kyrelix Security Advisor is proprietary and closed source.** Making these documents public does not grant rights to the unpublished application source or proprietary binaries. See [COPYRIGHT.md](COPYRIGHT.md).

References to Google, GitHub, Microsoft, Appwrite, or other services are descriptive and do not imply sponsorship, endorsement, or partnership.
