Connection Reporter - iOS Module
====================================

This project is the source for the iOS version of the module. It's a XCode Titanium Mobile Module Project for the Titanium Studio.

CAUTION
-------------------------
When Titanium Studio creates a Mobile project, It contains some files pointing directly to the local harddrive under the user directory, so just downloading this project and importing to TiStudio(short for Titanium Studio) won't work, cause this project has files pointing to a "lleal" folder inside my computer. That's a problem with TiStudio.

Look for references to this specific folder and edit the files for a proper use of the project's source code and successful build.

SDK VERSION
-------------
This module was initially written for the TISDK 3.3.0, but for newer compilations using the newest Android Developer Tools, you will probably need to update your Titanium SDK to 3.4.0 or higher for It to compile successfully.

This Module will run on any iOS Project targetting iOS 6 or higher. It shoud be able to compile as a 64-Bit module with no problem, but It's still untested. I will commit any necessary changes of needed to compile this project to 64-Bit.
