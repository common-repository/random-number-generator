=== Random Number Generator ===
Contributors: Whiler
Donate link: http://blogs.wittwer.fr/whiler/
Tags: random, numbers, generator, sample, howto
Requires at least: 2.7
Tested up to: 2.9
Stable tag: 1.3.2

Simply replace the tag [random-number] by a random number.

== Description ==

It can be used to avoid browsers cache by inserting a random number.
For instance, http://my_url?[random-number]" could generate http://my_url?134548.


[random-number from="2" to="72" format="%b"]%d minutes[/random-number]

output: an integer value between 2 & 72 followed by the word 'minutes'



**This plugin is a sample on how to create a plugin which:**
* supports internationalization,
* provides an option screen,
* saves some options,
* use images,
* replaces a tag.


By the way, **it generates randomized numbers** ;o)

If you need more functionalities, feel free to ask (email/blog)...

A post with a French tutorial is available [here](http://blogs.wittwer.fr/whiler/2009/11/23/exemple-complet-extension-wordpress/).

== Supported languages ==

* English
* French
* Russian (Thanks to [Vladimir / ShinePHP.com](http://www.shinephp.com/))

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload folders and files  to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `[random-number]` in a post (if you haven't changed the tag caption in the options)

== Frequently Asked Questions ==

Does it work with WordPress MU?

- Yes

Which languages are included when I install the plugin?

* English
* French
* Russian (Thanks to [Vladimir / ShinePHP.com](http://www.shinephp.com/))

== Screenshots ==

1. Options in English
1. Options in French
1. Options in Russian
1. Sample

== Changelog ==

= 1.3.2 =
* Submenu was displayed in Dashboard menu when not on RNG options page: fixed

= 1.3.1 =
* The previous page isn't anymore obsolete but it's still recommended to navigate to the new one (from the new submenu).

= 1.3.0 =
* Parent menu can be changed in options page. Warning, after saving, the previous page will be obsolete and you will have to navigate to the new one (from the new submenu).
* JavaScript method renamed to avoid potential issue

= 1.2.3 =
* Links added under the plugin description in the plugins management page
* Description translated

= 1.2.2 =
* More comments examples in the source code for translators / used with param --add-comments=Tr.: 
* Russian screenshot added

= 1.2.1 =
* Russian added in languages (Thanks to [Vladimir / ShinePHP.com](http://www.shinephp.com/))
* Submenu capability updated to 'manage_options' ; script called even if not admin ; visible in 'WordPress Admin Bar'

= 1.2.0 =
* A direct link to the editor is available in the options plugin page
* Images added in the options page (settings icon, a dice)
* format used in content can include others shortcode tags
* Shortcode tag can be customized

= 1.1.0 =
* Can generate till 5 numbers within the same format, ie: '%d-%d-%d%-d-%d'
* Output an error if format is invalid
* New screenshot available and [French sample](http://blogs.wittwer.fr/whiler/2009/11/24/exemple-random-number-generator/)

= 1.0.1 =
* Dynamic path extension really fixed

= 1.0.0 =
* Tag supports attributes ([from][to][format]) and a content for its format
* Dynamic path extension fixed
* UTF-8 Source files (instead of ISO)

= 0.0.1 =
* First release
