SilverStripe 327
===================================

Helps you get up and running an existing SilverStripe 3.2 installation on PHP7.

It basically apply changes from this pull request to your current installation:

https://github.com/silverstripe/silverstripe-framework/pull/4551

Warning : use with caution!

How to use
-------------------
Run 327/migrate.php to update your installation. For security reason, this file should not be
accessible on a public website.

Why ?
-------------------
Because you don't want to wait for SilverStripe 4.0 to be out. Keep in mind that some modules
might not be compatible, so it's up to you..

Speed gains
-------------------
On my setup, to display a basic home page, I go from 400 ms to 250 ms, so it's almost twice as fast.
Your mileage may vary, this is not by any means something that is properly tested.

Maintainer Contacts
-------------------
LeKoala (<thomas@lekoala.be>)

Requirements
------------
* SilverStripe 3.1+

Documentation
-------------
[GitHub](https://github.com/lekoala/silverstripe-invoice/wiki)

Installation Instructions
-------------------------

1. Place the files in a directory called invoice in the root of your SilverStripe installation
2. Visit yoursite.com/dev/build to rebuild the database

Usage Overview
--------------

WIP

Known Issues
------------
[Issue Tracker](https://github.com/lekoala/silverstripe-invoice/issues)
