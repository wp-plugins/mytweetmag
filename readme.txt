=== MyTweetMag ===
Contributors: MyTweetMag, Bueltge
Donate link: http://www.mytweetmag.com/
Tags: News, RSS, Twitter
Requires at least: 2.8
Tested up to: 2.9

MyTweetMag - Create Collaborative Newsstreams with Twitter and Integrate them into Wordpress.

== Description ==

This plugin works in combination with the plattform www.mytweetmag.com and allows you to integrate rss-feeds from mytweetmag into your wordpress-blog.

There are two ways to integrate the feeds: \n
1. with a widget on the sidebar \n
2. with a shortcode in a static page \n
3. with php \n
 
PHP-USAGE:

Use following code in Templates of the Theme \n
Example: &lt;?php MyTweetMag(10, &quot;myusername&quot;); ?&gt;

All params with default-values:

$display = 5, \n
$username = '', \n
$before_desc = '&lt;br/&gt;', $displaydescriptions = 0, $after_desc = '', \n
$html = 1, \n
$truncatedescchar = 200, $truncatedescstring = ' ... ', $truncatetitlechar = '', $truncatetitlestring = ' ... ', \n
$before_date = '&lt;br/&gt;&lt;small&gt;', $date = 0, $after_date = '&lt;/small&gt;', $date_format = '', \n
$before_creator = '&lt;br/&gt;&lt;small&gt;', $creator = 0, $after_creator = '&lt;/small&gt;', \n
$start_items = '&lt;ul class=&quot;mtm&quot;&gt;', $end_items = '&lt;/ul&gt;', \n
$start_item = '&lt;li&gt;', $end_item = '&lt;/li&gt;', \n
$target = 'self', \n
$rel = 'follow', \n
$charsetscan = 0, \n
$debug = 0, \n
$before_noitems = '&lt;p&gt;', $noitems = 'No items, feed is empty.', $after_noitems = '&lt;/p&gt;', \n
$before_error = '&lt;p&gt;', $error = 'Error: Feed has a error or is not valid', $after_error = '&lt;/p&gt;', \n
$paging = 0, $prev_paging_link = '&amp;laquo; Previous', $next_paging_link = 'Next &amp;raquo;', $prev_paging_title = 'more items', $next_paging_title = 'more items', \n
$use_simplepie = 1, \n
$view = 1 \n

SHORTCODE-USAGE: 

use the following code in post or pages \n
Example: [MyTweetMag display=&quot;5&quot; username=&quot;&quot; target=&quot;self&quot;]

All params with default-values:

'display' =&gt; 5, \n
'username' =&gt; '', \n
'before_desc' =&gt; '&lt;br/&gt;', \n
'displaydescriptions' =&gt; 1, \n
'after_desc' =&gt; '', \n
'html' =&gt; 1, \n
'truncatedescchar' =&gt; '', \n
'truncatedescstring' =&gt; ' ... ', \n
'truncatetitlechar' =&gt; '', \n
'truncatetitlestring' =&gt; ' ... ', \n
'before_meta' =&gt; '&lt;br/&gt;&lt;small&gt;', \n
'meta' =&gt; 0, \n
'after_meta' =&gt; '&lt;/small&gt;', \n
'start_items' =&gt; '&lt;ul class=&quot;mtm&quot;&gt;', \n
'end_items' =&gt; '&lt;/ul&gt;', \n
'start_item' =&gt; '&lt;li&gt;', \n
'end_item' =&gt; '&lt;/li&gt;', \n
'target' =&gt; 'self', \n
'rel' =&gt; 'follow', \n
'charsetscan' =&gt; 0, \n
'debug' =&gt; 0, \n
'before_noitems' =&gt; '&lt;p&gt;', \n
'noitems' =&gt; __('No items, feed is empty.', FB_MTM_TEXTDOMAIN), \n
'after_noitems' =&gt; '&lt;/p&gt;', \n
'before_error' =&gt; '&lt;p&gt;', \n
'error' =&gt; __('Error: Feed has a error or is not valid', FB_MTM_TEXTDOMAIN), \n
'after_error' =&gt; '&lt;/p&gt;', \n
'paging' =&gt; 0, \n
'prev_paging_link' =&gt; __('&amp;laquo; Previous', FB_MTM_TEXTDOMAIN), \n
'next_paging_link' =&gt; __('Next &amp;raquo;', FB_MTM_TEXTDOMAIN), \n
'prev_paging_title' =&gt; __('more items', FB_MTM_TEXTDOMAIN), \n
'next_paging_title' =&gt; __('more items', FB_MTM_TEXTDOMAIN), \n
'use_simplepie' =&gt; 1, \n
'view' =&gt; 0 \n
 
== Installation ==

1. Upload the folder "mytweetmag" to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to the widget-section of Wordpress and integrate the MyTweetMag-Widget in your sidebar or
1. Create a page and integrate the shortcode using the "MyTweetMag"-button in the edit-bar.  

== Frequently Asked Questions ==

= How can I integrate a rss-feed of the MyTweetMag-plattform? =

To integrate a rss-stream of MyTweetMag please add the TWITTER-NAME of the magazine-editor as username. If you don't know the twitter-name of the editor, take the last part of the MyTweetMag-URL, e.g. "mytweetmag" of the URL http://www.mytweetmag.com/mytweetmag . 

= Can I integrate a rss-feed which is not from mytweetmag? =

No. The MyTweetMag-Plugin is especially designed for the MyTweetMag-plattform. If you want to integrate other rss-feeds, please use the plugin RSS-Import by Frank Bueltge.

= Where can I find a more detailed user-guide of this plugin? = 

Please go to http://blog.mytweetmag.com and click on plugin. You will find a demo and a How-to-Use for this plugin.

= How can I style the output of the plugin? =

You can style the plugin with your CSS-stylesheet. You will find detailed descpriptions in the MyTweetMag-Blog mentioned above.

== Screenshots ==

1. The MyTweetMag-widget for your sidebar screenshot-1.jpg
2. The MyTweetMag-button in the edit-bar screenshot-2.jpg
3. A Demo of the plugin in action (sidebar and static page) screenshot-3.jpg
