=== Big Bio Box ===
Contributors: ypraise
Donate link: http://wp.ypraise.com/2014/bbpress-big-bio-box/
Tags: user description, user bio, author
Requires at least: 3.3
Tested up to: 4.1
Stable tag: 1.2

Adds an additional bio box with tinymce editor into the profile page and swaps the default user description in author.php with the new formatted bio.

== Description ==

This plugin needs at least Wordpress 3.3 to work as it uses the new wp_editor call introduced in WP 3.3.

The Big Bio Box plugin uses the latest wp_editor api to allow your author to provide a full formatted about me page. It uses a new box in the profile page and then the user description on the author.php page is swapped for this new bio. The default description can continue to be used in other plugins such as author box at end of posts or wdigeted bios.

The new box has a fully functional tinymce editor - exactly the same as you get with the post editor so ensure your authors are responsible!

There are no setting to configure just upload and  activate.

There is no free support for this plugin.

For users of bbPress the version available at wp.ypraise.com has been enhanced to allow a tinymce editor to show on the front-end profile editor so your users can enhance their profile. Details at <a href="http://wp.ypraise.com/2014/bbpress-big-bio-box/">http://wp.ypraise.com/2014/bbpress-big-bio-box/</a>

You can see an example bbPress enhanced profile at <a href="http://raisingnoise.co.uk/forums/users/kevin/">Kevin Heath</a>




== Installation ==

1. Upload bigbiobox folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to you user profile page and check out the new big bio box.


== Frequently Asked Questions ==

= What exactly does this plugin do to my Wordpress instalation =

1. This plugin will use a filter to add a new box to the profile pages of your authors. It will also save the contents of that box into your database.
2. The plugin runs a conditional filter so if the page is an author profile page then the user description call will return the big bio box data and if the page is a single post then the user description call will return the default bio contents.

The conditional filter means that if you are using an author box pluin or function to display deatils about the author then it will still return the default description.

= The plugin does not work =

The plugin in was tested on a clean install of wordpress 3.3 and a child theme of 2010. If the plugin does not work then raise a topic for this plugin and tell me: what version of wordpress you are using, what theme are you using, do you have problems with any other tinymce call in your theme.

= What does the future hold for Big bio Box =

There seems to be a IE8 specific issue with the tinymce editor. When you use one of the drop down menus such as headings then the drop down on the first instance goes to the top of the web page. This problem does not happen in chrome or firefox.

== Screenshots ==

1. A new bio box on profile page has a full tinymce editor.
2. The new big bio box contents replaces the normal user description above the authors blog posts on the author.php page.


== Changelog ==

= 1.2 =
* Confirm operation in Wordpress 4.1 and provided notice of bbPress version.

= 1.1 =
* Cleaned up a bit of code, missing table row tags.

= 1.0 =
* The first flavour launched.


== Upgrade Notice ==

= 1.1 =
added the missing tablwe row tags to clean up the code.

= 1.0 =
None
