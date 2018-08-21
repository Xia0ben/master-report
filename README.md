# Master report
Research Report for my Engineering Degree

## Build

As all required source files and resources are in this repository, if you have a standard latex install, opening the "main.tex" file in your favorite editor should allow you to build it easily. Tested with the [Atom editor](https://atom.io/), using the [latex plugin](https://github.com/thomasjo/atom-latex), which in turn used the [xelatex engine](http://xetex.sourceforge.net/) and [dvipdfmx PDF Producer](https://www.ctan.org/pkg/dvipdfmx-def). You will also need the [pygmentize](http://pygments.org/) package.

### Note: Exporting the libreoffice tables

+ Copy (Select > Ctrl+C) the portions of tables that you want to be included in the final render
+ Special-Paste (Ctrl+Shift+V) them into a libreoffice draw document, choosing the "calc8" special-paste
+ Select the same elements and click on File > Export.
+ Tick the "Selection" box, choose the .png format and overwrite the existing file or create a new one

## TODO

### High priority

+ Fix all algorithms according to the latest numbers
+ Change the way the code is commented so that it doesn't clutter the reading (maybe change local sentences as local notes, add extra explanations on the notations at the beginning and reduce overall detail level)
+ Add basic figures from main article in chapter 3 to illustrate

### Medium priority

+ Adjust comparison criteria from newest observations brought by coding and the one already copied in chapter 2, "Determining appropriate comparison criteria" section, "Performance criteria"

### Low priority

+ Find a new title closer to final content, but keep the current title as subtitle might be relevant
+ Have the bibliography use numbers
+ Have the bibliography be ordered chronologically by date of publication
