# Utility Commands

<p>Small helpers that are always available - no setup needed.</p>

<chapter title="/userinfo" id="userinfo" collapsible="true">
    <p>Shows a profile card of a member: when they joined the server and when the account was created, their roles, since when they are boosting and whether they are timed out. If the <a href="LevelSystem.md">level system</a> or the <a href="Economy-System.md">Economy System</a> is active, the card also shows their level and coins.</p>
    <p>Without the <code>user</code> option, you see your own card.</p>
</chapter>

<chapter title="/clear" id="clear" collapsible="true">
    <p>Deletes the latest messages in the current channel. Enter how many (1 to 100).</p>
    <p>With the <code>user</code> option, only messages from that member are deleted. The bot looks through the last 100 messages of the channel for them.</p>
    <note>
        <p>Pinned messages are kept. Messages older than 14 days can't be deleted this way - Discord does not allow it. The bot tells you how many messages it skipped.</p>
    </note>
    <p>You need the <b>Manage Messages</b> permission. The bot needs <b>Manage Messages</b> and <b>Read Message History</b> in the channel.</p>
</chapter>
