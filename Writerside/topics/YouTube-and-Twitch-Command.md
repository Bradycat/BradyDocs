# YouTube and Twitch

<tabs>
    <tab id="twitch" title="Twitch">
        <p>The bot posts an announcement as soon as a streamer you follow goes live on Twitch. When the stream ends, the announcement is updated with the game and how long the stream lasted.</p>
        <procedure title="" id="twitchprocedure">
            <step>
                <p>First enter <code>/enablefeature Twitch</code>.</p>
            </step>
            <step>
                <p>Set the channel with <code>/twitch setchannel</code> and the ping role with <code>/twitch setrole</code>.</p>
            </step>
            <step>
                <p>Add the streamers with <code>/twitch adduser</code>.</p>
            </step>
        </procedure>
        <warning>
            <p>The ping role is required. Without a role, the bot does not post any announcements.</p>
        </warning>
        <p>If you just type <code>/twitch</code> (and don't press enter), you can see all of Twitch's customizable features:</p>
        <img src="twitch_command_list.png" alt="The /twitch commands"/>
        <chapter title="/twitch adduser" id="twitchadduser" collapsible="true">
            <p>Since the bot cannot guess which users it should follow, you must add them with this command.</p>
            <warning>
                It is important that you use the username of the user, otherwise it will not find the user.<br/>
                https://twitch.tv/flashbassfm (The username is flashbassfm)
            </warning>
        </chapter>
        <chapter title="/twitch listusers" id="twitchlistuser" collapsible="true">
            <p>This allows you to see which channels the bot is following.</p>
        </chapter>
        <chapter title="/twitch removeuser" id="twitchremoveuser" collapsible="true">
            <p>Here you simply enter the username that you no longer wish to follow.</p>
        </chapter>
        <chapter title="/twitch setchannel" id="twitchsetchannel" collapsible="true">
            <p>Here you simply enter the channel where the livestream announcements should be posted.</p>
        </chapter>
        <chapter title="/twitch setmessage" id="twitchsetmessage" collapsible="true">
            <p>Opens a small form where you can write the message that appears above the announcement.</p>
            <img src="twitch_setmessage.png" alt="The Twitch message form"/>
            <p><code>{name}</code> for the username</p>
            <p><code>{link}</code> for the link</p>
            <p><code>{role}</code> for the ping role</p>
            <note>All optional</note>
        </chapter>
        <chapter title="/twitch setrole" id="twitchsetrole" collapsible="true">
            <p>Here you simply enter the role that is to be pinged.</p>
            <note>You can change the role at any time with this command. It cannot be removed, because the announcements need a role.</note>
        </chapter>
        <note>
            <p>All <code>/twitch</code> commands need the <b>Administrator</b> permission. You can also manage Twitch in the dashboard, see <a href="Socials-Module.md"/>.</p>
        </note>
    </tab>
    <tab id="youtube" title="YouTube">
        <warning>
            <p>YouTube announcements are currently not available. The option still shows up in <code>/enablefeature</code>, but switching it on has no effect for now.</p>
        </warning>
    </tab>
</tabs>
