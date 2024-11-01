=== WP-PageNavi-LightWord ===
Contributors: Agus Suhanto
Donate link: http://suhanto.net/wp-pagenavi-lightword/
Tags: navigation, pagination, paging, pages
Requires at least: 2.8
Tested up to: 3.0
Stable tag: 1.0

Adaptation of [WP-PageNavi](http://wordpress.org/extend/plugins/wp-pagenavi/) for [LightWord WordPress theme](http://www.lightword-theme.com/). Adds a more advanced paging navigation to your WordPress site.

== Description ==

Adaptation of [WP-PageNavi](http://wordpress.org/extend/plugins/wp-pagenavi/) for [LightWord WordPress theme](http://www.lightword-theme.com/). Adds a more advanced paging navigation to your WordPress site.

Example:

	Pages (17): [1] 2 3 4 » ... Last »


<br>
[Demo](http://lesterchan.net/wordpress/) | [Translations](http://dev.wp-plugins.org/browser/wp-pagenavi/trunk/lang/)

== Installation ==

You can either install it automatically from the WordPress admin, or do it manually:

1. Unzip the archive and put the `wp-pagenavi` folder into your plugins folder (/wp-content/plugins/).
1. Activate the plugin from the Plugins menu.

= Usage =

1. Open `wp-content/themes/your-theme-name/footer.php`
2. Add anywhere: `<?php wp_pagenavi(); ?>`
3. Go to *WP-Admin -> Settings -> PageNavi* to configure WP-PageNavi.

= Changing the CSS =

If you need to configure the CSS style of WP-PageNavi, you can copy the `pagenavi-css.css` file from the plugin directory to your theme's directory and make your modifications there. This way, you won't lose your changes when you update the plugin.

Alternatively, you can uncheck the "Use pagenavi.css?" option from the settings page and add the styles to your theme's style.css file directly.


== Screenshots ==

1. Default appearance
2. Options page

== Frequently Asked Questions ==
Please visit [WP-PageNavi-LightWord' Comments](http://suhanto.net/wp-pagenavi-lightword//#comments) for questions and answers.

== Changelog ==

= 1.0 (2010-04-19) =
* first published version, based on WP-PageNavi 2.72