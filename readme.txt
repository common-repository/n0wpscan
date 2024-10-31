=== N0WPScan ===
Contributors: WartraxX (GeekParadize.Fr Team)
Tags: hackers, wpscan, scanning, firewall, security, geekparadize, N0WPScan
Requires at least: 5.2
Tested up to: 5.3 or higher
Requires PHP: 5.6 or higher
Stable tag: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Secure your Wordpress of WPScan
Prevent hackers using WPScan to find vulnerabilities in your site, disable this plugin when you are security testing or looking for vulnerabilities

== Description ==

We love security testing, we do it! We love WPSCAN, we use it! However we don't love people abusing WPSCAN and other automated methods to try and gain access to WordPress sites through known and often easy vulnerabilities. N0WPScan is not a silver bullet, but it will stop unskilled attackers, bots and automated attacks which account for over 90% of all WordPress breaches. The other 10% can be offset with a good firewall, IDS and NSM services. Server load will also be lower and sites faster as this tool will prevent a lot of WordPress related automated testing.

[!] You can prevent most of the common attacks simply by keeping plugins, themes and the core WordPress framework updated

Benefits
*   Disables access to admin for everyone except admins and editors
*   Disables the use of WPScan, a tool commonly used by hackers to attack WordPress, also blocks other automated WP scanners
*   Blocks hackers from scanning your website for admin users, vulnerable themes, vulnerable plugins and exposed files
*   Reduces the load on your server
*   Prevents access to sensitive files

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `N0WPScan.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= What is WPSCAN? =

WPScan is a WordPress vulnerability scanner.

= What is a vulnerability? =

In computer security, a vulnerability is a weakness which allows an attacker to reduce a system's information assurance. Vulnerability is the intersection of three elements: a system susceptibility or flaw, attacker access to the flaw, and attacker capability to exploit the flaw.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png`
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= 5.6 =
* Release date: January 15, 2020
* Fix bug minor
* Added more htaccess security headers
* Added more bots, scanners and payloads to block

= 5.3 =
* Fix bug minor

= 5.2 =
* Fix bug minor

= 5.1 =
* Fix bug minor

= 5.0 =
* Fix bug minor

= 4.0 =
* Added more htaccess security headers
* Added more bots, scanners and payloads to block

= 3.0 =
* Fix minor bug

= 2.0 =
* Fully tested and stable release

= 1.0 =
* First release

== Upgrade Notice ==

