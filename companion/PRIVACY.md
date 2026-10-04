# Pulse Browser Companion privacy policy

Last updated October 4, 2026. Applies to Pulse Browser Companion version 0.2.1.

Pulse Browser Companion connects the Roblox session in your browser to a compatible Pulse desktop test build on your own computer. It is an independent project, not an official Roblox product.

## Data handled

When you pair, the extension reads the signed-in Roblox account's ID, username and display name. While connected, it handles avatar preview requests, outfit details, outfit creation requests and Roblox API responses. It passes requested responses to the paired Pulse desktop application at 127.0.0.1 on your computer. Requests to Roblox use your browser's existing authenticated session.

The extension does not read or export your Roblox session cookie, ask for your Roblox password, or send those credentials to Pulse. Roblox receives the authenticated requests directly from your browser. A short-lived Roblox CSRF token can be handled in memory to authorize a requested write; it is not sent to Pulse.

A temporary pairing code authorizes communication with Pulse. The extension keeps the connection information in memory and does not use extension storage, analytics, advertising, or a publisher-operated data collection server. Closing the companion tab ends its in-memory connection. Pairing expires after two hours or when Pulse closes. Requests already sent to Roblox may still complete after disconnecting.

Pulse may retain account and avatar information locally for its features, including drafts you save. Outfits saved to Roblox remain on Roblox and are governed by Roblox's policies. Disconnecting the extension does not delete desktop drafts or Roblox outfits.

## Scope and control

Only the current signed-in browser account is used. Switching accounts requires reconnecting; the extension does not enumerate other accounts or access their private information. It does not access browsing history, messages, purchases, or arbitrary webpages. Use Disconnect or close the companion tab to stop processing new requests, and uninstall the extension to remove it.

Data is used only to provide the requested account and avatar functionality. It is not sold, used for advertising, or used to determine creditworthiness. The use of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including its Limited Use requirements.

For support and privacy questions, open an issue at https://github.com/Paralied/PulsePublic/issues. Issues are public: do not include passwords, session cookies, pairing codes or private account data.
