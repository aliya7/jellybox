=== jellybox ===
Contributors: jellyfilledstudios 
Donate link: http://www.jellyrobotics.com/
Tags: plugin,shortcode,animation,tilt,slide,drawer,text rotation,rotation,image rotation
Requires at least: 3.5.1
Tested up to: 3.5.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

jellybox provides a simple to use shortcode that allows you to display tilted, and/or animated text, images and boxes. Image, box and text rotation also works on older versions of Internet Explorer.




== Description ==

jellybox provides a simple to use shortcode that allows you to display tilted, and/or animated text, images and boxes. Image, box and text rotation also works on older versions of Internet Explorer.


= Example Usage =

[jellybox class="jellyboxGreen" width="200" height="140" angle="15"]
This text will appear in an attractive green gradient colored box tilted to a 15 degree angle.
[/jellybox]

[jellybox class="jellyboxBlue" width="200" height="140" deltaheight="100" deltatop="-100"]
This text will appear in an attractive blue gradient colored box. When you click on this box, it will grow by 100px.
[/jellybox]



= Documentation & Support =

Detailed examples and instructions for use can be found at http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/

You can find [documentation](http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/) and more detailed information about jellybox at [JellyRobotics.com](http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/). If you were unable to find the answer to your question on the examples page or in any of the documentation, please check the [support forum](http://wordpress.org/support/plugin/jellybox) on WordPress.org.




== Installation ==

1. Extract the content of the `jellybox.zip`
2. Upload the extracted content to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress




== Frequently Asked Questions ==

= Where can I find additional FAQs for jellybox? =

The 'live' site for documentation, FAQs and comments for jellybox is http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/


= Where can I find some examples?

Detailed examples can be found at http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/

= Some of my boxes appear have a line space above them

This is an issue with the wordpress wpautop() function and certain themes. The problem appears to be that after jellybox embeds javascript into the page, wpautop() is appending the javascript with a </p> tag. 

The workaround for this issue has been to insert something like this above the affected boxes:

<div class="pfix"></div>

Next, add a style class to your page or theme:

.pfix { margin-bottom: -40px; }

The actual margin correction will vary based on your theme and line heights



== Screenshots ==

1. Detailed examples can be found at http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/



== Changelog ==

Version 1.0.0 released
Version 1.1.0 updated to use WP constants for include paths
Version 1.2.0 updated the readme.txt file with more detailed description


== Upgrade Notice ==

Nothing to say here yet




