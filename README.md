⚡ ⚡ ⚡ **ATTENTION:** THIS PLUGIN IS NOT MAINTAINED BY AIRCONSOLE. This is based off of the AirConsole version, with my own additions.


# AirConsole Construct2
Construct2 plugin second generation for AirConsole version 1.7.0

AirConsole can be visited on www.airconsole.com and is a great way for unique game experience using your smartphones as controllers
Construct 2 is a great 2D game creation tool that allows anybody, with or without coding experiences, to start developping their own games

This plugin allows you to build both games and the controllers with Construct2! Don't forget to check out the external merging tool when you need to package your game before testing: https://github.com/Psychokiller1888/AirConsoleMerger/releases

## Basic Info
More information about the plugin:

http://developers.airconsole.com/#/guides/construct2

## Version 1.7.0.21
* Removed c2addon file, please use the plugin files and put them into the C2 Exporters/Plugins folder
* Fixed offline GetUID to return a string, preventing a type conversion error

## Version 1.7.0.20 (WIP)
* Added basic Translation functionality
* Enter com.airconsole.plugin.unity to use test message keys such as left, right, and center.
* Handles basic translation by key, such as welcome_message. Does not do string replacements.
* Must have translations in the Developer Console 
* If translation missing, undefined string returned (make sure you are not translating the word undefined) 
* More info available here: https://developers.airconsole.com/#!/guides/translations


## Version 1.7.0.19
* On device motion should be a trigger
* Edit profile impossible from screen
* Using isController
* Setting controller orientation
* Ordering

## Version 1.7.0.18
* Fixing all messenging functions for controller mode

## Version 1.7.0.17
* Fixed controller orientation

## Version 1.7.0.16
* Added OnDeviceMotion trigger
* Added GetPremium action
* Added Vibrate action
* Added MotionData expression

## Version 1.7.0.15
* Added ability to get device ID that is currently being used (Controller function)
* Added Edit Profile


## Version 1.7.0.14
* Added controller mode support
* Brought API mock-up from C3 to C2 plugin

## Version 1.7.0.13
* Added preset message support, on an idea by Toby R

## Version 1.7.0.12
* Fixed wrong usage of "deprecated", thanks Mad_Spy and Toby R for bringing this up

## Version 1.7.0.11
* Added expression airconsole.AdShown()
* Added expression airconsole.IsAdShowing()
* Added expression airconsole.GetProfilePictureWithSize(deviceId, picturesize)
* Deprecated expression airconsole.GetProfilePicture()
* Added condition AdShown()
* Added condition IsAdShowing()
* Fixed N-Dream naming in plugin infos....

## Version 1.7.0.10
* Fixed OnCustomDeviceStateChange trigger
* Fixed ConvertDeviceIdToPlayerNumber expression
* Comparison fix
* Cleanup

## Version 1.7.0.9
* Fixed GetPersistentData and GetHighscores expressions wrong return type

## Version 1.7.0.8
* Fixed onDeviceProfileChange (trigger not defined)

## Version 1.7.0.7
* Fixed GetMasterControllerDeviceId

## Version 1.7.0.6
* Fixed illogic expressions order and naming

## Version 1.7.0.5
* Updated documentation links and website links

## Version 1.7.0.4
* Fixed Message and Broadcast

## Version 1.7.0.3
* Missing GetActivePlayerDeviceIds

## Version 1.7.0.2
* Missing IsPluginOffline condition
* Missing IsPluginOffline expression
* Missing IsMultipartMessage condition

## Version 1.7.0.1
* Initial plugin release

## Translation Tips
To try translations (this assumes you have some AirConsole knowledge):
1. Open Pong Example
2. Export as HTML5
3. Upload/Run in local server in combination with AirConsole Simulator
4. When asked, enter com.airconsole.plugin.unity as your game id. Later, you will want to modify this with your game id.
5. See how the screen says something along the lines of, "center was translated to..."
6. See the Translation event sheet to modify with your own usages.

## About this Plugin
This plugin was created and is maintained by Psychokiller1888 and not by the AirConsole Team. It has become so popular that the AirConsole Team has decided to host it in the official AirConsole GitHub account.
