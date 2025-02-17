# YouTube and Twitch

<tabs>
    <tab id="youtube" title="YouTube">
        <warning>
        The feature is currently still in closed beta
        </warning>
        <procedure title="" id="youtube">
            <step>
                <p>First enter <code>/enablefeature youtube</code>.</p>
            </step>
            <step>
                <p>After that, if you just type <code>/youtube</code> (and don't press enter), you can see all of YouTube's customizable features</p>
                <img src="youtube_command_list.png" alt=""/>
            </step>
        </procedure>
        <p>Now that you have activated the YouTube system, I will explain the individual things that it does.</p>
        <chapter title="/youtube adduser" id="adduser" collapsible="true">
            <p>Since the bot cannot guess which users it should stalk, you must add them with this command.</p>
            <warning>It is important that you use the @ of the user, otherwise it will not find the user!</warning>
        </chapter>
        <chapter title="/youtube listusers" id="listuser" collapsible="true">
            <p>This allows you to see which channels the bot is following.</p>
        </chapter>
        <chapter title="/youtube removeuser" id="removeuser" collapsible="true">
            <p>Here you simply enter the channel name that you no longer wish to follow. It is important that you enter it without the @.</p>
        </chapter>
        <chapter title="/youtube setchannel" id="setchannel" collapsible="true">
            <p>Here you simply enter the channel where the video/livestream announcements should be posted.</p>
        </chapter>
        <chapter title="/youtube setrole" id="setrole" collapsible="true">
            <p>Here you simply enter the role that is to be pinged.</p>
            <warning>You can only remove this roll by deleting it. You can otherwise create a role, set it and then simply delete it.</warning>
        </chapter>
    </tab>
    <tab id="twitch" title="Twitch">
        <procedure title="" id="twitch">
            <step>
                <p>First enter <code>/enablefeature twitch</code>.</p>
            </step>
            <step>
                <p>After that, if you just type <code>/twitch</code> (and don't press enter), you can see all of Twitch's customizable features</p>
                <img src="twitch_command_list.png" alt=""/>
            </step>
        </procedure>
        <p>Now that you have activated the YouTube system, I will explain the individual things that it does.</p>
        <chapter title="/twitch adduser" id="twitchadduser" collapsible="true">
            <p>Since the bot cannot guess which users it should stalk, you must add them with this command.</p>
            <warning>
                It is important that you use the username of the user, otherwise it will not find the user.<br>
                https://twitch.tv/flashbassfm (The username is flashbassfm)
            </warning>
        </chapter>
        <chapter title="/twitch listusers" id="twitchlistuser" collapsible="true">
            <p>This allows you to see which channels the bot is following.</p>
        </chapter>
        <chapter title="/twitch removeuser" id="twitchremoveuser" collapsible="true">
            <p>Here you simply enter the channel name that you no longer wish to follow. It is important that you enter it without the @.</p>
        </chapter>
        <chapter title="/twitch setchannel" id="twitchsetchannel" collapsible="true">
            <p>Here you simply enter the channel where the video/livestream announcements should be posted.</p>
        </chapter>
        <chapter title="/twitch setmessage" id="twitchsetmessage" collapsible="true">
            <p>Here you can set a message that will appear above the embed.</p>
            <img src="twitch_setmessage.png" alt=""/>
            <p><code>{name}</code> for the username</p>
            <p><code>{link}</code> for the link</p>
            <p><code>{role}</code> for the ping role</p>
            <note>All optional</note>
        </chapter>
        <chapter title="/twitch setrole" id="twitchsetrole" collapsible="true">
            <p>Here you simply enter the role that is to be pinged.</p>
            <warning>You can only remove this roll by deleting it. You can otherwise create a role, set it and then simply delete it.</warning>
        </chapter>
    </tab>
</tabs>