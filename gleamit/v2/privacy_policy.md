# Privacy Policy

**Last updated: May 1, 2026**

## Introduction

Gleamit ("we", "our", or "the app") is a mobile application designed to help
you track oral hygiene habits such as brushing, reminders, brush replacement,
and dental care information. This Privacy Policy explains what information
Gleamit stores, how that information is used, and how account-based cloud
backup changes the app's data handling.

## Overview

Gleamit supports two usage modes:

- **Without an account** — your data stays only on your device.
- **With an account** — Gleamit stores synced app data both on your device and
  on Gleamit's backend so you can restore it on another device.

Creating an account is optional. The core app can still be used without one.

## Information We Store

Depending on how you use the app, Gleamit may store the following categories of
data.

### Data stored locally on your device

The app stores local data using on-device storage such as SQLite (via Drift),
SharedPreferences, and secure device storage.

This local data may include:

- **Brushing sessions** — timestamps, durations, and local calendar dates for
  completed brushing sessions.
- **Streak and derived progress data** — current streaks, best streaks, and
  related derived statistics stored to support app features.
- **Reminder settings** — reminder labels, enabled states, and reminder times.
- **Brush tracking data** — toothbrushes, brush heads, start dates, colors,
  and retirement/replacement state.
- **Dentist information** — dentist name, clinic, phone number, email address,
  postal address, and last cleaning date, if you choose to enter them.
- **Appointments** — appointment titles, dates, times, notes, and time zone
  information.
- **Floss tracking and onboarding state** — local feature state used by the app.
- **App preferences** — theme, language, and similar device-level preferences.
- **Authentication session data** — when you sign in, access credentials are
  stored locally in secure device storage so the app can keep you signed in.

### Data stored on Gleamit's backend when you use an account

If you create or sign into a Gleamit account, the app may store synced app data
on Gleamit's backend database so it can be restored later.

This synced account-backed data currently includes:

- brushing sessions
- toothbrushes
- brush heads
- reminders
- dentist information and last cleaning date
- appointments

The backend also stores account and authentication data needed to operate the
service, such as:

- your account email address
- your account display name
- password hashes and authentication-related token records
- account-level sync state needed to manage first-time backup and restore flows

Gleamit does **not** use cloud sync as a real-time collaborative or multi-user
service. It is designed as an account-based backup and restore system.

## How Account Sync Works

When you sign into an account, Gleamit may do one of the following:

- **First backup on that account** — upload eligible local data from your device
  to the backend.
- **Restore on a fresh device** — download previously backed-up data from the
  backend onto the device.
- **Server-wins replacement on a conflicting fresh device** — if the account
  already has a backup and the new device already contains meaningful local
  synced data, the app asks for confirmation before replacing the device's
  synced local data with the server backup.

Some settings remain device-local and are not treated as account-backed cloud
data, such as theme and language preferences.

## Logout and Account Deletion

If you log out:

- Gleamit clears the local authenticated session from the device.
- Gleamit removes account-owned local synced data from the device.
- Gleamit restores the signed-out local baseline needed for the app to keep
  functioning, such as default reminders and account-independent preferences.

If you delete your account from within the app:

- the account is deleted from Gleamit's backend
- synced backend data associated with that account is deleted
- the local authenticated session is cleared
- account-owned local data on the device is also cleared

Some purely device-level preferences may remain if they are not tied to the
account, such as theme or language settings.

## Notifications

Gleamit uses local notifications for:

- brushing reminders
- cleaning reminders
- brush replacement reminders
- appointment reminders

These notifications are scheduled locally on your device. Notification content
is not delivered through a remote push notification service by Gleamit at this
time.

## Password Reset

If you request a password reset, Gleamit may process the information needed to
verify the request and deliver password-reset instructions associated with your
account.

## How We Use Information

We use stored information only to operate Gleamit's features, including:

- saving and showing your oral hygiene records
- restoring account-backed data on another device
- keeping your signed-in session active
- scheduling local reminders and related notifications
- deleting account data when you request account deletion
- maintaining app reliability, security, and account integrity

We do not use your data for advertising profiling within the app.

## Third-Party Services and Infrastructure

Gleamit does not currently use third-party advertising networks or analytics
SDKs inside the mobile app.

However, when you use an account, your synced data may be processed or stored
through infrastructure providers used to host Gleamit's backend services and
databases.

## Data Sharing

We do not sell or rent your personal data.

We may share data only when necessary to operate the service, such as through
service providers that host Gleamit's backend infrastructure, or when required
by law.

## Data Retention

- If you use Gleamit without an account, your data remains on your device until
  you delete it, uninstall the app, or clear app storage.
- If you use a Gleamit account, synced account-backed data remains on the
  backend until you delete the account or until we need to remove it for legal,
  security, or operational reasons.

## Your Choices and Rights

You can:

- use the app without creating an account
- review and edit data inside the app
- log out to clear account-owned local data from a device
- delete your account from within the app
- uninstall the app or clear device storage to remove local app data

Depending on where you live, you may also have legal rights regarding personal
data stored on the backend, such as access, correction, or deletion rights.

## Children's Privacy

Gleamit is not directed to children under 13, and we do not knowingly collect
personal information from children under 13 through the service. If you believe
that a child has provided personal information, please contact us.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will reflect changes by
updating the "Last updated" date at the top of this page.

## Contact Us

If you have any questions about this Privacy Policy, please contact:

**Email:** lorenzozabot@gmail.com
