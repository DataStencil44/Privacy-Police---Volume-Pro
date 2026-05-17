# Privacy Policy — Volume Pro

**Last updated:** 17 May 2026

Volume Pro ("the extension") is a browser extension that lets you boost and
fine-tune the volume of any browser tab. This policy explains what data the
extension handles and why.

## Summary

**Volume Pro does not collect, transmit, or sell any personal data.** It has no
servers, no analytics, and no third-party tracking. Everything the extension
stores stays inside your own browser.

## What the extension stores

Volume Pro saves a small amount of data locally so your settings persist
between sessions:

| Data | Where it is stored | Purpose |
| --- | --- | --- |
| **Per-site volume profiles** — a website's hostname (e.g. `youtube.com`) paired with your chosen volume percentage | `chrome.storage.sync` | Restores your preferred volume the next time you visit that site |
| **Soft Limiter preference** — a single on/off setting | `chrome.storage.sync` | Remembers whether the audio limiter is enabled |
| **Pre-mute volume** — the volume level of a tab before it was muted | `chrome.storage.session` | Restores the previous level when you un-mute; cleared automatically when the tab closes |

This data is stored only as website hostnames and numbers. It contains no
names, email addresses, passwords, browsing history, page content, or any
other personal information.

## Chrome Sync

Volume Pro uses `chrome.storage.sync` so your per-site volume profiles follow
you across devices where you are signed in to the same browser profile. This
synchronization is performed entirely by your browser's built-in sync feature.
The extension's developer never receives or has access to this data. You can
disable browser sync at any time in your browser settings.

## Permissions and why they are needed

| Permission | Why Volume Pro needs it |
| --- | --- |
| `storage` | Save your volume profiles and the limiter preference (see above) |
| `tabs` | Read tab titles, addresses, and favicons to show the list of tabs with adjusted volume, and to apply keyboard shortcuts to the active tab |
| `scripting` | Inject the audio-control script into a tab when needed so volume changes take effect immediately |
| `activeTab` | Apply volume changes to the tab you are currently viewing |
| Host access (`<all_urls>`) | The audio-control script must be able to run on any website you choose to adjust the volume on |

These permissions are used solely to provide the extension's volume-control
features. Volume Pro never reads, records, or transmits the content of the
pages you visit.

## Data sharing

Volume Pro does **not** share any data with the developer or with any third
party. No data is sent over the network by the extension.

## Children's privacy

Volume Pro does not knowingly collect any information from anyone, including
children.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised. Material
changes will be reflected in the extension's store listing.

## Contact

For questions about this privacy policy, contact the developer at:
**knyshbohdan44@gmail.com**
