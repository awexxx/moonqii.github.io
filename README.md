<p align="center">
  <img width="260" src="https://cdn.medal.tv/assets/img/avatars/default.png">
</p>

<p align="center">
	<strong>An extra Medal Clip Sharing method</strong>
</p>

<hr>

<p align="center">Ever needed a second method to share your clips to Discord or Guilded but don't have the space for Medal, are building a community or are on Guilded and don't have MedalBot?<br>
<strong>You've come to the right place!</strong></p>

<p align="center">This webhook is developed in PHP and POSTs to a basic webhook, whether that be Discord, Guilded, or maybe even Slack (if you're looking into that???)!<br>
This webhook is mainly for users who are building a community but don't clip games and just want a way for your users to share clips and/or are on Guilded or Slack (or any other social media service that accepts webhooks).<br>
However, this webhook does not have some things that Medal has, like auto-uploading, integrated uploading, and more. I still sincerely recommend using <a href="https://medal.tv/download">Medal</a>, maybe even use my <a href="https://medal.tv/?ref=awex_partner">partner link</a> ;).</p>

<hr>

<h2 align="center">A few key points..</h2>
	<p align="center"><strong>First point</strong>: If you'd like to self host this, it is expected you have at least <i>some</i> experience with PHP, however I'm happy to help and answer any questions you may have regarding setting this up! You should check out the <a href="https://github.com/awexxx/medal-clip-webhook/wiki">wiki</a> for more info on self-hosting this script.</p>
		<p align="center"><strong>Second point</strong>: There are multiple scripts to this webhook, all do different things.<br>
			<strong>webhook.php</strong> - JSON Embedded version (Shows in a Discord/Guilded embed).<br>
			<strong>webhook-plaintext.php</strong> - Plain Text Version (Shows in.. well plain text).</p>
			<p align="center">
				<strong>Point two and a half: Using Query Strings</strong><br>
				You can only send queried webhooks via these files.<br>
				You can use the following params:<br>
				<strong>clip</strong> - Clip link (without HTTP protocol, already embedded in the code of the file. without it, the links would not embed properly)<br>
				<strong>caption</strong> - The caption you want displayed<br>
				<strong>user</strong> - Your Medal Username<br>
				<strong>url</strong> - Webhook URL (eg. https://discordapp.com/api/webhooks/...)
				<hr>
				<p align="center">Point two and 3/4: Query Scripts</p>
			<strong align="center">query.php</strong> - Uses query string params to send the post request (Embedded Version).<br>
			<strong align="center">query-plaintext.php</strong> - Same as above, but make it <strong><i>plain text</i></strong>.</p>
