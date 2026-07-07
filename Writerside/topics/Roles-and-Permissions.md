# Roles and Permissions

Team-Panel has its own role system. It looks similar to Discord's, but it's separate - a role here only controls what someone can do *inside the panel*, not on the Discord server itself.

<note>
The person who owns the Discord server (the actual server owner) always has full access to everything in the panel, no matter what roles say. That can't be taken away, so there's always at least one person who can fix a permissions mistake.
</note>

## Creating and assigning roles

Roles live under **Roles & Rechte** (Roles & Permissions) in the sidebar. Anyone with the `manage_roles` permission (or the owner) can:

- Create a new role with a name and color
- Pick which permissions it grants
- Assign it to one or more members

A member can have several roles at once. If any of their roles grants a permission, they have it - permissions are additive, there's no "deny" that overrides a grant from another role.

<tip>
A role can also be given the wildcard `*` permission, which grants everything, current and future. Use this sparingly - it's meant for a small "Admin" role, not for general staff roles.
</tip>

## What permissions exist

Permissions are grouped by area:

<deflist type="medium">
    <def title="General">
        <code>manage_roles</code>, <code>assign_roles</code>, <code>manage_modules</code>, <code>manage_members</code> (kicking members from the team)
    </def>
    <def title="Organization">
        <code>manage_calendar</code>, <code>manage_meetings</code>, <code>write_protocol</code> (editing live meeting notes), <code>manage_absences</code>, <code>confirm_absences</code>, <code>bypass_self_confirm</code>
    </def>
    <def title="Communication">
        <code>manage_announcements</code>, <code>manage_kummerkasten</code>
    </def>
    <def title="Productivity">
        <code>manage_boards</code>, <code>manage_notes</code>, <code>create_notes</code>
    </def>
    <def title="Services">
        <code>manage_status</code>, <code>view_status</code>, <code>read_github</code>, <code>manage_github</code>, <code>read_wiki</code>, <code>manage_wiki</code>
    </def>
    <def title="Statistics">
        <code>view_stats</code> (your own ticket stats), <code>view_all_stats</code> (everyone's)
    </def>
</deflist>

Most modules follow the same pattern: a `read_*`/`view_*` permission to see content, and a `manage_*` permission to create, edit or delete it. If a section only has one permission (like Boards or Absences), that single permission covers both reading and managing.

## A practical starting point

For a small team, three roles usually cover it:

1. **Owner/Admin** - the `*` wildcard, for one or two trusted people.
2. **Moderator** - `manage_members`, `manage_announcements`, `manage_kummerkasten`, plus whatever specific manage permissions your moderators actually need day to day.
3. **Member** - just enough to read things (`read_wiki`, `view_status`, `create_notes`) without being able to change team-wide settings.

You can always come back and adjust roles later - changes apply immediately, no need to ask people to log out and back in.
