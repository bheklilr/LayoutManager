Origami 2
=========
Origami 2 is a new way of thinking about panes in Sublime Text: you tell Sublime Text where you want a new pane, and it makes one for you.  This plugin was adapted from the original Origami plugin in the Sublime Text repository

Ordinarily one uses the commands under View>Layout, or if one is quite intrepid a custom keyboard shortcut can be made to give a specific layout, but both of these solutions were unsatisfactory to me. Perhaps they were to you too! That's what this plugin is for.

Try it out! I think you'll like it.

Keyboard shortcuts
------------------
Origami is driven by keyboard shortcuts. By default, these keyboard shortcuts are all two-stage, and are hidden behind `super+k`. First press `super+k`, then press the arrow keys with modifiers:

* no modifiers: travel to an adjacent pane
* `super`: carry the current file to the destination
* `alt` (`option`): clone the current file to the destination
* `shift`: create an adjacent pane
* `super+shift`: destroy an adjacent pane

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

    git clone git://github.com/bheklilr/Origami-2.git

That's it!

