=== Toolset Types Embedded ===
Contributors: brucepearson, AmirHelzer, jadpm, jozik, mihaimihai, jans-1, christianglingener, iworks
Donate link: http://wp-types.com
Tags: CMS, custom field, custom fields, custom post type, custom post types, field, fields post, post type, post types, taxonomies, taxonomy, toolset
License: GPLv2
Requires at least: 3.7
Tested up to: 4.4.1
Stable tag: 1.9

The Embedded version lets you create custom types, taxonomies and fields for your theme or plugin, without requiring any plugin.

= Instructions =

1. Create the directory called 'embedded-types' in the root folder of your theme or plugin.

2. Copy the entire content of this directory (embedded) to the 'embedded-types' that you just created.

3. Include them from the theme’s functions.php file by adding these statements at the very beginning (right after the php statement):

require_once dirname(__FILE__) . '/embedded-types/types.php';

4. Export your configuration from your development site. Go to the Types->Import/Export menu and click on the 'Export' button. You will receive a ZIP file with the XML and PHP configuration files (both are required).

Unzip that file and place both settings.xml and the setting.php into the embedded-types directory.


You're done!
