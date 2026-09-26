# Custom Commands

<note>It is important to note that this feature is currently only available in the closed beta.</note>

<p>Custom commands are your own slash commands: a member types e.g. <code>/rules</code> and the bot answers with a text you wrote. They are created in the dashboard - there is no bot command for it.</p>

<procedure title="Creating a custom command" id="custom-command-create">
    <step>
        <p>Open your server in the dashboard and go to <b>Settings</b> → <b>Custom Commands</b>.</p>
    </step>
    <step>
        <p>Add a command, give it a <b>name</b> and write the <b>response</b>.</p>
    </step>
    <step>
        <p>Optional: make the answer only visible to the person who used the command (<b>ephemeral</b>), or limit the command to certain <b>roles</b>.</p>
    </step>
    <step>
        <p>Save. The command shows up in Discord shortly after.</p>
    </step>
</procedure>

## Rules for the name

- Only lowercase letters, numbers, <code>-</code> and <code>_</code>, up to 32 characters.
- Every name can only be used once.
- Names of built-in commands like <code>/rank</code> or <code>/setup</code> can't be used.

## Good to know

- Responses can be up to 2000 characters long.
- If you restrict a command to roles, admins can still always use it.
- Members and roles mentioned in the response are pinged, <code>@everyone</code> and <code>@here</code> never.
- Discord allows up to 100 commands per server, including the built-in ones. Custom commands that don't fit anymore are skipped.

To delete a custom command, remove it in the dashboard and save.

See also <a href="Custom-Commands-Module.md"/>.
