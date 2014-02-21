**NOTE - You will need QVSource 1.5.0.0 or later to use this sample.**

This example QlikView load script illustrates how to use the FollowerIds and Post_FollowerIds_Info tables of the Twitter Connector (and Friend equivalents) in conjunction with the UserLookupById table to build up a collection of all the followers and friends of a particular account over a number of reloads (if required).

This is necessary because the Twitter API only allows enough API calls to retrieve 15x5000=75,000 follower IDs per 15 minute window.

This script uses a new feature in QVSource which is under development and explained in more detail here:
http://wiki.qvsource.com/Getting-Follow-Up-Information-Based-On-A-Previous-Tables-Response.ashx

Further work would be needed to allow this to capture new followers/friends. Perhaps a stamp could be used and all followers/friends could be completely re-captured every X days.

Change Log
==========

1.0.2 - 21/02/14
----------------
* Now only loads distinct ids.
* Reviewed and tested against QVSource 1.4.9.6 (requires this version or later).
* Now includes following (friends) functionality also.
* Now includes User lookup.

1.0.1 - 04/12/13
----------------
* Added badge.

1.0.0 - 04/09/13
----------------
* Initial version.