# Privacy Policy

**Effective Date:** August 6, 2025
**Last Updated:** August 27, 2025

This Privacy Policy describes how **Tripura Industrial Development Corporation Limited ("TIDCL", "we", "us", or "our")** collects, uses, stores, and protects information when you use the **TIDCL Project Monitoring System ("PMS", the "App")** mobile application. The App is an internal/enterprise tool used by TIDCL personnel and authorised project stakeholders to monitor the progress of projects undertaken by TIDCL. For more information about TIDCL, please visit our official website at **[https://tidc.tripura.gov.in/](https://tidc.tripura.gov.in/)**.

The App has been developed by **Develegance Innovatech Private Limited** (official website: [https://develeganceinnovatech.in/](https://develeganceinnovatech.in/)) acting as a technology development partner. However, the App, its content, the data collected through it, and all rights therein are **owned and controlled by TIDCL**, which is the data controller responsible for your personal data under this Privacy Policy. Develegance Innovatech Private Limited acts solely as a data processor on behalf of TIDCL and does not use your personal data for its own purposes.

By installing, registering for, or using the App, you agree to the practices described in this Privacy Policy. This Policy is issued in accordance with the **Digital Personal Data Protection Act, 2023 (DPDP Act)** of India and other applicable laws.

> **Note on audience:** The App is intended for use by authorised employees, officers, consultants, contractors, and assigned project users of TIDCL. It is not directed at the general public.

---

## 1. Information We Collect

### 1.1 Information you provide
- **Account credentials:** Your username and password, which you enter to sign in. Passwords are submitted to our server for authentication and are not permanently stored by the App on your device.
- **Profile information:** Your name, username, email address, mobile number, and assigned role, as returned by the server after login and displayed on your in-app profile.
- **Project & contractor data:** Information about projects and associated companies/contractors that you are authorised to view, including company name, email, mobile number, GST number, PAN, and address.
- **Progress updates:** Physical-progress percentages, remarks, and photographs that you capture or select and submit for a project.

### 1.2 Information collected automatically
- **Photographs:** Images you capture using the device camera or select from the device gallery to attach to project-progress submissions. These are uploaded to our backend storage service (MinIO).
- **App usage and diagnostic data:** Limited usage events and crash/performance diagnostics collected via **Google Firebase** services (see Section 4). This may include device model, operating-system version, app version, language/region settings, and timestamps of events.
- **Session identifiers:** Authentication cookies/tokens stored on your device to keep you signed in during a session.

### 1.3 Permissions the App requests
To provide its features, the App requests the following Android permissions:

| Permission | Purpose |
|---|---|
| `INTERNET` | Communicate with the TIDCL backend and Firebase services. |
| `POST_NOTIFICATIONS` | Send you push notifications (e.g., project updates) via Firebase Cloud Messaging (Android 13+). |
| `CAMERA` | Capture photographs for project-progress submissions. |
| `READ_EXTERNAL_STORAGE` / `READ_MEDIA_IMAGES` | Select existing photographs from your device gallery for upload. |

The App **does not** request or collect precise or coarse device location (GPS), contacts, call logs, microphone audio, SMS, or calendar data.

---

## 2. How We Use Your Information

We use the information collected to:
1. **Authenticate** you and manage your user session.
2. **Display** your authorised projects, profile, and associated contractor/company information.
3. **Record and track** physical progress of projects, including progress percentages, remarks, and supporting photographs.
4. **Store** uploaded photographs on our backend object-storage service so they can be viewed and reviewed alongside project records.
5. **Send push notifications** regarding project updates and App activity.
6. **Monitor, stabilise, and improve** the App through crash reporting and limited usage analytics.
7. **Maintain security, prevent fraud,** and comply with applicable legal obligations.

---

## 3. How We Store Information

- **On your device:** The App stores limited data locally on your device using platform storage (SharedPreferences, Hive/GetStorage), such as in-progress project data and references to photographs you have selected, so the App can resume your work and operate offline-friendly. This data remains on your device until you clear it or uninstall the App. Logging out clears your in-session user data from the App.
- **On our servers:** Account, profile, project, contractor, and progress data is stored on the TIDCL backend (`services.tripuraidc.in`). Uploaded photographs are stored in our backend object storage (MinIO).
- **Retention:** We retain personal data for as long as your account is active and for such additional period as required by applicable law, audit requirements, or legitimate business/record-keeping needs of TIDCL. In-progress data you have not yet submitted is retained locally on your device and is removed when you clear it or uninstall the App.
  > _Specify institutional retention period here, if fixed — e.g., "Project records are retained for [X] years after project completion as per TIDCL record-retention norms."_

---

## 4. Third-Party Services

The App uses the following third-party processors. Each processor processes data on our behalf and is governed by its own privacy and security practices.

| Service | Provider | Purpose | Data involved |
|---|---|---|---|
| Firebase Analytics | Google LLC | Aggregate usage metrics and event tracking | App events, approximate device characteristics, App version |
| Firebase Crashlytics | Google LLC | Crash and error diagnostics | Stack traces, device model/OS, App version, timestamps |
| Firebase Cloud Messaging | Google LLC | Push notifications | Push token, notification delivery |
| Firebase Remote Config | Google LLC | Serve runtime configuration (e.g., backend endpoint) | App instance identifier |
| Firebase Auth / Firestore / Storage | Google LLC | Backend platform services (as configured) | Data routed through Firebase where applicable |
| Backend object storage (MinIO) | Hosted by TIDCL backend | Storage of project photographs | Uploaded image files |
| HTTP client / cookies | — | Session management with backend | Session cookies |

**Google Firebase** may transfer data outside India subject to Google's privacy and security framework. We do not sell your personal data to any third party, and we do not use advertising SDKs or share data for cross-context advertising.

---

## 5. How We Share Information

We do not sell your personal data. We may share information:
1. **Internally** within TIDCL and the Government of Tripura, with authorised personnel who require it to perform their duties.
2. **With service providers** (such as Google Firebase and our hosting/storage providers) who process data on our behalf to operate the App.
3. **When required by law**, with government, regulatory, or judicial authorities pursuant to a lawful request.
4. **In connection with audits, investigations, or statutory compliance** relevant to TIDCL's operations as a public-sector entity.

---

## 6. Security

We take reasonable technical and organisational measures to protect your data, including:
- Authenticated API access with session validation and logout.
- Use of HTTPS for communication between the App and our backend.
- Server-side storage of project and image data within the TIDCL backend environment.
- Automatic crash reporting to detect and remediate defects.

No method of transmission or storage is fully secure, however, and we cannot guarantee absolute security. Unauthorised disclosure of your login credentials may compromise the security of your account — please keep your credentials confidential.

---

## 7. Your Rights

Depending on applicable law (including the DPDP Act, 2023), you may have rights relating to your personal data, including:
- **Access** a summary of your personal data held by us.
- **Correction / updating** of inaccurate or incomplete data.
- **Withdrawal of consent** for certain processing, where applicable.
- **Erasure / deletion** of data, subject to legal and record-retention obligations.
- **Grievance redressal:** You may contact us using the details in Section 9 to exercise any of these rights or to raise a complaint.

Please note that some data (such as official project records and audit-relevant information) may be retained as required by law even after you request deletion.

---

## 8. Children's Privacy

The App is not intended for, and is not directed at, individuals under 18 years of age. We do not knowingly collect personal data from children. If you believe a child has provided us with personal data, please contact us so we can take appropriate action.

---

## 9. Contact Us / Grievance Officer

If you have questions, requests, or complaints regarding this Privacy Policy or your personal data, please contact:

> **Tripura Industrial Development Corporation Limited (TIDCL)**
> *(A Government of Tripura Undertaking)*
>
> Shilpa Nigam Bhawan, Near Ginger Hotel, Khejur Bagan
> P.O.: Kunjaban, Agartala, West Tripura, India — PIN 799006
>
> **Phone:** 0381-2416617, 2416446, 2416373
> **Fax:** 0381-2414503
> **Email:** tidcltd.in@gmail.com
>
> **Office Hours:** Daily 10:00 A.M. to 5:30 P.M. (Sunday and second & fourth Saturday closed)

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the App, legal requirements, or our practices. The "Effective Date" at the top indicates when the Policy was last revised. We will notify you of material changes through the App or via notification where appropriate. Continued use of the App after a change constitutes acceptance of the updated Policy.

---

*End of Privacy Policy.*
