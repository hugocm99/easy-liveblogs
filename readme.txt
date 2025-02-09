=== Easy Liveblogs ===
Author URI: https://vanrossum.dev
Plugin URI: https://vanrossum.dev
Contributors: jeffreyvr
Tags: liveblog
Donate link: https://vanrossum.dev/donate
Requires at least: 4.4
Tested up to: 6.0
Stable Tag: 2.1.2
License: MIT

Live blogging made easy with the Easy Liveblogs plugin from vanrossum.dev.

== Description ==

Covering a conference, sports event, breaking news or other quickly developing events? You want your readers to be updated as quickly as possible. The best way to do that is by providing them with a liveblog.

= Built with developers in mind =

The plugin has tons of filter and action hooks so that developers can adjust the plugin to their liking. Feel free to contribute on [GitHub](https://github.com/jeffreyvr/easy-liveblogs).

== Installation ==

1. Install the plugin from your WordPress admin, or upload and install the plugin folder to your plugins directory (e.g. /wp-content/plugins/)
2. Activate the plugin
3. Go to Easy Liveblogs > Settings and configure the options

== Screenshots ==

1. Front-end liveblog example
2. Front-end liveblog example 2
3. Liveblog entry in admin
4. Post as liveblog in admin
5. Liveblog entries in admin
6. Posts filtered on liveblogs
7. Settings

== Changelog ==

= 2.1.2, June 22th, 2022 =
* Fix: check if liveblog needs to be init.

= 2.1.1, June 6th, 2022 =
* Added 'nofollow' to post edit link.

= 2.1.0, May 20th, 2022 =
* Added several properties to the structured data JSON-LD.

= 2.0.2, May 14th, 2022 =
* Fix: notice error when no default value is set for select setting.

= 2.0.1, May 14th, 2022 =
* Bump stable tag.

= 2.0.0, May 14th, 2022 =
* Complete rewrite of the liveblog rendering, now fully through JavaScript.
* A liveblog is rendered using an endpoint available through the WP Rest API.
* Set default value of '_elb_status' meta key on 'open'.
* Use elb_edit_entry_link instead of function edit_post_link.
* Added option to use object or transient caching.
* Added option to set a date(time)-format to be displayed with the liveblog entries.
* Added shortcode [elb_liveblog]. You can either pass the ID ([elb_liveblog id="1"]) or the endpoint-URL ([elb_liveblog endpoint="https://"]).
* Upgrade guide for developers: https://github.com/jeffreyvr/easy-liveblogs/wiki/Upgrade-from-v1-to-v2

= 1.7.1, April 14, 2022 =
* Fix not loading more entries when last item contains a list item.

= 1.7.0, March 22, 2022 =
* Only list open liveblogs in entry screen.
* Fixed issue where one liveblog item might be skipped when other item is on the exact same datetime.
* Show the liveblog to which an item is attached in the admin overview as a column.
* Add the direct link of liveblogs items inside the item meta box.
* Use a transient to cache the liveblog entries for meta data.

= 1.6.2, May 25, 2021 =
* Fixed issue where update polling was done on non liveblog pages. (Thanks for reporting @briandd)

= 1.6.1, May 14, 2021 =
* Update stable tag.

= 1.6, May 14, 2021 =
* Use GET requests instead of POST on liveblog refresh and load more actions.
* Increased the limit on the setting for liveblog entries being shown from 20 to 50.
* Now loads the same amount of entries on loading more as the initial amount.
* Updated readme.

= 1.5, November 9, 2020 =
* Fix not resetting postdata when no entries are listed yet.
* Fix warning notice on empty entries in schema.
* Add inline-block styling to social media icons to prevent some themes displaying the icons over multiple lines.
* Update Dutch translation.

= 1.4, October 2, 2020 =
* Added structured data.
* Added ability to link to specific entry with highlight effect.
* Update Dutch translation.
* Added option to show sharing options with entries.

= 1.3, September 2, 2020 =
* Adding the option to display author (Thanks inerds).

= 1.2, April 7, 2020 =
* Minor translation changes.
* Updated readme.
* Tested with WordPress 5.4.

= 1.1, May 21, 2019 =
* Using custom content and title function for liveblog entry to prevent unwanted applied filters.
* Completed dutch translation.

= 1.0, May 12, 2019 =
* The very first release of the Easy Liveblogs plugin.
