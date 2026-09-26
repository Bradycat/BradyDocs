# Autorole on Join

<p>Gives every new member one or more roles automatically as soon as they join your server.</p>

<procedure title="Setting it up with /setup autorole" id="autorole-setup">
    <step>
        <p><b>Do you want to activate the auto-role system?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>What role should you get when you enter the Discord Server?</b> - mention one or more roles with <code>@</code>.</p>
    </step>
</procedure>

<warning>
<p>The bot's own role has to be <b>above</b> the roles it should hand out, otherwise Discord does not allow it.</p>
</warning>

<note>
<p>Autorole and the <a href="Setup-Verify-System.md">Verify System</a> work together: while Autorole is active, new members get their roles from Autorole right away, and the Verify System only checks the accounts.</p>
</note>

<tip>
<p>You can also set this up in the dashboard, see <a href="Autorole-and-Verify-Module.md"/>.</p>
</tip>
