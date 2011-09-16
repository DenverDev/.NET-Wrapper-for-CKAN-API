﻿See https://github.com/opencolorado/.NET-Wrapper-for-CKAN-API for additional information.

## Version 1.0 (9/5/2011)
* Implemented cache admin page for viewing the cache and clearing items from the cache on demand
* Added improved error handling for failed CKAN requests including a configurable timeout
* Added support for taking the catalog offline with a custom offline message.
* Added detailed documentation for all parameters in web.config and reorganized the settings
* Miscellaneous code improvements and bug fixes

## Version 0.4 (8/8/2011)
* Added tag route for tidy tag URL (ex. /tag/<tag>)
* Implemented background caching support for main page items that are costly to update.
* Added support for CKAN markdown formatting in package descriptions
* Implemented dynamic handling of CKAN package 'extra' properties including configurable labels
* Documented project dependencies/third party libraries
* Package resources section is not displayed if there are no resources

## Version 0.3 (7/31/2011)
* Added RSS feed for package revisions
* Implemented configurable resource actions including multiple actions for some resources.
* Implemented caching pattern for CKAN API wrapper that allows all request types to be cached for performance.
* Fixed IE7 & IE8 CSS issues.
* General user interface improvements to the default theme.
* Bug fixes.

## Version 0.2 (7/24/2011)
* Handles inconsistent date formats in CKAN repositories.
* Completed full unit testing of CKAN API.
* Moved all parameters to config file.
* Added initial caching for CKAN requests.
* Added logging (log4net)

## Version 0.1 (7/17/2011)
* Initial published prototype.