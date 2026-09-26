# Custom Commands

Create your own slash commands directly from the dashboard, under **Settings > Custom Commands**. This is the only way to create them - there is no bot command for it. Custom commands are part of the closed beta.

For each command you define:

- **Name** - what members type after the slash. Lowercase letters, numbers, <code>-</code> and <code>_</code>, up to 32 characters.
- **Response** - the message the bot replies with (up to 2000 characters).
- **Ephemeral** - whether the response is only visible to the person who used the command, or shown to everyone in the channel.
- **Allowed roles** - restrict who can use the command. Leave empty to let everyone use it. Admins can always use it.

You can add as many custom commands as you need, and remove or edit them the same way.

<note>
Commands with an invalid name, a name that is used twice or the name of a built-in command (like <code>/rank</code>) are skipped. The same happens once your server reaches Discord's limit of 100 commands.
</note>

More details are in <a href="Custom-Commands.md"/>.
