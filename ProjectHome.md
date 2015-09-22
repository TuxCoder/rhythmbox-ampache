# Ampache plugin for Rhythmbox #

This is a plugin for [Rhythmbox](http://projects.gnome.org/rhythmbox/) music player that allows it to stream directly from an instance of an [Ampache](http://www.ampache.org) music streaming server.

![![](http://sevatech.com/tmp/thumb-screenshot-2008.02.29-001.png)](http://sevatech.com/tmp/screenshot-2008.02.29-001.png)

## Ampache Configuration ##

Read Ampache [Access Control Lists](http://ampache.org/wiki/config:acl) documentation and create an ACL for RPC (XML API).

## Rhythmbox Configuration ##

Install the package (RPM for Fedora, DEB for Debian or Ubuntu) or untar and copy the ampache directory into either $HOME/.gnome2/rhythmbox/plugins or /usr/lib/rhythmbox/plugins

Run rhythmbox

Open Edit, select Plugins dialog box, enable "Ampache Library"

Click Configure, enter your infromation, for example URL `http://test.com/server/xml.server.php`

Click on Ampache under Shared, songs should appear in the browser

## Discuss ##

[Google Group](http://groups.google.com/group/rhythmbox-ampache)