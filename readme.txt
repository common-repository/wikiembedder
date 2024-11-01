=== Wikiembedder ===
Contributors: datagutten
Tags: mediawiki, wiki, embed
Requires at least: 3.5
Tested up to: 5.0
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Embed MediaWiki in a wordpress site and allow users to navigate the wiki without leaving your wordpress page.

== Description ==

The project is inspired by RDP Wiki-Press Embed by Robert D Payne. Some code is also copied (noted in source).

The difference is that this is simpler. It contains as little CSS as possible to be able to customize it for each theme.

Links are rewritten to make the users able to navigate in the wiki without leaving your wordpress page.

The text on the wiki image page will be added as a title="" tag to the image in wordpress, so by using the plugin [simple-lightbox](http://archetyped.com/tools/simple-lightbox), the text will be shown below the image in the lightbox.

It is developed for use with a private MediaWiki install, but it might work with wikipedia as well. 

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add the URL to your wiki under 'Settings'/'Mediapress' in Wordpress
4. Add the shortkode [wiki] or [wiki page="your page"] to the where your want to show your wiki.

== Tested themes ==

Virtue: Works well
WP-Forge: Works well
Twenty Ten: Trouble with image alignment
Twenty Thirteen: Works well
Twenty Fourtenn: Trouble with image alignment, pages get very narrow
Twenty Fifteen: Trouble with image alignment
