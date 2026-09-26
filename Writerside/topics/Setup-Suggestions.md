# Suggestions System

<p>Your members can post ideas for the server, and everyone votes on them. Your team then approves or declines each suggestion.</p>

<procedure title="Setting it up with /setup suggestion" id="suggestion-setup">
    <step>
        <p><b>Should suggestions be activated?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>In which channel should you be able to write suggestions?</b> - mention the channel where the suggestions should be posted.</p>
    </step>
    <step>
        <p><b>Which ranks should be able to edit proposals?</b> - mention the role of your team with <code>@</code>. Members with this role can approve and decline suggestions.</p>
    </step>
</procedure>

## Writing a suggestion

<procedure title="Using /suggestion" id="suggestion-usage">
    <step>
        <p>Enter <code>/suggestion</code> - in any channel.</p>
    </step>
    <step>
        <p>A small form opens. Write your suggestion (10 to 2000 characters) and send it.</p>
    </step>
    <step>
        <p>The bot posts it in the suggestions channel and adds 👍 and 👎 so everyone can vote.</p>
    </step>
</procedure>

<note>
<p>Each member can post one suggestion per minute.</p>
</note>

## Approving and declining

Under every suggestion there are two buttons, <b>Approve</b> and <b>Decline</b>. Only members with the editor role or the <b>Manage Server</b> permission can use them.

- You can add a reason, but you don't have to.
- The suggestion shows the decision, who made it and the final vote count.
- The author gets a direct message with the decision.

<tip>
<p>You can also set this up in the dashboard, see <a href="Suggestions-Module.md"/>.</p>
</tip>
