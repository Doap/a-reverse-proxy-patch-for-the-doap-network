=== A Reverse Proxy Patch for The Doap Network ===
Donate link: http://www.doap.com/about/donate/
Tags: reverse-proxy, x-forwarded-for, proxy, server, comments
Requires at least: 1.5.2
Tested up to: 3.5.2
Stable tag: 0.1.0

Sets the IP to the client IP provided by the X-Forwarded-For header.


== Description ==

Sets the comment IP to the client IP provided by the X-Forwarded-For header before the comment is saved to the database.

TODO: Enable X-Forwarded-for on all Wordpress MU via "Network-install". Currently only works on sub-sites. 


== Installation ==

1. Extract the compressed (zip) package in the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does this just work? =

Yep.

== Changelog ==

Please read the dynamic [changelog](http://doap.github.io/a-reverse-proxy-patch-for-the-doap-network "Reverse-Proxy Comment IP Fix ChangeLog")
