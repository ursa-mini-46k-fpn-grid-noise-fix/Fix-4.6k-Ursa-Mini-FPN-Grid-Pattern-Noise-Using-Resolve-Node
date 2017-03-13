# Fix 4.6k Ursa Mini FPN Grid Pattern Noise Using Resolve Node

## README

Apply only to the footage and in the timeline with the matching resolution—this will guaranty pixel to pixel mapping needed for this to work properly.

*IF THE DRX FILES WON'T IMPORT:* Select the folder the .drx files are in an d import  that instead.

## URSA Mini 4.6K - Grid Pattern Workaround

The workaround to alleviate the visible grid pattern will only work if applied to the ORIGINAL footage shot by the camera, and when used in certain conditions. Be sure to download the HD-UHD-46K-grid_2.zip file, unzip it, and move it to the desired folder destination in the system. The following settings and steps will help alleviate the issue when working with RAW 4.6K footage and ProRes footage shot in HD and UHD. The zip file also contains the files needed for 2K footage and can be applied in the same fashion.

**RAW 4.6**

Camera Settings:

- Codec: RAW, RAW 4:1, RAW 3:1 - Resolution: 4608x2592
- Sensor Area: Full DaVinci Resolve Settings:

1. Project Settings > Master Project Settings > Timeline Resolution: Custom For 4608x2592 - Project Settings > Master Project Settings > Video Monitoring > Monitor scaling: Bilinear
2. Import the footage into the timeline.
3. In the Color page, go to the Gallery window and open Still Albums
4. Right click and select Add Power Grade Album (so that you always have a shortcut to the fix) then right click in the grey are and select Import
5. Navigate to the location of the unzipped folder and select 4.6K_grid_1.1.1.drx (if this is greyed out, set the import window to All Files (*.*)) and Import it. If this isn’t an option, import the entire enclosing folder instead.
6. Then double click on the still so that it applies the fix to the selected clip in the timeline

**ProRes UHD**

Camera Settings:

- Codec: ProRes (any flavor) - Resolution: 3810x2160
- Sensor Area: Window
- Detail: Off

DaVinci Resolve Settings:

- Project Settings > Master Project Settings > Timeline Resolution: 3840x2160 Ultra HD
- Project Settings > Master Project Settings > Video Monitoring > Monitor scaling: Bilinear

1. Import the footage into the timeline.
2. In the Color page, go to the Gallery window and open Still Albums
3. Right click and select Add Power Grade Album (so that you always have a shortcut to the fix) then right click in the grey area and select Import
4. Navigate to the location of the unzipped folder and select 3840x2160_grd_1.1.1.drx (if this is greyed out, set the import window to All Files (*.*)) and Import it. If this isn’t an option, import the entire enclosing folder instead.
5. Then double click on the still so that it applies the fix to the selected clip in the timeline

**ProRes HD**

Camera Settings:

- Codec: ProRes (any flavor) - Resolution: 1920x1080
- Sensor Area: Window
- Detail: Off

DaVinci Resolve Settings:

- Project Settings > Master Project Settings > Timeline Resolution: 1920x1080 HD
- Project Settings > Master Project Settings > Video Monitoring > Monitor scaling: Bilinear

1. Import the footage into the timeline.
2. In the Color page, go to the Gallery window and open Still Albums
3. Right click and select Add Power Grade Album (so that you always have a shortcut to the fix) then right click in the grey are and select Import
4. Navigate to the location of the unzipped folder and select 1920x1080_grd_l.1.1.drx (if this is greyed out, set the import window to All Files (*.*)) and Import it. If this isn’t an option, import the entire enclosing folder instead.5. Then double click on the still so that it applies the fix to the selected clip in the timeline

If the settings aren’t correct, the workaround won’t work, so if you don’t see a difference double check your settings.
