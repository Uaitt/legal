# Privacy Policy

**Last updated: August 16, 2026**

**Policy version: 2026-08-16**

## Introduction

Gleamit ("we", "our", or "the app") is a mobile application that helps you
track oral hygiene habits such as brushing, flossing, reminders, brush
replacement, and dental care information. Gleamit is developed by **Lorenzo
Zabot, Milan, Italy**. This Privacy Policy explains what information Gleamit
stores and how it is handled.

Gleamit is designed to be private by default. There is **no Gleamit account
and no Gleamit backend**: your data is stored **on your device** and is not
sent to us. We do not use advertising networks, third-party analytics, or
tracking SDKs. The app connects to a third party in only two cases:

- to operate the optional in-app purchase, including checking at start-up
  whether you already own it (see "In-App Purchases"), and
- if you turn on the optional **cloud backup**, to keep a copy of your data in
  storage of your own (see "Cloud Backup"). It is off until you enable it, and
  the copy never reaches us.

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

The RevenueCat SDK also initialises when the app starts and checks the purchase
status, so that a purchase you already made (for example before a reinstall) is
recognised without you having to do anything. That check sends the anonymous
identifier and the technical information described above - nothing more. Your
oral hygiene data is **never** sent to RevenueCat or to your app store as part
of this process.

- Google Play billing: https://policies.google.com/privacy
- Apple App Store: https://www.apple.com/legal/privacy/
- RevenueCat: https://www.revenuecat.com/privacy/

## Cloud Backup

Gleamit's automatic safety net is the **cloud backup you turn on yourself**,
**off until you enable it**. Your device's
own system backup does **not** include Gleamit's data: app backup is switched
off on Android, and on iOS Gleamit's working files are marked as excluded from
the iCloud device backup. Gleamit's own cloud backup, described below, is a
separate copy that Gleamit puts there on purpose.

With cloud backup on, the app writes a copy of your data - your tracking records
(brushing and floss history, streaks, tooth map, dentist info, appointments,
brushes and reminders), your dentist documents and your smile photos - into
storage you control, on the frequency you choose in the app (daily, weekly or
monthly - weekly to start with - or only when you tap "Back up now", if you
choose the manual option) and only when new data is recorded. You can leave
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
  actually arrived. Automatic backups run when you leave the app, and Gleamit
  does not start one on mobile data unless you turn on "Back up using mobile
  data": on mobile data it waits for the next time you leave the app on Wi-Fi.
  An upload already under way finishes on whatever connection the device moves
  to. The "Back up now" button runs immediately on the connection you have, and
  a run you asked for that could not finish is retried the same way, mobile data
  included.

On Android, the sign-in is handled by Google and requests a single permission,
the app-scoped Drive storage area (`drive.appdata`). Gleamit receives your
account's email address, so it can show you which account holds the backup, and
an access token stored on your device. Gleamit cannot see any other file in your
Drive, and we never receive your backup: we cannot read, restore, or delete it.

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
  Gleamit, the app cannot back up. On Android your device's own power saving can
  also hold backups back indefinitely - Battery Saver while Gleamit's battery
  usage is "Optimized", or a manufacturer's app sleep setting applied to
  Gleamit. Gleamit shows these in the app rather than failing quietly, but it
  cannot fix them for you.
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

## How We Use and Share Information

Because your data stays on your device, we do not use it ourselves: the app
uses it locally only to operate its features. We do **not** use your data for
advertising or profiling, and we do **not** sell, rent, or share it. The only
third parties involved are the ones described above: your app store and
RevenueCat for the optional in-app purchase, and - only if you turn cloud
backup on - Apple (iCloud) or Google (Sign-In and Drive) holding your backup
under your own account and that company's terms (their privacy policies are
linked in "In-App Purchases").

## Exporting Your Data

Gleamit lets you export a full backup archive of your data (tracking records,
dentist documents and smile photos) so you can keep your own copy or move it to
another device, and generate a dentist report PDF from what you recorded. These
files are created on your device and shared by you through your device's own
sharing options; they are not sent to us, and you decide who receives them.

## Data Retention and Deletion

Your data remains on your device until you remove it. You can:

- delete individual items inside the app,
- clear the app's storage in your device settings, or
- uninstall the app.

Uninstalling the app or clearing its storage removes Gleamit's on-device data
from that device. If you turned cloud backup on, the copy Gleamit wrote stays
in your own cloud storage until you delete it there: on iOS by deleting
Gleamit's data in your iCloud settings, on Android by disconnecting Gleamit in
your Google Drive settings, as described in "Cloud Backup".

## Your Rights (EU/GDPR)

For the data you record in the app, we are not a data controller: it stays on
your device (and, if you enable cloud backup, in cloud storage of your own) and
never reaches us, so we could not access, correct, export, or delete it even on
request. The sections above explain how you do those things yourself.

For the optional in-app purchase, we act as the data controller, with
RevenueCat as our processor; your app store (Google or Apple) processes payment
data under its own terms. The legal basis is the performance of a contract
(Article 6(1)(b) GDPR), the data is limited to what is listed in "In-App
Purchases", and it is not used for any other purpose.

Under the GDPR you have the rights of access, rectification, erasure,
restriction, portability, and objection over that purchase data. To exercise
them, contact us at the email below. You also have the right to lodge a
complaint with a supervisory authority - in Italy, the Garante per la
Protezione dei Dati Personali.

## Medical Disclaimer

**Gleamit is not a medical device and does not give dental advice.** It is your
own record - it keeps track of what you log and shows it back to you, and it
never takes the health information you enter and returns an assessment of it.
Always consult your dental health professional when making decisions about your
teeth. The full disclaimer is in our
[Terms and Conditions](terms_and_conditions.md).

## Children's Privacy

Gleamit is a general-audience app and is **not directed to children**. We do not
knowingly collect personal information from children. Because the app has no
account of ours and no server of ours, any data entered stays on the device
under the control of the device's owner, who can remove it as described in
"Data Retention and Deletion".

## Changes to This Policy

We may update this Privacy Policy from time to time. We will reflect changes by
updating the "Last updated" date at the top of this page.

## Contact Us

If you have any questions about this Privacy Policy, please contact:

**Email:** lorenzozabot@gmail.com
