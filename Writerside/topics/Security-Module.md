# Security

Automated protection against spam bots and scam accounts. Configure under **Settings > Security**.

## Honeypot

A trap channel that real members have no reason to write in. Spam bots and scam accounts often post in every channel they can find - so anyone who writes in the honeypot channel is treated as one. The bot deletes the message and takes action automatically.

- **Enable/disable** the honeypot protection.
- **Honeypot channel** - the trap channel itself.
- **Action** - <b>Ban</b> or <b>Kick</b>.
- **Delete messages from the past** - for a ban: how many days of that account's messages get deleted as well (0-7 days).
- **Message deletion scope** - for a kick: delete only the message that triggered the honeypot, or all messages the account wrote today in every channel. Kicked accounts can join again.
- **DM to user** - a message sent to the account before the action is taken, if you want to explain why. Use <code>{name}</code> and <code>{guild}</code> as placeholders.

<warning>
The honeypot reacts to <b>everyone</b> who writes in the channel - moderators and admins included. Make it clear in the channel (e.g. with the status message below) that nobody should write there.
</warning>

## Log channel

- **Log channel** (optional) - where every ban or kick by the honeypot gets reported, separate from the general <a href="Logging-Module.md">Logging module</a>.

## Status message

You can post a status message in the honeypot channel - for example a warning not to write there, together with the number of accounts caught so far. Write <code>{count}</code> in a text block to show that number. The bot updates the message automatically every time the honeypot is triggered. You can also reset the counter.
