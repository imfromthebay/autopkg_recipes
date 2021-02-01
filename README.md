# Autopkg Recipes

## Caffeine
This recipe download the latest reslease of Caffeine from the Github repository it is now hosted on, [IntelliScape/caffeine](https://github.com/IntelliScape/caffeine). There is also a JSSImporter recipe for it, as well.

## OpenVPN Connect
This downloads the latest version of OpenVPN Connect, creates a pkg, and adds a version number using the PkgInfoReader custom proccessor built by [grahampugh](http://github.com/grahampugh), so you'll want to make sure you add his [autopkg repo](https://github.com/autopkg/grahampugh-recipes) for this recipe to work!

*there is allso a JSSImporter recipe too, but you will need to edit the smart group to remove the build number from the application version becuase I hvae not found away around haing it inserted (thanks OpenVPN...)*
