# Verify System

<p>New members have to solve a captcha before they get access to your server. This keeps out a lot of spam and raid accounts.</p>

<procedure title="Setting it up with /setup verify" id="verify-setup">
    <step>
        <p><b>Should the verification be activated?</b> - answer <code>yes</code>.</p>
        <p>If <a href="Setup-Autorole.md">Autorole</a> is active on your server, the setup ends here: new members get their roles from Autorole, and Verify only checks the accounts (see below).</p>
    </step>
    <step>
        <p><b>Where to send the message for verification?</b> - mention the channel new members should see first.</p>
    </step>
    <step>
        <p><b>What roles should users be given once they are verified?</b> - mention one or more roles with <code>@</code>.</p>
    </step>
    <step>
        <p>The bot posts a message with a <b>Verify</b> button in the channel.</p>
    </step>
</procedure>

## How members verify

<procedure title="Verifying" id="verify-usage">
    <step>
        <p>The member clicks <b>Verify</b>.</p>
    </step>
    <step>
        <p>The bot sends a captcha image by direct message.</p>
    </step>
    <step>
        <p>The member writes the code from the image back to the bot in that direct message - within 3 minutes.</p>
    </step>
    <step>
        <p>If the code is right, the member gets the roles you picked.</p>
    </step>
</procedure>

<note>
<p>Members need to allow direct messages from server members, otherwise the bot cannot send the captcha. The bot tells them if that's the case.</p>
</note>

## Account checks

- Accounts that have been reported to Bradycat several times are banned automatically when they click <b>Verify</b>.
- <b>Every bot</b> that joins your server is banned automatically while the Verify System is active.

<warning>
<p>Switch the Verify System off for a moment (<code>/disablefeature Verify System</code>) when you want to add a new bot to your server, otherwise it gets banned right away.</p>
</warning>

<tip>
<p>If <a href="Setup-Guild-Actions.md">Guild Actions</a> are set up, the results of these checks are posted in the Guild Actions channel.</p>
</tip>

## Commands

<chapter title="/sendverifymessage" id="sendverifymessage" collapsible="true">
    <p>Posts the verify message with the button in the verify channel again, e.g. after it got deleted, or after you set up Verify in the dashboard. Needs the <b>Administrator</b> permission.</p>
</chapter>

<tip>
<p>You can also set this up in the dashboard, see <a href="Autorole-and-Verify-Module.md"/>.</p>
</tip>
