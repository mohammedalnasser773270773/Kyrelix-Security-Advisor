# Project Overview

## What Is Kyrelix Security Advisor?

**Kyrelix Security Advisor** is an Android security application that combines authenticator functions and practical guidance for reviewing the security of online accounts.

The app aims to provide a clear view of available security information, distinguish verified facts from unavailable checks, and help users navigate to the correct official settings when action is appropriate.

This is the project's **official public documentation repository**. It does not distribute the Flutter/Android source code, private server configuration, signing keys, or user information.

## Product Capabilities

| Capability | Overview |
| --- | --- |
| Authenticator Center | TOTP/HOTP tools, camera-based QR enrollment, gallery QR import, and supported manual entry. |
| Account Security Advisor | Account inventory, available security findings, visual status indicators, and recommendations. |
| Authorized Provider Checks | Retrieval of selected security facts following user authorization, only where the provider's official API permits it. The GitHub integration is being developed and tested. |
| Password Advisor | Password suggestions generated on the device with optional memory aids; no claim to read a user's existing external password. |
| Passkeys & Connected Devices | Helpful links and guidance when a direct provider-supported check is unavailable. |
| Kyrelix Account Sessions | Session information from Appwrite when an authenticated session is available; a session is not necessarily a distinct physical device. |

## Meaning of Security Results

Kyrelix aims to distinguish:

- **Verified:** The relevant security information is supported by actual available evidence.
- **Attention needed:** A known status indicates that further action may be useful.
- **Confirmed issue:** A supported check has established a specific problem.
- **Permission or API access unavailable:** The connected service has not provided the required information through the integration.
- **Not assessed:** There is not enough evidence to assign a security status.

Missing data must not be presented as proof that two-factor authentication, passkeys, or another safeguard is disabled. Consent to connect an account does not guarantee access to all of its settings.

## Development and Availability

Kyrelix is under development and testing. Product features and integrations may vary by version and service. Only downloads announced and verified by the project owner should be treated as official. See the [roadmap](ROADMAP.md) and [release guidance](RELEASES.md).

## Privacy and Security

The [privacy information](PRIVACY.md) describes known areas under review; it is **not** a final legal privacy policy. Report suspected security issues only through the private channels described in [SECURITY.md](../SECURITY.md), without sharing passwords, OTP secrets, access tokens, or other sensitive information in public.

## Ownership

The application is proprietary and closed source. This documentation repository does not grant an open-source license to unpublished code or permission to redistribute proprietary binaries. See [COPYRIGHT.md](../COPYRIGHT.md).

Third-party service names are included to identify possible integrations, not to claim affiliation, certification, or endorsement.
