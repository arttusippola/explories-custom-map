=== Explories Custom Map ===
Contributors: anttiluokkanen, Hape Haavikko
Plugin Name: Explories Custom Map
Plugin URI: https://www.matkailukartta.fi
Tags: location, travel, explore, map, routes, nature
Requires at least: 5.0
Tested up to: 5.4.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: 1.1.1
Version: 1.1.1

Display markers and routes on Google Map.

== Description ==

Explories Custom Map is a geolocation-based map and feed functionality for i.e. outdoor and travel use.

A Google Maps API key is needed with the following libraries: `places,drawing`.

Request an unique theme and a theme key from info@locationews.com to use all functionalities.

More info at [Matkailukartta.fi](https://matkailukartta.fi).

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/explories-custom-map` directory or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the Explories Custom Map screen to configure the plugin.
  1. Select post types.
  2. Set Google Maps API key.
  3. Set default location (lat.itude,lon.gitude).
  4. Set default map zoom.
  5. Select default mode.
  6. Select theme or set custom theme key.
  7. Set different route colors.
  8. Set map div offset from top of the page.
  9. Set the page slug where the map shortcode is embedded.
4. Flush permalinks.

== Frequently Asked Questions ==

= How to embed the map? =

Use the shortcode ```[ecm-map]```.

= How to embed the map with feed enabled? =

Use the shortcode ```[ecm-map feed="1"]```.

== Changelog ==

= 1.1.1 (2020-05-21) =
* Include `explories-custom-map` application.

= 1.1.0 (2020-03-03) =
* CHANGED:  Check registered Google Maps script in template_redirect hook instead of in shortcode.

= 1.0.0 (2019-08-14) =
NEW:    Release the plugin for public use.

