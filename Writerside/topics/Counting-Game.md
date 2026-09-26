# Counting Game

<p>Your members count up together in one channel, one number per message: 1, 2, 3, ... Whoever writes a wrong number or counts twice in a row breaks the count, and it starts again at 1.</p>

<procedure title="Setting it up" id="counting-setup">
    <step>
        <p>Enter <code>/enablefeature CountingGame</code>.</p>
    </step>
    <step>
        <p>Enter <code>/countingsettings channel</code> and pick the channel to count in.</p>
    </step>
    <step>
        <p>Done! Optionally adjust the other settings with <code>/countingsettings</code> (see below).</p>
    </step>
</procedure>

## Rules

- Every message has to be the next number.
- You can't count twice in a row - wait for someone else.
- If someone breaks the count, it starts again at 1.
- If someone edits or deletes their number, the bot posts which number it was and where the count stands.

## Saves
A save protects the count from one of your mistakes: if you write a wrong number while you have a save, the count does not start over. Your save is used up, the mistake does not show up in your stats, and the others continue with the next number. Every member starts with 2 saves. More can be bought with <code>/counting buysaves</code> - this needs the <a href="Economy-System.md">Economy System</a>.

## Commands for everyone

<chapter title="/counting stats" id="stats" collapsible="true">
    <p>You can use this to display your counting stats: saves, highest number, correct and wrong numbers, and how often you counted.</p>
    <img src="counting_stats.png" alt="Counting stats"/>
</chapter>
<chapter title="/counting buysaves" id="buysaves" collapsible="true">
    <p>Buys one save for coins. The price is set with <code>/countingsettings savecost</code> (100 coins by default).</p>
</chapter>

## Commands for admins
All settings are in <code>/countingsettings</code>. It needs the <b>Administrator</b> permission.

<chapter title="/countingsettings show" id="show" collapsible="true">
    <p>Shows all current settings, the record and the blocked members.</p>
</chapter>
<chapter title="/countingsettings channel" id="channel" collapsible="true">
    <p>Sets the channel where the members are allowed to count.</p>
</chapter>
<chapter title="/countingsettings failrole" id="failrole" collapsible="true">
    <p>Sets a role that everyone who breaks the count gets. Leave the <code>role</code> option empty to remove it again.</p>
</chapter>
<chapter title="/countingsettings math" id="math" collapsible="true">
    <p>Allows calculations like <code>2*5+1</code> instead of plain numbers.</p>
</chapter>
<chapter title="/countingsettings onlynumbers" id="onlynumbers" collapsible="true">
    <p>If this is on, only numbers are allowed in the channel and any other message breaks the count. If you turn it off, members can also chat in the channel and normal messages are ignored.</p>
</chapter>
<chapter title="/countingsettings savecost" id="savecost" collapsible="true">
    <p>Sets how many coins one save costs.</p>
</chapter>
<chapter title="/countingsettings block" id="block" collapsible="true">
    <p>Stops a member from counting, for example trolls. Their messages in the counting channel are deleted.</p>
</chapter>
<chapter title="/countingsettings unblock" id="unblock" collapsible="true">
    <p>Lets a blocked member count again.</p>
</chapter>

<tip>
<p>The channel, the fail role, calculations and "only numbers" can also be set in the dashboard, see <a href="Games-Module.md"/>.</p>
</tip>
