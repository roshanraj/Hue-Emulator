Hue-Emulator Changelog
============
v0.5 (02-September-2015)

New Features:
---
* Removed possibility to create Custom WhiteList Entries + Added Randomly Generated Username.   This change was done because in December 2015/January 2016 the Philips Bridge will no longer accept Custom Whitelist Entries,  so I want developers to get into the habit of using the Randomly Generated Username.

New Features:
---
* Can now load and save different bridge JSON configs (e.g. for testing with different number of bulbs).
* Removed out-dated help web pages.  API docs should be viewed on: http://www.developers.meethue.com/philips-hue-api

v0.3 (23-January-2015)

New Features:
---
* Retrieving the lights now retrieves the full lights resource as per 1.3 bridges.

Bug Fixes:
---
* Retrieving lights resource doesn't retrieve a LightIdentifer: null and TransitionTime: null anymore, these have been removed.

v0.2 (01-December-2014)

New Features:
---
* UPNP Server. 1st attempt.  If you run the Emulator on Port 80 (if not blocked) some hue apps now work out of the box :-)
* Added Create User + Pushlink functionality (you must click the bridge icon to simulate pushlinking)
* Started Scenes implementation.  Get Scenes and Create Scenes functionality added + recall scenes.  Not 100% tested.
* Can now configure which JSON Strings to show in console (i.e. Requests, Responses, Full Config).
* Re-ordered some of the JSON to be more consistent with a hue bridge

Bug Fixes:
---
* Software version is now a string (not an integer).
* Clear console should now work.
* Added transition time (attribute only, not bulb transitions).