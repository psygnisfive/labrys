# Labrys Apps

A Labrys app is a program that runs inside Labrys and makes use of its identity management
in order to control access.

One of the main use cases for this is social media. A Labrys app might replace Twitter, for
instance, giving the blade owner total control of their Twitter-like experience. In such a
context, there would be a number of interesting things to consider. For instance, lots of
things on Twitter are globally shared and notified. For instance, when someone interacts
with your tweets in some way, or mentions you in some way, you get notified for all of these
things. In the context of Labrys, however, notification isn't possible in the usual sense.
A Twitter alternative could, of course, send messages to another instance of it running on
your blade, which would tell you about the actions others have taken, which might be seen
as a push based approach to information propagation, or your blade could pull the information
from the other blade. The pull approach requires that you know who to pull from, while the
former does not, but the former approach makes it feasible for someone to bombard your blade
with extraneous notifications. Care has to be taken in how to design this kind of thing, but
with Labrys, there is at least the possibility of making design decisions about them in the
first place.

Another consideration is the means by which access control is performed. Does the app as a
whole get put into the access control system, do its endpoints, its logical resources
(e.g. the tweets, etc.), or some or all of these?? 