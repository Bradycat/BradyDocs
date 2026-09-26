# Ticket System

<p>With the ticket system, members can open a private channel to talk to your team - for support questions, reports or applications.</p>

<procedure title="Setting it up with /setup ticket" id="ticket-setup">
    <step>
        <p><b>Should the ticket system be activated?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>Should the ticket claim system be activated?</b> - <code>yes</code> or <code>no</code>. With claiming, a team member can take over a ticket so everyone knows who is handling it.</p>
    </step>
    <step>
        <p><b>In which channel should you be able to create tickets?</b> - mention the channel where the ticket button should appear.</p>
    </step>
    <step>
        <p><b>In which category should the tickets be created?</b> - send the <b>ID</b> of the category (see <a href="setupcommands.md"/> for how to copy it).</p>
    </step>
    <step>
        <p><b>Which roles should have access to the tickets?</b> - mention your team roles with <code>@</code>.</p>
    </step>
    <step>
        <p>Enter <code>/sendticketmessage</code> to post the ticket message in the ticket channel.</p>
    </step>
</procedure>

## How tickets work

<procedure title="Opening a ticket" id="ticket-usage">
    <step>
        <p>A member clicks the 🎫 button under the ticket message and writes a short reason.</p>
    </step>
    <step>
        <p>The bot creates a new channel in the ticket category that only this member and your team roles can see.</p>
    </step>
    <step>
        <p>Your team answers in that channel. With claiming enabled, a team member can press <b>Claim Ticket</b> (and <b>Unclaim Ticket</b> to hand it back).</p>
    </step>
    <step>
        <p>When everything is solved, press <b>Close Ticket</b>. The channel is deleted a few seconds later.</p>
    </step>
</procedure>

<note>
<p>Every member can only have one open ticket at a time. Once a ticket is claimed, only the team member who claimed it can close it.</p>
</note>

## Commands

<chapter title="/sendticketmessage" id="sendticketmessage" collapsible="true">
    <p>Posts the ticket message (with the button to open a ticket) in the configured ticket channel. Use it after the setup, or when you changed the message or it got deleted. Needs the <b>Administrator</b> permission.</p>
</chapter>

<tip>
<p>More options are available in the dashboard: several ticket types to choose from, your own design for the ticket message, and transcripts of closed tickets. See <a href="Tickets-Module.md"/>.</p>
</tip>

<tip>
<p>You can switch claiming on and off later with <code>/enablefeature Ticket Claim</code> and <code>/disablefeature Ticket Claim</code>.</p>
</tip>
