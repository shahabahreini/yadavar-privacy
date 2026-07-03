# Privacy Policy — Yadavar (یادآور)

**Last Updated: July 3, 2026**
**Effective Date: July 3, 2026**

---

## 1. Introduction

Welcome to **Yadavar (یادآور)**, a Persian Calendar & Reminder application ("App", "we", "our", or "us") developed and maintained by **Shahab Bahreini Jangjoo** ("Developer"). This Privacy Policy explains how we collect, use, disclose, and protect information when you use our App on iOS, Android, or macOS.

We are committed to protecting your privacy. Yadavar is built on a **privacy-first philosophy**: your personal data stays on your device, and we have deliberately avoided analytics, advertising networks, and third-party tracking SDKs.

By using Yadavar, you agree to the practices described in this Privacy Policy.

---

## 2. Information We Collect

### 2.1 Data You Create (Stored Locally on Your Device)

When you use Yadavar, you may create:

- **Calendar event titles** — the names of events you add to your calendar
- **Event notes and descriptions** — additional details you attach to events
- **Reminder settings** — notification times and recurrence rules you configure

> **This data never leaves your device unless you explicitly enable Google Drive backup (see Section 3).**

All locally created data is stored in the App's private sandbox on your device and is not accessible to us or any third party.

### 2.2 Google Account Email (When Drive Backup Is Connected)

If you choose to connect your Google Account to enable the Google Drive backup feature, we receive your **Google Account email address** from Google's OAuth 2.0 service solely to:

- Display which account is linked in the App's settings
- Associate your backup files with the correct Drive account

We do **not** store your Google Account email on any external server. It is retained in the App's local storage only and is discarded when you disconnect Drive.

### 2.3 Persian Holiday API Requests

To display Persian national and religious holidays, the App makes **anonymous HTTP GET requests** to a third-party Persian holiday API. These requests:

- Contain **no personally identifiable information**
- Contain **no device identifiers**
- Are indistinguishable from any anonymous web browser request
- Are solely used to fetch publicly available holiday data

### 2.4 Information We Do NOT Collect

We explicitly **do not** collect:

- Device identifiers (IDFA, Android Advertising ID, IMEI, etc.)
- Location data
- Usage analytics or crash reports sent to us
- Contacts or address book data
- Photos or media
- Any biometric data
- IP addresses stored on our servers

---

## 3. Google Drive Backup

### 3.1 How It Works

The Google Drive backup feature is **entirely optional and user-initiated**. When you enable it:

- The App requests access using the `https://www.googleapis.com/auth/drive.appdata` OAuth scope
- This scope grants access **only** to a hidden application-specific folder in your Google Drive called `appDataFolder`
- This folder is **invisible** in your regular Google Drive view and is accessible **only by the Yadavar App**
- Your backup files are stored in this hidden folder under your own Google Account

### 3.2 What Is Backed Up

When you initiate a backup, the App uploads:

- Your calendar events (titles, notes, dates, reminder settings)
- App preferences and settings

### 3.3 Developer Access Limitation

> **The Developer CANNOT access your Google Drive backup data.**

The `drive.appdata` scope is specifically designed so that only the App itself — running under your authenticated session — can read or modify the data. Neither the Developer nor any third party has the ability to access this folder.

### 3.4 Optional Encryption

You may optionally enable **encrypted backups**:

- Encryption uses **AES-256-GCM**, an industry-standard authenticated encryption algorithm
- Your encryption key is derived from a passphrase **you choose**
- The passphrase and encryption key are **never transmitted** to us or stored anywhere outside your device
- Without your passphrase, **no one** — including the Developer — can decrypt your backup

### 3.5 Revoking Access

You can disconnect Google Drive at any time from within the App's settings. You can also revoke the App's access directly from your [Google Account permissions page](https://myaccount.google.com/permissions). Upon revocation, the App retains no credentials.

---

## 4. Local Notifications

Yadavar uses **local notifications** (device-only reminders) to alert you about upcoming events:

- Notifications are scheduled and delivered **entirely on your device**
- No notification content is sent to external servers
- No push notification service (APNs, FCM) is used for reminder delivery
- Notification permission is requested from your device's operating system; you may grant or deny it at any time in your device's system settings

---

## 5. Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Google Drive API** | Optional backup storage | OAuth token (when connected); no personal event data sent to Google beyond what you store in your own Drive account |
| **Persian Holiday APIs** | Fetch public holiday data | Anonymous HTTP GET requests only — no personal data |

We do **not** use:

- 📵 Analytics SDKs (e.g., Firebase Analytics, Mixpanel, Amplitude)
- 📵 Advertising networks (e.g., AdMob, Facebook Ads)
- 📵 Crash reporting services (e.g., Sentry, Crashlytics) that transmit data externally
- 📵 Social media tracking pixels

---

## 6. Data Retention

| Data Type | Location | Retention |
|-----------|----------|-----------|
| Calendar events & notes | Your device | Until you delete them or uninstall the App |
| Google Drive backup files | Your Google Drive `appDataFolder` | Until you delete them via the App or Google Drive settings |
| Google Account email | Your device (local storage only) | Until you disconnect Google Drive |
| Persian holiday cache | Your device | Refreshed periodically; cleared on uninstall |

---

## 7. Your Data Rights

Regardless of your location, we respect your right to:

### 7.1 Access
You can view all your calendar data directly within the App at any time.

### 7.2 Modify
You can edit or update any event, note, or reminder through the App's interface.

### 7.3 Delete
You can delete individual events or **all your data** by:
- Deleting events within the App, or
- Uninstalling the App (removes all local data from your device), or
- Deleting your Google Drive backup from within the App or directly from Google Drive

### 7.4 Export
You can export your calendar data using the App's built-in export functionality.

### 7.5 Portability
Your data is stored in open, standard formats compatible with other calendar applications.

### 7.6 Contact for Rights Requests
For any privacy-related request, contact us at: **[shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)**

---

## 8. GDPR Compliance (European Users)

If you are located in the European Economic Area (EEA), you have additional rights under the **General Data Protection Regulation (GDPR)**:

- **Legal Basis**: The App processes your data based on your consent (e.g., enabling Drive backup) and legitimate interest (local functionality)
- **Right to Erasure**: You may request deletion of all identifiable data we hold
- **Right to Restrict Processing**: You may limit how we process your data
- **Right to Object**: You may object to certain types of processing
- **Right to Lodge a Complaint**: You have the right to lodge a complaint with your local data protection authority

Since Yadavar does not collect personal data on our servers, most GDPR obligations are satisfied by design. For any inquiries, contact: **[shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)**

---

## 9. CCPA Compliance (California Users)

If you are a California resident, you have rights under the **California Consumer Privacy Act (CCPA)**:

- **Right to Know**: What personal information is collected (see Section 2)
- **Right to Delete**: Request deletion of your personal information
- **Right to Opt-Out**: We do not sell personal information — there is nothing to opt out of
- **Right to Non-Discrimination**: We will not discriminate against you for exercising your privacy rights

**We do not sell, trade, or otherwise transfer your personal information to outside parties.**

---

## 10. COPPA Compliance (Children's Privacy)

Yadavar is **not directed at children under the age of 13**. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided personal information through the App, please contact us at **[shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)** and we will take appropriate steps to remove such information.

---

## 11. Data Security

We implement industry-standard security measures:

- **Local data**: Protected by your device's operating system-level sandboxing and encryption (when device encryption is enabled)
- **Drive backups**: Transmitted over HTTPS (TLS) and optionally encrypted end-to-end with AES-256-GCM
- **OAuth tokens**: Stored securely in the device's system keychain/keystore
- **No passwords stored by us**: We never receive or store your Google password or any other authentication credentials

While we take reasonable precautions, no method of electronic storage or transmission is 100% secure. We encourage you to enable device-level encryption and use the optional backup encryption feature.

---

## 12. International Data Transfers

Yadavar is developed in Canada. If you use the Google Drive backup feature, your backup data is stored in Google's cloud infrastructure, which may be located in various countries. Google's data handling is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

Persian holiday data may be fetched from API servers in various jurisdictions. Since these requests contain no personal data, no transfer of personal information occurs.

---

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do:

- The **"Last Updated"** date at the top of this document will be revised
- For significant changes, we will notify you via an in-app notice on the next App launch
- Continued use of the App after changes constitutes acceptance of the updated policy

We encourage you to review this page periodically.

---

## 14. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data, please contact:

**Developer:** Shahab Bahreini Jangjoo
**Email:** [shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)
**GitHub:** [github.com/shahabahreini](https://github.com/shahabahreini)

We aim to respond to all privacy inquiries within **10 business days**.

---

*This Privacy Policy was last updated on **July 3, 2026**.*
