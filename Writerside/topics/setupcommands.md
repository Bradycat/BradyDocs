# /setup command

<p>This command contains all the features that need to be set up on a large scale, such as channels, roles, etc.</p>
<p>Enter <code>/setup</code> followed by the feature you want to set up. The bot then asks you a few questions in the chat, one after the other.</p>

| Command | What it sets up |
|---|---|
| `/setup level` | [Level system](LevelSystem.md) |
| `/setup ticket` | [Ticket system](Setup-Ticket-System.md) |
| `/setup autorole` | [Autorole on join](Setup-Autorole.md) |
| `/setup verify` | [Verify system](Setup-Verify-System.md) |
| `/setup guessnumber` | [Guess Number game](Setup-Guess-Number.md) |
| `/setup giveaway` | [Giveaway system](Setup-Giveaway.md) |
| `/setup guildaction` | [Guild Actions (server log)](Setup-Guild-Actions.md) |
| `/setup minecraft` | [Minecraft support](Setup-Minecraft.md) |
| `/setup suggestion` | [Suggestions](Setup-Suggestions.md) |
| `/setup voice_channel` | [Private voice channels](Setup-Private-Voice-Channel.md) |
| `/setup welcome` | [Welcome messages](Setup-Welcome.md) |

## How to answer the questions

<deflist type="medium">
    <def title="Yes / No">
        Write <code>yes</code> or <code>no</code>. <code>y</code>, <code>n</code>, <code>ja</code>, <code>nein</code>, <code>j</code>, <code>true</code> and <code>false</code> work as well.
    </def>
    <def title="Channels">
        Mention the channel with <code>#</code>, e.g. <code>#welcome</code>. Voice channels can be mentioned the same way.
    </def>
    <def title="Roles">
        Mention the role with <code>@</code>. Where several roles are allowed, simply mention all of them in one message.
    </def>
    <def title="Categories">
        Send the <b>ID</b> of the category. To copy it, enable the developer mode in Discord (<b>User Settings</b> → <b>Advanced</b>), then right-click the category and choose <b>Copy Category ID</b>.
    </def>
</deflist>

<tip>
<p>Write <code>exit</code> at any time to cancel the setup.</p>
</tip>

<note>
<p>Only the admin who started the setup can answer, and only one setup can run on a server at a time. If you answer "no" to the first question, the feature is switched off and the setup ends.</p>
</note>

Every setting can also be changed later in the <a href="Guild-Settings-and-Modules.md">dashboard</a>.
