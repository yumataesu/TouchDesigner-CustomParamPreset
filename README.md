# TouchDesigner-CustomParamPreset
 More Simple implementation than the one in Palette browser(Derivative > Techniques > Preset)
 
![ss](https://github.com/yumataesu/TouchDesigner-CustomParamPreset/blob/main/readme/ss.png)


## Presetable parameter
* Number Type (Int, Float, RGB, RGBA, UV, UVW, WH, XY, XYZ)
* String Type (Str)
* Menu Type (Menu, StrMenu)

other parameter type is ignored.


## How to use
1. Create your Comp with custom parameters on your project
2. Drag&Drop "Preset.tox" on your project
3. Fill in the blank "Comp" and "page" in Preset.tox
4. Hit "Init" pulse button in Preset.tox
4. Tweak your custom parameter which you've created at 1
5. Set "Name" and "Duraion"
6. Hit "ADD"
7. Select Preset on Bank and hit "APPLY"


## Technical Details
* Presets are saved as storage in a target Comp.


![ss](https://github.com/yumataesu/TouchDesigner-CustomParamPreset/blob/main/readme/output.gif)
