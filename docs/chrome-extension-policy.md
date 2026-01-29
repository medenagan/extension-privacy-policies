# Privacy Policy (Demo Extensions)

This repository hosts privacy disclosures for a set of demo / test browser extensions built by https://github.com/medenagan/extension-privacy-policies ("we", "us").

**Note:** These extensions are **not public extensions** and are intended solely for testing purposes or limited distribution (e.g., shared with specific testers or via unlisted links with clients). They are not available on the Chrome Web Store for general public use. Even in demo/testing form, we aim to minimize data usage and be transparent about our practices.

---

## Scope

This policy applies to the following demo/test extensions ("Extensions"):

- **Reader (Demo)** – extracts readable article text from the current tab and helps the user send it via email to an inbound address.

If an extension has additional data practices beyond what is described here, those will be disclosed in an extension-specific section below.

---

## Data we handle

Depending on what the user does, an Extension may handle:

### 1) Web page data (when the user activates extraction / clipping)
- Page URL
- Page title
- Extracted readable text (e.g., article body)
- Optional metadata (site name, byline, language), if available on the page

> The extracted text may contain sensitive information depending on the page content. The user controls what pages to extract and what content to send.

### 2) User-provided settings
- A user-provided inbound email address (for sending clipped content)
- UI preferences (e.g., toggles)

### What we do NOT do
- We do not sell user data.
- We do not use extracted content for advertising or cross-site profiling.
- We do not collect passwords, payment information, or precise location.

---

## How we use data

We use data only to provide the user-facing functionality of each Extension, for example:
- displaying extracted content in the extension UI (side panel / popup)
- preparing an email draft for the user to send (subject/body prefilled)

---

## Data sharing / transfers

### Email sending (Demo Reader)
When the user clicks "Send", the Extension prepares an email addressed to the inbound email the user entered.

- If sending is done via a `mailto:` link, the email is handled by the user's email client/provider.
- The email recipient (the inbound pipeline) will receive the content (title, URL, extracted text). Retention and processing on the recipient side depends on that service.

We do not share data with third parties other than what is necessary to perform the user-requested action (e.g., the user's email provider and the configured inbound address).

---

## Data storage & retention

- Extracted article content is typically kept only in memory for the current session, to display it in the UI.
- Settings (such as inbound email and UI toggles) may be stored using the browser's extension storage (e.g., `chrome.storage`) for convenience.
- You can remove stored settings by clearing the extension's storage or uninstalling the extension.

---

## Security

We take reasonable steps to protect data in our control:
- data minimization (we only handle what's needed for the feature)
- no automatic sending; the user must explicitly trigger sending
- we rely on standard browser mechanisms for storage and clipboard where applicable

---

## Your choices

You can:
- avoid using the extraction feature
- avoid sending content by email
- clear saved settings at any time
- uninstall the extension

---

## Contact

For privacy questions or requests, please visit: https://github.com/medenagan/extension-privacy-policies
