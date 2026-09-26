# LevelSystem

<p>Members earn XP by writing messages and level up over time. You can hand out roles as rewards for reaching a level.</p>

<procedure title="Setting it up with /setup level" id="level-setup">
    <step>
        <p><b>Should the level system be activated?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>In which channel should Level Up notifications be sent?</b> - mention one channel with <code>#</code>.</p>
    </step>
    <step>
        <p><b>In which channels should you not get XP?</b> - mention as many channels as you like with <code>#</code>. If every channel should give XP, just write <code>none</code>.</p>
    </step>
</procedure>

## How members earn XP

- Every message gives between 10 and 44 XP.
- A member can earn XP at most once per minute, so spamming does not help.
- Messages in the no-XP channels and in the ticket category don't give XP.
- When a member reaches a new level, the bot announces it in the level-up channel.

## Commands

<chapter title="/rank" id="rank" collapsible="true">
    <p>Shows your rank card with your level and XP. Add the <code>user</code> option to see the rank card of someone else.</p>
</chapter>
<chapter title="/leveltop" id="leveltop" collapsible="true">
    <p>Shows the 10 members with the highest level on the server.</p>
</chapter>
<chapter title="/setrewardrole" id="setrewardrole" collapsible="true">
    <p>You can use this to set the role rewards.</p>
    <p>First enter the level, e.g. level 5 (level 2 or higher), and then the role the member should get.</p>
    <warning>If a user is already above this level, they will not receive the role. It is only given when someone reaches exactly that level.</warning>
</chapter>
<chapter title="/removerewardrole" id="removerewardrole" collapsible="true">
    <p>You can use this to remove a role reward again.</p>
    <p>Enter the level, e.g. level 5, and press <shortcut>Enter</shortcut>.</p>
    <warning>Members who already got the role keep it. The bot does not remove it from them.</warning>
</chapter>

<note>
<p><code>/setrewardrole</code> and <code>/removerewardrole</code> need the <b>Administrator</b> permission. Reward roles are only handed out while a level-up channel is set, and the bot's role has to be above the reward roles.</p>
</note>

<tip>
<p>You can also manage all of this in the dashboard, see <a href="Level-System-Module.md"/>.</p>
</tip>
