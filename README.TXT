=== Tag Search ===
Contributors: wppluginsdev
Tags: search, tags, links, autolinks, SEO, automatic, tag
Requires at least: 2.7
Tested up to: 3.5
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Tag Search is a simple little tool you can use to automatically create links in your posts using your tags. 

== Description ==

Tag search grabs your saved post tags and when a tag word or phrase is encountered in your post content, Tag Search automatically creates a link which is pointed to the search page to turn the tag into a search term. When the user clicks the linked tag word or phrase all posts found to contain the tag word or phrase will be returned in the results. This is different from similar plugins that link the tagged word or phrase to it's tag page so only those posts sharing the tag are returned. 

For more information and support please visit http://wppluginsdev.com


== Credits ==

Copyright 2010 wppluginsdev


This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA



== Installation ==

Backup your WordPress database and files before you install or update. 

1. 	Upload the file and unzip it to the wp-content/plugins/ directory.

2.	Activate the plugin.

3.	Go to the Settings > Tag Search and configure the few options.

4. 	That's all there is to it. As long as everything is working and there are no conflicts with other plugins or your theme Tag Search should be functioning.

If you are having problems please visit http://wppluginsdev.com for help.


== Screenshots ==


== Changelog ==

= 1.8 =
* Settings link removed as it caused every plugin to have a settings link.

= 1.7 =
* The "Give credit to plugin author" functionality has been removed (this means: no more site wide links).
* Settings link now available from the plugins' list.  Also, the settings has been moved from its own menu to a submenu of the main Wordpress settings.

= 1.6 =
* Unfortunately, unknown due to a change in developer.

= 1.5 =
* Added an on off switch so you can turn off Tag Search from admin if desired.
* Now links only full words. Means, if tag to link is support and Tag Search finds the word 'supportive' Tag Search will now skip the word supportive instead of linking the 'support' part of the word 'supportive'.

= 1.4 =
* Changes alignment of footer credit to center instead of right.

= 1.3 =
* Fixes undefined index on line 182.

= 1.2 =
* Fixes error unexpected T_STRING on line 184


== Upgrade Notice ==

Upgrade of the plugin has been tested as much as possible, but if you encounter any problems, or anything isn't working after upgrade, then leave at a comment @ http://wppluginsdev.com/tag-search/version-1-8-released/ or make a request at the support page on Wordpress.org (http://wordpress.org/support/plugin/tag-search/).