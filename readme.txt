=== MyTweetMag ===
Plugin Name: MyTweetMag
Plugin URI: http://www.mytweetmag.com/
Text Domain: mytweetmag
Domain Path: /languages
Tags: News, RSS, Twitter
Description: Import news from a feed of MyTweetMag
Author: Frank B&uuml;ltge
Version: 0.5
License: GPL
Author URI: http://bueltge.de/
Last change: 07.06.2010 12:33:02

MyTweetMag - Create Collaborative Newsstreams with Twitter and Integrate them into Wordpress.

=== Description ===

 -----------------------------------------------------------
 PHP-USAGE: Use following code in Templates of the Theme
 Example: <?php MyTweetMag(10, "myusername"); ?>
 -----------------------------------------------------------
 all params with default-values:
 $display = 5,
 $username = '',
 $before_desc = '<br/>', $displaydescriptions = 0, $after_desc = '',
 $html = 1,
 $truncatedescchar = 200, $truncatedescstring = ' ... ', $truncatetitlechar = '', $truncatetitlestring = ' ... ',
 $before_date = '<br/><small>', $date = 0, $after_date = '</small>', $date_format = '',
 $before_creator = '<br/><small>', $creator = 0, $after_creator = '</small>',
 $start_items = '<ul class="mtm">', $end_items = '</ul>',
 $start_item = '<li>', $end_item = '</li>',
 $target = 'self',
 $rel = 'follow',
 $charsetscan = 0,
 $debug = 0,
 $before_noitems = '<p>', $noitems = 'No items, feed is empty.', $after_noitems = '</p>',
 $before_error = '<p>', $error = 'Error: Feed has a error or is not valid', $after_error = '</p>',
 $paging = 0, $prev_paging_link = '&laquo; Previous', $next_paging_link = 'Next &raquo;', $prev_paging_title = 'more items', $next_paging_title = 'more items',
 $use_simplepie = 1,
 $view = 1
  

 SHORTCODE-USAGE: use the following code in post or pages
 Example: [MyTweetMag display="5" username="" target="self"]
 -----------------------------------------------------------
 all params with default-values:
 'display' => 5,
 'username' => '',
 'before_desc' => '<br/>',
 'displaydescriptions' => 1,
 'after_desc' => '',
 'html' => 1,
 'truncatedescchar' => '',
 'truncatedescstring' => ' ... ',
 'truncatetitlechar' => '',
 'truncatetitlestring' => ' ... ',
 'before_meta' => '<br/><small>',
 'meta' => 0,
 'after_meta' => '</small>',
 'start_items' => '<ul class="mtm">',
 'end_items' => '</ul>',
 'start_item' => '<li>',
 'end_item' => '</li>',
 'target' => 'self',
 'rel' => 'follow',
 'charsetscan' => 0,
 'debug' => 0,
 'before_noitems' => '<p>',
 'noitems' => __('No items, feed is empty.', FB_MTM_TEXTDOMAIN),
 'after_noitems' => '</p>',
 'before_error' => '<p>',
 'error' => __('Error: Feed has a error or is not valid', FB_MTM_TEXTDOMAIN),
 'after_error' => '</p>',
 'paging' => 0,
 'prev_paging_link' => __('&laquo; Previous', FB_MTM_TEXTDOMAIN),
 'next_paging_link' => __('Next &raquo;', FB_MTM_TEXTDOMAIN),
 'prev_paging_title' => __('more items', FB_MTM_TEXTDOMAIN),
 'next_paging_title' => __('more items', FB_MTM_TEXTDOMAIN),
 'use_simplepie' => 1,
 'view' => 0
 
== Installation ==


1. Upload the folder "mytweetmag" to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to the widget-section of Wordpress and integrate the MyTweetMag-Widget in your sidebar or
4. Create a page and place the shortcode using the "MyTweetMag"-button in the edit-bar.  

== Frequently Asked Questions ==

= How can I integrate a rss-feed of the MyTweetMag-plattform? =

To integrate an RSS-Stream of MyTweetMag you have to add the TWITTER-NAME of the Magazine-Editor. If you don't know the Twitter-Name of the editor, take the last part of the MyTweetMag-URL, e.g. "mytweetmag" of the URL http://www.mytweetmag.com/mytweetmag . 

= Can I integrate a rss-feed outside of www.mytweetmag.com? =

No. The MyTweetMag-Plugin is especially designed for the MyTweetMag-Plattform. If you want to integrate other rss-feeds, please use the plugin RSS-Import by Frank Bueltge.

= Where can I find a more detailed user-guide of this plugin? = 

Please go to http://blog.mytweetmag.com and click on Plugin. You will find a Demo and a How-to-Use for this Plugin.

= How can I style the output of the plugin? =

You can style the plugin with your CSS-stylesheet. You will find detailed descpriptions in the MyTweetMag-Blog mentioned above.

== Screenshots ==
1. The MyTweetMag-widget for your sidebar screenshot-1.jpg
2. The MyTweetMag-button in the edit-bar screenshot-2.jpg
3. A Demo of the plugin in action (sidebar and static page) screenshot-3.jpg
