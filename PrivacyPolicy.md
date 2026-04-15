# Privacy Policy

**Last Updated:** April 15, 2026  
**App Name:** BudgetNotes  
**App ID:** com.budget.notes  
**Developed by:** FenilVS

---

## Definitions
“App” refers to BudgetNotes.

“User” refers to any individual using the App.

“Personal Data” refers to information that identifies an individual.

## 1. Introduction

Welcome to BudgetNotes. This Privacy Policy explains how BudgetNotes handles your data and protects your privacy when using it. 

BudgetNotes is designed to operate primarily offline. User-generated data remains on your device by default and is not intentionally transmitted to external servers, except for license verification and optional Dropbox sync (Pro feature).

---

## 2. Data We Collect

### 2.1. Data Stored Locally on Your Device

BudgetNotes stores the following data **locally on your device's IndexedDB**:

- **Budget Information:** Section budgets, note budgets, expense items, and savings calculations
- **User-Generated Content:** Note titles, note content, and expense entries
- **App Settings:** Currency preferences, date format, display modes, and visual preferences
- **Usage History:** Note title autocomplete history (to provide suggestions)
- **Section Data:** Section titles, colors, period types, and ordering
- **Dues Data:** Lent, Borrowed and its people/institutions and transactions.

All user-generated data is stored locally in your device’s IndexedDB and is not intentionally transmitted to external servers by default. If you enable Dropbox sync (Pro feature), your data is encrypted and transmitted to Dropbox's servers for synchronization purposes only.

### 2.2. License Verification Data

The app does not intentionally transmit user data except as described in this policy.

- **License Key Verification:** When you purchase the Pro version, the app verifies your license key with Google Play Billing API and RevenueCat stores this information for future authentication purposes.
- **Optional Dropbox Sync (Pro Feature):** If you enable Dropbox sync, encrypted budget data is transmitted to Dropbox API for synchronization across your devices.
- Google Play Billing, RevenueCat, and Dropbox may process transaction-related information necessary to validate purchases and provide sync services. Such processing is governed by their respective privacy policies.
- [Google Privacy Policy](https://policies.google.com/privacy?hl=en-US), [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/), [Dropbox Privacy Policy](https://www.dropbox.com/privacy)
---

## 3. How We Use Your Data

### 3.1. Local Data Usage

All data stored on your device is used **exclusively for**:

- Providing the budget tracking and note-taking functionality
- Displaying your budgets, expenses, and savings
- Saving your app preferences and settings
- Providing autocomplete suggestions for note titles
- Generating charts and visualizations

### 3.2. License Verification

License verification is used **solely for**:

- Confirming your Pro version purchase
- Ensuring you have access to premium features
- Preventing unauthorized use of paid features

The app is designed to store data locally on your device and does not intentionally transmit user-generated content to external servers, except when Dropbox sync is enabled (Pro feature).

---

## 4. Data Storage and Security

### 4.1. Offline-First Architecture

BudgetNotes is built with an **offline-first architecture**:

- ✅ All data is stored locally in IndexedDB (browser-native database)
- ✅ Data is stored using local browser-based storage mechanisms (IndexedDB) within the app environment.
- ✅ No cloud storage or external servers are used by default
- ✅ No data synchronization with any service by default
- ⚠️ **Optional Dropbox sync** (Pro feature): Encrypted data can be synchronized across devices if explicitly enabled by user
- ✅ No third-party analytics or tracking services
- ✅ No data collection for marketing purposes
- ✅ The app does not use crash reporting or error tracking services.


### 4.2. Backup and Restore

BudgetNotes provides backup and restore functionality that operates **entirely locally**:

- **Backup:** Exports your data to a JSON file saved to your device's local storage
- **Restore:** Imports data from a JSON file on your device
- **No cloud backup:** Backups are never uploaded to any server
- **No remote restore:** Restores only work from files stored on your device

**You maintain complete control over your backups.**

### 4.3. Data Encryption (Optional)

BudgetNotes offers optional backup encryption:

- You can choose to encrypt your backup files with a password
- Encrypted backups remain on your device only
- No encryption keys are stored or transmitted

---

### 4.4. Cloud Sync (Optional - Pro Feature)

BudgetNotes offers optional Dropbox cloud sync (Pro feature):

- **Opt-in Only:** Sync is disabled by default and requires explicit user activation
- **Encrypted Transmission:** All data is encrypted using AES-256-GCM encryption before transmission to Dropbox
- **Dropbox Storage:** Data is stored in your personal Dropbox account using Dropbox API
- **User Control:** You can disable sync at any time, which stops all cloud transmission
- **No Server Access:** We do not have access to your Dropbox data or encryption keys
- **Multi-Device:** Sync works across multiple devices linked to the same Dropbox account

**⚠️ Important: Dropbox sync is NOT end-to-end encrypted.** While your data is encrypted before upload, Dropbox could theoretically access your data if compelled by legal requests or if they choose to decrypt it. For 100% private storage, use password-encrypted local backups instead.

**Local backups remain the primary backup method. Dropbox sync is for convenience only.**

---

## 5. Data Sharing and Third Parties

### 5.1. No Third-Party Data Transfers

**We do not share your data with any third parties.** This includes:

- ❌ No advertising networks
- ❌ No analytics providers
- ❌ No data brokers
- ❌ No social media platforms
- ⚠️ No cloud storage services by default (optional Dropbox sync available for Pro users)
- ❌ No third-party APIs (except Google Play Billing for license verification and Dropbox API for optional sync)

### 5.2. No Ads

**BudgetNotes contains no advertisements.** We do not:

- Display ads of any kind
- Use ad networks
- Collect data for advertising purposes
- Sell ad space

### 5.3. Google Play Billing

The third-party services we use are **Google Play Billing** and **RevenueCat**:

- Used for Pro version license verification
- BudgetNotes does not intentionally collect personal data such as name, email address, phone number, or location.
- Google's privacy policy applies to license verification transactions.

### 5.4. Dropbox API (Optional - Pro Feature)

If you enable Dropbox sync (Pro feature), we use **Dropbox API**:

- Used **only** when you explicitly enable sync in settings
- Transmits **encrypted** budget data to your personal Dropbox account
- We do not have access to your Dropbox credentials or data
- Dropbox's privacy policy applies to data stored on their servers
- You can disable sync at any time to stop all Dropbox API usage
- [Dropbox Privacy Policy](https://www.dropbox.com/privacy)

#### Encryption Details

Your data is encrypted using **AES-256-GCM encryption** (the same standard used by financial institutions) before being uploaded to Dropbox.

**What This Protects Against:**
- ✅ Network snooping during upload/download - Your data is encrypted during transit
- ✅ Casual access to your Dropbox account - Your data remains encrypted on Dropbox servers
- ✅ Data breaches at Dropbox - Your information stays encrypted even if Dropbox is hacked

**What This Doesn't Protect Against:**
- ⚠️ **Legal requests to Dropbox** - Warrants, subpoenas, or court orders could compel Dropbox to provide your data
- ⚠️ **Dropbox's internal access** - Dropbox could theoretically decrypt your data if they choose to take the steps to do so

#### Alternative for 100% Private Storage

For stronger security, go to **Settings → Security** and enable **"Encrypt backups with password"**. Then create a **local backup**. Your backup file will be encrypted with your password, and only you can open it. You can store this backup anywhere - even on Dropbox - and it will remain 100% private.

---

## 6. Data Retention and Deletion

### 6.1. Data Retention

Your data is stored on your device **indefinitely** until you:

- Delete the app (which removes all data)
- Delete individual notes or sections
- Manually clear app data through device settings

### 6.2. Data Deletion

You can delete your data at any time by:

- **Deleting individual notes:** Open a note and tap the delete button
- **Deleting sections:** Delete a section to remove all notes within it
- **Clearing app data:** Go to device settings → Apps → BudgetNotes → Clear Data
- **Uninstalling the app:** Removes all app data from your device

**Once deleted, data cannot be recovered unless you have a local backup.**

---

## 7. Children's Privacy

BudgetNotes is a general-purpose budgeting application and is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13.

Since the app operates primarily offline and does not collect personal information, it is safe for users of all ages. Optional Dropbox sync (Pro feature) requires internet connection.

---

## 8. Your Rights and Choices

### 8.1. Data Access and Control

You have complete control over your data:

- ✅ View all your data within the app
- ✅ Edit any note, section, or setting
- ✅ Delete any note, section, or all data
- ✅ Export backups to your device
- ✅ Import backups from your device
- ✅ Choose whether to encrypt backups

### 8.2. No Account Required

BudgetNotes does **not require** you to:

- Create an account
- Provide an email address
- Provide personal information
- Sign up for any service

**You can use all features (except Pro version) without any account or personal information.**

### 8.3. Pro Version Purchase

To purchase the Pro version, you must:

- Use Google Play Billing
- Provide payment information to Google (not to us)
- This is handled entirely by Google's secure payment system

**We do not receive or store your payment information.**

---

## 9. Network Usage

### 9.1. Minimal Network Activity

BudgetNotes intentionally uses the internet for:

- License key verification (Pro version)
- App updates (through Google Play Store)
- **Dropbox sync (Pro feature, optional):** When enabled, encrypted data is synchronized with Dropbox servers

### 9.2. Offline Functionality

BudgetNotes works **completely offline** for core features (unless Dropbox sync is enabled):

- Creating and editing notes
- Setting budgets and tracking expenses
- Viewing charts and visualizations
- Managing sections and categories
- Exporting and importing backups
- Changing app settings

**You do not need an internet connection to use the app's core features.**

---

## 10. Security Measures

We implement reasonable security measures to protect your data:

- **Local Storage:** All data is stored on your device only
- **IndexedDB:** Uses browser-native secure database
- **Optional Encryption:** Backup files can be password-protected
- **External Transmission:** The app is designed to store data locally on your device and does not intentionally transmit user-generated content to external servers.
- **No Remote Access:** No remote access or cloud synchronization, except optional Dropbox sync (Pro feature)

**However, please note:**

- We cannot guarantee absolute security of data stored on your device
- You are responsible for securing your device (screen lock, encryption, etc.)
- If your device is lost or stolen, your data may be accessible
- We recommend regularly backing up your data to a secure location

---

## 11. Contact Information

If you have questions about this Privacy Policy or how we handle your data, please contact us:

**App Developer:** BudgetNotes Team  
**Email:** [To be provided]  
**App ID:** com.budget.notes  

---

## 12. Summary of Key Points

| Aspect | Status |
|--------|--------|
| **Offline-First** | ✅ App works completely offline |
| **Local Storage** | ✅ All data stored on device only |
| **Cloud Storage** | ⚠️ Optional Dropbox sync (Pro feature only) |
| **Data Sharing** | ❌ No third-party data transfers |
| **Ads** | ❌ No advertisements |
| **Analytics** | ❌ No tracking or analytics |
| **Account Required** | ❌ No account or email needed |
| **Network Usage** | ✅ Only for license verification |
| **Backup Location** | ✅ Local device storage only |
| **Restore Location** | ✅ Local device storage only |
| **Personal Info** | ❌ BudgetNotes does not intentionally collect personal data such as name, email address, phone number, or location. |
| **Data Encryption** | ✅ Optional backup encryption available |

---

## 13. Google Play Store Compliance

This Privacy Policy is designed to comply with:

- Google Play Developer Policy
- Google Play User Data Policy
- Google Play Families Policy
- App Privacy Requirements on Google Play

## 14. Legal Basis for Processing

Since BudgetNotes operates locally and does not collect personal data, no personal data is processed by the developer. License verification is processed based on contractual necessity.

## 15. Jurisdiction

This Privacy Policy shall be governed by the laws of India, without regard to conflict of law principles. Any disputes arising out of this Privacy Policy shall be subject to the exclusive jurisdiction of the courts located in India.


## 16. Changes to This Policy

We may update this Privacy Policy from time to time. Updated versions will be posted within the app and the “Last Updated” date will be revised accordingly. Continued use of the app after changes constitutes acceptance of the updated policy.

## 17. Severability Clause

If any provision of this Privacy Policy is found to be invalid or unenforceable, the remaining provisions shall remain in full force and effect.

## 18. Limitation of Liability Cap

In no event shall total liability exceed the amount paid by the user for the Pro version. If no amount has been paid, liability shall be limited to INR 1,000 or the minimum amount permitted by applicable law.

---

Terms of Use note:
The app is provided “as is” without warranties of any kind. To the maximum extent permitted by applicable law, the developer shall not be liable for indirect, incidental, or consequential damages arising from use of the app.
Nothing in this policy limits liability where such limitation is prohibited by law.
