# Privacy Policy

**Effective date:** November 27, 2026  
**App:** Klyki  
**Package ID:** `com.onozek.klyki`  
**Developer:** ONOZEK  
**Contact:** [onozek@gmail.com](mailto:onozek@gmail.com)

---

## 1. Introduction

**Klyki** is a privacy-first AI-powered Android keyboard application developed by **ONOZEK**. It helps you fix grammar, adjust tone, translate, summarize, and run custom AI commands directly from the keyboard command bar while typing across apps.

Your privacy matters. This Privacy Policy explains what information Klyki accesses on your device, when data is transmitted to third-party services, and what rights and controls you have.

---

## 2. How Klyki Works (Zero-Keystroke-Logging)

Klyki operates as a standard Android keyboard (**Input Method Service**), not an Accessibility Service, and **never logs, tracks, records, or transmits your keystrokes or typing history**.

- **No Background Keystroke Collection:** Normal typing stays strictly on your device for local keyboard input, autocorrect, and word predictions.
- **Explicit AI Actions Only:** Text leaves your device **only** when you explicitly tap an AI command/suggestion pill or type and trigger an AI command (such as `?fix`, `?tr`, `?summary`, or a custom command). Only the relevant text snippet and command instruction are sent directly to your configured AI provider.
- **Sensitive Field & App Protections:** Klyki automatically hides AI command tools in password and sensitive numeric fields, and you can block Klyki's AI bar in any specific app at any time using **Privacy & Blocked Apps**.

---

## 3. Information Sent to AI Providers

Klyki lets you configure your own AI providers, including:

- Google Gemini
- OpenAI
- Groq
- Anthropic Claude
- Custom OpenAI-compatible HTTPS endpoints

When you trigger an AI command, the selected text and prompt are sent **directly from your device** to the AI provider you selected over HTTPS. **ONOZEK does not operate an intermediary server** to receive, inspect, or store your messages, prompts, or AI responses.

Each third-party AI provider processes submitted content under its own privacy policy and terms of service. We do not control how external AI providers handle data once transmitted.

---

## 4. API Keys & On-Device Storage

Klyki stores your preferences and user-created items **locally on your device**:

- **Encrypted Sensitive Keys:** Your AI provider API keys and Gumroad license key are encrypted at rest using **Android hardware-backed Keystore (AES-256-GCM)** inside Klyki's private app storage.
- **Local App Data:** Built-in and custom AI commands, custom keyboard themes (including images imported via Android's zero-permission Photo Picker), pinned clipboard items, personal dictionary words, blocked app selections, on-device productivity counters, and optional offline language packs are stored locally on your device.
- **No ONOZEK Account Server:** ONOZEK does not operate a server that collects your API keys, custom commands, custom themes, clipboard items, or dictionary words.

Note that Android device backups (when enabled in system settings) or physical/root device access may affect locally stored app data.

---

## 5. Free Trial, Rewarded Video Unlock & Gumroad Lifetime Purchases

Klyki offers three independent access modes:

- **7-Day New-User Free Trial:** New users receive 7 days of ad-free access, Custom Commands, and Custom Theme Studio. Trial timestamps are stored locally on your device.
- **24-Hour Rewarded Video Pass:** After the trial, you may watch an optional rewarded video ad to unlock Custom Commands and Custom Themes for 24 hours (banner ads remain visible). When the pass expires, your saved custom commands and themes remain safely preserved on your device and are never deleted.
- **Klyki Premium – Lifetime ($2.99 USD via Gumroad):**
  - Purchases are processed directly by **Gumroad** (`https://onozek.gumroad.com/l/klyki-premium`) under Gumroad's Privacy Policy and Terms. ONOZEK does not collect or store your payment card or billing details in the app.
  - **License Verification & Device Limits:** Entering a license key sends the key and Klyki's product identifier directly to Gumroad's License API (`https://api.gumroad.com/v2/licenses/verify`) to verify purchase authenticity, enforce the **maximum 2 devices per license** limit, and restore licenses on the same device.
  - **Refund & Dispute Validation:** Klyki periodically re-checks your encrypted license status in the background (and when you tap **Check License Status**) without consuming extra device slots, solely to verify that the license has not been refunded, disputed, or charged back.
  - **Local License Metadata:** Klyki stores a masked version of your key, a cryptographic SHA-256 hash, the purchase email returned by Gumroad (if any), and active device count locally. You can unlink the current device at any time via **Deactivate This Device** without losing your saved custom commands or themes.

---

## 6. Advertising & Consent (Google AdMob & UMP)

Unless you have an active 7-day free trial or verified Lifetime license, Klyki displays banner ads—and offers optional rewarded video ads—served by **Google AdMob**.

- Google AdMob may collect your Advertising ID, IP address, and device/interaction signals to deliver and measure ads in accordance with Google's Privacy Policy.
- **Consent Management:** On first launch in eligible regions (such as the EU, UK, and Switzerland), Klyki presents Google's **User Messaging Platform (UMP)** consent dialog so you can choose personalized or non-personalized ads. You can update your consent preference anytime under **Settings → Ad Privacy Choices**.
- Klyki explicitly opts out of deprecated Privacy Sandbox AdServices permissions in its Android manifest.

---

## 7. Analytics & Crash Reporting

Klyki uses **Firebase Analytics** and **Firebase Crashlytics** (Google) to measure high-level feature reliability and diagnose app crashes:

- **Privacy-Safe Events Only:** Analytics events record only anonymized usage signals (such as app opens, theme or language changes, and error states). Klyki strictly blocks keystrokes, user text, AI prompts/outputs, API keys, and license keys from analytics or crash logs.
- Crashlytics collects stack traces, device model, OS version, and app version when unexpected errors occur.

---

## 8. Permissions We Use

Klyki follows a strict least-privilege approach:

- **Internet (`android.permission.INTERNET`):** Required only for sending your explicit AI requests to your chosen AI provider, verifying Gumroad licenses, downloading optional language packs, loading ads, and sending anonymized crash/analytics diagnostics.
- **Zero-Permission Media Selection:** Custom Theme Studio uses Android's built-in Photo Picker so Klyki never requests broad gallery or external storage permissions.
- **No Accessibility, Location, Camera, Contacts, or Overlay Permissions:** Klyki does not request or use these permissions.

---

## 9. Children's Privacy

Klyki is not directed to children under 13 (or the applicable minimum age in your jurisdiction), and ONOZEK does not knowingly collect personal information from children.

---

## 10. Your Rights & Data Deletion

Because your commands, themes, API keys, clipboard clips, and dictionary words live locally on your device, you can delete them anytime within Klyki, clear app storage in Android settings, or uninstall the app to remove all local data. For questions about this Privacy Policy, contact **ONOZEK** at [onozek@gmail.com](mailto:onozek@gmail.com).

---

## 11. Changes to This Policy

We may update this Privacy Policy as Klyki evolves. Any updates will be published at [`https://onozek.github.io/klyki-legal/privacy-policy`](https://onozek.github.io/klyki-legal/privacy-policy) with an updated effective date.
