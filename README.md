# Privacy Policy

**Apple Watch Ultra 4 · watchOS 27 New Tab** (Chrome extension)

**Effective date:** November 13, 2026 · applies to version 1.2.0 and later

> **The short version**
> - No account, no analytics, no ads, no tracking.
> - Your data stays in your own browser. The developer never receives any of it.
> - The only outside service is **Open-Meteo**, for the weather forecast, and only after you choose a location.

---

## 1. About this extension

"Apple Watch Ultra 4 · watchOS 27 New Tab" ("the extension") is a free Chrome extension that replaces the new tab page
with a smartwatch-style page. It is an unofficial, fan-made design and is not affiliated with or endorsed by Apple Inc.

The extension is published by the GitHub user [aminalakhsham](https://github.com/aminalakhsham) ("the developer").
The developer does not run any servers for the extension and does not collect, receive or store any of your data.

The extension only runs on its own new tab page. It does not read or change the websites you visit.

## 2. What information the extension uses

| Information | Where it is kept | Does it leave your device? |
|---|---|---|
| Your settings: watch face, colours, theme, case, band, background, options, App Menu style and the list of websites you add | Chrome's extension storage (`chrome.storage.sync`) and the page's local storage | Only through **Chrome Sync**, if you have it turned on (see section 4) |
| Weather location: either coordinates (rounded to about 100 m) or the name of a city you picked | Stored with your settings | Sent to **Open-Meteo** to get the forecast. Also synced by Chrome Sync if it is on |
| Reminders you write | Chrome's extension storage and local storage | Only through Chrome Sync, if it is on |
| Timer, stopwatch, Breathe minutes and the last weather forecast | Local storage on this device | No |
| The picture you choose for the Photo face | Local storage on this device only (shrunk to watch size) | **No.** It is never uploaded or synced |
| Your most-visited sites and their icons | Read from Chrome each time the App Menu is built. The extension does not save them | No |
| Text you type in the search box | Not stored | Passed to **your own default search engine** through Chrome, exactly like searching from the address bar |

The extension does **not** collect your name, email address, browsing history, the content of web pages, passwords,
payment details, health data or any other personal information.

## 3. Permissions and why they are needed

| Permission | Why |
|---|---|
| `storage` | Save your settings and reminders, and let Chrome sync them between your own devices. |
| `topSites` | Show your most-visited sites as icons in the App Menu. The list is only read on your device and is never sent anywhere. |
| `favicon` | Show the icons of those sites from Chrome's own icon cache, without contacting the sites. |
| `search` | Send what you type in the search box to the default search engine you chose in Chrome. |
| Location (optional) | Only if you click **Use my location**. Chrome asks you first. The coordinates are rounded to 3 decimal places (about 100 m) and used only to get the weather. You can type a city name instead. |

## 4. Services outside your browser

**Open-Meteo (weather).** When you set a location, the extension requests the forecast from
[Open-Meteo](https://open-meteo.com) (`api.open-meteo.com`). The request contains only the latitude and longitude. When you
search for a city, the text you type is sent to Open-Meteo's geocoding service (`geocoding-api.open-meteo.com`). No account,
cookie, ID or other information is sent. As with any website, Open-Meteo can see your IP address when your browser contacts
it. While a new tab is open, the forecast is refreshed about every 10 to 30 minutes. See
[Open-Meteo's terms and privacy information](https://open-meteo.com/en/terms). If you never set a location, the extension
makes no weather requests at all.

**Chrome Sync (Google).** If you are signed in to Chrome with sync turned on, Chrome syncs the extension's settings and
reminders to your other devices, as it does with other browser data. This is handled by Google under the
[Google Privacy Policy](https://policies.google.com/privacy). The developer has no access to it.

**Websites you open.** When you click a website in the App Menu or search for something, your browser goes to that website
or search engine, and their own privacy policies apply.

## 5. What the extension does not do

- No analytics, telemetry, crash reports, advertising or fingerprinting.
- No selling, renting or sharing of your data. Your data is never transferred to anyone except as described in section 4
  to show the weather.
- No use of your data for anything unrelated to the extension's features, and never to decide creditworthiness or for lending.
- No remote code: everything the extension runs is included in the extension package.

The use of information received from Chrome APIs follows the
[Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq),
including the Limited Use requirements.

## 6. Your choices and how to delete your data

- **Weather:** don't set a location, or use **Customize → Reset all settings** to remove it.
- **Photo face picture:** **Customize → Watch Face → Remove**.
- **Reminders:** delete them in the Reminders app.
- **Everything:** remove the extension from `chrome://extensions`. This deletes all of its data on that device.
  Data synced by Chrome can be cleared from your Google Account's Chrome Sync settings.

## 7. Children

The extension is not directed at children under 13 and does not knowingly collect personal information from anyone.

## 8. Security

All data stays in your browser's storage, which Chrome protects. The extension only contacts Open-Meteo, and always over
HTTPS.

## 9. Changes to this policy

If this policy changes, the new version will be posted here with a new effective date. Earlier versions can be seen in this
repository's commit history.

## 10. Contact

Questions about this policy or the extension: please open an issue at
[github.com/aminalakhsham/apple-watch/issues](https://github.com/aminalakhsham/apple-watch/issues).
