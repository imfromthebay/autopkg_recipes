# Autopkg Recipes

## Caffeine
This recipe download the latest reslease of Caffeine from the Github repository it is now hosted on, [IntelliScape/caffeine](https://github.com/IntelliScape/caffeine). There is also a JSSImporter recipe for it, as well.

## Intel Power Gadget (in progress, not yet working)
This recipe download the latest reslease of the Intel Power Gadget. 

## OpenVPN Connect
This downloads the latest version of OpenVPN Connect, creates a pkg, and adds a version number using the PkgInfoReader custom proccessor built by [grahampugh](http://github.com/grahampugh), so you'll want to make sure you add his [autopkg repo](https://github.com/autopkg/grahampugh-recipes) for this recipe to work!

*there is also a JSSImporter recipe too, but you will need to edit the smart group to remove the build number from the application version. I have not not found away around having it captured (thanks OpenVPN...)*
