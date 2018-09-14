# Advanced Custom Field: Audio/Video Player
Audio and Video Player for Advanced Custom Fields: select audio or video files from Media Library and display them using the wordpress builtin media player (or the native html5 player). 

# Description
Inspired by the [ACF Audio/Video Field](https://github.com/ipsips/acf-audio-video) this field let users select an audio or video file from the media library and it will be displayed using the media player.
This plugin is based on the native ACF File Field, that, unfortunately, does not have the feature to show the selected media file using the media player.

![ACF Audio/Video Field](https://github.com/ipsips/acf-audio-video/blob/master/acf-audio-video-screencast.gif)

# Development and Test
This field is still in development.
Please, test it before using in any production website.
If you find any issues, or need some updates/enanchements please feel fre to [report them here](https://github.com/virgo79/acf-audio-video-player/issues). I'll do my best to keep up to date everything.

# Installation
1. Copy the acf-audio-video-player folder into your wp-content/plugins folder
2. Activate the Advanced Custom Fields: Audio/Video Player Field plugin via the plugins admin page
3. Create a new field via ACF and select the Audio/Video Player type

# Usage
- Select Shortcode as returned format to display the default mediaplayer (MediaElements)
- Select Player HTML as returned format to display a basic HTML5 player (`<video>` or `<audio>`)

# Migration from ACF Audio/Video Field (@ipsips)
This field is the evolution of the [ACF Audio/Video Field](https://github.com/ipsips/acf-audio-video) (that [no longer works](https://github.com/ipsips/acf-audio-video/issues) with the latests versions of ACF).
If you wish to migrate from ACF Audio/Video to ACF Audio/Video Player Field, you can simply replace it with this field.
To replace the ACF Audio/Video Field with ACF Audio/Video Player simply:
- install the ACF Audio/Video Player
- go to any ACF Field Group Screen and change every field type from 'Audio/Video' to 'Audio/Video Player'
- check that everything is working fine
- uninstall ACF Audio/Video Field

# Compatibility
This ACF Field has been tested with:
- ACF 5.7.0 PRO or later (but should work also with ACF 5.x)
- Wordpress 4.9.8

- Does not work with ACF4

