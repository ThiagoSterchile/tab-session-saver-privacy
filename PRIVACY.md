# Tab Session Saver — Privacy Policy

Version 1.1.1 · Commercial release preparation

Tab Session Saver stores saved sessions in your local Chrome profile. A session
contains the URLs, titles and pinned state of HTTP/HTTPS tabs, window structure, a
session name and creation time. It does not read page contents, cookies, passwords
or form entries, and it excludes incognito windows.

## Storage and retention

Session data, backup preferences and optional local counters use
`chrome.storage.local`, not cloud sync. Manual sessions remain until you delete
them. A plan or license change never removes or hides saved sessions. You can export
a rescue JSON in any plan; that file contains saved links and titles, so store it
carefully.

## Payments and license verification

Checkout is provided by Gumroad. Gumroad processes the purchase information that you
provide at checkout under its own privacy practices. The extension never sends saved
sessions, URLs, titles, browsing history, cookies, passwords or form entries to
Gumroad.

When you activate or restore Pro, the extension sends only the configured Gumroad
product identifier and the license key you enter to `api.gumroad.com` over HTTPS.
It checks that the response belongs to this product and is not refunded, disputed or
charged back. The extension stores the key, product identifier, active status and
verification time locally to restore your entitlement; it does not store or log the
purchase email or the full Gumroad response. Network failure never deletes saved
sessions.

## Permissions

- **tabs**: read the URL, title and pinned state of tabs you choose to save, and
  open selected saved tabs on restore.
- **storage**: keep sessions, preferences, local counters and the minimal local
  license record in the Chrome profile.
- **alarms**: run periodic local backup checks when enabled.
- **api.gumroad.com**: verify an entered Gumroad license key. It is not
  used to transmit session or browsing data.

There are no content scripts, remote code, advertising or cloud sync. Optional
local counters contain no URLs, titles, names, payment data or identifiers; they are
never transmitted and can be turned off or reset in Settings.

## Contact

Support and privacy contact: thiagosterchile@gmail.com.
