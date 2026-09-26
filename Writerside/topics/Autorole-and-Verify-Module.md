# Autorole and Verify

Two related features on one settings page: **Settings > Autorole**.

## Autorole

Automatically gives new members one or more roles as soon as they join - no verification step required. Just enable it and pick the roles.

## Verify System

A stricter version: new members click a button in the verify channel, solve a captcha the bot sends them by direct message, and only then receive the standard roles.

- **Enable/disable** the verify system.
- **Verify channel** - where the verify button/message is shown.
- **Standard roles** - the roles given once someone verifies.

After saving, use <code>/sendverifymessage</code> in Discord to post the message with the verify button.

<warning>
While the Verify System is active, every bot that joins your server is banned automatically. Switch Verify off for a moment when you add a new bot.
</warning>

<note>
If both are active, Autorole hands out the roles right away and Verify only checks the accounts. More details are in <a href="Setup-Verify-System.md"/>.
</note>

<tip>
Use Autorole for a low-friction community where you're not worried about bots/spam accounts. Use Verify if you want an active step between joining and getting full access - it filters out a lot of automated join-spam.
</tip>
