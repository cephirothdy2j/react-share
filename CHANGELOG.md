## 1.9.1 (Aug 28, 2016)

* New end point for fetching Facebook share count.

## 1.9.0 (Aug 11, 2016)

* Added `windowWidth` and `windowHeight` props to share buttons to control opened window dimensions

## 1.8.2 (July 8, 2016)

* Added `title` and `description` props for FacebookShareButton. `title` was not working correctly previously.

## 1.8.1 (July 3, 2016)

* Fixed propType warnings that were caused by updating to React v. 15.2.0

## 1.8.0 (June 17, 2016)

* Share count will now be updated if url prop is changed
* Error callback with Facebook share counts is now correctly called

## 1.7.0 (May 28, 2016)

* added disabled and disabledStyle props to share buttons
* added iconBgStyle and logoFillColor to icon styles

## 1.6.1 (May 15, 2016)

* Inline style `display: 'inline-block'` is no longer added to icons. If you are upgrading from an older version, be sure to add the style yourself if needed.

## 1.6.0 (May 7, 2016)

* feature: added sharing support for VK
* internal changes for preparing version 2, assertion message changes
* minor breaking change: Google Plus button now has class `SocialMediaShareButton--googlePlus` instead of `SocialMediaShareButton--google-plus`

## 1.5.0 (Apr 12, 2016)

* Updated to support React v. 15.x.x

## 1.4.1 (Jan 11, 2016)

* Bugfix: className-prop was not propagating correctly in share-buttons.

## 1.4.0 (Nov 23, 2015)

* Removed Bluebird from dependencies: no need for Promises. The library has a much smaller footprint now.

## 1.3.0 (Nov 23, 2015)

* TwitterShareCount removed: Since 20th of November Twitter no longer supports open count API. The service was shut down and there is currently no way to fetch the share count. Thus, TwitterShareCount was removed in version 1.3.0.

## 1.1.0 (Nov 3, 2015)

### Changes

* use jsonp instead of fetch API when fetching Facebook share count
* use XHR instead of fetch API when fetching Google Plus share count
* fixed problem with window.open on <=IE9
