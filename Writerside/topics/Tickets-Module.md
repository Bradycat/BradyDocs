# Tickets

The support ticket system. Configure under **Settings > Tickets**.

## Basic setup

- **Enable/disable** the module.
- **Panel channel** - where members open a ticket.
- **Ticket category** - the Discord category new ticket channels are created under.
- **Helper roles** - roles that automatically get access to every new ticket.
- **Panel message** - the message shown in the panel channel, built with the same editor as <a href="Create-Message-Panel.md"/>. Without your own message, the bot uses a simple default one.

After saving, click **Send ticket message** to post the panel in the panel channel. Use it again whenever you changed the panel message or it got deleted - the same as <code>/sendticketmessage</code>.

## Ticket types

Without ticket types, the panel has a single 🎫 button. Instead, you can define several types (e.g. "Support", "Report a Player", "Partnership") - then members pick the type from a dropdown. Each type has:

- A name and a description, shown in the dropdown
- Its own Discord category to create the tickets in
- Its own set of roles that get access

The ticket channel is named after the type and the member, e.g. <code>Support-lukas</code>.

<note>
The <b>emoji</b> and <b>prefix</b> fields of a ticket type are currently not shown in Discord.
</note>

## Behavior options

- **Claiming** - lets a helper claim a ticket so it's clear who's handling it. A claimed ticket can only be closed by the helper who claimed it.
- **Transcript** - saves a transcript of the conversation when a ticket is closed, posted to a transcript channel you choose.
- **User transcript** - additionally sends the transcript to the ticket creator via DM.

How members open and close tickets is explained in <a href="Setup-Ticket-System.md"/>.
