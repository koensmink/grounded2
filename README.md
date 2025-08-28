# Performance tweaks for grounded 2

Although Grounded 2 can be quite demanding on system performance, this tweak significantly improves FPS. On an RTX 5080, I was able to maintain a stable 70–120 FPS on ultra settings without making any additional changes.

For lower-end GPUs, you can apply the following adjustment:

```
[ScalabilityGroups]

sg.ResolutionQuality=66

sg.ViewDistanceQuality=1

sg.AntiAliasingQuality=1

sg.ShadowQuality=1

sg.GlobalIlluminationQuality=1

sg.ReflectionQuality=1

sg.PostProcessQuality=1

sg.TextureQuality=1

sg.EffectsQuality=1

sg.FoliageQuality=1

sg.ShadingQuality=1

sg.LandscapeQuality=1
```

# Place configuration file

Be sure to create a backup of the original file before overwriting it. 

* Go to the folder: C:\Users\%username%\AppData\Local\Augusta\Saved\Config\WinGDK
* Place or create the Engine.ini file in here and set read-only permissions to the file


Creds: https://github.com/tgsAvylaar/Grounded2LaunchDayFPSFix
