Blender Addon to Import RepRap G-code
====================

This repository contains a Blender(http://blender.org) addon for importing
RepRap .gcode files as 3D models.  Each layer of the print is imported as
a frame of animation.

There is a folder in this repository for each version of Blender that is
supported.  Simple add the file or folder from the appropriate version to
your scripts/addons folder and enable the addon in Blender's "Addons"
pane in User Preferences.

Note: There is a known bug that will affect gcode generated by old
versions of slic3r or custom gcode with comments.  Make sure there is a
space preceeding the semi-colon on lines that contain both G-code
instructions and comments or you'll get an error.  This will be fixed in
the future.

This script is heavily based off the work of Simon Kirkby and David
Anderson's previous versions.
