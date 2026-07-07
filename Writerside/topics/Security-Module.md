# Security

Automated protection against spam bots and malicious accounts. Configure under **Settings > Security**.

## Honeypot

A hidden channel that real members never interact with. Anyone who posts in it is almost certainly a bot or a scam account, so the bot takes action automatically:

- **Honeypot channel** - the trap channel itself.
- **Action** - what happens to the account that triggers it (e.g. ban or kick).
- **Message deletion** - how many days of that account's messages get deleted along with the action (0-7 days).
- **Kick delete mode** - when the action is a kick, whether only the message that triggered the honeypot gets deleted, or a wider cleanup happens.
- **Custom DM message** - a message sent to the user before the action is taken, if you want to explain why.

## Logging

- **Log channel** - where security actions (bans/kicks triggered by the honeypot) get reported, separate from the general <a href="Logging-Module.md">Logging module</a>.

## Status message

You can also post a status embed showing the current security configuration to a channel, useful as a quick reference or for transparency with your moderation team.
