# What is Sysinfo? #
Sysinfo is a tool for Android(TM) developers who are going to build and deploy Android applications to run on various Android powered devices. Sysinfo can help developers by showing various system informations such as ‘product name’, ’sdk version’, ‘display resolution’, etc.

You can download the latest package(sysinfo.apk) on the 'Android Market' or on the download section at this website.

# News #
  * **30 May 2010 - Sysinfo 0.7 Released.**
  * 25 Mar 2010 - Sysinfo 0.6 Released.
  * 01 Feb 2010 - Sysinfo is now open source.
  * 01 Feb 2010 - Sysinfo 0.5 Released.
  * 28 Oct 2009 - Sysinfo 0.4 Released.
  * 29 Sep 2009 - Sysinfo 0.3 Released.
  * 20 Aug 2009 - Sysinfo 0.2 Released.
  * 18 Aug 2009 - Sysinfo 0.1 Released.

# Release Note #

## Sysinfo 0.7 ##
New Features:
  * Added information introduced with Froyo(API level 8).
  * Changed the minimum sdk version from '3' to '4' to support large screens.

Added Informations:
  * Build: values from...
    * `android.os.Build.CPU_ABI2`
    * `android.os.Build.HARDWARE`
    * `android.os.Build.RADIO`
    * `android.os.Build.BOOTLOADER`
  * Configuration: values from...
    * `android.content.res.Configuration.uiMode`
  * Display: values from...
    * `android.view.Display.getRotation()`
  * Environment: values from...
    * `android.os.Environment.getExternalStoragePublicDirectory`
  * System Settings: values from...
    * `android.provider.Settings.System.SCREEN_BRIGHTNESS_MODE`
    * `android.provider.Settings.System.VOLUME_BLUETOOTH_SCO`

## Sysinfo 0.6 ##
New Features:
  * NONE

Added Informations:
  * Device Configuration: values from '`android.content.res.Configuration`'

## Sysinfo 0.5 ##
New Features:
  * NONE

Added Informations:
  * All: all values listed in other categories.
  * Build: values from...
    * `android.os.Build.CPU_ABI`
    * `android.os.Build.MANUFACTURER`

## Sysinfo 0.4 ##
New Features:
  * NONE

Added Informations:
  * Activity: values from '`android.app.ActivityManager`'
  * Runtime: values from '`java.lang.Runtime`'

## Sysinfo 0.3 ##
New Features:
  * Options Menu
    * Save: Save the information as a file.
    * Send: Send the information via email or SMS.

Added Informations:
  * NONE

## Sysinfo 0.2 ##
New Features:
  * Options Menu
    * Refresh: Refreshes the values in the current list view.
    * About: Shows 'About' page.

Added Informations:
  * Telephony: values from '`android.telephony.TelephonyManager`'

## Sysinfo 0.1 ##
Initial Release.

Features:
  * Informations: Shows various system informations which can be read through the standard Android API.
  * Description Dialog: Shows description of an information item when the item is selected.
  * Android API Guide: The links in the description dialog will guide you to the Android API reference page whose URL has the form of '`http://developer.android.com/reference/package/name/ClassName.html#memberName`'.

Available Informations:
  * Build: values from '`android.os.Build`'
  * Environment: values from '`android.os.Environment`'
  * System Settings: values from '`android.provider.Settings`'
  * Display: values from '`android.view.Display`'

# Screenshots #
| Information List | Build Information | Display Information | Description Dialog |
|:-----------------|:------------------|:--------------------|:-------------------|
| ![http://sysinfo-for-android.googlecode.com/files/sysinfo-list.png](http://sysinfo-for-android.googlecode.com/files/sysinfo-list.png) | ![http://sysinfo-for-android.googlecode.com/files/sysinfo-info-build.png](http://sysinfo-for-android.googlecode.com/files/sysinfo-info-build.png) | ![http://sysinfo-for-android.googlecode.com/files/sysinfo-info-display.png](http://sysinfo-for-android.googlecode.com/files/sysinfo-info-display.png) | ![http://sysinfo-for-android.googlecode.com/files/sysinfo-desc-scaleddensity.png](http://sysinfo-for-android.googlecode.com/files/sysinfo-desc-scaleddensity.png) |