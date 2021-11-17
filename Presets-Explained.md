[<< BACK](VCC-Panel-Layout.md) | [CONTENTS](Contents.md) | [NEXT >>](Altering-The-Gradient-Colour-Ramp.md)

***

Here is an explanation of VCC's preset system, this applies to both Strength and Colour Presets.

As shown in the images below the strength and colour preset popups are essentially the same.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/preset%20strength%20and%20colour.jpg?raw=true)

This explanation will cover just colour presets as they are functionally interchangeable.

## Preset Storage

Presets are all stored in one JSON file, they are independant from your individual blend files so any changes made to them in one project will persist across all projects. By default the preset file will be stored in the root folder of your Blender installation, I would strongly advise you to set a custom location in the add-on preferences, somewhere outside of your Blender installation to make it easier to back it up and to avoid overwriting it.

## **Suddenly Empty Presets?**

If your presets are suddenly all gone then you may need to check the add-on preferences to make sure the correct directory has been set, however this can also occur when the add-on is disabled and then re-enabled or updated, this is because VCC checks for your save files when the Blend file is loaded. You can fix this by either reloading your Blend file, adding a new preset to the empty list will also bring them back. But just in case, as with all of your work I recommend you backup your preset files often.

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

[<< BACK](VCC-Panel-Layout.md) | [CONTENTS](Contents.md) | [NEXT >>](Altering-The-Gradient-Colour-Ramp.md)