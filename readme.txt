=== FairCoinWidget Shortcode ===
Tags: coinwidget, faircoin
Requires at least: 3.0
Tested up to: 4.0
Stable tag: trunk
License: GPLv2 or later

Defines a shortcode for embeddeding the standard coinwidget button on your Wordpress blog.

== Description ==

This plugin adds the shortcode [faircoinwidget] to embed a faircoin donation button.

Anywhere in a post or template (or sidebar widget if you have the appropriate plugins installed) you can include the text `[coinwidget address="your faircoin address"]` and it will be replaced with a button as seen on http://getfaircoin.net/widget/.

Supported attributes as documented here http://getfaircoin.net/widget/

* address - default ""
* currency - default "faircoin"
* counter - default "count"
* alignment - default "bl"
* qrcode - default "true" 
* auto_show - default "false"
* decimals - default "4"
* lbl_button - default "Donate"
* lbl_address - default "My Faircoin Address:"
* lbl_count - default "donations"
* lbl_amount - default "FAIR"

Example:

`[coinwidget
	address="fTSjheCjvTCHWkTqggn2bwyk13Cp32mvt2" currency="faircoin"
	counter="count" alignment="al" qrcode="false" auto_show="true"
	lbl_button="Press Me" lbl_address="Me Place" lbl_count="Gimme"
	lbl_amount="$$$"]`

or simply:

`[coinwidget address="<your faircoin address>"]` 

This plugin is now based on a forked version from the original coinwidget (by Sccot).
Faircoin version available at https://github.com/Yyuri/FairCoinWidget

Original bitcoin version https://github.com/scottycc/coinwidget.com 

To get public information about your Faircoin address it makes queries to https://chain.fair-coin.org/address/<your public faircoin address>.


== Usage ==

Embed the short [faircoinwidget] anywhere in your posts or template to include a coinbase button that, when clicked, will display a address for users to send Faircoin.

Supported attributes as documented here http://getfaircoin.net/widget/

* address - default ""
* currency - default "faircoin"
* counter - default "count"
* alignment - default "bl"
* qrcode - default "true" 
* auto_show - default "false"
* decimals - default "4"
* lbl_button - default "Donate"
* lbl_address - default "My Faircoin Address:"
* lbl_count - default "donations"
* lbl_amount - default "FAIR"

Example:

`[coinwidget
	address="fQntEehR37KGrqGQyLbaNxcpchtdNqWmXA" currency="faircoin"
	counter="count" alignment="al" qrcode="false" auto_show="true"
	lbl_button="Press Me" lbl_address="Me Place" lbl_count="Gimme"
	lbl_amount="$$$"]`

or simply:

`[coinwidget address="<your faircoin address>"]` 


== Installation ==

1. Download the plugin via WordPress.org or from getfaircoin.net/widget
1. Includes the faircoin version of coinwidget avaiable on (https://github.com/Yyuri/FairCoinWidget).
1. Include the shortcode anywhere in your posts or pages or template.  With the appropriate plugins you can also include shortcodes in sidebar widgets.

== Frequently Asked Questions ==

= I've installed the plugin - now what? =

Anywhere in a post or template (or sidebar widget if you have the appropriate plugins installed) you can include the text [coinwidget address="<your faircoin address>"] and it will be replaced with a button as seen on http://getfaircoin.net/widget/.

== Screenshots ==

1. The coinwidget button that how it will appear on the page
2. The expanded popup when the user clicks on the button.

== Changelog ==
= 1.1 =
* 2014-05-01
* Showing number of transactions from the chain.

= 1.0 =
* 2014-04-11
* Fork from Coinwidget Shortcode (Original Author: Kaz Okuda)
