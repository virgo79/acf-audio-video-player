# Advanced Custom Field: Audio/Video Player
Audio and Video Player for Advanced Custom Fields: select audio or video files from Media Library and display them using the wordpress builtin media player (or the native html5 player). 

# Description
This plugin let users select an audio or video file from the media library displaying it using the media player.
This plugin is based on the native ACF File Field, that, unfortunately, does not have the feature to show the selected media file using the media player.

# Installation
1. Copy the acf-audio-video-player folder into your wp-content/plugins folder
2. Activate the Advanced Custom Fields: Audio/Video Player Field plugin via the plugins admin page
3. Create a new field via ACF and select the Audio/Video Player type

# Migration from ACF Audio/Video Field (@ipsips)
This plugin is compatible with the old [ACF Audio/Video Field](https://github.com/ipsips/acf-audio-video) (that no longer works with the latests versions of ACF)
If you were using the ACF Audio/Video Field, and you are having issues using this field, you can simply replace it with this field.
To replace the old ACF Audio/Video Field with Acf Audio/Video Player simply:
- install the ACF Audio/Video Player
- go to any ACF Field Gruop Screen and change every field type from 'Audio/Video' to 'Audio/Video Player'

# Compatibility
This ACF Field has been tested with:
- ACF 5.7.0 PRO or later (but should work even with ACF5)
- Wordpress 4.9.8

