# Privacy Policy for ExpenseFlow (Expense Manager)

**Last Updated:** September 20, 2026

Welcome to **ExpenseFlow ("Expense Manager", "we", "our", or "us")**. We respect your privacy and are deeply committed to protecting your personal and financial information. This Privacy Policy explains our practices regarding data collection, usage, and security for the ExpenseFlow mobile application for Android.

---

## 1. Summary: 100% Offline & Zero Data Collection

- **Zero Data Collection:** We do not collect, transmit, store, sell, or share any personal or financial information.
- **100% Offline Storage:** All data (transactions, income, budgets, subscriptions, investments, and settings) is stored strictly on your local device within an isolated SQLite database.
- **No Third-Party Advertising:** ExpenseFlow is 100% ad-free. We do not integrate advertising SDKs, tracking pixels, or monetized data-sharing brokers.
- **No Third-Party Analytics:** We do not run third-party telemetry, behavior tracking, or user surveillance frameworks.
- **No Account Required:** You can use all features of ExpenseFlow without registering an account, providing an email, or linking a bank account.

---

## 2. Information We Handle Locally

All processing and storage occur exclusively on your local device:

1. **Financial Records:**
   - Transaction amounts, notes, dates, and categories.
   - Budget thresholds and limits.
   - Subscription billing cycles and renewal dates.
   - Asset names, investment amounts, and valuations.
2. **User Preferences:**
   - Selected display currency (e.g., INR, USD, EUR, etc.).
   - Appearance theme preference (System Default, Light, or Dark Mode).
   - Privacy Mode toggles and security configurations.
3. **Biometric Data:**
   - If enabled, biometric authentication (fingerprint or facial recognition) is handled strictly by your Android operating system's secure hardware enclave (`Android KeyStore` / `BiometricPrompt`). The app never has access to, nor does it store, raw biometric data.

---

## 3. Device Permissions and How They Are Used

ExpenseFlow requests minimal device permissions strictly necessary for user-directed functionality:

| Permission | Purpose |
| :--- | :--- |
| **POST_NOTIFICATIONS** | Used solely to deliver local, device-scheduled reminders for monthly budgets or upcoming subscription renewals. No remote push notifications or marketing messages are ever sent. |
| **USE_BIOMETRIC / FINGERPRINT** | Used solely to authenticate your local device lock before granting access to your expense database. |
| **WRITE_EXTERNAL_STORAGE / READ_EXTERNAL_STORAGE** (Legacy devices) | Used only when you explicitly trigger an export (e.g. exporting transactions to a CSV file) or import a backup file that you manually select. |

---

## 4. Data Security and User Control

- **Local Storage:** Your database is housed in your device's sandboxed internal storage (`expense.db`), shielded from other apps by the Android operating system sandbox.
- **Data Export:** You can export your data to CSV format at any time from Settings > Data Management.
- **Data Deletion:** You have complete autonomy over your data. You may delete individual transactions, wipe categories, or permanently erase the entire database from the Settings screen. Uninstalling the application completely deletes the local database and all associated preferences from your device.

---

## 5. Children's Privacy

ExpenseFlow does not collect any personal information from any user, including children under the age of 13 (or under the age of 16 in certain jurisdictions). The application is safe for general audiences of all ages.

---

## 6. Compliance with Google Play Developer Policies

ExpenseFlow complies fully with Google Play Developer Program Policies:
- We comply with the **Google Play User Data Policy**, including the Financial Services policy.
- We declare that our application **does not collect, handle, or transmit Personal and Sensitive User Data to any external servers**.
- Our local notifications conform to Android notification channel guidelines and can be toggled on or off at any time.

---

## 7. Changes to This Privacy Policy

Because ExpenseFlow does not maintain user accounts or cloud servers, any future revisions to this policy will be posted within the app update and updated in this repository. We recommend reviewing this document periodically.

---

## 8. Contact Information

If you have any questions, suggestions, or concerns regarding this Privacy Policy or your data privacy while using ExpenseFlow, please feel free to reach out:

- **Developer:** Karthikeyan
- **Project Repository:** [Expense Manager](https://github.com/karthikeyan)
- **Email:** support@expenseflow.local (or your developer email)
