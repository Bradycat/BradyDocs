# Wiki

The Wiki module is your team's own knowledge base - onboarding guides, internal rules, SOPs, whatever your team needs written down somewhere everyone can find it.

<note>
Needs the <code>wiki</code> module enabled, and <code>read_wiki</code> / <code>manage_wiki</code> permissions to view or edit, see <a href="Roles-and-Permissions.md"/>.
</note>

## Wiki spaces

A team can have up to **10 separate Wiki spaces**. Splitting content into spaces makes sense once you have more than one audience - for example a public "Server Rules" space anyone can read without logging in, and an internal "Staff Handbook" space only your team sees.

Each space has its own:

- Icon, name, description and accent color
- Visibility setting
- Article tree

### Visibility

<deflist type="medium">
    <def title="Team">
        Anyone on the team with <code>read_wiki</code> can see it. The default for internal documentation.
    </def>
    <def title="Restricted">
        Same as Team, but additionally limited to specific roles or specific people you pick. Useful for e.g. a "Moderator Notes" space.
    </def>
    <def title="Public">
        Visible on the open internet, no login required, under its own link (<code>/wiki/your-slug</code>). Good for rules or FAQs you want to link from your Discord server description.
    </def>
</deflist>

<warning>
Public means public - anyone with the link can read it, including search engines. Don't put anything in a public space that should stay internal.
</warning>

## Articles

Inside a space, articles are organized in a simple tree with one level of nesting - you can group related articles under a parent article, but not sub-sub-categories. That's intentional: it keeps things easy to navigate instead of turning into a maze of folders.

Every article has a **Draft** or **Published** status. Drafts are only visible to people who can manage the wiki, so you can write and review something before the whole team (or the public) sees it.

## Writing content

Articles are written in Markdown, with a few extras available through the **Insert Block** button in the editor:

- Columns and card grids for side-by-side layouts
- Buttons (CTAs), banners and quotes
- Accordions and tabs for content that doesn't need to be shown all at once
- Stat tiles, dividers, file download links, image galleries

You don't need to remember the syntax - the Insert Block palette writes it for you, and the live preview next to the editor shows exactly how it'll look before you save.

<tip>
Callouts also work with plain Markdown blockquote syntax if you prefer typing over clicking: <code>&gt; [!NOTE]</code>, <code>&gt; [!TIP]</code>, <code>&gt; [!WARNING]</code>, <code>&gt; [!IMPORTANT]</code> and <code>&gt; [!CAUTION]</code> each render as their own styled box.
</tip>

## Media

Each Wiki space has its own media library (2 GB per space) for images you upload into articles - drag an image into the editor or use the Media button in the sidebar to manage what's already uploaded.
