=== SharedItems2WP ===
Contributors: world_eggplant, jardenberg, fridholm
Author: jardenberg (Joakim Jardenberg)
Author URI: http://jardenberg.se/
Plugin URI: http://jardenberg.se/shareditems2wp
Tags: google, shareditems, shared-items, automatic, feed, feeds, rss, post
Requires at least: 2.8
Tested up to: 2.8.4
Stable tag: trunk

NOTE! FIRST RELEASE - MAY CONTAIN LOTS OF BUGS!
Use Google Reader to share with notes and let this plugin automatically and on schedule create a post in your Wordpress blog.

== Description ==

NOTE! FIRST RELEASE - MAY CONTAIN LOTS OF BUGS!
Use at own risk!

Sharing is caring and a lot of us came to love a plugin for Wordpress called Shared Items Post. Problem is, it was buggy and outdated, and the author stopped answering calls. So this is a new stab at that same functionality.

What it does: Use Google Reader to share with notes, set up some options in the admin panel of SharedItems2WP and watch your notes and links automatically and on schedule become a beautiful post in your Wordpress blog. Really simple and extremely handy to keep that daily blog post coming.

How to use:

   1. Simple setup, just enter the URL to your public sharing page from Google reader
   1. Set timer, or ”Run Now”
   1. Edit post template using simple elements
   1. Set default Author, Category and Tags
   1. There’s no step five…
   1. more info on [jardenberg.se](http://jardenberg.se/shareditems2wp)

Whats new?

* Stability. The previous version hade some timing- and duplicate issues.
* Link resolver. If you share a Feedburner URL we will do everything possible to resolve that to the proper url.
* Code cleanup.
* Fixed a long overdue problem with simplepie.

Credits:

* Jonas Skovmand [world_eggplant](http://twitter.com/world_eggplant)
* Marcus Fridholm [scatcat](http://twitter.com/scatcat)

== Installation ==

This plugin follows the [standard WordPress installation method]:

1. Upload `SharedItems2WP` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Edit your settings, It should be pretty much self-explanatory

[standard WordPress installation method](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins)

== Changelog ==

= 2.0.4 =
* WordPress timezone setting is now honored.

= 2.0.3 =
* Try to fix problem with Simplepie. Uses `require_once(ABSPATH.WPINC.'/class-simplepie.php');`


= 2.0.2 =
* In sync with Github. Bugfix

= 2.0.0 =
* Inital public release

= 1.0 =
* First version, only on [Github](http://github.com/jardenberg/SharedItems2WP/tree/master)
