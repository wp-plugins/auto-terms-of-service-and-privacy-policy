=== Auto Terms of Service and Privacy Policy ===
Contributors: cliffpaulick
Tags: legal, policy, privacy, t&c, terms and conditions
Requires at least: 3.0
Tested up to: 3.9
Stable tag: /trunk/
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Put your own details into a modified version of Automattic's "Terms of Service" and "Privacy Policy". 3 shortcodes available.

== Description ==

Puts your own information into a version of Automattic's <a href="http://en.wordpress.com/tos/">Terms of Service</a> and <a href="http://automattic.com/privacy/">Privacy Policy</a>, both available under the <a href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Sharealike</a> license, that have been modified to exclude specifics to Automattic (like mentions of "JetPack", "WordPress.com", and "VIP") and have more generic language that can apply to most any site or service provider, including single sites, subscription sites, blog networks, and others.

<strong>Enter your organization's information in the plugin's settings page. Then you can add your own page and use one of the 3 available shortcodes: [my_terms_of_service_and_privacy_policy], [my_terms_of_service], and/or [my_privacy_policy]

A video demo:
[youtube http://www.youtube.com/watch?v=58rwQ_yDMfs]

Disclaimer: <a href="http://tourkick.com/">Clifford Paulick of TourKick.com</a> is not an attorney. Additional disclaimer text within the plugin file(s).

== Installation ==

After automatically installing to wp-content/plugins/ or manually installing to wp-content/mu-plugins/ (Must Use, i.e. Always Active), enter your organization's information in the plugin's settings page.
== Frequently Asked Questions ==

Why?

Because Terms and Conditions and Privacy Policies are important to have and because some businesses don't understand their importance or are unable or unwilling to afford an attorney to draft custom T&C and Privacy Policy documents. This plugin allows you to create your own, based on Automattic's. Thanks to Automattic for telling us we can use and abuse theirs.

How?

Edit the plugin's actual file, starting at Line 40, following the steps listed there.

MultiSite?

Kinda... It Network Activates but doesn't show up under each site's list of intalled/available plugins. However, if they use the shortcode(s), the output will work.

How can I give back?

Please rate the plugin, Tweet about it (mentioning @TourKick would be appreciated), contribute code enhancements, etc. I do not want monetary compensation for this particular project, but thank you for the thought.

How do I add a "to the top" link?

<a href="http://wordpress.org/extend/plugins/dynamic-to-top/" target="_blank">Dynamic "To Top" Plugin</a> is a good one that works site-wide, not just for this plugin. It might be a solution for you.
== Screenshots ==
1. Administrator-only view of shortcode output before plugin has been customized or if On/Off setting is Off

2. View of editing the plugin's settings

3. Page/Post Editor screen, using this plugin's shortcode: [my_terms_of_service]

4. Output of [my_terms_of_service] after customizing this plugin

5. Page/Post Editor screen, using this plugin's shortcode: [my_privacy_policy]

6. Output of [my_privacy_policy] after customizing this plugin

7. Page/Post Editor screen, using this plugin's shortcode: [my_terms_of_service_and_privacy_policy]

8. Output of [my_terms_of_service_and_privacy_policy]. Creates in-page links for quick access.

9. Scroll or Click to Privacy Policy when using [my_terms_of_service_and_privacy_policy] shortcode, further down the same page as the previous screenshot. Separated by horizontal line with class of "auto-tos-pp".
== Changelog ==
* WARNING: All direct plugin file edits (required in versions prior to v1.4) will be lost and will need to be entered via the plugin's settings page. Make sure you backup your information BEFORE UPDATING to a new version.
* Changelog DIFFs for all versions are available at <a href="http://plugins.trac.wordpress.org/browser/auto-terms-of-service-and-privacy-policy/trunk" target="_blank">WordPress SVN</a>.
= Version 1.4.3 =
* April 28, 2014
* Fix for "Possessive Name" not displaying accurately in settings page due to apostrophe. However, the value with the apostrophe was saved properly, and the Possessive Name was displayed properly for users on the front-end.
* Added direct link to Settings page from Plugins page
= Version 1.4.2 =
* February 13, 2014
* Added class='auto-tos-pp' (and additional classes) to main headings, horizontal lines, and Back to Top links -- could use .auto-tos-pp { display:none; } to not show things
= Version 1.4.1 =
* February 13, 2014
* Updated plugin's description
* Hyperlinked to plugin's settings page for shortcode output (when appropriate)
= Version 1.4 =
* February 12, 2014
* Added plugin settings page so you don't have to edit the plugin's actual code.
* Added link back to the table of contents (to the top) for the [my_terms_of_service_and_privacy_policy] shortcode.
* Privacy Policy edited in line with Automattic's --> September 18, 2013: Added that blog commenter email addresses are disclosed to administrators of the blog where the comment was left.
= Version: 1.3.2012.12.29 =
* Fixed 2 more hard-coded references to "WordPress" within that same paragraph. That should be all of them now.
= Version: 1.2.2012.12.29 =
* Fixed a <a href="http://wordpress.org/support/topic/update-required?replies=1#post-3439913" target="_blank">hard-coded reference to "WordPress"</a>, reported by kc22033. Thanks!
* Checked WordPress' Terms of Service and Privacy Policy for updates, and there weren't any changes since this plugin's creation.
= Version: 1.1.2012.12.28 =
* Changed shortcodes to return instead of echo, to fix the shortcode display issue. Thanks to <a href="http://profiles.wordpress.org/birgire" target="_blank">birgire</a>.
* Fixed link anchor text to use the name specified in the settings, to fix the issue of displaying hard coded "Terms of Use" and "Privacy Policy" anchor text in the table of contents for the [my_terms_of_service_and_privacy_policy] shortcode.
= Version: 1.0.2012.09.12 =
* Initial release.