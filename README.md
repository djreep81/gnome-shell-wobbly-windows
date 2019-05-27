gnome-shell-wobbly-windows
==========================

Wobbly Windows extention for gnome shell.

For Gnome shell users, please activeate this extention via https://extensions.gnome.org/extension/669/wobbly-windows/

To avoid 'tearing' in the graphics alter the file /etc/enviornment to add the following line: 


CLUTTER_PAINT=continuous-redraw

Please note that alt-f2 and restart ('r') is not enough to apply the /etc/environment changes.  Please restart your computer after you make that change. 
