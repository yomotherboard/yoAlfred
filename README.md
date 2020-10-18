# yoAlfred
All my Alfred workflows. They are cattegorized by the function they provide or the application they interact with. The current categories are:
- Audio Hijack
- Code

## Audio Hijack
### Run Session
Run an Audio Hijack session.

### Refresh Session List
Refreshes the stored list of available Audio Hijack sessions.

To refresh the session list you must use refresh session list workflow. This is in case someone has an unfinished session open and would not like to add it to the session list yet. This also allows the command to run more smoothly as it spends less time interacting with the user interface.

## Code
### ASCII Art
Open FIGlet font generator with a font selected from the autocomplete engine.

Use for comment/section headers in configuration files.

### Get Accessibility Path
This workflow uses "AXFocusedUIElement" attribute of the frontmost application to get the accessability path of the currently focused element of the application.

This currently works best with native Mac applications and Swift/Cocoa applications.

### Get Bundle ID
This workflow grabs the application bundle ID from the application's Info.plist file. This file is stored in the contents of applications. 

To add a file make sure it is in the scope of the file filter at the beginning of the workflow.
