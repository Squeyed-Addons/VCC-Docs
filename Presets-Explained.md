* [CONTENTS](Contents.md)

***

Here is an explanation of VCC's preset system, this applies to both Strength and Colour Presets.

As shown in the images below the strength and colour preset popups are essentially the same.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20strength%20and%20colour.jpg?raw=true)

This explanation will cover just colour presets as they are functionally interchangeable.

## Preset Storage

Presets are all stored in one JSON file, they are independant from your individual blend files so any changes made to them in one project will persist across all projects. By default the preset file will be stored in the root folder of your Blender installation, I would strongly advise you to set a custom location in the add-on preferences, somewhere outside of your Blender installation to make it easier to back it up and to avoid overwriting it.

## **IMPORTANT**

This add-on checks in either the default or your custom location for your preset file each time a scene is loaded. If it's not detected it will create a new one. If you disable/uninstall this add-on followed by re-enabling/reinstalling/updating this add-on without re-loading your blend file, you risk overwriting your previously created preset file. This occurs because the add-on has missed it's chance to find the file when activated in an already loaded scene, then when you make any change to the new blank presets it will overwrite the old file. Please be careful to occassionally backup your presets and always re-load your scene if you've done any of the previously mentioned steps before making changes to your presets.

# The Preset Popup

After selecting the Presets button you will be presented with a menu like this, though it will be empty on first use:

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20colour%20main.jpg?raw=true)

### Show Favourites

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20icon%20heart.jpg?raw=true)

When selected the only presets in the list will be those that have been set as favourites. This allows you to reduce a longer list of presets down to a smaller, managable and more pertinently useful selection.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20colour%20show%20favourites.jpg?raw=true)

### Add New Preset

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20icon%20plus.jpg?raw=true)

This will add your current Strength or Colour value to the bottom of your preset list. The value can still be changed once it's in the preset list by selecting it directly.

### Lock

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20icon%20lock.jpg?raw=true)

When this is selected it unlocks this list of presets so that you can move the presets up and down their list as well as delete them as seen in the image below:

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20icon%20edit%20strip.jpg?raw=true)

### Page Controls

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20icon%20page.jpg?raw=true)

If you have more than 10 presets in a list you can use the arrow buttons at the bottom of the presets panel to move the visible section of the list up or down. To the right of the buttons is the list number of the top value currently visible, then the bottom value currently visible and lastly the total number of presets in the list.

***

* [< BACK](VCC-Panel-Layout.md) | [NEXT >](Altering-The-Gradient-Colour-Ramp.md)