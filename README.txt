=== Add Genesis CPT Archive Image ===
Contributors: roadwarriorwp, alh0319, philwebs, stevejonesdev
Donate link: https://roadwarriorcreative.com/donate/
Tags: Genesis, custom post type, archive
Requires at least: 4.6
Tested up to: 5.2
Stable tag: 4.9
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds image meta field to the Genesis CPT Archive Settings Page

== Description ==

This plugin will add a metabox and field to add an image to the Genesis CPT Archive Settings Page. This is a developer level plugin that requires you to edit your theme template files to function.

== Installation ==

1. Install via WordPress.org plugin directory (coming soon!)...or...
2. Download zip file, unzip, and upload rwc-pass-parameters-to-iframe directory to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Use `genesis_get_cpt_option( 'rwc_cpt_featured_img' );` in your archive tempalate to retrive the URL of the image added on the Genesis CPT Archive Settings Page. 

== Frequently Asked Questions ==

= How do I display the archive image on my CPT archive template? =
The featured image is stored as a Genesis option.  To display the image use `genesis_get_cpt_option( 'rwc_cpt_featured_img' );` on the archive template for the CPT, which will return a string of the image URL.
= How do I enable Genesis CPT Archive Settings for my custom post type? =
When you register a CPT you will need to add `genesis-cpt-archives-settings` in the `supports` array. You can find more information about do this [here](https://www.billerickson.net/genesis-archive-settings-for-custom-post-types/).


