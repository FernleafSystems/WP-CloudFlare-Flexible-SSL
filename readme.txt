=== Plugin Name ===
Contributors: paultgoodchild
Donate link: http://icwp.io/q
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Tags: CloudFlare, SSL, Flexible SSL, Universal SSL, redirect loop, HTTPS, HTTP_X_FORWARDED_PROTO
Requires at least: 3.2.0
Tested up to: 4.5
Stable tag: 1.2.2

Fix For CloudFlare Flexible SSL Redirect Loop For WordPress.

== Description ==

[Click For Full Implementation Guide](http://icwp.io/6z).

Using CloudFlare® Flexible SSL on WordPress isn't as simple as just turning it on.

This plugin forms an **integral part** to enabling Flexible SSL on WordPress and prevents infinite redirect loops when loading WordPress sites under Cloudflare's Flexible SSL system.

*Cloudflare is a registered trademark of Cloudflare, Inc.*

One Dollar Plugin is not affiliated in any way with Cloudflare, Inc. This plugin provided separately and completely independently.

Remember: This plugin is just part of the installation process for Flexible SSL. [Please follow the full guide](http://icwp.io/6z)

== Frequently Asked Questions ==

= Does this plugin affect non-SSL traffic? =

No. It only comes into play when Cloudflare is serving HTTPS traffic from your site.

= Should I change my WordPress Site URL to HTTPS? =

No - there is no need.  Use Cloudflare's pages rules to redirect your visitors.  You can then safely turn off SSL whenever you want from within Cloudflare and your WordPress site will still load on HTTP.

= What happens if I disable this plugin AFTER enabling Flexible SSL on Cloudflare? =

Your WordPress site will not load on HTTPS/SSL. You will create an infinite loop loading problem and the only way to solve this is to turn off SSL redirects within Cloudflare.

= Does I need this plugin if I use Cloudflare FULL or Strict SSL? =

No. It is designed only to assist with Flexible SSL.

== Screenshots ==

n/a

== Installation ==

For full installation instructions, please review the following article: [Installation Instructions](http://www.icontrolwp.com/2014/10/enabling-cloudflares-universal-flexible-ssl-wordpress-without-infinite-redirect-loops/).

== Changelog ==

= 1.2.2 =

UPDATED:	Supported WordPress Version to v4.5

= 1.2.1 =

FIXED:		Checking to ensure certain data types

= 1.2.0 =

ADDED:		The plugin will try to set itself to load first, before all other plugins.

= 1.1.0 =

UPDATED:	Supported WordPress Version
UPDATED:	Also works for any standard SSL Proxy scenario that uses HTTP_X_FORWARDED_PROTO - it doesn't have to Cloudflare

= 1.0.0 =

First Release

== Upgrade Notice ==

= 1.0.0 =

First Release

