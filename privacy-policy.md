# Aptovil — Privacy Policy

**Developer/Publisher:** Aptovil, a software development company. Aptovil builds and
operates this medical-rep reporting app on behalf of its pharma clients — it does not
itself employ the medical representatives using the app.
**Applies to:** Life Gain (`com.aptovil.ibms.lifegain`) and Smart Rep
(`com.aptovil.ibms.smartrep`) — the same underlying app Aptovil built, published as two
separate Play Store listings, one per client brand
**Last updated:** 2026-07-05

> Play Console does not accept a file upload for this — it requires a public **URL**.
> Host this content (company website, GitHub Pages, Google Sites, etc.) at one URL and
> use that **same URL** for both apps' Play Console → Store presence → Privacy policy
> field, since one policy covers both. See the bottom of this file for the Data Safety
> form answers (identical for both listings).

---

## What these apps are

Aptovil is a software development company that builds field-reporting apps for pharma
clients. Life Gain and Smart Rep are two such apps, each built for a different client,
used by that client's own **medical representatives (the client's employees, not
Aptovil's)** to log their daily customer visits (doctors, chemists, stockists),
product/sample activity, and attendance as part of their job. They are not public
consumer apps. Both run the same codebase Aptovil built and collect data the same way,
each published as a separate Play Store listing for its respective client.

## Information we collect

| Data | What it's for |
|---|---|
| **Location (GPS)** | Captured only while the app is in the foreground, at check-in/check-out of a visit and at attendance punch-in/out — used to confirm a rep actually visited the location logged. We do **not** track location in the background or outside these moments. |
| **Camera** | Used only when a rep manually adds a new/unlisted doctor record, to attach a reference photo. The photo is not uploaded automatically — sharing/use is user-initiated. |
| **Visit & customer records** | Doctor/chemist/stockist name and business details, products discussed, samples given, and similar call-related notes the rep enters — this is business/CRM data about the rep's work, not the end customer's personal or medical information. |
| **Account/login information** | Employee login used to identify which rep is submitting a report. |
| **Device information** | Basic device identifiers used to associate submitted data with a device/installation for support and record-keeping. |

## What we do **not** collect

- No patient health records, prescriptions, or medical history of any individual
- No financial or payment information
- No background location tracking
- No data shared with, or sold to, advertisers or third-party marketers
- No third-party analytics, advertising, or crash-reporting SDKs are integrated in
  either app

## How data is used and stored

Data entered in either app is transmitted to backend systems that Aptovil builds and
operates on behalf of the relevant client, and is used solely so that client can review
and manage its own field representatives' work. Aptovil, as the developer/operator of
this infrastructure, has the technical access necessary to build, host, and support the
app, but does not use client data for its own independent purposes. Data collected
under one client brand (Life Gain or Smart Rep) is kept separate from the other's and
is not shared between clients.

## Who can access it

The relevant client's own authorized personnel (the rep's reporting managers and
relevant internal admin staff for that client) can access the data submitted through
their app. Aptovil, as the developer/operator, has technical access as needed to
provide and support the service, under obligations to the client not to use that data
for any other purpose.

## Data retention & deletion

Data is retained for as long as needed for the relevant client's internal
business-reporting purposes. A rep, or their employer (the client company), may request
review or deletion of their data by contacting Aptovil using the details below.

## Children's privacy

These apps are intended solely for use by adult employees of Aptovil's client
companies, in the course of their employment. They are not directed at, and we do not
knowingly collect information from, children.

## Changes to this policy

If this policy changes, the updated version will be posted at this same URL with a
revised "Last updated" date above.

## Contact

For questions about this policy or to request access/deletion of your data, contact:
**[insert Aptovil support/contact email here before publishing]**

---

## For Play Console's Data Safety form (reference, not part of the public policy)

Same answers apply to both the Life Gain and Smart Rep listings:

| Question | Answer |
|---|---|
| Does your app collect or share user data? | Yes |
| Location — collected? | Yes, approximate + precise, foreground only |
| Location — shared with third parties? | No |
| Location — purpose | App functionality (visit verification) |
| Photos — collected? | Yes (Camera) |
| Photos — shared with third parties? | No |
| Photos — purpose | App functionality |
| Is data encrypted in transit? | **Confirm before publishing** — see
  [play-store-deployment.md §3](./play-store-deployment.md) which currently flags
  `usesCleartextTraffic` and a plain-HTTP `API_BASE_URL` in the Android build config as
  needing to move to HTTPS. Do not answer "yes" here until that's fixed. |
| Can users request data deletion? | Yes, via contact email above |
| Data collection is required or optional? | Required (core functionality of the app) |
