# Privacy Policy for Ads Revenue Calc

**Effective Date:** November 2, 2026  
**Last Updated:** November 2, 2026

This Privacy Policy describes how **Ads Revenue Calc** ("we", "our", or "the App"), developed under package name `com.dimension.adrevenuecalc`, collects, uses, stores, and discloses information when you use our mobile application.

By downloading, installing, or using **Ads Revenue Calc**, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this policy, please do not use our application.

---

## 1. Overview and Core Functionality

**Ads Revenue Calc** is a productivity and utility tool designed for mobile app developers, publishers, and digital creators to calculate, forecast, and simulate advertising revenue, eCPM, CTR, CPC, and audience milestones.

The calculations you perform (such as input impressions, target eCPM, custom ad metrics, and goal planners) are executed and stored **locally on your device**. We do not harvest, monetize, or sell your calculation data.

---

## 2. Information We Collect

### A. Information Stored Locally on Your Device
- **Calculation Inputs & Settings:** Values such as daily impressions, custom eCPM rates, CTR, target revenue goals, and custom ad unit IDs entered in the app settings are stored locally using Android `SharedPreferences`. This data does not leave your device unless you explicitly use the export/share function.
- **Exported Reports:** When you choose to export or share a revenue forecast report, the text report is passed to the Android system share sheet at your explicit request.

### B. Automatically Collected Technical Information (Device Telemetry)
To ensure service reliability, provide remote configuration updates, enforce application security, and prevent abusive activity, our app automatically transmits non-personally identifiable technical information to our backend infrastructure (hosted via Supabase):
- **Device Identifiers:** A pseudonymous unique installation identifier (UUID or pseudo-anonymized Android ID).
- **Device Hardware & System Information:** Device manufacturer, device model, and Android OS version.
- **App Version & Diagnostics:** Current app version code/name and timestamp of active session.
- **Network & Connectivity Status:** Basic connectivity status to verify remote configuration availability.

*Note: This technical telemetry is collected strictly for app functionality, maintenance notifications, critical update enforcement, and fraud/abuse mitigation.*

### C. Information Collected by Third-Party Services (Advertising)
Our application integrates third-party software development kits (SDKs) that may collect information used to identify you or your device. Specifically:

#### Google AdMob (Google Mobile Ads SDK)
We use Google AdMob to display banner, interstitial, and app open advertisements. Google AdMob may collect and process:
- IP address (which may be used to infer general location)
- Google Advertising ID (GAID) or ID for Advertisers
- Device identifiers and technical device data
- Ad interaction information (such as ad impressions, clicks, view duration)
- Crash logs, performance metrics, and diagnostic information

Google's use of data collected via the AdMob SDK is governed by the [Google Privacy & Terms](https://policies.google.com/privacy) and [Google AdMob Policies](https://support.google.com/admob/answer/6128543).

---

## 3. Permissions Requested and Why We Need Them

The App requests the following standard Android permissions:
- **`android.permission.INTERNET`**: Required to load advertisements from Google AdMob, fetch remote configuration/update rules, and sync anonymous service telemetry.
- **`android.permission.ACCESS_NETWORK_STATE`**: Required to check whether your device has an active internet connection before attempting network requests, ensuring an optimized offline experience.

We **do not** request sensitive permissions such as Camera, Microphone, Fine/Precise Location, Contacts, SMS, or Storage permissions.

---

## 4. Third-Party Services and External Links

The App utilizes third-party service providers to facilitate our service:

- **Google AdMob & Google Play Services**  
  Used for serving in-app advertisements.  
  Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)  
  Ad Technologies: [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)

- **Supabase Cloud Backend**  
  Used for remote feature toggles, app maintenance notices, and fleet telemetry.  
  Privacy Policy: [https://supabase.com/privacy](https://supabase.com/privacy)

The App may also contain external links or buttons (e.g., "Rate App on Google Play", developer resources, or recommended tools). If you click on a third-party link, you will be directed to that third party's site or app. We strongly advise you to review the Privacy Policy of every external service you visit.

---

## 5. Data Retention and Deletion

- **Local Data:** You can delete all locally stored calculations and configurations at any time by clearing the App's data in Android Settings (`Settings > Apps > Ads Revenue Calc > Storage > Clear Data`) or by uninstalling the application.
- **Telemetry Data:** Anonymous device telemetry (device model, OS version, last active timestamp) is retained only as long as necessary for administrative maintenance, security, and version tracking. Because this data is pseudonymous and not linked to an identifiable user account, it is periodically purged.
- **Data Deletion Requests:** If you wish to request the deletion of any device telemetry associated with your installation UUID, please contact us at the contact email provided below.

---

## 6. Children's Privacy (COPPA Compliance)

Our service is intended for a general audience and is not directed at children under the age of 13 (or under the age of 16 in the European Economic Area). We do not knowingly collect personally identifiable information from children. If you are a parent or guardian and believe that your child has provided personal information to us, please contact us immediately, and we will take appropriate steps to remove such information.

---

## 7. Security of Your Data

We value your trust in providing us with information. All network communication between the App, Supabase, and Google AdMob is transmitted using industry-standard Transport Layer Security (TLS/HTTPS) encryption. However, please remember that no method of transmission over the internet or method of electronic storage is 100% secure, and we cannot guarantee absolute security.

---

## 8. International Data Transfers

Information collected via third-party services like Google AdMob and cloud infrastructure may be transferred to and processed on servers located outside your state, province, or country where data protection laws may differ. By using the App, you consent to this transfer.

---

## 9. Your Rights (GDPR & CCPA/CPRA Compliance)

Depending on your geographic location, you may have rights under data privacy regulations such as the General Data Protection Regulation (GDPR) or California Consumer Privacy Act (CCPA):
- **Right to Access:** You may inquire what data has been collected.
- **Right to Opt-Out of Personalized Ads:** You can opt-out of personalized advertising on Android devices by navigating to `Settings > Google > Ads` and resetting your Advertising ID or enabling "Delete advertising ID".
- **Right to Erasure:** You can clear local app data or request deletion of server logs by contacting us.

---

## 10. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect changes in our legal obligations, features, or third-party SDK updates. We will notify you of any changes by updating the "Last Updated" date at the top of this document and, where appropriate, displaying an in-app notice or update prompt. You are advised to review this page periodically for any changes.

---

## 11. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy or our data handling practices, please contact us:

- **Developer / Organization:** Ads Revenue Calc Team
- **Contact Email:** darkdotdarkline@gmail.com
- **Package Name:** `com.dimension.adrevenuecalc`
