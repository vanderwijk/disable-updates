=== Disable Updates for WordPress Core, Plugins and Themes ===  
Contributors: vanderwijk  
Donate link:  https://www.paypal.me/vanderwijk  
Tags: disable updates, disable, updates, plugin update, theme update, core update  
Requires PHP: 7.0  
Requires at least: 4.6  
Tested up to: 6.3  
Stable tag: 1.3.4  

Disables the WordPress update checking and notification system for all core, plugin and theme updates.

== Description ==

This plugin disables all WordPress updates (core, plugins and themes). This can be useful if you have multiple environments such as a live and staging server and you don't want your users to use the update functionality.

This plugin not only disables the update mechanism for the core, plugins and themes, but it also removes the update menu item from the left navigation menu in the admin.

== Screenshots ==

1. WordPress admin before activating the plugin.
2. After activating the plugin all update notices are disabled.

== Installation ==

1. Unzip the zip file and upload the folder to the `wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= I am not sure what this plugin does, should I be using it? =

No, keeping WordPress up-to-date is very important for security reasons. You should only disable WordPress updates if you keep your system up to date using another mechanism such as a staging server or svn.

= Can I submit a feature request or bug report? =

Yes, please use the [support forum](https://wordpress.org/support/plugin/disable-updates/) to report any issues you may have. You can submit code suggestions in the [GitHub repository](https://github.com/vanderwijk/disable-updates).

== Changelog ==

= 1.3.5 =  
Changed minimum WordPress version to 4.6

= 1.3.4 =  
Corrected translation filenames

= 1.3.2 =  
Disable update health check

= 1.3.0 =  
Added translation support

= 1.2.9 =  
WordPress 6.3 compatibility tested

= 1.2.5 =  
WordPress 5.8 compatibility tested

= 1.2 =  
PHP 7.2 compatibility update

= 1.1 =  
Added `automatic_updater_disabled` filter

= 1.0 =  
Initial release

== Upgrade Notice ==

= 1.3.4 =  
Corrected translation filenames, no changed to functionality