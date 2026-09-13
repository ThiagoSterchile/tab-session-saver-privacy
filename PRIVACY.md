# Tab Session Saver — Privacy Policy

Version 1.1.0 · Prepared September 7, 2026

Tab Session Saver stores your sessions in your local Chrome profile. A saved session contains the URLs, titles and pinned state of HTTP/HTTPS tabs, window structure, a session name and creation time. It does not read page contents, cookies, passwords or form entries, and it excludes incognito windows.

## Storage and retention

Session data and backup preferences use chrome.storage.local, not cloud sync. Manual sessions remain until you delete them. Automatic backup retention, when Pro is available and enabled, removes only older automatic snapshots according to your selected count when a new snapshot is saved. A plan or license change does not remove or hide saved sessions.

You can download a rescue JSON in any plan. That file, imported JSON and clipboard exports contain saved links and titles: store and share them with care. Deleting the extension or its local data removes sessions, settings and counters. Local storage has a finite Chrome quota. Backups in the same profile do not protect against device loss and are not encrypted by this extension.

## Local usage counters

Settings includes an optional local-only set of counters: installation, first manual session saved, backup intent, backup enabled, upgrade clicks, and license activation. Development builds keep a separate simulation counter that is not a purchase. Counters contain no URLs, titles, names, email, payment data, identifiers or event timestamps. They are enabled locally by default, never transmitted, and can be viewed, reset or turned off. Turning them off erases them. Sharing their text with support is entirely your choice; it is never required to use Free.

A generic local last-backup status helps identify a skipped or failed backup. It does not contain browsing data or a raw error log.

## Network and payments

This version has no remote analytics, advertising, checkout, licensing requests or other network integration. It does not sell or send your saved sessions to anyone. When you restore a tab, Chrome visits that website normally, and the website's own privacy practices apply.

Payments and license activation are not available in this version. You should not enter card data into the extension. Before enabling a payment provider, this policy will be updated to name the provider, explain the data sent for licensing, retention and user choices. Purchase information will not include your sessions.

## Permissions

- **tabs**: read the URL, title and pinned state of currently open tabs to save a session, and restore selected saved tabs. No history API permission is used.
- **storage**: keep sessions, preferences and local counters on the device.
- **alarms**: schedule periodic local backup checks when available and enabled.

No host permissions, content scripts, remote code or unlimitedStorage permission are requested. Free remains usable without any external account.

## Contact

Support and privacy contact: thiagosterchile@gmail.com
