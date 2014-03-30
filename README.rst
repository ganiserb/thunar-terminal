About...
========

The script
----------

A simple workarround script to open a terminal on the current directory in Thunar (The default Xfce file manager) under GNU/Linux.

The author
----------

Originally written by "Anjishnu Sarkar". Initial vesion taken from `this post`_.

  .. _`this post`: http://linuxunderthesky.blogspot.com.ar/2011/11/keyboard-shortcut-for-open-terminal.html

How to get this working
=======================

**Note**: If you don't know what ``$PATH`` or ``$PWD`` mean you should really google about "*environment variables*".


1. Download the script `from master`_.

#. Copy it to your ``$PATH`` (create ``~/bin`` maybe?).

#. Set the ``$TerminalEmulator`` variable. Use the command to start the terminal emulator of your preference.

#. Add ``$ExtraParameters`` if necessary.

#. Tweak the ``$WorkingDirParameter`` so that the terminal sets ``$PWD`` correctly.


.. _`from master`: https://github.com/ganiserb/thunar-terminal/blob/master/thunar-terminal.sh
