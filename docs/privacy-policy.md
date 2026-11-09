# Privacy Policy

**FastFixIt** – Last updated: November 2026 · Version 2.3

> **Note.** This is a reference copy for GitHub. The complete and up-to-date Privacy Policy is published on the website: <https://fastfixit.it/privacy>

---

> **In short.** We collect the data needed to register you, help you find professionals, send requests and chat. We do not sell your data. We use technical providers (database, hosting, email, notifications, maps, photo checks). Chats are **not end-to-end encrypted**. You can delete your account at any time.

## 1. Data controller

The data controller is **Adriano Falone**, owner of FastFixIt (FastFixIt app and [fastfixit.it](https://fastfixit.it) website), who can be reached at [assistenza@fastfixit.it](mailto:assistenza@fastfixit.it). No Data Protection Officer has been appointed because it is not mandatory (Art. 37 GDPR). This notice is provided under Articles 13 and 14 of Regulation (EU) 2016/679 (GDPR) and Italian Legislative Decree 196/2003.

## 2. Data we collect

- **Registration:** first name, last name, username, email, password (stored only as a bcrypt hash, never in plain text), phone number, address.
- **Professional data (Providers):** business name, owner's first and last name, VAT number, professional category, description, any data or documents provided for a check. If a Client becomes a Provider with the same account, we collect the same professional data.
- **Profile photo (if any):** the image (JPEG, PNG or WebP) you choose to upload. It is optional. Before saving it we resize it and remove its metadata (for example camera data and GPS location); we check it automatically to detect inappropriate content (see section 5).
- **Location:** only with your explicit consent, to show you nearby professionals. The address you enter may be converted into coordinates (see section 5). For Providers the coordinates (from GPS, if you allow it, or derived from the business address) are saved in the profile, because without coordinates the profile does not appear in nearby searches; if they are missing, the app asks for them again at a later login. For Clients the position is used only at the time of the search and is not saved in the profile.
- **Requests, messages and reviews:** service requests, text messages exchanged in chat, reviews and ratings.
- **Blocks and reports:** the Users you block or report, the reason given, and reports concerning you.
- **Measures:** if your account is suspended or banned, the reason, duration and date.
- **One-time codes (OTP):** sent by email to verify your address; they are short-lived and allow a limited number of attempts.
- **Technical data:** your device's push notification token (FCM); session tokens (kept as hashes after logout); IP address and security logs used for request limits and abuse prevention. The position you send to search for nearby professionals may appear in technical logs, together with the IP, for the period shown in the retention table. On the website we save in the browser only your language preference.

The app does **not process payments** or card data, and does not ask you for special categories of data (health, religion, political opinions, sexual orientation): please do not enter them in chats and descriptions. Registration data is necessary to create the account and use the service: without it we cannot provide it. Location, profile photo and notifications are optional.

## 3. Why we use it and on what basis

| Purpose | Legal basis |
|---|---|
| Creating the account, verifying email (OTP), authenticating you | Contract (Art. 6.1.b) |
| Provider search, requests, chat, notifications, reviews, profile visible to other Users | Contract (Art. 6.1.b) |
| Provider coordinates derived from the business address, to appear in nearby searches | Contract (Art. 6.1.b) |
| Service communications (password reset, maintenance, security) | Contract (Art. 6.1.b) |
| Location and profile photo | Consent (Art. 6.1.a), revocable |
| Automated check of profile photos (inappropriate content, names or logos of other businesses) | Legitimate interest in platform safety (Art. 6.1.f) |
| Checks on Providers (including VAT number), reports, blocks, suspensions and bans | Legitimate interest in safety and reliability (Art. 6.1.f); legal obligation where applicable |
| Security, request limits, prevention of fraud and attacks | Legitimate interest (Art. 6.1.f) |
| Tax obligations and authority requests; defence of legal claims | Legal obligation (6.1.c); legitimate interest (6.1.f) |

We do not make decisions based solely on automated processing that produce legal effects on you. Automated systems (for example request limits) may temporarily block a suspicious access, and the photo check may reject an inappropriate image: you can upload another one or ask us for a human review.

## 4. Who sees your data

**Other Users.** If you are a Provider, your profile (name or business name, category, description, area, profile photo if any, reviews) is visible to Clients. If you send a Request, the Provider sees the data needed to handle it. The chat is visible only to the two participants, but remember that what you write may be kept by them: it is outside our control.

**Technical providers (processors).** They process data on our behalf, with only the instructions needed for the service. We do not sell or transfer your data to third parties for marketing.

**Authorities.** We may disclose data when required by law or to protect a right.

## 5. Third-party services

- **Supabase** – database (PostgreSQL) and storage of profile photos, with servers in Europe.
- **Oracle Cloud** – application hosting, servers in Italy (Milan).
- **Resend** – sending of transactional emails (OTP and service communications).
- **Google Firebase Cloud Messaging** – sending of push notifications: it receives the device token and the notification text, which includes the sender's name and the first characters of a message.
- **OpenStreetMap (Nominatim)** – conversion of the address into geographic coordinates: it receives the address, city and province, without your name. It is a public service that acts as an independent party, not as our processor.
- **Google Cloud Vision** – automated check of uploaded profile photos: it receives the image (already resized and without metadata) only to detect inappropriate content and names or logos of other businesses. If the service is unavailable, the check may be skipped.

Resend, Google and the OpenStreetMap Foundation may process data outside the European Economic Area (for example the United States and the United Kingdom). We rely on adequacy decisions (including the EU–US Data Privacy Framework for certified providers) or Standard Contractual Clauses. You can ask us for a copy of the safeguards.

## 6. Security and chats not end-to-end encrypted

We adopt appropriate technical and organisational measures: HTTPS/TLS encrypted communications, bcrypt password hashing, JWT token authentication (invalidated at logout), API request limits, and system access restricted to authorised personnel.

**Chats are not end-to-end encrypted.** They travel over an encrypted connection, but are stored on our servers in a form readable by the system and may be accessed only by authorised personnel for support, reports, security or legal obligations. Do not send sensitive data in chat. No system is 100% secure: in the event of a data breach presenting risks to you, we will notify the supervisory authority within 72 hours where required and, if necessary, you.

## 7. How long we keep data

| Data | Retention |
|---|---|
| Account, profile, profile photo, requests, messages, reviews, blocks and reports | While the account is active; deleted with the account |
| Replaced profile photo | The previous photo is deleted from our storage when it is replaced |
| Chat deleted by only one participant | Remains visible to the other for 7 days after deletion, then the messages are permanently deleted for both; deletion takes place with the daily cleanup, earlier if both delete it; always with the account |
| OTP codes | A few minutes, until expiry or use |
| Push notification tokens | Deleted with the account |
| Invalidated session tokens (hash only) | Up to 8 days |
| Access and security logs (including IP) | At most 30 days |
| Moderation action log (sanctions, removals) | For the time needed to prevent circumvention and defend our rights |
| Tax or accounting data, if applicable | For the period required by law |
| Deletion request | From the app: immediate. By email: within 5 working days. Any residues (for example backups) within 30 days |

## 8. Your rights

You have the right to access your data, rectify it, erase it, restrict its processing, object to processing based on legitimate interest, request portability, and withdraw consents (for example location and photo) without affecting processing already carried out. To exercise them write to [assistenza@fastfixit.it](mailto:assistenza@fastfixit.it) from your account email; we will reply within one month (extendable in complex cases) and may ask you to verify your identity. You can delete your account from **Settings › Account › Delete account** or as explained on the [Delete account](https://fastfixit.it/delete-account) page.

You have the right to lodge a complaint with the **Italian Data Protection Authority (Garante per la protezione dei dati personali)** (garanteprivacy.it) or the authority of the country where you reside. For users in Switzerland, Swiss data protection law remains applicable.

## 9. Minors

FastFixIt is reserved for adults (aged 18 or over). We do not knowingly collect data from minors under 18: if we find out, we close the account and delete the data.

## 10. Changes and contact

We may update this notice; material changes will be communicated in the app or by email. For any question: [assistenza@fastfixit.it](mailto:assistenza@fastfixit.it).
