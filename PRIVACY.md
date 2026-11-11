# Nocopas privacy policy

Last updated: 11 November 2026

Nocopas is a Chrome side-panel extension that inserts your saved reply templates into chat boxes. It has no server, no account, no analytics and no advertising. **Nothing the extension handles is ever sent to the developer or to any third party.**

## What stays on your device

Nocopas stores the following in Chrome's local extension storage (`chrome.storage.local`) and the panel's `localStorage`, on your computer only:

- **Your templates** (text, category, keywords, usage counts).
- **Your site list**: the websites where direct insert is turned on.
- **Suggestion learning data**: when you use a template while a chat is open, the extension remembers which individual words in the customer's message led you to pick it, so it can suggest better next time. Only single words and weights are kept, never full messages or names.
- **Your theme choice** (System, Light or Dark).

Uninstalling the extension deletes all of this. Use **Export** first if you want a backup of your templates.

## What the extension reads

- **The focused chat box**, only when you click a template, so the text can be inserted. Nothing is read from it.
- **Recent customer messages**, only on Instagram and Threads, only while the panel is open and only on sites you allowed. They are used to suggest templates. They are held in the panel's memory and are never saved or transmitted; closing the panel clears them. Only the learning words described above are kept.
- **The Chat log** in Settings is an on-device debugging view. It lives in memory, is cleared when the panel closes, and leaves your device only if you press **Copy log** and paste it somewhere yourself.

Nocopas does not read passwords, payment details, cookies or browsing history.

## Permissions

| Permission | Why |
|---|---|
| `sidePanel` | Shows the template panel beside the page. |
| `storage` | Saves your templates, site list and settings locally. |
| `activeTab`, `scripting` | Inserts the chosen template into the focused chat box, and reads the open conversation to suggest templates. |
| Optional access to websites | Requested per site, only when you press **Allow** or add a site. You can remove it at any time in Settings or in `chrome://extensions`. |

## Sharing and selling data

None. Nocopas does not sell, share or transfer user data, does not use it for advertising or credit decisions, and does not load or run remote code.

## Children

Nocopas is not directed at children.

## Changes

If this policy changes, the new version will be published in this file with an updated date.

## Contact

Questions or concerns: open an issue at https://github.com/ibuds/nocopas/issues
