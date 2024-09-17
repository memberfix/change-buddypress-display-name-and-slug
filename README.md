#  Plugin Name 
Contributors: MemberFix
Donate link: https://memberfix.rocks/
Tags: BuddyPress, display name, slug
Requires at least: 3.0.1
Tested up to: 5.2.1
Stable tag: 5.2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


## Important Notice:

This plugin is provided "as is" and is not officially supported. While we strive to ensure its functionality and compatibility, we make no guarantees regarding its performance or reliability. Users are encouraged to test the plugin thoroughly before using it in a production environment.

By using this plugin, you acknowledge that:

The plugin may have bugs, issues, or limitations that could affect its performance.
We are not responsible for any damage or loss that may result from using this plugin.
We do not offer any formal support or updates for this plugin.
Any use of this plugin is at your own risk.
Thank you for understanding.

## Description 

This plugin will allow you to change the display name and slug (http://yoursite.com/author/the-slug) for a certain user.
It also changes the BuddyPress display name and all existing mentions in discussions and activity.

Shortly, this plugin will do the following:

- Update nicename/slug and display name for WordPress user
- Update user's BuddyPress display name
- Update user's existing mentions in BuddyPress discussions and BuddyPress activity

The WordPress database tables where the above user details are replaced are:

- wp_users
- wp_bp_activity
- wp_bp_messages_messages
- wp_bp_messages_meta
- wp_usermeta
- wp_bp_xprofile_data
- wp_bp_activity
- wp_posts


== Installation ==

1. Download the zipped file.
2. Extract and upload the contents of the folder to /wp-contents/plugins/ folder.
3. Go to the Plugin management page of WordPress admin section and enable the 'Change BuddyPress User Display Name and Slug' plugin.


After the plugin is installed and before you use it, please perform a database backup.

After the backup is done go to Plugin Settings page (Users > Change BuddyPress User Display Name and Slug), add the username of the user and the new Display Name and click "Submit".
