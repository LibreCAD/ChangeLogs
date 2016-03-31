### What happened to the old CAD toolbar?

It has been removed from the program for a few reasons.

The code is overly complex and difficult to read / maintain.  
This limits possibilities and potential contributions.

The two column design is forced,  
which results in undefined cross-platform behavior.  
That means we can't guarantee how the toolbar will work on all platforms;  
and in fact it does not work the same on all platforms,  
and malfunctions in a few cases.  
It also doesn't work properly with an icon size option.

The replacement widgets are not forced in any way;  
therefore, we can guarantee, as much as Qt guarantees,    
that the toolbars will work properly on all platforms.  

You can now make as many custom toolbars as you want.  
Toolbars can be dragged and dropped anywhere you want.

In the drawing area, right-click will exit the current tool and then open a menu.  
Any tool you use will be placed at the top of the right-click menu.

You can also create a custom menu that appears when you double-click.  
