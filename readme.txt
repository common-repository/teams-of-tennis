=== Teams of Tennis ===
Contributors: vrriecke
Tags: tennis,btv,team,club,sport
Donate link:
Requires at least: 4.9
Tested up to: 4.9.4
Requires PHP: 5.6
Stable tag: 1.0.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

show all games of a tennis team or club from the BTV site inside an iframe, manage game availability of players

== Description ==

* your are playing tennis inside Bavarian?
* you want to display the games and players of your team from the BTV page?
* you want to find out which games comes next for your club?
* you want to see the availability of your team members for all your games?

**Then this plugin is the right one.**

* With a simple shortcode you can display your team inside your own homepage.
* Also with a shortcode you can find out, which games comes next for your club.
* And organizing your team availability is also possible with simple shortcode. This feature is only available for logged in users.

For further details see FAQ section.

== Changelog ==

= 1.0.2 =
*   initial version

== Frequently Asked Questions ==

**How can i use this plugin?**

**On settings page you can find 2 links to the BTV page**

*    Team Link: link to the embedded team page: *http://btv.liga.nu...&team=*. the team number will be added by the shortcode (see below)
*    Club Link: link to the embedded club page for searching games: *http://btv.liga.nu...&club=*. the club number will be added by the shortcode (see below)

Go to the site, where you want to display the team, club or availability, and a add shortcode.

**Team link**
*    shortcode: [vr_tennisteam team="**#number**" width="100%" height="500"]
*    width and height are optional (above values are default)
*    the #number comes from the BTV page of your team, see FAQ

**Club link**
*    shortcode: [vr_tennisclub club="**#number**" width="100%" height="500"]
*    width and height are optional (shown values are default)
*    the #number comes from the BTV page of your team, see FAQ

**Availability link**
*    shortcode: [vr_tennisavailable team="**#number**" width="100%" height="500"]
*    width and height are optional (shown values are default)
*    the #number comes from the BTV page of your team, see FAQ

**How to get the team number from BTV page?**

* search your club on BTV page and then select your team or
* search inside the teams page for your league and select your team

If your team page is visible, then you have to use the number behind *team=* in the browser adress lineand then the embedded part of this page (beginning with *Mannschaftsportrait*) will be displayed in front end.

**How to get the ckub number from BTV page?**

Search your club on BTV page and then select info about your club.
Use the number in brackets after your club name and then the embedded part of this page (beginning with *your club name*) will be displayed in the front end.

** How can i use the availability feature?**

You must be logged in as a user to use this feature.
**The following functions can be used**

*    add a user - write your username in the textbox and press button **Hinzuf&uuml;gen**
*    remove a user - press trash symbol on the right side of your user line
*    change availability - click on the symbol under a game in your user line to change state. Possible states: unknown -> yes -> no-> ifneeded -> unknown.

The list of games will be extracted from the Team link site by analyzing the html content and stored to the database.

== Screenshots ==

1. Back end settings 
2. Front end game availability of players [vr_tennisavailable]
3. Front end games of a team [vr_tennisteam]
4. Front end searching for club games [vr_tennisclub]

