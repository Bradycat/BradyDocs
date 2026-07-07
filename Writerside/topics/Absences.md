# Absences

The Absences module lets team members mark themselves as away (vacation, busy period, whatever) and have that reflected everywhere else in the panel automatically.

<note>
Needs the <code>absences</code> module enabled.
</note>

## Requesting an absence

Any team member can submit an absence request with a start and end date. What happens next depends on your team's settings:

- If confirmation is required, someone with `confirm_absences` needs to approve it before it counts.
- `bypass_self_confirm` lets specific people (usually team leads) confirm their *own* absence requests instead of waiting on someone else.

`manage_absences` covers the settings themselves - whether confirmation is required at all, and general oversight of the absence list.

## What it affects

Once an absence is active:

- The person shows up as away in <a href="Members-and-Team-List.md">Team List</a>.
- If <a href="Calendar-and-Meetings.md">Meetings</a> is enabled, they're automatically excluded from attendance expectations for meetings that fall inside the absence period - no need to manually decline each one.

This is the main reason to enable Absences even for smaller teams: it saves the awkward "sorry I forgot to say I'm on vacation" moment before every meeting.
