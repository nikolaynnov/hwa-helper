# Privacy policy — "Hero Wars: помощник гильдии"

## What the extension does

The extension keeps your hero and titan power values in your guild's Telegram bot up to date. It works only for one specific guild in Hero Wars Alliance; for anyone else it does nothing.

## What it reads

While you have the game open at hero-wars-alliance.com, the extension reads the game's own network responses on that page to obtain your hero and titan roster (unit id, power, level, equipped talisman) and your guild's id and name. It reads nothing else on the page and does not read pages of other sites.

When the bot's mini app (archery.devmsk.com) is open inside Telegram Web, the extension reads the mini app's own responses to obtain the power values the bot currently stores for you, and the mini app's own access parameters, so that it can call the bot's API from that same page on your behalf.

## What it stores

All data is stored locally in your browser (chrome.storage.local) and never leaves your device except as described below: your roster snapshot, the bot's snapshot, the mini app access parameters, your guild id, your settings (reminder threshold, staleness period) and the state of the last update. Uninstalling the extension deletes all of it.

## What it sends, and where

Data is sent only when you click "Update in bot", and only to your guild's bot at archery.devmsk.com: unit ids, power values and talisman/relic flags for your own heroes and titans. The bot identifies you the same way it already does inside Telegram; the extension adds no identifiers of its own.

Nothing is ever sent to the developer of the extension or to any third party. There are no analytics, no telemetry, no advertising and no remote code.

## Telegram

To reach the bot, the extension opens web.telegram.org in a background tab and presses the bot's "open app" button for you, then closes the tab. It does not read your chats, contacts or messages and does not send messages on your behalf.

## Permissions

storage — local storage described above; notifications — to report the result; tabs — to open and close the Telegram tab; host access to hero-wars-alliance.com, web.telegram.org and archery.devmsk.com — for the reading and sending described above.

## Contact

<https://t.me/nikolaynnov>
