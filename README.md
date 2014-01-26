eminent
=======

About Awesome
-------------
If you found your way here you probably already know what Awesome-WM is. 
Should you not: http://awesome.naquadah.org/

About Eminent
-------------
Eminent patches some Awesome so that tags are hidden / shown 
depending on if they have clients associated with them or not.

More information on eminent can be found here:
http://awesome.naquadah.org/wiki/Eminent

About this fork
---------------
This fork slightly changes the behaviour of eminent:
- New tags are never created dynamically / hidden tags are never reused.
- The first tag (tagindex == 1) is never hidden. Even if it has no clients.

Is is still possible to access a hidden tag by explicitly navigating to it
(default: MODKEY+tagnumber). 

This behaviour is useful if you make heavy use of Awesome rules to
automatically associate common clients with certain tags. These tags will then
only be visible if and only if one of the associated clients are started.  All
non-associated clients will then open under the default tag that is always
visible.
