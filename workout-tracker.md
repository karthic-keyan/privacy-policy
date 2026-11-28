# Privacy Policy for Workout Tracker

**Last Updated:** November 28, 2026  
**Effective Date:** November 13, 2026  
**Application Name:** Workout Tracker  
**Package Name / Application ID:** `com.ironlogtracker.app`  
**Developer / Publisher:** k-Tech Innovation (KTech Innovation / Karthikeyan)  
**Google Play Store Listing:** [Workout Tracker on Google Play](https://play.google.com/store/apps/details?id=com.ironlogtracker.app)  
**Hosted Privacy Policy URL:** [https://karthic-keyan.github.io/privacy-policy/workout-tracker.html](https://karthic-keyan.github.io/privacy-policy/workout-tracker.html)  
**Contact Email:** ktechinnovationltd@gmail.com / karthik.devacc@gmail.com  
**Developer Organization:** [https://github.com/k-Tech-innovation](https://github.com/k-Tech-innovation)  

---

## 1. Introduction & Overview

Welcome to **Workout Tracker** ("we", "our", or "us"), developed and published by **k-Tech Innovation**. We take your personal privacy seriously. This Privacy Policy explains our practices regarding user data, device permissions, and security for the **Workout Tracker** mobile application for Android (`com.ironlogtracker.app`).

Workout Tracker is a privacy-first fitness app that works offline. We do not operate user accounts, we do not sync your workout logs to any cloud database, and your workouts, body measurements and profile never leave your device. The app does not currently show ads. It includes Google's AdMob advertising SDK so that ads can be added in a future update; Section 5 explains what Google would collect if ads are shown.

---

## 2. Summary

* 🛡️ **Your workout data stays on your device:** We (k-Tech Innovation) do not collect, receive, sell, or share your workouts, personal records, profile, or body weight.
* 📶 **Works offline:** All workout routines, custom exercises, sets, weights, repetitions, and personal records (PRs) are stored in the app's private storage on your device. Logging workouts never needs an internet connection.
* 📢 **Advertising:** The app does not currently show ads. It includes the Google Mobile Ads SDK (AdMob) for possible future use; if ads are shown, Google may collect your device's advertising ID and other device and usage information, as described in Section 5.
* 🔒 **No Account Required:** You can use every feature of Workout Tracker without providing your name, email address, phone number, or social media logins.
* 📊 **No analytics SDKs from us:** We do not add analytics or crash-reporting frameworks (no Google Analytics for Firebase, Mixpanel, or Facebook SDK).

---

## 3. Information Handled Strictly Locally

All data created or modified while using Workout Tracker is processed on your device's local CPU and saved strictly within local application sandboxed storage (`AsyncStorage`):

1. **Workout Logs & Performance Metrics:**
   * Exercise names, muscle group categorizations, equipment types, and notes.
   * Set metrics: weights lifted, target repetitions, completed repetitions, and custom set tags.
   * Calculated training volume (tonnage) and elapsed session durations.
   * Personal record (PR) timestamps and milestones.
2. **Templates & Custom Exercises:**
   * User-defined workout splits and templates (e.g., Push/Pull/Legs).
   * Custom exercise definitions, custom target muscle groups, and movement setup notes.
3. **Application Preferences:**
   * Display toggles (total volume, workout count, sets logged).
   * Visual theme and unit configurations (kg vs. lbs).

---

## 4. Device Permissions & How They Are Used

Workout Tracker requests only minimal permissions strictly required to execute user-directed features:

| Permission | Technical Requirement | Explicit Usage |
| :--- | :--- | :--- |
| **VIBRATE** | `android.permission.VIBRATE` | Triggers responsive haptic feedback when you tap to complete a set or interact with weight steppers. No sensory or biometric data is accessed. |
| **System Clipboard & Sharing** | Android OS Share Sheet Intent | Used solely when you tap "Share with AI" or "Copy Workout Summary" to send your workout text to clipboard or external note apps. This is 100% user-directed; no automated background transmissions occur. |
| **Local File Access** *(Optional)* | Scoped Storage / Storage Access Framework | Used strictly if you manually trigger an export or import of a local workout backup file. |

| **INTERNET** | `android.permission.INTERNET` | Reserved for the Google Mobile Ads SDK to request ads if ads are added in a future update. Your workout data is never sent over the network. |
| **Advertising ID** | `com.google.android.gms.permission.AD_ID` | Lets the Google Mobile Ads SDK read your device's advertising ID for ads (see Section 5). You can reset or delete this ID in your device settings. |

Workout Tracker does **NOT** request access to sensitive permissions such as location (`ACCESS_FINE_LOCATION`), camera, microphone, contacts, biometric credentials, or phone state.

---

## 5. Advertising (Google AdMob)

Workout Tracker includes the **Google Mobile Ads SDK (AdMob)**, provided by Google LLC. **The app does not currently request or show ads.** If ads are added in a future update, we will update this policy and the app's Google Play listing first. When the app requests an ad, the SDK may collect and send to Google:

* **Device identifiers:** the Android advertising ID and the app set ID.
* **Approximate location:** derived from your IP address.
* **Usage and diagnostic information:** such as ad views and taps, app launches, device model, operating system version, and SDK performance and crash data.

Google uses this information to deliver, measure, and personalize ads and to prevent fraud. It is handled under [Google's Privacy Policy](https://policies.google.com/privacy) and [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites).

Your choices:

* You can reset your advertising ID, or delete it to opt out of personalized ads, in your device settings (*Settings > Privacy > Ads*, or *Settings > Google > Ads* on some devices).
* Your workouts, personal records, profile, and body weight are **never** shared with Google or any ad network.

We do not sell your data, and we do not use any analytics or data-broker services.

---

## 6. Google Play Data Safety Section Declarations

Workout Tracker declares the following in the Google Play Console **Data safety** form:

* **Data collected and shared:** Device or other IDs (advertising ID), declared because the Google Mobile Ads SDK and the advertising ID permission are included in the app. Workout data is never collected.
* **Is all of the user data collected by your app encrypted in transit?**  
  👉 **Yes.** The Google Mobile Ads SDK uses encrypted (HTTPS) connections.
* **Does your app use the advertising ID?**  
  👉 **Yes**, through the Google Mobile Ads SDK, for advertising.
* **Does your app provide a way for users to request that their data be deleted?**  
  👉 **Yes.** All workout data is stored only on the device and can be erased at any time (see Section 7). The advertising ID can be reset or deleted in device settings.
* **Does your app contain ads?**  
  👉 **No**, not at present. This will be changed to **Yes** before any ads are shown.

---

## 7. Data Retention, Control & Deletion Policy

Because all workout information is stored exclusively on your device, **you have 100% autonomy and control over your data**:

1. **In-App Deletion:** You can delete individual exercises, workout sessions, or templates directly from their respective screens in the app.
2. **Device Data Clear:** You can permanently erase all stored workouts, settings, and custom exercises at any time through your Android device settings:  
   *Go to `Settings > Apps > Workouts > Storage & cache > Clear storage`.*
3. **Uninstall Deletion:** Completely uninstalling Workout Tracker from your Android device immediately and permanently deletes all associated local application storage.

---

## 8. Children's Privacy (COPPA & GDPR-K Compliance)

Workout Tracker is not directed at children under the age of 13 (or under the age of 16 in the European Union), and we do not knowingly collect personal information from them. Workout data entered in the app never leaves the device, whatever the user's age.

---

## 9. Security

Your workout records are never sent to any server. They stay in the app's sandboxed storage on your device, protected by Android's operating system security boundaries and file-system encryption.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect new features or Google Play policy updates. Any revisions will be reflected with an updated "Last Updated" date at the top of this page. You can always view the live policy at [https://karthic-keyan.github.io/privacy-policy/workout-tracker.html](https://karthic-keyan.github.io/privacy-policy/workout-tracker.html).

---

## 11. Contact Us

If you have questions, feedback, or need clarification regarding this Privacy Policy or Workout Tracker, please contact:

* **Developer Entity:** k-Tech Innovation
* **Support Email:** `ktechinnovationltd@gmail.com`
* **Developer Direct:** `karthik.devacc@gmail.com`
* **GitHub Repository:** [https://github.com/k-Tech-innovation](https://github.com/k-Tech-innovation)

