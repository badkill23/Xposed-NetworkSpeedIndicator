Network Speed Indicator
=======================

Displays traffic statistics on the notification bar. Requires a rooted phone with Xposed Module installed.

This is a continuous work from [Dzakus's great work](http://repo.xposed.info/module/pl.com.android.networkspeedindicator). Many thanks to the contributors and translators!

**Translators,** please see notes below.

To install, look for "NetworkSpeedIndicator" in your **Xposed Installer** app. You can also find the APK file in the [Xposed Repository](http://repo.xposed.info/module/tw.fatminmin.xposed.networkspeedindicator).

For support, please open a new issue in the **Issues** section. Or you could fork and fix the issue, then give us a pull request! `:)`

For discussions, visit the [XDA thread here](http://forum.xda-developers.com/xposed/modules/xposed-networkspeedindicator-v0-9-t2636971).

Features
--------
 * Shows upload and download speeds
 * Works for both Mobile and Wi-Fi networks
 * Highly customizable
  * Update interval and speed display
  * Positioning, display and suffix
  * Unit choice and formatting
  * Font styles, size and color

Translating
-----------
Thank you for helping us provide localization of the app. When contributing translations (fork, modify and send pull request) please keep the following in mind:
 * Translate the original `strings.xml` in your fork (original source code).
 * Do not translate `strings.xml` or `arrays.xml` extracted from the APK file.
 * Do not translate `values.xml` or `dimens.xml`.
 * Application name (`app_name`) should ideally remain in English, unless your locale specifically requires a translated name.
 * Do not translate or change the value of the "name" attribute.
 * Follow the capitalization and style of the default strings.
 * Only include strings that were translated. Non-translated strings must fall back to defaults in `/res/values/strings.xml`.
 * For string arrays, always include all items in the correct order (regardless of how many items were translated).
 * Place translations in the correct locale folder (for example `/res/values-de/strings.xml`).
 * Remove any obsolete strings that are not present in the default file.
