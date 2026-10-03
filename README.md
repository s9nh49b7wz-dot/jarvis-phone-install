# Jarvis for Your Phone 🤖

This repository helps you set up a Jarvis-style AI assistant on **Android** and **iPhone**.

---

## 📱 iPhone / iOS Version

### Important Reality Check
Apple does **not** allow third-party apps (or files) to have unrestricted control over the whole iPhone the way Android Accessibility Services do.  
Any app is sandboxed. True full-device control requires a jailbreak (not recommended — it breaks security and warranty).

What **is** possible:

### Option 1 — Instant Voice Jarvis (this repo)
A self-contained HTML file with **voice recognition** + speech replies.

**How to install on iPhone:**

1. Open this link on your iPhone in **Safari**:  
   https://raw.githubusercontent.com/s9nh49b7wz-dot/jarvis-phone-install/main/jarvis-iphone.html

2. Tap the **Share** button (square with arrow) → **Add to Home Screen**.

3. Name it "Jarvis" and tap **Add**.

4. Open the new icon on your Home Screen.  
   Tap the glowing orb and speak. It will listen and reply with voice.

> Note: Microphone permission will be requested the first time. This runs entirely in Safari / as a web app. It cannot open other apps or control system settings by itself.

### Option 2 — Deeper Control with Apple Shortcuts + Siri (Recommended for real usefulness)

This is the closest official way to get voice-controlled automation on iPhone:

1. Open the **Shortcuts** app (pre-installed).
2. Create a new Shortcut named **Jarvis**.
3. Add actions you want (examples):
   - Open App
   - Send Message
   - Set Alarm / Timer
   - Control HomeKit devices
   - Get Weather / Calendar
   - Run JavaScript / call an AI API (ChatGPT, Claude, Groq, etc.)
4. Then go to **Settings → Accessibility → Vocal Shortcuts** (iOS 18+) and train a phrase like "Hey Jarvis" that triggers your Shortcut.
   Or simply say **"Hey Siri, Jarvis"**.

This gives you real system access (apps, messages, HomeKit, alarms, etc.) through Apple’s official channels + voice recognition via Siri.

---

## 🤖 Android Version (Full Device Control Possible)

See the Android section below. Open Jarvis can control many parts of your phone via Accessibility Service.

### Recommended: Open Jarvis

1. Download the latest APK from:  
   https://github.com/tokenarc/open-jarvis/releases
2. Install it (allow unknown sources).
3. Grant Accessibility Service + Overlay permissions.
4. Add an AI provider (Groq is free) or use a local model.

---

## Summary

| Platform | Full Device Access | Voice Recognition | How |
|----------|--------------------|-------------------|-----|
| **Android** | Yes (via Accessibility) | Yes | Install Open Jarvis APK |
| **iPhone** | Limited (Apple sandbox) | Yes | Add `jarvis-iphone.html` to Home Screen + use Shortcuts/Siri for real control |

---

Made with ❤️. Enjoy your personal Jarvis!
