# Privacy Policy for ID Card Wallet

**Last Updated:** November 28, 2026  
**Effective Date:** October 19, 2026  
**Application Name:** ID Card Wallet — Offline Encrypted Identity Storage  
**Package Name / Application ID:** `com.id_vault.app`  
**Developer / Publisher:** k-Tech Innovation (KTech Innovation / Karthikeyan)  
**Google Play Store Listing:** [ID Card Wallet on Google Play](https://play.google.com/store/apps/details?id=com.id_vault.app)  
**Contact Email:** ktechinnovationltd@gmail.com  
**Developer Support:** karthik.devacc@gmail.com / support@ktechinnovation.com  
**Organization:** [https://github.com/k-Tech-innovation](https://github.com/k-Tech-innovation)  

---

Welcome to **ID Card Wallet ("we", "our", or "us")**, published by **k-Tech Innovation**. We respect your privacy and are deeply committed to protecting your sensitive identity, document, and credential data. This Privacy Policy governs the practices regarding data handling, permissions, and security for the **ID Card Wallet** mobile application for Android (`com.id_vault.app`).

---

## 1. Summary: Offline, Encrypted & Zero Data Collection

- **Zero Data Collection:** We do not collect, transmit, store, sell, or share any personal, identity, document, or biometric information.
- **Offline Storage:** All stored identities, credentials, scanned documents, and notes reside strictly on your local device in an encrypted SQLite database and secure hardware keychain.
- **Client-Side Hardware Encryption:** Sensitive keys and credentials are encrypted using AES-256 and Android Secure KeyStore (`expo-secure-store`). Decryption keys never leave your device.
- **No Third-Party Advertising:** ID Card Wallet is 100% ad-free. We do not integrate advertising SDKs, tracking pixels, or data brokers.
- **No Third-Party Analytics:** We do not run third-party telemetry, behavior tracking, or user surveillance frameworks (no Google Analytics, Firebase, or Facebook SDK).
- **No Cloud Account Required:** You can use all features of ID Card Wallet without registering an account, providing an email, or connecting to any cloud server.
- **Update Check Only:** The only network request the app makes is a check for a newer app version. It downloads a small public version file from GitHub (and, as a fallback, the public Google Play listing page). No vault data, identifiers, or analytics are sent with this request.

---

## 2. Information We Handle Locally

All data processing and storage occur exclusively on your physical device:

1. **Identity & Document Records:**
   - Saved identity card numbers, passport information, driving licenses, and membership details.
   - Encrypted document images or card photo attachments.
   - Custom tags, categories, and private secure notes.
2. **User Preferences & Security Configurations:**
   - Biometric lock preferences (fingerprint or face unlock).
   - Auto-lock timeout settings.
   - Display theme preferences (Light / Dark mode).
3. **Biometric Data:**
   - When enabled, biometric authentication is handled strictly by your Android operating system's secure hardware enclave (`Android KeyStore` / `BiometricPrompt`). The application never has access to, receives, or stores your raw biometric data.

---

## 3. Device Permissions and How They Are Used

ID Card Wallet requests minimal device permissions strictly necessary for local, user-initiated security functions:

| Permission | Purpose |
| :--- | :--- |
| **USE_BIOMETRIC / USE_FINGERPRINT** | Used solely to authenticate your local device lock via Android `BiometricPrompt` before unlocking your encrypted identity database. |
| **CAMERA** | Used strictly when you choose to photograph an ID card, document, or passport to store an encrypted image scan directly inside your local vault. No photos or camera feeds are ever sent over the network. |
| **INTERNET** | Used only to check whether a newer version of the app is available (see Section 1). Your documents, profiles, and keys are never sent over the network. |

ID Card Wallet does not request storage permissions. Photos are chosen with the Android system photo picker, and backup files are opened or shared through the system file picker and share sheet, which grant access only to the file you select. Screenshots and screen recording are blocked by default while the app is open; you can change this in Settings.

---

## 4. Data Security and User Control

- **Encrypted Local Storage:** Your stored documents are kept inside your device's sandboxed internal storage and protected with AES-256 encryption.
- **Master Password & Keys:** Your master password or PIN is verified using salted cryptographic hashes. We do not store or transmit your master password.
- **Data Export & Backups:** You can generate and export encrypted backup files at any time from the app's settings.
- **Complete Data Deletion:** You have complete autonomy over your data. You may delete individual identity entries, delete scanned attachments, or wipe the entire vault at any time. Uninstalling the app permanently erases the local database, encryption keys, and all stored data from your device.

---

## 5. Children's Privacy

ID Card Wallet does not collect any personal information from any user, including children under the age of 13 (or under the age of 16 in applicable jurisdictions). The application is safe for general audiences of all ages and complies with COPPA, GDPR, and Google Play Families Policy guidelines.

---

## 6. Compliance with Google Play Developer Policies

ID Card Wallet complies fully with Google Play Developer Program Policies:
- We comply strictly with the **Google Play User Data Policy**, including sensitive permissions and personal data handling.
- We declare that our application **does not collect, handle, or transmit Personal and Sensitive User Data to any external servers**. The only outgoing request is the anonymous app-update check described in Section 1.
- All cryptographic storage adheres to industry standards.

---

## 7. Changes to This Privacy Policy

Because ID Card Wallet stores everything on your device and does not maintain user accounts or cloud servers, any revisions to this policy will be posted on our public privacy policy portal and updated in this repository.

---

## 8. Contact Information

If you have questions, suggestions, or concerns regarding this Privacy Policy or your data privacy while using ID Card Wallet, please reach out:

- **Developer / Entity:** k-Tech Innovation (KTech Innovation)
- **Lead Developer:** Karthikeyan
- **Play Store Contact Email:** [ktechinnovationltd@gmail.com](mailto:ktechinnovationltd@gmail.com)
- **Support Email:** [karthik.devacc@gmail.com](mailto:karthik.devacc@gmail.com) / [support@ktechinnovation.com](mailto:support@ktechinnovation.com)
- **Project Repository:** [https://github.com/k-Tech-innovation/identity-vault](https://github.com/k-Tech-innovation/identity-vault)
