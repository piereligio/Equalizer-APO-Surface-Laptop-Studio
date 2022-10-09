# Equalizer APO presets for Microsoft Surface Laptop Studio
Since I first got my hands on my Microsoft Surface Laptop Studio I appreciated the speakers quality, but less their default EQ. 
It tends to be a bit too high on mids, and not to fully take advantage of the hardware. 
So I immediatelly installed Equalized APO and started tinkering with my presets. 

The presets are three (+1 that loads them): one for "laptop mode", one for reverse mode, one for tablet mode (that is also good for stage mode). 
All of them have their dedicated EQ curve, because each mode has a different sound. 
In all of them I aimed at a flat frequency response. 
If you got a good microphone for creating better profiles, of course feel free to share your versions.

There is also config.txt that you need to use (you can overwrite your current config.txt if it's empty, otherwise you can join it with a text editor), it's just referencing to the other 3 profiles in order to make easy to switch the preset that you're using (it filters to my speakers output excluding the others, <b>you will need to set yours otherwise there won't be any have effect</b>).

The profiles also use a free VST compressor called RoughRider3, which is available here. https://www.audiodamage.com/pages/free-downloads
If you want to use the compression as I do, then put the dll file in this path: C:\Program Files\Vstplugins\Audio Damage\ .


