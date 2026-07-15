# Privacy Policy for Clipmap

**Last Updated:** July 15, 2026

At Clipmap, we respect your privacy and are committed to protecting the personal data you share with us. This Privacy Policy explains how we collect, use, and safeguard your information when you use the Clipmap mobile application (the "App") and its associated backend services.

---

## 1. Information We Collect

### A. Data You Provide Directly
* **Shared Links & Video URLs:** When you share or paste Instagram reels, videos, or posts into the App, we collect the text, URLs, and any accompanying caption content you submit.
* **Subscription Information:** If you purchase Clipmap Pro, we process subscription status, product identifiers, plan type, entitlement status, expiration dates, purchase/restore events, and purchase metadata such as price and currency. Payments are processed by Google Play and RevenueCat; we do not receive or store your full payment card details.

### B. Automatically Processed Data
* **Anonymous Account Identifier:** The App may create a Supabase anonymous user ID so you can use Clipmap without first creating an email/password account. This ID is used to keep your saved collections, places, jobs, and subscription entitlement separate from other users.
* **Semantic Extraction & Geographic Locations:** Our backend parses address details from the captions of the videos you submit and converts them into latitude and longitude coordinates. We also extract qualitative insights (like a summary of the place, highlights, tags, confidence, source, ambiguity notes, failure reason codes, and result summaries) and generate a numerical representation (embedding) of this data. This powers the natural language search and recovery capabilities within the App.
* **Manual Place Search & Corrections:** If the automatic place detection cannot confidently map a reel, you may search for and select a place manually. We process the place search query you submit, the Google Places candidates returned, the selected place, optional notes, and the related reel/job identifier so the place can be saved and subscription/free save limits can be applied fairly.
* **App Usage & Interaction Data:** We record in-app events and interactions — such as paywall views, purchase or restore outcomes, save-limit blocks, fair-use blocks, manual place additions/corrections, the screens you view, and taps/navigation within the App — to understand how the App is used, confirm it is working correctly, and improve it. These events are linked to your anonymous account identifier (described above) so we can analyze usage on a per-user basis. We do **not** record your screen. We only process text you intentionally submit to Clipmap, such as reel URLs, search queries, or optional notes.
* **App Usage Data:** We do not automatically track your device's precise location in the background.

---

## 2. How We Use Your Information

We use the collected information for the following purposes:
* To provide, maintain, and improve the App's core functionality (pinning shared videos to the map).
* To manage and secure your user account.
* To perform geolocation queries (converting text addresses to coordinates).
* To provide manual place search and correction when automatic curation is uncertain or fails.
* To retrieve relevant post metadata to display in the App.
* To provide, verify, restore, and enforce paid subscription features.
* To measure basic product performance and diagnose issues, including subscription funnel and save-limit events.

---

## 3. Third-Party Services We Use

We utilize reliable third-party infrastructure and APIs to deliver our services. These partners process data according to their own privacy guidelines:
* **Supabase:** Used for user authentication and hosting our database securely, including saved places, collections, curation jobs, reason codes, result summaries, and subscription entitlement metadata.
* **RevenueCat:** Used to manage subscription entitlements, purchase status, plan identifiers, purchase currency, renewals, cancellations, and restore purchases. We use secure Google Play service credentials with RevenueCat to validate purchase and subscription status; we do not receive or store your full payment card details.
* **Google Play Billing:** Used to process Android in-app subscriptions, regional prices/currencies, and payment management.
* **Google Places API:** Used to convert place names and address text (e.g., "123 Main St") into latitude/longitude coordinates and a map location, retrieve a representative cover photo, and return candidate places for manual search/correction.
* **Google Gemini API:** Used to identify places and location details from the content you submit — the post caption, top comments, and (when needed) the reel video itself, which is uploaded for analysis and deleted afterward. We also use Gemini to generate semantic embeddings of these places for search capabilities.
* **PostHog:** Product analytics provider used to capture in-app usage and interaction events, and AI/LLM operational metrics (model, token counts, latency, and cost) so we can monitor and improve the Gemini-powered curation pipeline. PostHog receives only this metadata — **not** the prompt/response content — and does not receive screen recordings.
* **Instagram (Meta):** When playing or embedding videos, the content is served directly from Instagram’s servers.

---

## 4. Data Sharing and Disclosure

We do not sell, trade, or rent your personal information to third parties. We do not share your private data with advertisers. We may only disclose your data:
* To comply with legal obligations or respond to valid public authority requests.
* To protect the rights, property, or safety of Clipmap, our users, or the public.

---

## 5. Security of Your Data

We use industry-standard security measures (including secure HTTPS connections and database encryption) to protect your data. However, no method of transmission over the Internet or electronic storage is 100% secure. While we strive to protect your personal information, we cannot guarantee its absolute security.

---

## 6. Permissions Required

* **Internet Access:** Necessary to communicate with our backend APIs, load map tiles, and fetch/play shared video streams.

---

## 7. Children's Privacy

Our services are not intended for children under the age of 13. We do not knowingly collect personal data from children. If we discover that a child under 13 has provided us with personal data, we will delete it immediately.

---

## 8. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy in this repository. You are advised to review this policy periodically for any changes.

---

## 9. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us at:
* **Email:** ankitpangy@gmail.com
