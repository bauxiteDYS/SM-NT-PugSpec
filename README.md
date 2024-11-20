# SM-NT-PugSpec

SourceMod plugin for Neotokyo that allows semi-fair spectating for dead players in semi-comp games. It's still possible to *ghost* using this plugin but mainly when rotating the camera to look behind a teammate, vastly reduced usefulness for ghosting than free-camera, and much better than black-screen, although not suitable for tournament play.  

A modified version of Rain's nt_fadefix plugin, intended for a different purpose, experimental, may or may not work properly. Use nt_fadefix by Rain if you don't feel like experimenting.  
https://github.com/Rainyan/sourcemod-nt-fadefix  

## Compile requirements
* SourceMod 1.9 or newer.
* [Neotokyo include](https://github.com/softashell/sourcemod-nt-include) v1.0 or newer.

## Server requirements
#### If using nt_competitive plugin
* Recommended nt_competitive plugin version: 0.5.0 or newer
  * Older versions of the nt_competitive plugin use their own built-in (inferior) fade system, which may interfere with this plugin
* Not compatible with nt_fadefix plugin (use that one for serious competitive games, or just in general)

## Usage
Set the cvar value `mp_forcecamera 1` to enable this plugin. The [nt_competitive plugin](https://github.com/Rainyan/sourcemod-nt-competitive) sets the cvar `mp_forcecamera 1` automatically when going live, so you don't need to do anything if using these plugins in tandem.
