# Privacy Policy — FocusTimes

**Effective date:** 2026-06-05
**Last updated:** 2026-06-05

FocusTimes ("we", "our", "the app") is an iOS focus and study timer. We take your privacy seriously. This policy explains exactly what data the app handles and what it does not.

## TL;DR

> **FocusTimes does not collect, transmit, or share any personal data.** Everything you create — scenarios, session history, settings — stays on your device. We have no servers, no accounts, and no third-party trackers.

---

## 1. Information we do **not** collect

We do **not** collect, store on a server, or transmit any of the following:

- Your name, email address, phone number, or any account credentials
- Your device identifiers (IDFA, IDFV, advertising IDs)
- Your location, contacts, calendar, photos, or any other personal data
- Crash logs, analytics events, or usage telemetry
- IP addresses or network metadata

The app contains **no analytics SDKs, no advertising SDKs, and no third-party trackers**.

## 2. Information stored locally on your device

The following data is created by you and saved **only on your iPhone or iPad**. It never leaves your device:

| Data | Where it is stored | Purpose |
|---|---|---|
| Custom scenarios you create | SwiftData (local database) | So you can re-use your focus routines |
| Completed session history | SwiftData (local database) | So you can see your stats and streak |
| App preferences (haptics, notifications, sound, volume, mute, onboarding state) | iOS UserDefaults | So your settings persist between launches |

This data is included in your **device backup** (iCloud Backup or encrypted iTunes backup) if you have backups enabled, **but it is not sent to us or anyone else**. Apple manages those backups under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

You can delete all of this data at any time by deleting the app from your device.

## 3. iOS system features we use

FocusTimes integrates with the following iOS system features. These run entirely on your device.

### Notifications (local only)
We use Apple's `UNUserNotificationCenter` to schedule local notifications when a focus or break phase ends. These notifications are generated and shown locally by iOS — they are not pushed from a server. We do not receive any data about whether you opened, dismissed, or interacted with them. You can disable notifications at any time in **Settings → FocusTimes → Notifications** or inside the app's **Settings**.

### Live Activities & Dynamic Island
We use Apple's `ActivityKit` to display the currently running session on your Lock Screen and Dynamic Island. The activity data (phase title, countdown end time, scenario name) is held in memory by iOS and shown on your device only.

### Audio playback
We play short ambient sounds bundled inside the app (no streaming, no downloads). The audio uses Apple's `AVAudioSession` with the `mixWithOthers` option so it can play alongside your other media.

### Haptics
We use `UINotificationFeedbackGenerator` to vibrate the device on phase transitions when haptics are enabled in settings.

## 4. Third-party services

**None.** FocusTimes does not use any third-party SDKs, services, or APIs. The app never makes a network request.

## 5. Children's privacy

FocusTimes is appropriate for all ages and does not knowingly collect data from anyone, including children under 13. Because we collect no data at all, no special handling is required under COPPA or similar regulations.

## 6. Your rights (GDPR, CCPA, and similar)

Because we do not collect or store any of your data on our servers, requests for access, deletion, correction, or portability are not applicable. You retain full control of your data — it lives on your device, and deleting the app deletes the data.

If you have questions about your rights under GDPR (EU), CCPA (California), or similar regulations, contact us using the address below.

## 7. Changes to this policy

If we change this policy, we will update the "Last updated" date at the top of this page. Material changes will also be noted in the App Store release notes for the version that introduces them.

## 8. Contact

Questions or concerns about this privacy policy?

- **Email:** phanminhtam002@gmail.com
- **App Store:** https://apps.apple.com (search "FocusTimes")

---

*This policy is provided in good faith based on the app's current behavior. If you discover behavior that contradicts this policy, please report it to the email above — we will investigate and correct it promptly.*
