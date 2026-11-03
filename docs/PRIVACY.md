# Privacy Information

> **Draft for product review — not a final legal privacy policy.** This document must be checked against the production application, backend settings, data retention practices, third-party processors, and applicable legal requirements before being presented as the official privacy policy.

## Data and Functionality to Review

| Category | Current Project Context | Required Production Verification |
| --- | --- | --- |
| Authentication codes | The Android application provides TOTP/HOTP functionality and local credential storage. | Encryption, backup/export behavior, synchronization, retention, and recovery procedures. |
| Provider authorizations | Supported integrations may use authorized API tokens after user consent. | Permission scopes, storage, token validity, renewal, revocation, and deletion. |
| Security findings | The advisor may process account labels, status categories, and verification timestamps. | Exact data fields, on-device vs. server storage, retention, and user controls. |
| Kyrelix account | Appwrite supports account-related functions and may expose session metadata. | Data fields, access controls, hosting locations, and account deletion. |
| Auditing and subscriptions | Existing backend services may record audit events and subscription activity. | Logged event types, retention, recipients, and access restrictions. |
| Notifications | Firebase Cloud Messaging is used in the project. | Payload content, permissions, identifiers, and user opt-out controls. |
| Password suggestions | Suggestions are designed to be generated locally. | Clipboard handling, logs, analytics, backups, and production behavior. |

## Requirements Before Publishing a Final Policy

Confirm the service operator's identity and reliable contact details; data collected and processed; processing and storage locations; applicable legal bases; retention and deletion periods; third-party recipients; user rights; analytics and crash reporting; account deletion; backup and synchronization; children's privacy where applicable; and payment-provider disclosures.

Publish an accessible, stable policy URL before release requirements make it necessary. The final policy must accurately describe the **actual production application**, not merely planned behavior.

**Do not include passwords, OTP secrets, access tokens, private email addresses, phone numbers, or other personal data in public issues.**
