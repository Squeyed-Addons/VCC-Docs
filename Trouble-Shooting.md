[<< BACK](Altering-The-Gradient-Colour-Ramp.md) | [CONTENTS](Contents.md)

***

When you apply values they don't appear on the mesh?

* Try deselecting your mesh and reselecting it, then apply the values again.
* See the entry for "Can't see the vertex colours you've applied?".

Can't see the vertex colours you've applied?

* If you're using the VCC Channel Viewer material make sure you're using the correct channel, this can be checked at the bottom of the VCC panel.
* With the mesh selected, go to the "Object Data Properties", look in the "Vertex Colors" tab, if there is more than one layer, check that the correct layer has the camera icon to it's right highlighted, this makes it so that layer is the "Active Render" layer.

Can't see your saved presets?

* Check the add-on preferences setting called "Preset Directory" is set to the correct directory and that the saved JSON file at that location has not had it's name changed from "VCC Presets.json".
* Close and re-open your current blend file, presets are checked for and loaded when a blend file is opened.
* If both sets of presets are empty and a new preset is added, this will also cause the add-on to check for pre-existing presets.

Seeing "Warning: 1 x Draw window and swap: x.xxx ms, average: x.xxx ms" in your console?

* This is caused by the add-on as a forced re-draw of the blender window is required to perform various parts of this add-on's functionality. It doesn't cause any issues during the operation of this add-on.

***

[<< BACK](Altering-The-Gradient-Colour-Ramp.md) | [CONTENTS](Contents.md)