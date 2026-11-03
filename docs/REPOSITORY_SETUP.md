# Public Repository Setup Guide

The **Kyrelix-Security-Advisor** repository is intended for official product information, documentation, and approved releases—not source-code hosting. Maintain it separately from the Flutter application project.

## 1. Repository Details

- **Repository name:** `Kyrelix-Security-Advisor`
- **Visibility:** `Public` (only after checking the current files **and Git history** for sensitive content).
- **Default branch:** `main`
- **Description:** `Kyrelix Security Advisor — Android account security guidance, authenticator tools, and official project information. Proprietary software; source code is private.`
- **Topics:** `android`, `security`, `authenticator`, `totp`, `hotp`, `account-security`, `passkeys`, `closed-source`
- **Website:** Leave blank until a valid official website or release link is available.
- **License:** Do not select an open-source license for the proprietary application. See `COPYRIGHT.md`. Third-party license obligations still apply.

If an existing repository named `Kyrelix-Auth` is free of source files and secrets, it can be renamed under **Settings → General → Repository name**. **Renaming a repository does not erase sensitive content from its Git history.**

## 2. Target File Structure

```text
Kyrelix-Security-Advisor/
├── README.md
├── SECURITY.md
├── COPYRIGHT.md
├── .gitignore
└── docs/
    ├── OVERVIEW.md
    ├── PRIVACY.md
    ├── ROADMAP.md
    ├── RELEASES.md
    └── REPOSITORY_SETUP.md
```

**Important:** `docs` must be a directory, not a file named `docs`. In GitHub, choose **Add file → Create new file** and type `docs/PRIVACY.md` in the filename field; the directory will be created automatically.

## 3. Uploading Files in Order

1. Open the repository's **Code** tab.
2. Choose **Add file → Upload files** and upload the four files from the root: `README.md`, `SECURITY.md`, `COPYRIGHT.md`, and `.gitignore`. Confirm with **Commit changes**.
3. Upload the `docs` directory while preserving relative paths, or create each `docs/` file individually using GitHub's file editor.
4. Confirm that `README.md` renders automatically on the repository's main page.
5. Check internal links and set the repository description and topics under **About**.

If a file named `docs` was created accidentally, open it, use the menu next to the edit icon to select **Delete file**, commit that deletion, and then create `docs/PRIVACY.md` correctly.

## 4. Security Settings

- Enable **Private vulnerability reporting** under the repository's security settings if available.
- Use public issues for general questions or non-sensitive bugs—not vulnerability exploit details.
- Grant write access only to trusted collaborators.
- Review release artifacts and screenshots carefully before making them public.

## 5. Do Not Upload

Do not publish Flutter source directories (`lib/`, `android/`), source ZIP archives, application signing material (`*.jks`, `key.properties`), OAuth secrets, sensitive Appwrite settings, API credentials, database exports, or screenshots containing private account information.

`.gitignore` is only an additional safeguard; it does not prevent uploads through GitHub's web interface or files force-added to Git. Keep this public documentation repository physically separate from the private application workspace.

## 6. Flutter and Android Application Identifiers

The public name **Kyrelix Security Advisor** can be used for this repository without changing Flutter's internal package name or Android's `applicationId`. Any changes to app identifiers, store listings, authentication callbacks, Appwrite connections, or Google Play billing should be reviewed separately to avoid disrupting existing users or integrations.
