Layout Manager
==============
Layout Manager is a new way of thinking about panes in Sublime Text: you tell Sublime Text where you want a new pane, and it makes one for you.  This plugin was adapted from the Origami plugin in the Sublime Text 2 repository.

Ordinarily one uses the commands under View>Layout, or if one is quite intrepid a custom keyboard shortcut can be made to give a specific layout, but both of these solutions were unsatisfactory to me. Perhaps they were to you too! That's what this plugin is for.

Try it out! I think you'll like it.

Keyboard shortcuts
------------------
The Layout Manager plugin is driven by keyboard shortcuts. By default, these keyboard shortcuts are all two-stage, and are hidden behind `super+k`. First press `super+k`, then press the arrow keys with modifiers:

* no modifiers: travel to an adjacent pane
* `super`: carry the current file to the destination, creating a pane if needed.
* `alt` (`option`): clone the current file to the destination
* `shift`: create an adjacent pane
* `super+shift`: destroy an adjacent pane
* `super+r`: reset the layout, moving all open files to one pane
* `super+k`: immediately create a two column layout of three panes with the left pane spanning two rows.

These keyboard shortcuts are designed to make it really easy to modify the layout of your editor.

(Note: Windows uses `ctrl` instead of `super`.)


Manual Install
--------------

Go to your Packages subdirectory under ST2's data directory:

* Windows: %APPDATA%\Sublime Text 2
* OS X: ~/Library/Application Support/Sublime Text 2
* Linux: ~/.config/sublime-text-2
* Portable Installation: Sublime Text 2/Data

Then clone this repository:

    git clone git://github.com/bheklilr/LayoutManager.git

That's it!

