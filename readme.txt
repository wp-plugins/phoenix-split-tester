=== Phoenix Split Tester ===
Contributors: Joshua Ziering
Donate link: http://www.FullSpeedSEO.com
Tags: comments, spam
Requires at least: 2.9.0
Tested up to: 2.9.2
Stable tag: 1.0

Plugin let you split test pages and posts against each other with different sets of analytics.

== Description ==

This is the long description.  No limit, and you can use Markdown (as well as in the following sections).

For backwards compatibility, if this section is missing, the full length of the short description will be used, and
Markdown parsed.

A few notes about the sections above:

*   "Contributors" is a comma separated list of wp.org/wp-plugins.org usernames
*   "Tags" is a comma separated list of tags that apply to the plugin
*   "Requires at least" is the lowest version that the plugin will work on
*   "Tested up to" is the highest version that you've *successfully used to test the plugin*. Note that it might work on
higher versions... this is just the highest one you've verified.
*   Stable tag should indicate the Subversion "tag" of the latest stable version, or "trunk," if you use `/trunk/` for
stable.

    Note that the `readme.txt` of the stable tag is the one that is considered the defining one for the plugin, so
if the `/trunk/readme.txt` file says that the stable tag is `4.3`, then it is `/tags/4.3/readme.txt` that'll be used
for displaying information about the plugin.  In this situation, the only thing considered from the trunk `readme.txt`
is the stable tag pointer.  Thus, if you develop in trunk, you can update the trunk `readme.txt` to reflect changes in
your in-development version, without having that information incorrectly disclosed about the current stable version
that lacks those changes -- as long as the trunk's `readme.txt` points to the correct stable tag.

    If no stable tag is provided, it is assumed that trunk is stable, but you should specify "trunk" if that's where
you put the stable version, in order to eliminate any doubt.

== Installation ==

1) Unzip and upload to your plugins directory.
2) Activate Plugin
3) Make another Google Analytics Profile for your domain.
4) Plug in the UA numbers to the Wordpress Split Tester options screen under “Settings”
5) Add a meta field to your split test post. Call it “splittestpost” and put in the Post ID of the post you’d like to split test against. It doesn’t matter if it’s a draft. This way, you can have alternate non-published content.

So, from then on it will test both pages at 50%. You can see the results on your Google analytics pages. Your main analytics will continue to fire because it loads two sets of analytics on the split tested paged.

Now you can split test things like bounce rate, time on page, and complete goals. Woo!

Notes: You should disable other analytics plugins and remove any GA Code from your Footer.php file. The plugin will add your regular profile in on NON-Split tested pages.