# Status Monitor

Uptime monitoring for whatever services your team cares about - your own website, an API, a Minecraft server - with a status page you can share publicly.

<note>
Needs the <code>status</code> module enabled. <code>manage_status</code> is required to configure monitors; <code>view_status</code> lets someone view the status page if it isn't public.
</note>

## Monitors

Each monitor checks a service on a schedule and records whether it was up, down or degraded. Monitors can be grouped into categories (e.g. "Website", "Game Servers") so the status page doesn't turn into one long undifferentiated list.

## The public status page

Every team can have its own public status page under a custom link (`/status/your-slug`). You choose whether it's fully public or restricted to people with `view_status`.

The status page shows:

- Current status per monitor, grouped by category
- Manual incidents - if something's down for a reason your automated check doesn't catch cleanly, you can post a manual incident explaining what's going on
- Scheduled maintenance - announce planned downtime ahead of time so people aren't surprised when a check goes red

<tip>
Use scheduled maintenance whenever you can plan around downtime. It stops your monitor from firing alerts (and worrying people) for downtime you already knew about.
</tip>
