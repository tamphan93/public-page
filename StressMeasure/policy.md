# Privacy Policy — StressMeasure

**Effective date:** 2026-07-06
**Last updated:** 2026-07-06

StressMeasure ("we", "our", "the app") is a wellness app for Apple Watch and iPhone that estimates a stress score from your heart rate variability (HRV). We take your privacy seriously. This policy explains exactly what data the app handles and what it does not.

## TL;DR

> **StressMeasure has no servers and collects no personal data.** Your health data is read on your device through Apple HealthKit, used only to calculate your stress score, and stays on your device / in Apple Health. We have no accounts and no third-party trackers. We never sell or share your data.

---

## 1. Information we do **not** collect

We do **not** collect on a server, or transmit to us, any of the following:

- Your name, email address, phone number, or any account credentials
- Your device identifiers (IDFA, IDFV, advertising IDs)
- Your location, contacts, calendar, or photos
- Crash logs, analytics events, or usage telemetry
- IP addresses or network metadata

The app contains **no analytics SDKs, no advertising SDKs, and no third-party trackers**, and does not operate any backend server of its own.

## 2. Health data the app uses

With your explicit permission (through Apple **HealthKit**), StressMeasure reads the following health data to calculate your stress score:

| Data | Access | Purpose |
|---|---|---|
| Heart rate variability (HRV / SDNN) | Read | Core input to the stress score and your baseline |
| Heart rate | Read | Adjusts the score relative to your resting rate |
| Resting heart rate | Read | Reference for the heart-rate adjustment |
| Respiratory rate | Read | Additional context signal |
| Mindful minutes | Write | Saved to Health when you finish a breathing exercise |

This data is processed **locally** on your iPhone and Apple Watch. It is stored by **Apple Health** and in a private app container shared between the app's own components (an **App Group**). It is **never** transmitted to a server operated by us.

Health data is **not** used for advertising and is **not** shared with or sold to any third party, in accordance with Apple's HealthKit requirements.

## 3. Information stored locally on your device

The following is created by the app and saved **only on your devices**:

| Data | Where it is stored | Purpose |
|---|---|---|
| Your stress scores and history | App Group container | Show your dashboard, trends and 30-day history |
| Your 14-day HRV baseline | App Group container | Personalize the score to you |
| App preferences (alerts on/off, alert threshold) | UserDefaults | Persist your settings between launches |

Settings sync directly between your iPhone and Apple Watch using Apple's **WatchConnectivity** (device to device). This data may be included in your **device backup** (iCloud or encrypted local backup) if you have backups enabled, but it is not sent to us. Apple manages backups under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

You can delete all local app data at any time by deleting the app. Data written to Apple Health (mindful minutes) can be managed or removed in the Health app.

## 4. iOS / watchOS system features we use

These run entirely on your devices:

### HealthKit
Used to read heart data and write mindful minutes, as described above. You grant access on first launch and can change it any time in **Settings → Health → Data Access & Devices → StressMeasure**.

### Background delivery (watchOS)
The watch app uses HealthKit background delivery of HRV samples to keep your score up to date through the day. Samples are recorded by watchOS on its own schedule and processed on device.

### Notifications (local only)
If you enable high-stress alerts, the app schedules **local** notifications on your Apple Watch when your score crosses your chosen threshold (at most once every 2 hours). These are generated on your device — nothing is pushed from a server.

### Extended runtime & haptics
The 1-minute active measurement uses an Apple mind-and-body runtime session (the same mechanism as the Breathe app) so watchOS samples heart data. Guided breathing uses haptics on device.

## 5. Third-party services

**None.** StressMeasure does not use any third-party SDKs, services, or APIs, and does not make network requests to any server we control.

## 6. Children's privacy

StressMeasure is not directed to children under 13 and does not knowingly collect data from them. Because we collect no data on any server, no special handling is required under COPPA or similar regulations.

## 7. Your rights (GDPR, CCPA, and similar)

Because we do not collect or store your data on our servers, requests for access, deletion, correction, or portability are handled entirely by you on your device and in Apple Health. If you have questions about your rights under GDPR (EU), CCPA (California), or similar regulations, contact us below.

## 8. Medical disclaimer

StressMeasure is a **wellness indicator, not a medical device**. It is not intended to diagnose, treat, cure, or prevent any disease or condition. Consult a qualified healthcare provider for medical advice.

## 9. Changes to this policy

If we change this policy, we will update the "Last updated" date above. Material changes will also be noted in the App Store release notes for the version that introduces them.

## 10. Contact

Questions or concerns about this privacy policy?

- **Email:** phanminhtam002@gmail.com
- **App Store:** https://apps.apple.com (search "StressMeasure")

---

*This policy is provided in good faith based on the app's current behavior. If you discover behavior that contradicts this policy, please report it to the email above — we will investigate and correct it promptly.*
