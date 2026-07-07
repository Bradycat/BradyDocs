# Getting Started with Team-Panel

<warning>
Team-Panel is closed beta right now. If your server hasn't been given access yet, you won't see it - see <a href="What-is-Team-Panel.md"/>.
</warning>

<procedure title="Logging in for the first time">
    <step>
        <p>Go to <a href="https://beta.bradycat.de">beta.bradycat.de</a> and click <b>Login</b>.</p>
    </step>
    <step>
        <p>You'll be sent through Discord's OAuth flow. Accept it - we only ask for the permissions we actually need (your username, avatar and which servers you're in).</p>
    </step>
    <step>
        <p>You'll land on your personal dashboard. Any server where the bot is present <b>and</b> where you're a member shows up as a team you can open.</p>
    </step>
</procedure>

<warning>
If you reject cookies on your first visit, login can silently fail. See <a href="I-can-t-Login-to-dashboard.md"/> if that happens to you.
</warning>

## Getting a team set up

If your server isn't showing up, one of two things is missing:

- The bot isn't in your server yet - invite it first.
- Nobody has opened the Team-Panel for that server yet. The first person from that server to log in and click on it effectively "creates" the team entry in the panel.

Once a team exists, whoever is the Discord server owner (or has been given the right role, see <a href="Roles-and-Permissions.md"/>) can start assigning permissions to other members so they don't need owner-level access just to, say, edit the Wiki.

## Finding your way around

Every team has the same basic layout: a sidebar on the left with all active modules, and the actual content on the right. What you see in that sidebar depends on two things:

1. Which <a href="Modules-and-Settings.md">modules</a> are enabled for the team.
2. Whether your role gives you permission to view that section at all.

<tip>
If something is missing that you expect to see, it's almost always one of those two - either ask whoever manages roles to give you the permission, or check under Modules whether the feature is even turned on.
</tip>

If you manage multiple servers, you can switch between them at any time using the team switcher in the top bar, no need to log out and back in.
