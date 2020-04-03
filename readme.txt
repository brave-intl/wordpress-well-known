=== brave-payments-verification ===
Contributors: pfefferle, mrose17
Tags: well-known, well-known-uris, discovery, brave
Requires at least: 3.5.1
Tested up to: 5.3.2
Stable tag: 1.0.4
License: MPL2
    
"Well-Known URIs" for WordPress!

== Description ==

This plugin creates the /.well-known/brave-payments-verification.txt file.

You will need 'manage_options' capability in order to use the Settings page for this plugin.

NOTE: as with all plugins, once you are no longer using the plugin, you should de-activate it.
This is a good security practice.
    
== Changelog ==

= 1.0.4 =

* Optimized for Brave Publisher Verification
    
== Installation ==

1. Upload this plugin to the `/wp-content/plugins/` directory.
2. Activate the plugin through the *Plugins* menu in WordPress.
3. Go to *Settings > Brave Payments Verification*, enter the verification code you received, and click on `Save Changes`.
4. Once you have received an e-mail that your site has been verified, deactivate this plugin.
    

== Frequently Asked Questions ==

= It doesn't work =

Please check that your .htaccess file is configured correctly (it should contain "RewriteEngine On").
On a fresh Wordpress install, you can generate the .htaccess file by going to Settings -> Permalinks,
choosing a permalink format and clicking Save Changes.

You can also debug rewrite rules with with https://wordpress.org/plugins/rewrite-rules-inspector/
