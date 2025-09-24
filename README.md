# This is my build for the wireless split keyboard Corne v4.0 including the files I use for remaps in my OS

## Considerations
- I run this on Debian 13 with dwm;
- I already have key remaps and tap/hold configurations using setxkbmap, xcape and sxhkdrc. So vial is only used to define where each key goes in each layer and the keys to travel between the layers;
- My workflow is heavilly keyboard based, so this is optimized for not needing a mouse;
- For navigating the web I use Librewolf with the Vimium plugin;


## Goals
- VIM like navigation;
- Keys should have analog functionalities to itself across the layers;
- Try to keep everything I need in 2 key presses max;
- Try to make it so I don't have to press 2 keys with the same hand;


## Non-Goals
- I don't need a thousand media keys, I've only included the ones I might need fast in some situations (Mute, VolUp, VolDown, PrtScrn);
- I don't want to overload my mentalstack with state variables from my software+keyboard, so premanently switching layers is used only when needed;
