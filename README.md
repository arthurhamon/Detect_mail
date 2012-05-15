<h1>detect_mail.js</h1>

detect_mail is a Jquery plugin for mail detection among your website.
This plugin relies on the Jquery librairy that you have to load  before using detect_mail.js

It will be supported by any browser.

<h1>Usage</h1>


First, in order to use this plugin, you need to load it in your header, after you loaded the last version of jquery.
Once this first step is done, you have to write a command in your script to launch the plugin.

<pre>
	<code>
		$(document).ready(function(){
			$('body').detect_mail({
			});
		});
	</code>
</pre>

<h1>Options</h1>

Default :
<pre>
	<code>
		popup : false,
		newtab : false,
		color : "#43494d",
		backgroundColor : "#aaa",
		border : "1px solid #888",
		colorhover : "#43494d",
		backgroundColorhover : "#ddd",
		mailcolor : "#000",
		mailstyle : "italic"
	</code>
</pre>

