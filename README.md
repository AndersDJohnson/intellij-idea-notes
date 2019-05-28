# IntelliJ IDEA notes

## Useful hotkeys

Hotkey | Description
--- | ---
`Ctrl+G` | Go to line
`Ctrl+E` | Recent Files
`Alt+F1` | Select Target context menu (Show file in Project Explorer)


## Config file
Look for "idea.exe.vmoptions" in the install directory under "bin" in the install dir.

## Settings

Show "classes" and other hidden-by-default files in Project browser. [http://blog.jetbrains.com/idea/2011/04/intellij-idea-does-not-show-some-files-know-the-hiding-places/]

## Version Control

### Subversion

If you're working with an older Subversion server, and using a newer version of IntelliJ, you may get an error like "svn: Querying mergeinfo requires version 3 of the FSFS filesystem schema". To fix, disable mergeinfo options under Settings -> Version Control -> Subversion -> Presentation.
