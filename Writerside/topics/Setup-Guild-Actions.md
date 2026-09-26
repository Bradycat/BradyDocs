# Guild Actions

<p>Guild Actions are the server log: the bot posts a message in a channel of your choice whenever something changes on your server. Useful if you want a history for your team without digging through Discord's audit log.</p>

<procedure title="Setting it up with /setup guildaction" id="guildaction-setup">
    <step>
        <p><b>Want to receive Guild Action alerts?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>In which channel should the notifications appear?</b> - mention the log channel with <code>#</code>. Best use a channel only your team can see.</p>
    </step>
</procedure>

## What gets logged

- Members joining and leaving the server
- <b>Server settings</b> - name, description, icon, banner, verification level, boost tier
- <b>Channels</b> - created, deleted, renamed, topic, category, slowmode, NSFW
- <b>Roles</b> - created, deleted, name, color, permissions, hoisted, mentionable
- <b>Members</b> - nicknames, timeouts, roles added or removed, bans and unbans
- <b>Voice</b> - joining, leaving and moving between voice channels, mute and deafen
- <b>Emojis and stickers</b> - added, removed, renamed
- <b>Messages</b> - edited and deleted messages
- <b>Invites</b> - created and deleted

<tip>
<p>In the dashboard you can choose which of these categories you want to see, see <a href="Logging-Module.md"/>.</p>
</tip>

<note>
<p>For deleted or edited messages the bot can only show the old content if it has seen the message before. Messages from before the log was enabled show up without content.</p>
</note>

The <a href="Setup-Verify-System.md">Verify System</a> also posts its results in this channel.
