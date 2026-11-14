# B45 Labs – Privacy Policy

**Effective date:** 2026-11-15  
**Last updated:** 2026-11-14  
**Applies to:** B45 Labs | Wayfinder v0.0.1 (Autodesk Navisworks Manage 2026)

This Privacy Policy explains how B45 Labs ("B45 Labs", "we", "our", "us") collects and uses information when you use the B45 Labs | Wayfinder add-in for Autodesk Navisworks (the "Software").

## 1. Scope
This Policy applies to information collected through the Software: usage analytics and error logs used solely for internal product development, stability improvements, and user support.

## 2. What We Collect
The Software may collect the following categories of information. Collection is organized in **two tiers**:

- **Essential data** (sections 2.1 to 2.5) is collected by default to operate, support, and improve the Software. You can turn it off entirely with the **"Share anonymous usage data to help improve B45 Labs"** toggle in the in-app My Profile window (My Profile > Privacy).
- **Optional data** (section 2.6, your user profile) is synced **only if you opt in** via the **"Also sync my profile"** toggle in My Profile > Privacy. It is **off by default**.

### 2.1 Usage Data
- One usage event for each B45 Labs | Wayfinder ribbon button you click: the button's name/identifier, whether it worked, and the time.
- Add-in version, the Navisworks product, year and build number (e.g., "Autodesk Navisworks Manage 2026"), and the Navisworks interface language (e.g., English, Portuguese).

### 2.2 Error and Diagnostic Data
- Errors of the Software itself only; errors of other add-ins are never recorded. For a failure the Software handled, only the kind of error (the exception type and its code). For a crash inside the Software, a short error message, its stack trace, and the command that was active.
- File paths, model file names, and email addresses are automatically redacted before this data leaves your machine.

### 2.3 Installation and Update Data
- First-seen and last-updated timestamps, the current add-in version, the version first installed, and the version an upgrade came from.

### 2.4 Pseudonymous Identifiers
- A randomly generated installation identifier (`install_id`) and session identifier (`session_id`). These contain no name, email, or personally identifiable information and are used only to group usage and error records for troubleshooting and analytics. The installation identifier is shared by the B45 Labs products installed on the same computer.

### 2.5 Region Data
- Country, continent, and region, derived from your IP address at the time of submission. This is coarse location only (never a street address, city, or GPS coordinates) and your IP address itself is not stored. It is collected by default under the essential tier (legitimate interest); turning off **"Share anonymous usage data to help improve B45 Labs"** stops the IP lookup entirely. The lookup is performed by a third-party service (ipwhois.app).

### 2.6 User Profile Data (Voluntary, synced only if you opt in)
If you choose to fill out the optional in-app User Profile, it is stored **encrypted** on your computer (`%AppData%\B45Labs\user-profile.enc`) and can be edited or erased at any time from the My Profile window. The profile file is shared with the other B45 Labs products installed on the same computer, and it may hold more fields than the Software ever sends (for example preferred name, industry, sector, and experience level).

If you also turn on **"Also sync my profile"** (and the usage-data toggle above is on), the Software sends these fields to our servers: full name, email address, company/studio name, role/title, and how you found B45 Labs, together with the installation identifier, the add-in version, and the time you saved the profile. It is sent again when you save your profile. Otherwise your profile never leaves your computer.

## 3. What We Do NOT Collect
We do not intentionally collect any "sensitive personal data" (special categories), such as health data, biometric identifiers, precise location data, government IDs, financial account data, or authentication credentials.

We do not collect:
- Project file contents, drawings, geometry, or BIM data.
- Navisworks model file names, file paths, or folder locations.
- The items you select or group, clash results, or project names.
- Payment information.
- Precise geolocation (street address / GPS coordinates).
- Passwords, authentication credentials, or personal communications.
- Your Windows username or computer name.
- Device or hardware specifications (processor, memory, screen resolution) or operating-system details.
- Anything you type into the Software.

Log files written on your computer (`%LOCALAPPDATA%\B45Labs\B45Wayfinder\logs`) are never sent by the Software. They may contain model or item names that appear in an error message, so redact them before you share one with support.

If such information appears in a user-provided support screenshot or log, please redact it before sharing.

## 4. How We Use Information

We use collected information strictly for internal purposes, including:
- Measuring feature adoption and command usage to prioritize development and improvements.
- Improving stability, performance, and reliability across different Navisworks versions and environments.
- Debugging and fixing errors and regressions.
- Validating installer/update distribution health (e.g., adoption by version, compatibility signals).
- Producing aggregated, anonymized metrics (e.g., usage volume by command or region) for roadmap planning.

## 5. Sharing and Disclosure
We do not sell your data and we do not share collected data with third parties for advertising or marketing.

We may use trusted service providers to store or process analytics (e.g., hosting or database services). Such providers are used only to support our internal operations and are not authorized to use the information for their own purposes. Where we rely on a named third-party service, such as **ipwhois.app** for coarse region lookup, that provider is bound to protect the data to the same standard described in this Policy and may not use it for its own purposes.

We may disclose information if required by law, court order, or to protect our rights and the security of the Software.

## 6. Other Network Use (not controlled by the usage-data toggle)
Two background requests are made by the Software whether or not "Share anonymous usage data to help improve B45 Labs" is on:

- **Update check.** At startup the Software asks the B45 Labs servers for its signed update message (a request to `https://b45labsbackend.bubbleapps.io/version-live/api/1.1/wf/latest_version_signed?plugin=Wayfinder`). The request carries only the product name (in the address and as the program name, "B45Labs-Wayfinder"); the answer is verified with a digital signature before it is used. If the request fails or the answer cannot be verified, nothing happens. As with any web request, the receiving server can see your IP address.
- **Tips & Tricks content.** The Software downloads a public content list (`https://www.b45labs.com/suite/suite.json` and its signature) so the tips and news stay current, and verifies the signature before showing it. The request carries no personal data from the Software.

The "B45 Labs Docs" and "YouTube Tutorials" buttons open your web browser only after you confirm. Apart from the above and the data described in section 2, the Software sends nothing.

## 7. Data Retention
We retain data only as long as necessary for internal analytics, troubleshooting, and product improvement.

As a general guideline:
- Usage and diagnostics data may be retained for up to **24 months** unless a longer retention is required to investigate recurring issues or to comply with legal obligations.

On your computer, usage rows that could not be sent are kept in a small queue and dropped after 3 days.

## 8. Security
Data is transmitted over encrypted (HTTPS/TLS) connections, and the local user profile is encrypted at rest on your computer. Error data is sanitized to remove file paths, model file names, and email addresses before transmission. Collected data is stored on access-controlled infrastructure and is limited to authorized personnel for the purposes described in this Policy. We implement reasonable administrative, technical, and organizational safeguards to protect collected information. However, no method of transmission or storage is 100% secure.

## 9. Your Choices and Requests
You control collection from the in-app **My Profile** window (My Profile > Privacy):
- **"Share anonymous usage data to help improve B45 Labs"**: master switch; turn it off to stop all telemetry collection (including coarse region). Anything still waiting to be sent is discarded.
- **"Also sync my profile"**: optional tier, **off by default**; turn it on to sync the profile you saved (full name, email, company, role, and how you found B45 Labs) to our servers. Turning it off, or turning off the master switch, stops further uploads. It does not by itself delete what was already stored; use **"Erase my data"** for that.
- **"Export my data"**: download a copy of what is stored locally about you (your installation ID, privacy choice, profile, Wayfinder settings, and the usage rows still waiting to be sent) as a JSON file. Rows already sent are not kept on your computer.
- **"Erase my data"**: asks the B45 Labs servers to delete the data linked to your installation ID, then deletes everything B45 Labs keeps on this computer (profile, branding, installation identity, and the Software's telemetry files). Because the profile, the installation ID and the privacy choice are shared, this also covers the other B45 Labs products on the same computer. Your on/off privacy choice is kept.

You may also contact us to:
- request information about data associated with your usage,
- request correction or deletion where applicable.

We may ask for additional information to verify your request.

## 10. International Use
The Software may be used in different countries. Information may be processed in the United States or other locations where our service providers operate.

## 11. Changes to This Policy
We may update this Policy from time to time. The "Last updated" date will reflect the most recent revision. Material changes may be communicated through release notes or in-Software notices.

## 12. Contact
For privacy questions or requests, contact:

**B45 Labs Support**  
Email: support@B45Labs.com
