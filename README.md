# SoulBTL — Android App Downloads

Two SoulBTL Android apps are available — pick either (same account, same data):

## 📱 SoulBTL (WebView app)
Lightweight WebView wrapper of the web app.

**➡️ [SoulBTL-v1.5.9.apk](SoulBTL-v1.5.9.apk)** (versionCode 24 — latest)

## ⚡ SoulBTL Native (pure native, zero WebView)
Fully native Android app — direct Supabase connection, fast offline-friendly shell, built-in reminders & PDF export.

**➡️ [SoulBTL-Native-v2.1.0-native.apk](SoulBTL-Native-v2.1.0-native.apk)** (versionCode 2 — latest)

## Install

1. Download the APK (button above / tap the file)
2. Android may ask "Allow installing unknown apps" for your browser — allow it once
3. Open the APK → Install → open SoulBTL

Updates install directly over older versions (same signing key) — data is safe.
Both apps can be installed side-by-side (different package names).

## Recent changes

### SoulBTL Native (2.1.0-native)
- **2.1.0** — 📄📊 download customers as **PDF or Excel** (single card or full table); 📝 **notes thread** (add/done/delete + reminder date); 💬 WhatsApp send auto-logs history; 🎛️ area/business/birthday-month/anniversary-month filters; 🔔 daily 9 AM local reminders (AlarmManager, reboot-safe)
- **2.0.0** — first native release: login/signup/OTP, customers, reminders, alerts, plan, WhatsApp quick-send, CSV export, instant-boot cache

### SoulBTL (WebView)
- **1.5.9** — ⚡ one-tap WhatsApp quick-send from birthdays/anniversaries (opens WhatsApp directly, no browser hop; hold = edit message)
- **1.5.8** — instant boot (cached shell), cache hygiene on logout + every 12h
- **1.5.6** — admin subscriptions, golden Lifetime card
