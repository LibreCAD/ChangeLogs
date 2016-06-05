My primary goal for this release was to make something more efficient than the two column [QCAD toolbar][1].  
I've replaced it with several other toolbars and dock widgets;  
however, I recommend making custom toolbars and menus (e.g. right-click menu).
[1]:https://github.com/LibreCAD/ChangeLogs/blob/master/developers/r-a-v-a-s/2-1/2-1-0/old_cad_toolbar.md

It's been a year and there's still plenty of refinement that can be done;  
however, everything works; and the improvements are too significant to wait any longer.
LibreCAD is a much more stable and customizable program now.

- https://github.com/r-a-v-a-s
- http://r-a-v-a-s.github.io/

Thanks to all contributors and special thanks to:

- dxli: for helping me become a team member, many bug fixes, eliminating over 50,000 compiler warnings and improvements of the geometry algorithms
- lordofbikes: for translations and applying translations to the program, and offering pre-releases for Windows
- maqifrnswa: for adding static analysis and travis ci to the repository, and offering pre-releases for debian/ubuntu
- dellus: for being a beta tester and creating almost 200 new SVG icons
- Cantar4: for being a beta tester and donating 
- R. van Twisk: for starting the LibreCAD project, and trusting / supporting me as a team member

## Custom Toolbars

The Toolbar Creator (in the Widgets menu) offers a list of every tool (action)
in LibreCAD. You can create any amount of toolbars and edit them later.
Like all toolbars they can be dragged and dropped to where you want them.

There is also a new toolbar icon size option in 'Widget Options'.

https://github.com/LibreCAD/LibreCAD/wiki/Widgets

## Custom Menus

The Menu Creator is similar to the Toolbar Creator,
and allows you to assign a pop-up menu to  
Double-Click, Right-Click, Ctrl+Right-Click and Shift+Right-Click.

## Action History

If a custom menu has not been assigned,
Right-Click will invoke a list of recently used tools.

## Dock Areas

Dock widgets (e.g. command line or layer list) 
can be moved and docked at the top, bottom, left or right.
You can now show and hide all the dock widgets 
in a specific dock area. You can also toggle
the visibility of all floating dock widgets
(those which are not currently docked).

## Keycodes

In Application Preferences you can enable Keycode mode.
A command of two characters is considered a keycode,
and it will automatically trigger (i.e. you don't need to press Enter).

## Styles and Style Sheets

You can now dramatically change the way LibreCAD looks! 
https://github.com/LibreCAD/LibreCAD/wiki/Style-Sheets

## Exclusive snap mode

There is an 'Ex' toggle with two states:

- On: only one snap mode is allowed
- Off: multiple snap modes are allowed

The snap modes are remembered in each state. 

## More...

I recommend trying the new Spiderweb snap indicator
in combination with the "Hide cursor when snapping" option.

There is a fullscreen mode.

There is an anti-aliasing option.

Disabling the scrollbars seems to improve performance.

A lot of bugs have been eliminated, including crashes and memory leaks.  
The most noteworthy bugs fixed:

- the app would get stuck in the plugin loop and persist in the background after exit
- layers were activated when clicking their inline icons (e.g. visibility)
- invalid objects were allowed to exist, causing auto-zoom errors
- export image's resolution field did not work
- the fixed extension line length option for dimensions didn't work

This is just the tip of the iceberg, and only includes the highlights of my changes.

[Change Log](https://github.com/LibreCAD/ChangeLogs/blob/master/developers/r-a-v-a-s/2-1/2-1-0/2-1-0.md)
