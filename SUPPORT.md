# 🛟 Support — Yadavar (یادآور)

Thank you for using **Yadavar (یادآور)**, your Persian Calendar & Reminder companion. This page covers how to get help, report issues, and request features.

---

## 📋 Table of Contents

1. [Getting Help](#getting-help)
2. [Reporting Bugs](#reporting-bugs)
3. [Requesting Features](#requesting-features)
4. [FAQ — Frequently Asked Questions](#faq)
5. [Contact](#contact)

---

## 💬 Getting Help

Before reaching out, please check the [FAQ section](#faq) below — your question may already be answered there.

If you can't find what you need:

- 📧 **Email us:** [shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)
- 🐛 **Open a GitHub Issue:** [github.com/shahabahreini/yadavar-privacy/issues](../../issues)

We typically respond within **2–5 business days**.

---

## 🐛 Reporting Bugs

Encountered something broken? We want to know!

### Before Reporting

1. **Update the App** — make sure you're on the latest version
2. **Restart the App** — close it fully and reopen
3. **Search existing issues** — someone may have already reported it: [View Issues](../../issues)

### How to Report

[**Open a Bug Report →**](../../issues/new?template=bug_report.md)

Please include:
- Your **App version** (found in Settings → About)
- Your **platform** (iOS, Android, or macOS) and OS version
- **Steps to reproduce** the issue
- What you **expected** to happen vs. what **actually** happened
- Screenshots or screen recordings if applicable

The more detail you provide, the faster we can fix it! 🙏

---

## 💡 Requesting Features

Have an idea to make Yadavar better? We love hearing from our community!

[**Submit a Feature Request →**](../../issues/new?template=feature_request.md)

Please describe:
- The **problem** you're trying to solve
- Your **proposed solution**
- Any **alternatives** you've considered

We review all feature requests, though we can't guarantee implementation timelines.

---

## ❓ FAQ

### ☁️ Backup & Restore

---

#### How do I backup my data?

1. Open **Settings** in Yadavar
2. Tap **Backup & Restore**
3. Tap **Connect Google Account** and sign in
4. Once connected, tap **Backup Now**

Your data will be saved to a private, hidden folder in your Google Drive that only Yadavar can access. You can optionally enable **encrypted backup** for extra security.

> **Note:** Backups are user-initiated. Yadavar does not automatically back up your data without your action.

---

#### How do I connect Google Drive?

1. Go to **Settings → Backup & Restore**
2. Tap **Connect Google Account**
3. Sign in with your Google Account and grant the requested permission
4. You'll see your account email displayed once connected

The App only requests the `drive.appdata` permission scope — it cannot access any other files in your Google Drive.

---

#### How do I restore from a backup?

1. Open **Settings → Backup & Restore**
2. Ensure your Google Account is connected
3. Tap **Restore**
4. Select the backup you want to restore from the list
5. If the backup is encrypted, enter your encryption passphrase
6. Confirm the restore — your current data will be replaced

> ⚠️ **Warning:** Restoring from a backup will overwrite your current data. We recommend creating a new backup first.

---

#### What happens if I forget my encryption passphrase?

Unfortunately, **encrypted backups cannot be recovered without the passphrase**. The encryption key is derived entirely from your passphrase and is never stored anywhere by us. Please store your passphrase safely.

---

### 🔔 Notifications

---

#### Why can't I see my notifications?

There are several possible reasons:

1. **Notification permission denied:** Go to your device's **System Settings → Yadavar → Notifications** and ensure notifications are enabled.

2. **Do Not Disturb / Focus mode:** Check if your device has a focus mode or DND schedule that may be silencing notifications.

3. **Low power / battery saver mode:** Some devices suppress app notifications in battery saving modes.

4. **iOS only — Background App Refresh:** Go to **Settings → General → Background App Refresh** and enable it for Yadavar.

5. **Reminder not set correctly:** Open the event in Yadavar and confirm a reminder is set with a future date and time.

If none of these help, please [report a bug](../../issues/new?template=bug_report.md).

---

### 🗑️ Data Management

---

#### How do I delete all my data?

**To delete local data:**
- You can delete events individually within the App, or
- Uninstall Yadavar — this removes all App data from your device

**To delete your Google Drive backup:**
1. Go to **Settings → Backup & Restore**
2. Tap **Manage Backups**
3. Select the backup(s) and tap **Delete**, or
4. You can remove all App data from Google Drive by going to [Google Account → Apps with access to your account](https://myaccount.google.com/permissions) and revoking Yadavar's access, then deleting the `appDataFolder` contents

---

### 🔒 Privacy & Security

---

#### Is my data safe?

Yes. Yadavar is designed with privacy as a core principle:

- **Your calendar data never leaves your device** unless you explicitly initiate a Google Drive backup
- **Google Drive backups** are stored in a hidden folder only your App can access — the Developer cannot see your data
- **Optional AES-256-GCM encryption** ensures even your backups are unreadable without your passphrase
- **No analytics, no ads, no tracking** — we don't monitor how you use the App
- Persian holiday data is fetched via **anonymous requests** with no personal data attached

See the full [Privacy Policy](./PRIVACY_POLICY.md) for complete details.

---

#### Does the App work offline?

**Yes!** The core functionality of Yadavar works fully offline:

- ✅ Viewing your Persian calendar
- ✅ Creating, editing, and deleting events
- ✅ Setting and receiving local reminders
- ✅ Viewing previously cached Persian holidays

**Requires internet connectivity:**
- 🌐 Syncing new Persian holiday data from the API
- 🌐 Google Drive backup and restore

---

#### What Google permissions does Yadavar request?

When you connect Google Drive, Yadavar requests only:

- **`drive.appdata`** — access to a hidden, App-specific folder in your Drive

This is the most restricted Drive scope available. The App **cannot** see, read, or modify any of your regular Google Drive files, Gmail, Google Calendar, or any other Google service.

---

#### Can I use Yadavar without a Google account?

**Absolutely!** Google Account integration is entirely optional. All core features — calendar, events, reminders — work without any Google account. You simply won't have cloud backup capability.

---

## 📧 Contact

For anything not covered here, reach out directly:

**Developer:** Shahab Bahreini Jangjoo
**Email:** [shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com)

Please include your **App version** and **platform** in your message to help us assist you faster.

---

*Yadavar — یادآور — Persian Calendar & Reminder*
