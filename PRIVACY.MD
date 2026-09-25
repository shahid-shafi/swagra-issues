# Privacy Policy

**Last updated:** September 25, 2026

Swagra ("the Extension") is a Chrome extension that lets developers import, explore, test, compare, and mock OpenAPI and Swagger APIs directly in the browser.

Swagra has no backend server and no account system. The developer never receives any of your data.

## Data Collection

Swagra does **not** collect, transmit, sell, or share any personal information. It contains no analytics, telemetry, advertising, or tracking.

## Data Stored on Your Device

To remember your workspace, Swagra saves the following in the browser's local storage (`localStorage`) on your device:

- Imported OpenAPI or Swagger specifications and recently opened specs
- API Client collections, request drafts, open tabs, and request history
- Environments and variables
- Authentication values you enter to call your own APIs, such as API keys or bearer tokens
- Cookies returned by the APIs you call, kept so they can be sent with your later requests to those APIs
- Saved spec comparisons and Mock Studio templates
- Settings and preferences, such as theme and layout
- Optional profile details you enter (name and email), which are shown only on the dashboard

None of this leaves your device unless you export it yourself as a backup file. You can delete it at any time by clearing the extension's site data or removing the extension.

## Network Activity

Swagra connects only to addresses that you choose. It does this when you:

- Import a specification from a URL, or sync a URL-imported specification to get its latest version
- Send an API request from "Try it out" or the API Client
- Open a WebSocket, Server-Sent Events, or Socket.IO connection from the API Client
- Open the product documentation, which opens in a new browser tab

These requests go directly from your browser to the address you chose. Swagra does not proxy, inspect, or copy them, and it does not send any request or response to a server run by the developer.

API Diff and Mock Studio run entirely in your browser. Mock data can contain sample image links (for example to `i.pravatar.cc` or `picsum.photos`). These are plain text and are loaded only if you open them yourself.

## Permissions

Swagra requests one permission: host access (`<all_urls>`). The API servers you work with can be anywhere (localhost, staging, production, or third-party APIs), so this access lets the extension send the requests you start to any of them. Swagra does not inject scripts into web pages or read your browsing data.

## Third-Party Services

Swagra uses no third-party services. It does not sell or transfer user data to third parties.

## Changes to This Privacy Policy

This policy is updated whenever Swagra's data handling changes. The "Last updated" date at the top shows when the latest change was made.

## Contact

For privacy questions, bug reports, or feature requests, please open an issue at https://github.com/shahid-shafi/swagra-issues/issues.
