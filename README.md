CocoonJS Plugin for Construct 2
==================
This plugin can be used in Construct 2 to manage the CocoonJS JavaScript APIs.

## Demo Example [capx]
This plugin comes with a .capx (a valid Construct 2 project) as a reference to know how to use it, you can download it from [here](capx/CocoonJS Plugin Demo.capx?raw=true).

Here are some screenshots of the .capx:

![Demo](http://support.ludei.com/hc/en-us/article_attachments/200643378/Screen_Shot_2014-04-14_at_12.58.54.png)
![Demo](http://support.ludei.com/hc/en-us/article_attachments/200697397/social_actions.png)
![Demo](http://support.ludei.com/hc/en-us/article_attachments/200694983/social_login_leaderboard.png)

## Configuration
The plugin can be configured by selecting the object "cocoonjsads" from the "Object types" list inside Construct 2.

![Configuration panel](http://support.ludei.com/hc/en-us/article_attachments/200687973/Screen_Shot_2014-04-14_at_13.10.28.png)
## Installation
### Manual Install
* *Close Construct 2*
* Checkout the 'master' branch from this repository
* Copy the file src/cocoonjs_prelude.js into *_CONSTRUCT_2_INSTALLATION_FOLDER_*\exporters\html5\, make sure to replace the file when you are asked.
* Copy the contensts of the folder /src/plugin/cocoonjsads into *_CONSTRUCT_2_INSTALLATION_FOLDER_*\exporters\html5\plugins\cocoonjsads.
* That's all!

### Automatic installation
This plugin already comes bundled with Construct 2, however the update rate of Construct 2 may differ from the latest version of this plugin, we encourage you to manually update the plugin everytime a new version of the plugin comes out.
## Need help?
Visit [our help center](https://support.ludei.com).
## Changelog

### April 16, 2014 
* Fixed bug that shows a banner when should not
* Updated readme.md
* Updated folder structure

### April 14, 2014 
* Added support for Google Play Games / Game Center leaderboards & Achievements
* Fixed bug that prevents the user to finish a in-app purchase.
* Updated documentation