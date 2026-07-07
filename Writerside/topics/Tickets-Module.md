# Tickets

The support ticket system. Configure under **Settings > Tickets**.

## Basic setup

- **Enable/disable** the module.
- **Panel channel** - where members click a button to open a ticket.
- **Ticket category** - the Discord category new ticket channels are created under.
- **Helper roles** - roles that automatically get access to every new ticket.
- **Panel message** - the message shown in the panel channel, built with the same editor as <a href="Create-Message-Panel.md"/>.

If you ever need to re-send the panel message (after editing it, or if it got deleted), you can trigger a resend from the ticket settings page instead of rebuilding it from scratch.

## Categories

Instead of one generic ticket type, you can define multiple categories (e.g. "Support", "Report a Player", "Partnership"), each with:

- An emoji and name shown on the button
- A prefix used for the ticket channel name
- A description
- Its own Discord category to create tickets under
- Its own set of roles that get access

## Behavior options

- **Claiming** - lets a helper claim a ticket so it's clear who's handling it.
- **Transcript** - saves a transcript of the conversation when a ticket is closed, posted to a transcript channel you choose.
- **User transcript** - additionally sends the transcript to the ticket creator via DM.
