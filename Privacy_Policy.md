# Privacy Policy for Ads Revenue Calc

**Effective Date:** November 2, 2026  
**Last Updated:** November 2, 2026

This Privacy Policy ("Policy") governs the privacy practices of **Ads Revenue Calc** ("the App", "we", "us", or "our"), identified under Android package name `com.dimension.adrevenuecalc`. This document explains how we collect, use, store, process, and disclose information when you install, access, or interact with our mobile application.

We are committed to respecting and protecting your privacy. Please read this Privacy Policy carefully before using the App. By downloading, accessing, or using Ads Revenue Calc, you explicitly acknowledge that you have read, understood, and agree to the terms described herein. If you do not agree with this Policy, please do not download, install, or use the App.

---

## 1. About the Application

**Ads Revenue Calc** is a professional financial forecasting, revenue calculation, and analytics utility designed for digital publishers, mobile app developers, content creators, and media buyers. The application provides calculations for:
- Ad Impression estimation
- Effective Cost Per Mille (eCPM)
- Click-Through Rate (CTR) and Cost Per Click (CPC)
- Blended ad format revenue mixing (Banners, Interstitials, App Open, Rewarded)
- Monthly and annual revenue milestones & active user (DAU/MAU) targets

---

## 2. Information We Process and How It Is Handled

We believe in strict data minimization. Our data handling is categorized into three tiers:

### A. Locally Processed Financial & Calculation Data (On-Device Only)
- **User Inputs:** Numerical figures entered for impressions, ad unit CPMs, click rates, target revenues, and currency selections.
- **Custom Configuration:** Any custom AdMob ad unit IDs entered manually in app settings.
- **Storage Mechanism:** This data is stored strictly in your device's private local sandboxed storage via Android `SharedPreferences`.
- **Transmission:** This data is **NEVER** transmitted to our servers, sold, rented, or shared with third parties. It remains 100% private on your hardware.
- **Report Exporting:** If you choose to generate and export an executive forecast summary, the report text is sent only through the native Android system share dialog (`Intent.ACTION_SEND`) to apps you deliberately choose (e.g., Email, WhatsApp, Google Drive).

### B. Anonymous Technical & Device Telemetry (Cloud Operations & Security)
To ensure reliable app performance, deliver remote feature flags, enforce maintenance notices, verify minimum app versions, and mitigate security threats or abusive traffic, the App connects to our cloud backend (hosted on Supabase) and transmits non-personally identifiable technical telemetry:
- **Pseudonymous Device Identifier:** A generated Universally Unique Identifier (UUID) or pseudonymized installation ID.
- **Hardware Profile:** Device manufacturer, brand, and hardware model name (e.g., Samsung Galaxy, Xiaomi, Google Pixel).
- **Operating System:** Android OS version and API level.
- **App Version Data:** Version name, version code, and active session timestamp.
- **Account Requirement:** The App does not require user registration, login credentials, passwords, social log-ins, or phone numbers.

### C. Information Collected Automatically by Third-Party Ad Networks
The App displays advertisements powered by **Google AdMob** (Google Mobile Ads SDK). Google AdMob and its advertising network partners may collect and process certain device information to serve relevant contextual or personalized ads, detect click fraud, and monitor ad performance:
- Google Advertising ID (GAID / AAID)
- Internet Protocol (IP) address (used to infer general country or city-level location)
- Device interaction data (ad impressions served, clicks, video completion, engagement duration)
- Network carrier, connection type (Wi-Fi / Cellular)
- App crash reports and performance telemetry

---

## 3. Android System Permissions

Ads Revenue Calc requests only the minimal necessary permissions required for core utility and ad serving:

| Permission | Technical Name | Reason & Usage |
| :--- | :--- | :--- |
| **Full Internet Access** | `android.permission.INTERNET` | Required to communicate with Google AdMob servers for ad loading and check for remote version updates via Supabase. |
| **View Network Connections** | `android.permission.ACCESS_NETWORK_STATE` | Allows the app to detect whether an internet connection is present, preventing failed network requests and enabling seamless offline calculation mode. |

> **Explicit Sensitive Permissions Disclosure:**  
> The App **DOES NOT** request, access, or track:
> - GPS or Precise Location
> - Camera or Microphone
> - Contacts or Address Book
> - SMS or Call Logs
> - Read/Write External Shared Storage or Media Library
> - Biometric Data or Health Data

---

## 4. Third-Party Service Providers & External Links

We partner with trusted third-party providers that adhere to international privacy and security standards. Their collection of data is governed by their respective privacy policies:

1. **Google AdMob & Google Play Services**
   - **Service:** In-app advertisement delivery, ad frequency capping, and ad analytics.
   - **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
   - **Ad Technology Partners:** [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
   - **Opt-Out Information:** [https://adssettings.google.com](https://adssettings.google.com)

2. **Supabase (Backend as a Service)**
   - **Service:** Remote configuration caching, version compatibility check, and fleet device telemetry.
   - **Privacy Policy:** [https://supabase.com/privacy](https://supabase.com/privacy)

3. **External Links**
   - The App may provide buttons or links to external destinations (e.g., Google Play Store rating page, developer resources). We do not control and are not responsible for the privacy practices or content of third-party websites or services.

---

## 5. Data Retention, User Control, and Data Deletion Policy

We retain information only as long as necessary to provide the services described in this Policy:

- **Local Storage:** All on-device calculation inputs and saved ad unit preferences persist until you clear the application data via Android Settings (`Settings > Apps > Ads Revenue Calc > Storage > Clear Storage / Clear Data`) or uninstall the application.
- **Server Telemetry:** Anonymous device telemetry recorded on our cloud backend is periodically purged or aggregated for historical analytics.
- **Right to Request Data Deletion (Google Play Compliance):**  
  Because our application does not use accounts or store personal user profiles, most data resides purely on your phone. However, if you would like to request the purge of any backend log associated with your installation UUID, you may submit a request by emailing **darkdotdarkline@gmail.com** with the subject line *"Data Deletion Request - Ads Revenue Calc"*. We will process verified requests within 30 days without charge.

---

## 6. Children’s Privacy (COPPA & Global Standards)

**Ads Revenue Calc** is directed to adult creators, developers, business owners, and media planners. It is not structured to attract, and does not knowingly collect personal information from, children under the age of 13 (or under 16 in the European Economic Area / UK).

If you are a parent or legal guardian and discover that your minor child has provided us with personal data, please contact us immediately at **darkdotdarkline@gmail.com**, and we will promptly take steps to delete any such information from our records.

---

## 7. Security of Your Information

We employ industry-standard technical, organizational, and administrative safeguards to protect data:
- All external data exchanges between the App, Supabase, and Google AdMob are encrypted in transit using **TLS 1.2 / TLS 1.3 (HTTPS)** protocols.
- On-device data is secured within the Android sandbox application environment, isolated from other installed apps.
- Despite our efforts, no method of transmission over the Internet or method of electronic storage is 100% impenetrable. Therefore, we cannot guarantee absolute security.

---

## 8. International Data Transfers

Third-party service providers (such as Google and Supabase) operate global cloud infrastructure. Consequently, technical data such as advertising IDs, IP addresses, and telemetry may be transferred to, stored, and processed in countries outside of your state, province, or country of residence, including the United States, where data protection regulations may differ. By using the App, you consent to these cross-border data transfers governed by Standard Contractual Clauses (SCCs) and appropriate privacy safeguards.

---

## 9. Notice for California Residents (CCPA / CPRA)

Under the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA), California residents are entitled to specific disclosures:
- **Sale of Personal Data:** We **DO NOT** sell your personal information to third parties for monetary consideration.
- **Sharing of Personal Data:** As described in this policy, we share pseudonymous identifiers (e.g., Advertising ID) with Google AdMob for targeted and non-targeted in-app advertising.
- **Consumer Rights:** California users have the right to request access to their collected data, request deletion, and opt-out of cross-context behavioral advertising without discriminatory treatment.
- **Opt-Out Exercise:** You can opt-out of personalized ads directly on your Android device by visiting `Settings > Google > Ads` and turning on *"Delete advertising ID"* or *"Opt out of Ads Personalization"*.

---

## 10. Notice for European & UK Users (GDPR Compliance)

If you reside in the European Economic Area (EEA) or the United Kingdom (UK), processing of your data is governed by the General Data Protection Regulation (GDPR):
- **Legal Basis for Processing:**  
  - *Legitimate Interests:* We process anonymous telemetry to secure the app, fix technical errors, and maintain compatibility.  
  - *Consent:* Google AdMob requests consent for personalized advertising and cookies/identifiers via the User Messaging Platform (UMP) or Google consent framework where legally required.
- **Your Rights:** You have the right to access, rectify, restrict processing, object to processing, or request erasure of your data.
- **Supervisory Authority:** You have the right to lodge a complaint with your local Data Protection Authority regarding our collection and processing of your data.

---

## 11. "Do Not Track" and Advertising ID Management

Android allows you full control over how advertising networks track your device:
1. Open your Android device **Settings**.
2. Tap **Google** (or **Privacy**).
3. Tap **Ads**.
4. Tap **Delete advertising ID** or **Reset advertising ID**.

When deleted, ad networks cannot track your activity across apps for targeted advertising purposes.

---

## 12. Changes and Amendments to This Privacy Policy

We reserve the right to revise or update this Privacy Policy at our discretion to accommodate changes in our app features, legal requirements, or advertising partner guidelines. When updates are published, the "Last Updated" date at the top of this document will be revised. Significant modifications will be communicated via in-app update prompts or visible notices where practicable. We encourage you to review this page periodically.

---

## 13. Contact Information and Developer Inquiries

If you have questions, feedback, or legal inquiries concerning this Privacy Policy, or wish to exercise any of your data rights, please contact our designated privacy contact:

- **Application Title:** Ads Revenue Calc
- **Android Package Identifier:** `com.dimension.adrevenuecalc`
- **Developer / Publisher Contact Email:** [darkdotdarkline@gmail.com](mailto:darkdotdarkline@gmail.com)
- **Response Commitment:** All genuine user inquiries and privacy requests will be answered within 30 business days.
