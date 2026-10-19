# Fantasy Sports for Watch Privacy Policy

Last updated: October 14, 2026

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

On your device:

• ESPN authentication tokens (SWID and espn_s2) are stored in the iOS/watchOS Keychain, which is encrypted by the operating system.
• League IDs, Sleeper usernames, and app preferences are stored in UserDefaults and App Group shared containers (for communication between the iPhone app, Watch app, widgets, and complications).

On our server (only if you use Live Activities):

To keep Live Activities on your Lock Screen and Dynamic Island up to date while the App isn't open, our server keeps a small amount of information about each matchup you are following:

• Push notification tokens issued by Apple, which let the server update your Live Activities and briefly wake the App to refresh them. These identify the activity or app installation, not you.
• What the Live Activity shows: team names, league name, scores, and the names, positions, and points of players in the lineups.
• Information needed to calculate live scores: league and roster identifiers, lineups (players, lineup positions, pro teams, projected and actual points), and your league's scoring rules.

Your ESPN authentication tokens and your Sleeper username are never stored on the server. This information is deleted automatically: Live Activity records 12 hours after their last update, automatic-start settings after 14 days without use, and records for ending activities after 2 days. It is also removed when you end a Live Activity.

Third-Party Services

The App communicates with the following third-party services to retrieve your fantasy league data:

• ESPN Fantasy API (lm​-api​-reads​.fantasy​.espn​.com, fan​.api​.espn​.com): Your ESPN authentication tokens are sent directly to ESPN's servers to fetch your league, roster, and matchup data. ESPN's own privacy policy governs their handling of this data.
• Sleeper API (api​.sleeper​.app): Your Sleeper username and league IDs are sent to Sleeper's public API to fetch league data. No authentication tokens are required. Sleeper's own privacy policy governs their handling of this data.
• Cloudflare Workers (fantasy​-watch​-backend​.amiracle​.workers​.dev): Our server, hosted on Cloudflare. It relays league data requests to ESPN and Sleeper for the widgets, complications, and the Offload Processing setting; for those requests your ESPN authentication tokens pass through it to ESPN and are not stored. It also keeps Live Activities up to date as described above, using ESPN's and Sleeper's public data. Cloudflare may keep short-lived operational logs of requests.
• Apple Push Notification service: Used to deliver Live Activity updates to your device.

Data Sharing

We do not sell, rent, trade, or share your personal data with any third parties. Your data is only transmitted to ESPN, Sleeper, and our server for the sole purpose of retrieving and displaying your fantasy league information.

Data Retention and Deletion

Uninstalling the App removes all data stored on your device, including your ESPN tokens, Sleeper username, league IDs, and preferences. Any Live Activity information on our server is deleted automatically within the periods above.

You can also clear your ESPN credentials or Sleeper username from within the App's settings at any time without uninstalling.

Children's Privacy

The App is not directed at children under the age of 13 and does not knowingly collect personal information from children.

Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected by updating the "Last updated" date at the top of this page.

Contact

If you have any questions or concerns about this privacy policy, please contact us at:

[azeltzdev@gmail.com]

# About Fantasy Sports for Watch

Fantasy Sports for Watch brings your ESPN and Sleeper fantasy leagues to your wrist. View live matchup scores, rosters, standings, and player stats — all from Apple Watch. Supports football, basketball, baseball, and hockey.
