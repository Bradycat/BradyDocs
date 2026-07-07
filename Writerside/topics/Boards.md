# Boards

Boards give you Trello-style task management right inside the panel - lists, cards, labels, assignees, due dates, subtasks.

<note>
Needs the <code>board</code> module enabled and <code>manage_boards</code> to create or edit boards.
</note>

A team can have up to **10 boards**. Each board is its own space with its own lists and cards - use separate boards for separate projects rather than cramming everything into one.

## Visibility

A board is either:

- **Internal** - visible to all team members by default, or restricted further to specific roles/people if you set that up.
- **Public** - anyone with the link can view it, useful for a public roadmap or "what we're working on" board.

## Working with cards

Each card can have:

- **Labels** - color-coded tags you define per board
- **Assignees** - one or more team members responsible for it
- **Due dates** - with reminders if notifications are enabled
- **Subtasks** - a small checklist inside the card
- **GitHub links** - connect a card to a pull request or commit if <a href="GitHub-Integration.md">GitHub</a> is set up

Assignees who aren't board managers can still edit the card's description and check off subtasks - they just can't restructure the board itself (rename lists, delete cards, etc.).

## Auto-archiving

If a list tends to fill up with finished cards (a "Done" list, for example), you can turn on auto-archiving for it: set how many days a card can sit there before it's automatically moved to the archive. Archived cards aren't deleted - you can restore them from the board's archive view at any time.

## Board managers

By default, only people with `manage_boards` can edit a board. You can additionally delegate management of a *specific* board to certain roles or people without giving them `manage_boards` team-wide - handy if one project lead should only be able to touch their own board.
