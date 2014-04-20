Location Lab
=============================

Week 7 lab - Locations.

This is an example application that uses the Android Location Service to get location data. It registers to receive location 
updates from the LocationManager.NETWORK_PROVIDER (aka cell/wifi). It then checks if the location gathered is "new" in the 
sense that it is 1000 meters from the most recently gethered location. Then, it adds the location to a list view, using an
AsyncTask to download and update the UI. It performs this location check every five minutes.
In this code, though, I don't think it actually
gets my location from my phpne. To test the functionality, you can use the menu to choose hard-coded mock
locations. When you choose a mock location, the functionality then works correctly. If you are still at the same location,
a Toast notification pops up.
