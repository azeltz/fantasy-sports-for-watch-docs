# Fantasy Sports for Watch Privacy Policy

Last updated: March 27, 2026

Overview

Fantasy Sports for Watch ("the App") is a companion app for Apple Watch and iPhone that displays your fantasy sports league data from ESPN and Sleeper. This privacy policy explains what data we collect, how it is stored, and how it is used.

Data We Collect

The App collects the following information, provided directly by you:

• ESPN Authentication Tokens: Your SWID and espn_s2 cookie values, used to authenticate with the ESPN Fantasy API on your behalf.
• Sleeper Username: Used to look up your Sleeper user ID and retrieve your league data from the Sleeper API.
• League IDs: Identifiers for the fantasy leagues you choose to track.
• App Preferences: Settings such as your selected season, display name, and low data mode preference.

The App does not collect analytics, usage data, device identifiers, or any data beyond what you explicitly provide.

How Your Data Is Stored

All data is stored locally on your device:

• ESPN authentication tokens (SWID and espn_s2) are stored in the iOS/watchOS Keychain, which is encrypted by the operating system.
• League IDs, Sleeper usernames, and app preferences are stored in UserDefaults and App Group shared containers (for communication between the iPhone app, Watch app, widgets, and complications).

We do not maintain any servers or databases that store your personal data.

Third-Party Services

The App communicates with the following third-party services to retrieve your fantasy league data:

• ESPN Fantasy API (lm​-api​-reads​.fantasy​.espn​.com, fan​.api​.espn​.com): Your ESPN authentication tokens are sent directly to ESPN's servers to fetch your league, roster, and matchup data. ESPN's own privacy policy governs their handling of this data.
• Sleeper API (api​.sleeper​.app): Your Sleeper username and league IDs are sent to Sleeper's public API to fetch league data. No authentication tokens are required. Sleeper's own privacy policy governs their handling of this data.
• Cloudflare Workers (fantasy​-watch​-backend​.amiracle​.workers​.dev): A serverless proxy that relays API requests to ESPN and Sleeper on behalf of the App. This worker processes requests in real time and does not persist, log, or store any user data, credentials, or API responses. It acts solely as a stateless relay.

Data Sharing

We do not sell, rent, trade, or share your personal data with any third parties. Your data is only transmitted to ESPN and Sleeper for the sole purpose of retrieving your fantasy league information.

Data Retention and Deletion

Since all data is stored locally on your device, uninstalling the App removes all stored data, including your ESPN tokens, Sleeper username, league IDs, and preferences.

You can also clear your ESPN credentials or Sleeper username from within the App's settings at any time without uninstalling.

Children's Privacy

The App is not directed at children under the age of 13 and does not knowingly collect personal information from children.

Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected by updating the "Last updated" date at the top of this page.

Contact

If you have any questions or concerns about this privacy policy, please contact us at:

[azeltzdev@gmail.com]
