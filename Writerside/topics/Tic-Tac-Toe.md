# Tic-Tac-Toe

<warning>
The feature is currently still in closed beta
</warning>

<p>Play Tic-Tac-Toe against another member or against the bot, right in Discord.</p>

<procedure title="Setting it up" id="tictactoe-setup">
    <step>
        <p>Enter <code>/enablefeature TicTacToe</code>.</p>
    </step>
    <step>
        <p>Optional: limit the game to one channel with <code>/tictactoe settings channel:#games</code>.</p>
    </step>
</procedure>

## Commands

<chapter title="/tictactoe challenge" id="tictactoe-challenge" collapsible="true">
    <p>Challenges another member. They have 60 seconds to accept or decline.</p>
</chapter>
<chapter title="/tictactoe bot" id="tictactoe-bot" collapsible="true">
    <p>Starts a game against the bot.</p>
</chapter>
<chapter title="/tictactoe stats" id="tictactoe-stats" collapsible="true">
    <p>Shows your wins, losses, draws and your win rate. Add the <code>user</code> option to see the stats of someone else.</p>
</chapter>
<chapter title="/tictactoe settings" id="tictactoe-settings" collapsible="true">
    <p>Sets the channel the game can be played in and the stake in coins (<code>startcoins</code>). Needs the <b>Manage Server</b> permission.</p>
</chapter>

<note>
<p>A game ends automatically if nobody makes a move for 2 minutes.</p>
</note>

## Playing for coins
If the <a href="Economy-System.md">Economy System</a> is active, every player pays the stake (50 coins by default) when the game starts:

- Against a member, the winner gets both stakes.
- Against the bot, you get double your stake back if you win.
- A draw gives everyone their stake back.

<tip>
<p>You can also switch the game on and off and pick the channel in the dashboard, see <a href="Games-Module.md"/>.</p>
</tip>
