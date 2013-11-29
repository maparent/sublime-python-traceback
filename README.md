PythonTraceback
===============

PythonTraceback is a plugin for Sublime Text 3, that allows easy navigation in
your python tracebacks.  Copy a traceback from your terminal to clipboard,
switch to Sublime Text and press `Ctrl+t`, `Ctrl+v`. New scratch buffer will be
opened with the traceback. Place cursor on a line you want to navigate to and
press `Alt+d`: file will be opened at the line, specified in traceback.

Pressing `Ctrl+t`, `Ctrl+v` again will replace traceback buffer with new
traceback from the clpboard.

Defined commands
----------------

PythonTraceback defines the following commands:

Command                 | Title                      | Default Key Binding                                 | Context
:-----------------------|:---------------------------|:----------------------------------------------------|:-------------------------------
`traceback_paste`       | Traceback: Paste Traceback | `Ctrl+t`, `Ctrl+v` on PC or `⌘-t`, `⌘+v` on OSX   | Any window
`traceback_goto_line`   | Traceback: Go To Line      | `Alt+d`                                             | Traceback window only