# Minecraft

<p>With our bot you can find out information about a Minecraft player (whether Bedrock or Java) and check whether a Minecraft server is online.</p>
<p>Minecraft support has to be switched on first, see <a href="Setup-Minecraft.md"/>.</p>

<chapter title="/minecraft player" id="minecraft-player" collapsible="true">
<p>Shows a Minecraft player. Enter the player name, the UUID or - for Bedrock players - the Xbox gamertag.</p>
<p>With the <code>edition</code> option you can choose between <b>Java</b> and <b>Bedrock</b>. Without it, the bot looks for a Java player first and then for a Bedrock player.</p>
<tabs>
<tab title="Java" id="javaplayer">
    <p>For a Java player you get the name, the UUID, the skin (with its type) and the cape, plus links to the profile on NameMC and LabyMod.</p>
</tab>
<tab title="Bedrock" id="bedrockPlayer">
    <p>For a Bedrock player you get the gamertag, the XUID and the Floodgate UUID the player has on Java servers with Geyser.</p>
    <note>The skin of a Bedrock player is only known if the player has joined a server with Geyser before.</note>
</tab>
</tabs>
</chapter>

<chapter title="/minecraft server" id="minecraft-server" collapsible="true">
<p>Shows whether a Minecraft server is online. Enter the address of the server, e.g. <code>play.example.net</code> or <code>play.example.net:25565</code>.</p>
<tabs>
<tab title="Online" id="onlineServer">
    <p>For an online server you see how many players are online and how many fit on the server, the version and the message of the day. Bedrock servers also show their game mode, Java servers get a link to the server on NameMC.</p>
</tab>
<tab title="Offline" id="offlineServer">
    <p>If the server is offline or cannot be reached, the bot tells you that.</p>
</tab>
</tabs>
<note>Please enter the domain of the server, not an IP address. For privacy reasons the bot never shows server IPs.</note>
<p>The <code>edition</code> option works the same as for players: without it, Java is checked first, then Bedrock.</p>
</chapter>

<warning>
<p>Hypixel statistics are no longer available.</p>
</warning>
