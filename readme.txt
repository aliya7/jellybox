=== jellybox ===
Contributors: jellyfilledstudios 
Donate link: http://www.jellyrobotics.com/
Tags: plugin,shortcode,animation,tilt,slide,drawer,text rotation,rotation,image rotation
Requires at least: 3.5.1
Tested up to: 3.5.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

jellybox provides a simple to use shortcode that allows you to apply rotations and/or animations to text, images and boxes.




== Description ==

jellybox provides a simple to use shortcode that allows you to apply rotations and/or animations to text, images and boxes. Image, box and text rotation also works on older versions of Internet Explorer.


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

= Installation via WordPress admin panel =

1. Navigate to the plugins section
2. Select Add New
3. In the search box enter jellybox
4. Install and activate the plugin jellybox
 

= Manual Installation =

1. Download the file `jellybox.zip` from WordPress.org
2. Extract the content of the `jellybox.zip`
3. Upload the extracted content to the `/wp-content/plugins/` directory
4. Activate the plugin through the 'Plugins' menu in WordPress




== Frequently Asked Questions ==

= Where can I find additional FAQs for jellybox? =

The 'live' site for documentation, FAQs and comments for jellybox is http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/


= Where can I find some examples? =

Detailed examples can be found at http://www.jellyrobotics.com/2013/02/09/jellybox-shortcode-wordpress-plugin/

= Some of my boxes have a line spaces above them =

This is an issue with the wordpress wpautop() function and certain themes. The workaround for this issue has been to insert a div tag above the affected jellybox with a bottom margin that will offset the P tag added by wpautop()



== Screenshots ==

1. In-line text at an angle using jellybox
2. Simple jellybox
3. nested jellybox with rotations
4. nested jellyboxes with animation


== Changelog ==

Version 1.0.0 released

Version 1.1.0 updated to use WP constants for include paths

Version 1.2.0 updated the readme.txt file with more detailed description

Version 1.3 added new option `inline="YES"` (default is "NO"). This new option allows the jellybox to be displayed as in-line text using SPAN tags rather than the default wrapper which is DIV tags.


== Upgrade Notice ==

Nothing to say here yet




