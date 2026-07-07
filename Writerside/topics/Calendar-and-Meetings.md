# Calendar and Meetings

These are two separate modules that work well together: the **Calendar** for general team events, and **Meetings** for anything that needs attendance tracking.

<note>
Both need their own module enabled (<code>calendar</code>, <code>meetings</code>) and <code>manage_calendar</code> / <code>manage_meetings</code> to create entries.
</note>

## Calendar

The Calendar is a shared team calendar for maintenance windows, updates, internal events - anything worth marking on a timeline that isn't a meeting with attendees. Anyone who can view the module sees upcoming entries; only people with `manage_calendar` can add or edit them.

## Meetings

Meetings go a step further:

- **Scheduling** - set a date, time and description.
- **Attendance tracking** - members can RSVP, and if <a href="Absences.md">Absences</a> is enabled, someone marked as away is automatically handled without them having to manually decline every meeting.
- **Live protocol** - during (or after) the meeting, whoever has `write_protocol` can take notes directly in the meeting entry, so there's one place everyone can check back on afterward instead of a Discord message that scrolls away.

<tip>
`write_protocol` is separate from `manage_meetings` on purpose - you can let a note-taker write the protocol without giving them the ability to reschedule or delete meetings.
</tip>
