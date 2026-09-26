# Top Words

<warning>
The feature is currently still in closed beta
</warning>

<p>The bot counts which words are written most often on your server and shows them as a ranking.</p>

<procedure title="Setting it up" id="topwords-setup">
    <step>
        <p>Enter <code>/enablefeature TopWords</code>.</p>
    </step>
    <step>
        <p>From now on, the bot counts the words in new messages. Enter <code>/topwords</code> to see the ranking.</p>
    </step>
</procedure>

## /topwords
Shows the most used words on the server, 10 by default. With the <code>count</code> option you can show between 3 and 25 words.

## What counts as a word

- Only words with 3 to 30 letters.
- Common filler words (in English and German, like "the" or "und") are ignored.
- Links, mentions, custom emojis and code blocks are ignored.
- Every word counts only once per message, so spamming a word doesn't push it up the list.

<note>
<p>Only messages written after the feature was switched on are counted.</p>
</note>

<tip>
<p>You can also switch Top Words on and off in the dashboard under <b>Settings</b>, see <a href="Guild-Settings-and-Modules.md"/>.</p>
</tip>
