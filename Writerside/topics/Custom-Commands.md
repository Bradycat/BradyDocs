# Custom Commands

<note xmlns="">It is important to note that this feature is currently only available in the closed beta.</note>

<chapter title="Creating a Custom Command" collapsible="true">
<p>With the <code>/customcommand</code> command, you can create your own custom commands that execute predefined actions when invoked. This allows you to tailor the bot's functionality to better suit your needs.</p>
<p>To create a custom command, use the following syntax:</p>
<pre><code>/customcommand create &lt;name&gt; &lt;response&gt;</code></pre>
<p>Replace <code>&lt;name&gt;</code> with the desired command name and <code>&lt;response&gt;</code> with the message you want the bot to execute when the command is called.</p>
<p>For example, to create a command named <code>greet</code> that responds with "Hello, welcome to the server!", you would use:</p>
<pre><code>/customcommand create greet Hello, welcome to the server!</code></pre>
<p>Once created, you can invoke your custom command by simply typing <code>/greet</code> in the chat, and the bot will respond with your predefined message.</p>
</chapter>
<chapter title="Deleting a Custom Command" collapsible="true">
<pre><code>/customcommand delete &lt;name&gt;</code></pre>
<p>Replace <code>&lt;name&gt;</code> with the name of the command you wish to delete.</p>
<p>For example, to delete the <code>greet</code> command, you would use:</p>
<pre><code>/customcommand delete greet</code></pre>
<p>This will remove the command from the bot's list of custom commands.</p>
</chapter>