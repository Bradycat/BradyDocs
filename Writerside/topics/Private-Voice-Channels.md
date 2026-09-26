# Private Voice Channels

<p>Every member can get their own voice channel and decide who is allowed in. The feature has to be set up first, see <a href="Setup-Private-Voice-Channel.md"/>.</p>

## Getting your own channel

There are two ways:

<deflist type="medium">
    <def title="Join the create channel">
        Join the voice channel your server set up for this. The bot creates a channel named after you and moves you into it right away. This channel is public.
    </def>
    <def title="/pchannel create">
        Choose <b>Private</b> (only people you add can join) or <b>Public</b> (everyone can join). The bot creates the channel, and you have 5 minutes to join it - otherwise it is deleted again.
    </def>
</deflist>

<warning>
<p>Your channel is deleted as soon as <b>you</b> leave it - even if others are still inside.</p>
</warning>

<note>
<p>You can only have one personal voice channel at a time.</p>
</note>

## Managing your channel
You have to be in your channel to use these commands, and only the owner can use them.

<chapter title="/pchannel open" id="pchannel-open" collapsible="true">
    <p>Opens your channel for everyone.</p>
</chapter>
<chapter title="/pchannel close" id="pchannel-close" collapsible="true">
    <p>Closes your channel. From now on, only members you add can join.</p>
</chapter>
<chapter title="/pchannel add" id="pchannel-add" collapsible="true">
    <p>Allows a member to join your channel.</p>
</chapter>
<chapter title="/pchannel remove" id="pchannel-remove" collapsible="true">
    <p>Removes a member from your channel.</p>
</chapter>
<chapter title="/pchannel setslots" id="pchannel-setslots" collapsible="true">
    <p>Sets how many people fit into your channel.</p>
</chapter>
