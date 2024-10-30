=== Plugin Name ===
Contributors: bobvann
Donate link: http://example.com/
Tags: google, analytics, cookieless
Requires at least: 3.0.1
Tested up to: 4.4.2
Stable tag: 0.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple plugin which integrates Google Analytics in your website without using third party cookies

== Description ==

This is a plugin which integrates Google Analytics into your blog or website, but in a different way.
It does not install any cookie from analytics, but it does use a php ajax backend which stores the data in php SESSION, which is preserved using a cookie, but a first party technical cookie.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/cookieless-google-analytics` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the "CL Analytics" menu entry to set up



== Frequently Asked Questions ==

= How does it work? =

It uses php SESSION instead of cookies, so information is stored server side and only PHP SESSID first party technical cookie is installed

== Screenshots ==

1. Plugin settings page

== Changelog ==

= 0.0.1 =

First version released

= 0.0.1 =

First version released
