=== ListSaver ===
Contributors: FunnelEnvy.Eddy
Tags: email, form, mailchimp, cro, follow up emails,
Requires at least: 3.8
Tested up to: 3.9.1
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

List Saver automatically captures email addresses from a Mailchimp form, and sends the subscriber a follow up "reminder" email.

== Description ==

Using Mailchimp to manage your subscriber list and campaigns? You could be
losing a lot of potential subscribers because they forget to complete the
double-opt in. List Saver helps you recover those 'lost' subscribers and
improves the conversion rates to your email list.

List Saver is a WordPress plugin that automatically captures email addresses
from a Mailchimp form, and sends the subscriber a follow up "reminder" email after a
certain (configurable) number of days if they haven't signed up. It uses the
Mailchimp API to check if they've signed up and only sends them an email if they
haven't.

Works with any Mailchimp custom form
1. Configurable interval (days) to check
2. Will only send the reminder if the email is not already on the list (no duplicate messages).
3. Completely editable reminder email text
4. Automatically adds the user to the list if they click on the link in the reminder email
5. View Pending and Actvated (saved) subsribers
6. Reminders run as a WordPress background process to minimize any performance
  impact

http://www.funnelenvy.com

== Installation ==

1. Upload the `list-saver` directory into your `wp-content/plugins` directory
2. Navigate to the *Plugins* dashboard page
3. Locate the menu item that reads *List Saver*
4. Click on *Activate*



== Changelog ==

= 0.1 =
* Released on Wordpress Repository