# StressMeasure — Support

**Last updated:** 2026-07-06

Welcome! This page covers how to get the most out of StressMeasure, common questions, and how to reach us.

---

## About StressMeasure

StressMeasure turns your Apple Watch into a simple stress tracker based on heart rate variability (HRV) — a signal widely used to reflect the body's stress and recovery. The iPhone companion shows your trends and history.

> ⚠️ StressMeasure is a **wellness indicator, not a medical device**. It does not diagnose or treat any condition.

**Highlights**
- One-minute active measurement on Apple Watch
- All-day background tracking from HRV
- Guided breathing (4s inhale / 6s exhale) with haptics
- High-stress alerts on your watch
- iPhone dashboard, day/week/month charts, and 30-day history
- Watch-face complication
- Available in English and Vietnamese (Tiếng Việt)

---

## Quick start

1. Install StressMeasure on your **iPhone**; the **Apple Watch** app installs alongside it.
2. Open the app and **grant all Health permissions** (HRV, heart rate, resting heart rate, respiratory rate, and mindful minutes). Full access is needed for the score to work.
3. On the watch, tap **Measure Now** and sit still for about a minute.
4. Your stress score (0–100) appears, and syncs to the iPhone dashboard.
5. Wear your watch through the day so the score personalizes to your own baseline.

---

## How the stress score works

1. **Baseline** — the app learns the mean and variation of your HRV over the last **14 days** (recomputed daily). Until you have at least 5 samples, a general population reference is used.
2. **Comparison** — your current HRV is compared with your baseline. HRV **below** your normal usually accompanies higher stress.
3. **Adjustment** — the score is nudged slightly based on how elevated your heart rate is versus your resting heart rate.
4. **Levels** — 0–29 **Low** · 30–59 **Moderate** · 60–79 **High** · 80–100 **Very High**.

---

## Frequently asked questions

### General

**Q: Do I need an Apple Watch?**
Yes. A real Apple Watch with a heart sensor is required to measure stress. The iPhone app shows trends and history but cannot measure on its own.

**Q: Do I need an account?**
No. StressMeasure works without sign-up and without any server.

**Q: Is my data private?**
Yes. Health data is processed on your device and stored via Apple Health. There is no server and no tracking. See the [Privacy Policy](policy.md).

### Measuring

**Q: Why don't I get a score right away?**
Until you have at least 5 HRV samples, the app uses a population reference (50 ± 20 ms). Wear your watch through the day and the score becomes personalized to your own 14-day baseline.

**Q: How do I take a measurement?**
Open the app on your Apple Watch, tap **Measure Now**, and sit still for about a minute. A fresh HRV reading is captured and scored.

**Q: The score didn't update in the background.**
watchOS records background HRV samples on its own schedule (typically every 1–2 hours while the watch is worn). Keep wearing the watch and background scores accumulate through the day.

**Q: My iPhone shows different / no data.**
The iPhone reads the same HealthKit data, which syncs between your devices. Make sure both devices are signed into the same iCloud account and that you granted Health access on the iPhone too.

### Breathing

**Q: What does guided breathing do?**
It runs a 4-second inhale / 6-second exhale exercise with gentle haptics (1–3 minutes), saves your **mindful minutes** to Health, and measures your HRV afterward.

### Alerts

**Q: How do high-stress alerts work?**
Enable them in **Settings** and pick a threshold (50–90). You'll be notified on your Apple Watch when your score reaches it, at most once every 2 hours.

**Q: I'm not getting alerts.**
Check:
1. Alerts are turned **on** in the app's Settings.
2. Notifications for StressMeasure are **allowed** on the Apple Watch.
3. A **Focus** / Do Not Disturb mode isn't silencing them.
4. Your watch has recorded a recent HRV sample above your threshold (background samples are infrequent).

### Complication

**Q: How do I add the watch-face complication?**
Long-press your watch face → **Edit** → choose a complication slot → select **StressMeasure**. Circular, corner, inline, and rectangular styles are supported.

---

## Troubleshooting

### The score seems stuck or blank
Open the watch app and take a manual measurement with **Measure Now**. If HealthKit permissions were denied, re-enable them in **Settings → Health → Data Access & Devices → StressMeasure**.

### Permissions were denied by mistake
Go to **Settings → Health → Data Access & Devices → StressMeasure** and enable all categories, then reopen the app.

### The app crashes on launch
1. Force-close the app.
2. Restart the device.
3. Update to the latest iOS / watchOS.
4. Update StressMeasure from the App Store.

If it still crashes, email us with your device models and OS versions.

---

## Send feedback or report a bug

Please include:

- Your **iPhone and Apple Watch models**
- Your **iOS / watchOS versions**
- Your **StressMeasure version**
- A clear description of what happened and what you expected
- (Optional) screenshots

**Email:** phanminhtam002@gmail.com

We'll do our best to respond within a few days.

---

## Hỗ trợ tiếng Việt

Ứng dụng song ngữ Việt–Anh. Tóm tắt nhanh:

- **Cần Apple Watch thật** có cảm biến nhịp tim để đo stress; app iPhone hiển thị xu hướng và lịch sử.
- **Cách đo:** mở app trên Apple Watch → chạm **Đo ngay** → ngồi yên khoảng 1 phút → nhận điểm (0–100).
- **Các mức:** 0–29 Thấp · 30–59 Vừa · 60–79 Cao · 80–100 Rất cao.
- **Cảnh báo stress cao:** bật trong Cài đặt và chọn ngưỡng (50–90); tối đa 2 giờ một lần.
- **Quyền riêng tư:** dữ liệu xử lý trên máy, lưu qua Apple Health, không có máy chủ, không theo dõi. Xem [Chính sách quyền riêng tư](policy.md).
- Đây là **chỉ số sức khỏe tham khảo, không phải thiết bị y tế**.

Mọi câu hỏi xin gửi **phanminhtam002@gmail.com**.

---

*Thank you for using StressMeasure. Take a breath.*
