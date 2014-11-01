#Tag Page As Terms Of Use Name

Contributors: ludovicroland
Tags: terms of use
Requires at least: 4.0
Tested up to: 4.0
Stable tag: 0.1
License: GNU GPL v2.0
License URI: http://www.gnu.org/licenses/gpl-2.0.html

##Description

Adds a meta box to the Edit Page page where you can tag a page as a "terms of use" page.

##Installation

* Download the plugin and uncompress it
* Copy the entire directory in your plugin directory of your WordPress blog (/wp-content/plugins)
* Activate the plugin through the 'Plugins' menu in WordPress

Now you can:

* define a page as the "terms of use" page of your blog
* retrieve the page that has been tag with :

    $pages = get_pages(array('meta_key' => TERMS_OF_USE_META_KEY));

#Screenshots

![French](https://raw.github.com/ludovicroland/tagPageAsTermsOfUse-wordpress/screenshot-1.jpg))
![English](https://raw.github.com/ludovicroland/tagPageAsTermsOfUse-wordpress/screenshot-2.jpg))

== Changelog ==

= 0.1 =
* first version
