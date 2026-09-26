# Private Voice Channel

<p>Members get their own voice channel on demand instead of you creating a fixed number of voice rooms. This page covers the setup, how members use their channel is explained in <a href="Private-Voice-Channels.md"/>.</p>

<procedure title="Setting it up with /setup voice_channel" id="voice-setup">
    <step>
        <p><b>Do you want to activate the personalized voice channels?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>Which channel should you enter to be able to create a voice channel?</b> - mention a voice channel with <code>#</code>. Whoever joins this channel gets their own channel.</p>
    </step>
    <step>
        <p><b>In which category should the Personalized Voice Channels be created?</b> - send the <b>ID</b> of the category (see <a href="setupcommands.md"/> for how to copy it).</p>
    </step>
</procedure>

<tip>
<p>Create an empty voice channel called something like "➕ Create channel" and use it as the channel to join.</p>
</tip>

<note>
<p>The bot needs the <b>Manage Channels</b> and <b>Move Members</b> permissions in that category.</p>
</note>

You can also set this up in the dashboard, see <a href="Voice-Channels-Module.md"/>.
