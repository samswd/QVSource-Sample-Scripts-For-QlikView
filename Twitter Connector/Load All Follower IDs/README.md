Change Log
==========
This example QlikView load script illustrates how to use the FollowerIds and Post_FollowerIds_Info tables of the Twitter Connector to build up a collection of all the followers or a particular account over a number of reloads.

This is necessary because the Twitter API only allows enough API calls to retrieve 15x5000=75,000 follower IDs per 15 minute window.

This script uses a new feature in QVSource which is under development and explained in more detail here:
http://wiki.qvsource.com/Getting-Follow-Up-Information-Based-On-A-Previous-Tables-Response.ashx

1.0.1 - 04/12/13
----------------
* Added badge.

1.0.0 - 04/09/13
----------------
* Initial version.