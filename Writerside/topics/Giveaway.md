# Giveaway

<p>Here I explain step by step how the giveaway system works.</p>

<warning>
<p>The giveaway system has to be set up first, see <a href="Setup-Giveaway.md"/>. All <code>/giveaway</code> commands can only be used by members with the giveaway role or the <b>Manage Server</b> permission.</p>
</warning>

<chapter title="/giveaway create" id="giveaway-create" collapsible="true">
<p>As the command says, you use it to create a giveaway.</p>
<deflist type="medium">
    <def title="prize">
        What can be won.
    </def>
    <def title="duration">
        How long the giveaway runs, e.g. <code>30m</code>, <code>2h</code>, <code>1d12h</code> or <code>1w</code>. Anything from 10 seconds to 90 days works.
    </def>
    <def title="winners (optional)">
        How many winners are drawn, 1 to 50. Default is 1.
    </def>
    <def title="channel (optional)">
        Where the giveaway is posted. Default is the channel you are in.
    </def>
    <def title="required-level (optional)">
        The minimum level members need to take part. Only works if the <a href="LevelSystem.md">level system</a> is active.
    </def>
    <def title="required-role (optional)">
        A role members need to take part.
    </def>
</deflist>
<p>If you press enter, the giveaway is posted in the channel. Members click <b>Enter</b> to take part - and can leave again with the button in the confirmation.</p>
</chapter>

<chapter title="/giveaway list" id="giveaway-list" collapsible="true">
<p>This allows you to view all running giveaways with their ID, prize, number of participants and end time.</p>
</chapter>

<chapter title="/giveaway end" id="giveaway-end" collapsible="true">
<p>End a giveaway early and draw the winners right away.</p>
<tip>Just enter the ID. It's shown below the giveaway ("Giveaway #12" → ID <code>12</code>) and in <code>/giveaway list</code>.</tip>
</chapter>

<chapter title="/giveaway reroll" id="giveaway-reroll" collapsible="true">
<p>The winner doesn't want the prize, doesn't respond or whatever?</p>
<p>You can use this to draw again for a giveaway that has already ended. Enter the ID of the giveaway. With the <code>winner</code> option you only replace that one winner - without it, all winners are drawn again.</p>
</chapter>

<chapter title="/giveaway delete" id="giveaway-delete" collapsible="true">
<p>This allows you to cancel a giveaway without drawing a winner. The giveaway message is removed as well.</p>
<tip>Just enter the ID.</tip>
</chapter>

## When a giveaway ends

- The bot draws the winners from all participants who still meet the requirements.
- The winners are announced in the giveaway channel and get a direct message.
- If nobody took part, the bot says so and no winner is drawn.

<tip>
<p>You can also switch giveaways on and off and pick the giveaway role in the dashboard, see <a href="Giveaway-Module.md"/>.</p>
</tip>
