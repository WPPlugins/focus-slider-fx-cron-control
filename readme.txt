=== Focus SliderFx cron control ===
Contributors: tarnazar
Donate link: http://tarnazar.pp.ua/wp_plugins/
Tags: galery, xml, flashxml
Requires at least: 2.0.2
Tested up to: 3.2.1
Stable tag: 0.2.0.2

Plugin generates XML file for FlashXML plugins. This XML file containes pathes to latest loaded pictures on the site.

== Description ==

The Focus Slider FX cron control is plug-in for wordpress, which generates XML
file for FlashXML Focus Slider FX plug-in. This file containes pathes to
latest loaded pictures on the site.
Plugin inscribes database's adjustments to the script automatically.
You might change the path to the file from which Focus Slider FX takes
necessary adjustments.
The number of pictures displaying on the page is also variable.
Focus Slider FX plug-in doesn't came with this package. It should be installed
separately.

Please contact me if you need help or have any suggestions for improving the
script. wp_scripts@tarnazar.pp.ua

== Installation ==

1. Upload focus-slider-fx-cron-control to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. The Cron Job is writing manually as it is * * * * * cd /path/to/wp-plugin-dir/focus-slider-fx_cron_control; /path/to/php gen_flashxml.php 1>/dev/null 2/dev/null.
   You can specify the time to run the cron job as you wish

== Frequently Asked Questions ==
none

== Screenshots ==

no available

== Changelog ==
 = 0.2.0.2 =
 * Now you can use comments for your pictures

 = 0.2.0.1 = 
 * Plugin Renamed!
 * 1. Bug fixes;
 * 2. Added manualy update (without cron job) option
 * 3. Photo Flipper FX Plugin Tested - it works!

== Upgrade Notice ==

 = 0.2.0.2 =
 * Now you can use comments for your pictures

== Arbitrary section ==
 
  = In future versions: =
 * The ability to choose pictures, images manually
 * Add comments to photos from plugin page
 * Support for other products FlashXML


== A brief Markdown Example ==
none
