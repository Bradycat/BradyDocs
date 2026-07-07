# Create Message via Panel

Instead of building an embed through slash command options one at a time, you can put together a message visually in the dashboard and send it straight to a channel.

<procedure title="Sending a message">
    <step>
        <p>Open your server's dashboard and go to <b>Create Message</b>.</p>
    </step>
    <step>
        <p>Pick the target channel from the list - only text channels the bot can see are shown.</p>
    </step>
    <step>
        <p>Build your message in the editor (text, embeds, buttons - whatever components you add).</p>
    </step>
    <step>
        <p>Send it. The panel talks to the bot directly, so it appears in Discord within a second or two.</p>
    </step>
</procedure>

<warning>
The bot still needs permission to view and send messages in the target channel. If sending fails, that's the first thing to check - see <a href="Create-message-via-panel-does-not-work.md"/> for the full list of reasons a send can fail.
</warning>
