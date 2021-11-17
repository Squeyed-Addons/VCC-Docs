Here I will explain the basics of VCC by explaining how to apply a strength value to indiviual or multiple colour channels in the Strength tab, these methods carry over to both the Colour and Gradient tabs with some varience in the buttons used to apply values, more information regarding those sections of VCC can be found in this link: https://github.com/Squeyed-Addons/VCC-Docs/wiki/VCC-Panel-Layout.

Though before applying any values, to see them you need to be able to view them. You can simply view vertex colours by setting your viewport shading to Solid and enabling vertex colours but this will restrict the features of VCC.

* Solid shading only allows you to see the RGB channels and not the Alpha channel. 
* You would not be able to use the gradient feature of VCC which relies on the VCC Channel Viewer. 
* The VCC Channel Viewer material is not affected by light so each colour should be easier to see accurately.

More information about the Channel Viewer can be found in this link: https://github.com/Squeyed-Addons/VCC-Docs/wiki/VCC-Panel-Layout#channel-viewer-section

***

To use the VCC Channel Viewer material open the VCC Panel via the key binding (default: alt + c) or find it in your N-Panel, then at the bottom of the panel there should be a button called "Import Channel Viewer", click that.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Import%20CV.jpg?raw=true)

***

Then apply the material to the mesh/s you wish to work with.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Material%20Selection.jpg?raw=true)

***

Finally set your viewport shading to Material Preview mode.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Material%20Preview.jpg?raw=true)

***

Moving on to using VCC, select a single or multiple meshes in the standard Modelling 3D-View in Object Mode.

***

Enter whichever of the 3 Edit Modes you require, Vertex Select, Edge Select or Face Select (Applying a value when in face select will create a hard edge effect on the border of your selection).

***

Then in the 3D-View select the components of each mesh you wish to apply values to.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Component%20Selection%20Apply.jpg?raw=true)

***

Now open the VCC Panel either using the key binding (default: alt + c) or find it in your N-Panel.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Open%20Panel.jpg?raw=true)

***

Select the Strength tab.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Tab%20Select.jpg?raw=true)

***

Set a Strength value from 0 - 1, by default when a vertex colour layer is first created it is entirely white (R = 1, G = 1, B = 1, A = 1) so setting Strength to 0 would be the most obvious application. I usually apply a Strength value of 0 to R, G, B and A before anything else to create a blank black starting colour.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Strength%20Value.jpg?raw=true)

***

Select which channels to apply the value to by toggling the RGBA icons on or off, if they are highlighted blue then they are toggled on.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Channels.jpg?raw=true)

***

Now click the brush icon, this will apply your chosen Strength value to your chosen vertex colour channels.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Apply.jpg?raw=true)

***

The other simple function on this tab is the dropper button to the left of the Strength value, this button copies the average stength value of the channel you select, the average is calculated from all of the components you have selected, so for precision you would only select a single component.

![](https://github.com/Squeyed-Addons/VCC-Docs/blob/main/Media/Images/Getting%20Started%20Copy.jpg?raw=true)

***

The Colour tab is practically the same as the Strength tab, but the Gradient tab is quite different, you can either experiment on your own or look at the VCC Panel Layout page of this documentation to understand it further, though the basic idea of selecting the vertex, edges or faces before applying values remains the same.