# Privacy Policy

**Last updated: August 13, 2026**

**Policy version: 2026-08-13**

## Introduction

Gleamit ("we", "our", or "the app") is a mobile application that helps you
track oral hygiene habits such as brushing, flossing, reminders, brush
replacement, and dental care information. This Privacy Policy explains what
information Gleamit stores and how it is handled.

Gleamit is designed to be private by default. There is **no Gleamit account and
no Gleamit backend**. Your data is stored **on your device** and is not sent to
us.

## Overview

- Gleamit works entirely **on-device**. There is no Gleamit sign-up, no Gleamit
  account, and no Gleamit cloud.
- We do **not** operate a backend that receives, stores, or syncs your data.
- We do **not** use advertising networks, and we do **not** embed third-party
  analytics or tracking SDKs.
- The app connects to a third party in only two cases: to process an optional
  in-app purchase (see "In-App Purchases" below), and, if you turn on cloud
  backup, to store that backup in your own cloud storage (see "Cloud Backup").
- You can turn on an optional **cloud backup** that keeps a copy of your data in
  storage of your own (see "Cloud Backup" below). It is off until you enable it,
  and the copy never reaches us.
- On Android, turning cloud backup on asks you to connect a Google account. That
  sign-in is optional, belongs to Google rather than to us, and is scoped to the
  hidden Gleamit-only area of your own Google Drive - nothing else.

## Information Stored on Your Device

Gleamit stores your data locally using on-device storage. This data stays on
your device unless you choose to export it, or unless you turn on cloud backup
(see "Cloud Backup").

Local data may include:

- **Brushing sessions** - timestamps, durations, local calendar dates, and the
  time zone in which a session was recorded.
- **Floss sessions** - completion timestamps.
- **Streak and derived progress data** - current streaks, best streaks, and
  related statistics.
- **Reminder settings** - reminder labels, times, and enabled states.
- **Brush tracking data** - toothbrushes and brush heads, including names,
  start dates, colors, and retirement/replacement state.
- **Dentist information** - dentist name, clinic, phone number, email address,
  postal address, and last cleaning date, if you choose to enter them.
- **Appointments** - appointment type, date, time, notes, and time zone.
- **Tooth map data** - per-tooth conditions, optional notes, and a local
  history of changes.
- **Dentist documents** - files you choose to attach (for example scans or
  images), stored in the app's private storage.
- **Smile photos** - photos you choose to add, stored in the app's private
  storage, with optional captions and dates.
- **Dentist report settings** - the name you choose to print on the dentist
  report.
- **App preferences** - theme, language, onboarding and disclaimer
  acknowledgement state, and whether you dismissed the backup reminder.
- **Cloud backup settings** - whether cloud backup is on, how often it runs,
  which parts are included, whether it may use mobile data on Android, the
  Google account you connected on Android, and when the last backup ran or
  failed.
- **Purchase state** - a local flag recording whether the "Pro" upgrade is
  active, so the app can work offline.

When you generate the dentist report, the PDF is built on your device from the
data listed above and written to your device's temporary storage so that you can
share it. Your device clears that temporary storage; the report is never sent to
us. The same applies to backup archives you export.

We do not have access to any of this data. It is not transmitted to us.

## In-App Purchases

Gleamit offers a single optional one-time in-app purchase ("Pro") that unlocks
additional features. Purchases are handled by **your app store's billing system**
(Google Play Billing or the Apple App Store) and by **RevenueCat**, a third-party
billing infrastructure provider that validates and manages the purchase.

When you make or restore a purchase, purchase-related information may be
processed by your app store and RevenueCat, such as:

- the purchase token and product identifier issued by the app store,
- an anonymous app-generated user identifier created by the RevenueCat SDK
  (not linked to a Gleamit account, because there is no Gleamit account),
- technical information used to validate the receipt and prevent fraud, such as
  device/app and network information.

This processing happens **only** if you interact with the purchase flow. If you
never open or use the purchase feature, the app does not contact RevenueCat.
Your oral hygiene data is **never** sent to RevenueCat or to your app store as
part of this process.

- Google Play billing: https://policies.google.com/privacy
- Apple App Store: https://www.apple.com/legal/privacy/
- RevenueCat: https://www.revenuecat.com/privacy/

## Cloud Backup

Gleamit has no server of its own, so its automatic safety net is a **cloud
backup you turn on yourself**. It is **off until you enable it**. Your device's
own system backup does **not** include Gleamit's data: app backup is switched
off on Android, and on iOS Gleamit's working files are marked as excluded from
the iCloud device backup. Gleamit's own cloud backup, described below, is a
separate copy that Gleamit puts there on purpose.

With cloud backup on, the app writes a copy of your data - your tracking records
(brushing and floss history, streaks, tooth map, dentist info, appointments,
brushes and reminders), your dentist documents and your smile photos - into
storage you control, on the frequency you choose in the app (daily, weekly or
monthly - weekly to start with) and only when something changed. You can leave
your smile photos or your dentist documents out of that copy; turning one off
also removes it from that storage. It keeps the latest copy only, replacing it
each time.

Where that copy goes depends on your platform:

- **iOS** - Gleamit's own private area of **your iCloud Drive**, hidden from the
  Files app so it cannot be moved or deleted by accident. iCloud is a service
  managed by Apple and running under your own Apple Account: Apple's software
  uploads and stores those files under Apple's terms, and what Apple can access
  depends on your iCloud settings, not on us. Gleamit writes the files locally;
  when they reach iCloud, and whether they use mobile data, is governed by your
  iCloud settings.
- **Android** - the hidden, app-scoped area of **your own Google Drive** (the
  "app data" folder), which only Gleamit can see and which does not appear in
  your Drive file list. To use it, you connect a Google account of yours in the
  app. Gleamit uploads the backup itself, so it can tell you when your data
  actually arrived. Automatic backups run overnight and wait for Wi-Fi unless
  you turn on "Back up using mobile data"; the "Back up now" button runs
  immediately on whatever connection you have.

On Android, the sign-in is handled by Google and requests a single permission,
the app-scoped Drive storage area (`drive.appdata`). Gleamit receives your
account's email address, so it can show you which account holds the backup, and
an access token stored on your device. Gleamit cannot see any other file in your
Drive. We do not receive any of this: there is no Gleamit account and no Gleamit
server involved. We never receive your backup and cannot read, restore, or
delete it.

Some things worth knowing:

- **The files are not encrypted by Gleamit.** They are ordinary, readable files
  in storage you control, the same as a backup archive you export yourself.
  Google and Apple encrypt them in transit and at rest like anything else in
  your storage, but there is no end-to-end encryption and no passphrase: how
  well the backup is protected depends on your account with that provider and
  your device settings.
- **Disconnecting Gleamit in Google Drive deletes the backup.** The app-scoped
  area belongs to the app: if you remove Gleamit from your Google Account's
  connected apps (Drive settings, "Manage apps"), Google deletes the hidden
  backup along with it. That is also how you delete the backup deliberately.
- **Switching or disconnecting the account inside Gleamit deletes nothing.**
  Choosing another Google account points future backups at that account and
  leaves the earlier copy where it is; disconnecting simply turns cloud backup
  off. No part of the app deletes a remote backup on its own, except the media
  parts you explicitly exclude.
- **Backups can stop.** If your cloud storage is full, if you withdraw
  Gleamit's access to your Google account, or if iCloud Drive is off for
  Gleamit, the app cannot back up. Gleamit shows this in the app rather than
  failing quietly, but it cannot fix it for you.
- **Restoring happens in the app.** On a new device you install Gleamit and
  restore from your backup yourself; the operating system will not bring
  Gleamit's data back on its own.
- **Turning cloud backup off** stops future backups. The copy already in your
  storage stays there until you delete it.

## Notifications

Gleamit uses **local notifications** scheduled on your device for reminders such
as brushing reminders, cleaning reminders, brush replacement reminders, and
appointment reminders. These notifications are generated on-device. Gleamit does
**not** use remote push notifications and does not operate a notification server.

## How We Use Information

Because your data stays on your device, we do not use it ourselves. The app uses
your data locally only to operate its features, such as:

- saving and showing your oral hygiene records,
- calculating streaks and insights,
- scheduling local reminders,
- rendering and sharing a dentist report you generate.

We do **not** use your data for advertising or profiling.

## Data Sharing

We do **not** sell, rent, or share your personal data.

The only third parties involved are your app store's billing system (Google Play
Billing or the Apple App Store) and RevenueCat, and only for processing the
optional in-app purchase described above. If you turn on cloud backup, your
backup files also sit with Apple (iCloud) or Google (Drive), under your own
account with that company - we do not share them with anyone, and we never see
them (see "Cloud Backup").

## Exporting Your Data

Gleamit lets you export your data (including a full backup archive of your
tracking data - brushing and floss history, streaks, tooth map, dentist info,
appointments, brushes and reminders - together with your vault documents and
smile photos) so you can keep your own copy or move it to another device. You can
also generate a dentist report PDF from the data you recorded. Exported files and
generated reports are created by you, shared through your device's own sharing
options, and are not sent to us.

## Data Retention and Deletion

Your data remains on your device until you remove it. You can:

- delete individual items inside the app,
- clear the app's storage in your device settings, or
- uninstall the app.

Uninstalling the app or clearing its storage removes Gleamit's on-device data
from that device. If you turned cloud backup on, the copy Gleamit wrote stays in
your own cloud storage until you delete it there: on iOS by deleting Gleamit's
data in your iCloud settings, on Android by removing Gleamit from the connected
apps in your Google Drive settings ("Manage apps"), which deletes the hidden
backup with it.

## Medical Disclaimer

**Gleamit is not a medical device and does not give dental advice.** It is your
own record - it keeps track of what you log and shows it back to you. Always
consult your dental health professional when making decisions about your teeth.

Gleamit is not intended to diagnose, treat, cure, or prevent any disease or
condition, and it never takes the health information you enter and returns an
assessment of it. In particular:

- **The tooth conditions and notes you record are your own notes, not
  findings.** You choose each tooth's condition yourself, including "Problem".
  The app stores that label and shows it back to you; it never examines,
  assesses, or interprets it.
- **The educational content is general information, not personalised advice.**
  It is the same static text for every user and is not driven by anything you
  enter.
- **The dentist report is a self-reported summary, not a clinical record.** It
  renders what you entered - including the tooth conditions and notes you chose -
  and every page says so.

## Children's Privacy

Gleamit is a general-audience app and is **not directed to children**. We do not
knowingly collect personal information from children. Because the app has no
account of ours and no server of ours, any data entered stays on the device
under the control of the device's owner. If you believe a child has used a
device in a way that concerns you, you can clear the app's storage or uninstall
the app to remove the on-device data.

## Third-Party Services and Infrastructure

Gleamit does not use third-party advertising networks or analytics SDKs. The
third-party services the app itself contacts are your app store's billing system
(Google Play Billing or the Apple App Store) and RevenueCat, used solely for the
optional in-app purchase, and - only if you turn cloud backup on - Google Sign-In
and Google Drive on Android.

If you turn on cloud backup, the files Gleamit writes are stored by the platform
you are on - Apple's iCloud on iOS, or the hidden app-scoped area of your own
Google Drive on Android - under your own account and that company's terms (see
"Cloud Backup"):

- Google (Sign-In and Drive): https://policies.google.com/privacy
- Apple (iCloud): https://www.apple.com/legal/privacy/

## Changes to This Policy

We may update this Privacy Policy from time to time. We will reflect changes by
updating the "Last updated" date at the top of this page.

## Contact Us

If you have any questions about this Privacy Policy, please contact:

**Email:** lorenzozabot@gmail.com
