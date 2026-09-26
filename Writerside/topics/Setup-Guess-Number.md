# Guess Number

<p>The bot thinks of a number and your members try to guess it in a dedicated channel.</p>

<procedure title="Setting it up with /setup guessnumber" id="guessnumber-setup">
    <step>
        <p><b>Should the game be enabled?</b> - answer <code>yes</code>.</p>
    </step>
    <step>
        <p><b>Which channel should the game be in?</b> - mention the channel with <code>#</code>.</p>
    </step>
</procedure>

## Playing

<procedure title="Starting a round" id="guessnumber-play">
    <step>
        <p>Enter <code>/guessnumber</code> in the game channel and pick a difficulty.</p>
    </step>
    <step>
        <p>Everyone writes numbers into the channel. The first one to hit the number wins.</p>
    </step>
</procedure>

| Difficulty | Range | Hints |
|---|---|---|
| Easy | 1 - 500 | The bot tells you if the number is higher or lower |
| Medium | 1 - 1000 | The bot tells you if the number is higher or lower |
| Hard | 1 - 300 | No hints |

<note>
<p>Only one round can run on a server at a time. The channel topic shows the current round and, afterwards, the latest winner.</p>
</note>

## Rewards
If the <a href="Economy-System.md">Economy System</a> is active, players get coins when the round ends:

- The winner gets 100 coins (Easy), 150 coins (Medium) or 250 coins (Hard).
- All other players who guessed split 60 coins between them.

<tip>
<p>You can also set this up in the dashboard, see <a href="Games-Module.md"/>.</p>
</tip>
