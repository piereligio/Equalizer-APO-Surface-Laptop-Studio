# Equalizer APO presets for Microsoft Surface Laptop Studio
Since I first got my hands on my Microsoft Surface Laptop Studio I appreciated the speakers quality, but less their default EQ. 
It tends to be a bit too high on mids, and not to fully take advantage of the hardware. 
So I immediatelly installed Equalized APO and started tinkering with my presets. 

<b>Description</b>
The presets are four: 
- "laptop mode";
- stage mode;
- tablet mode;
- stage mode;
- reverse mode. 
All of them have their dedicated EQ curve, because everytime you change mode, the sound timbre changes. 
In all of them I aimed at a flat frequency response. 
I used a calibrated Electrovoice ND767a, but it wasn't good enough, so I proceded with manual comparison with a calibrated Sennheiser HD599. 
If you got a good microphone for creating better profiles, of course feel free to share your versions (let me know preferably).

<b>Instructions for installation</b>
- [Prerequisite] EqualizerAPO set up and installed on the speakers output using configurator app;
- [Optional prerequisite for compression, highly recommended] 
Install RoughRider3, which is available here. https://www.audiodamage.com/pages/free-downloads
Use the setup file in the default path, or manually put the dll file in this path: C:\Program Files\Vstplugins\Audio Damage\ .
- Download all files or the project as a zip;
- Put all the files in C:\Program Files\EqualizerAPO\config\ (config.txt will be overwritten, if you didn't customize it just do it, otherwise merge them with a text editor);
- Start "Configuration Editor" from the start menu.
<img width="463" alt="image" src="https://user-images.githubusercontent.com/11073747/221178614-0cb36c13-8366-4d54-aee5-83d675c84c36.png">
If it looks like the previous image but with a red text in the first row, it'll be like mine when you click "Change" button and select your speakers output device. <b>It's a needed step.</b> Once done, it should work using the "laptop mode" profile.
- To select the various profiles, turn off and on one profile at a time. You haven't to turn on more than one included profile together, otherwise it'll sound very bad.
