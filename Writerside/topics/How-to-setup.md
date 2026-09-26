# How to setup

Bradycat has a lot of features, and there are three ways to set them up. All three change the same settings, so you can mix them freely.

<deflist type="medium">
    <def title="/setup">
        A guided setup in the chat: the bot asks you a few questions (which channel, which role, ...) and you answer them. Used for features that need channels or roles. See <a href="setupcommands.md">/setup</a>.
    </def>
    <def title="/enablefeature and /disablefeature">
        Simple on/off switches for features that don't need any further setup, or that are configured with their own command afterwards. See <a href="enablefeature.md">/enablefeature</a>.
    </def>
    <def title="Bot Dashboard">
        All settings as forms on our website, no commands needed. See <a href="Bot-Dashboard-Overview.md">Bot Dashboard</a>.
    </def>
</deflist>

With <a href="setlanguage.md"/> you can set the language of the bot.

<note>
<p>All setup commands require the <b>Administrator</b> permission on your server.</p>
</note>

## Permissions of the bot
Most problems during setup come from missing permissions. Make sure the bot can see and write in the channels you pick, and that the bot's own role is <b>above</b> every role it should hand out (level rewards, autorole, verify roles, ...). Discord does not allow a bot to give out roles that are higher than its own.
