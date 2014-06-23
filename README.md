This simple HTML code to control a PTZ camera over Internet.

This will require the ptzserver code located @ https://github.com/acassis/ptzserver

When the user presses the arrow buttons over 1 second period it will move camera faster.
If the user pressed the arrow buttons and release mouse buttom quickly (less than 500ms) it will move camera slowly.

It calls the "pelco" command (code from http://sourceforge.net/projects/pelco-ptz) running on your server.
In your server you need to use a RS-485 interface (i.e. a USB/RS485 converter) connected to PTZ Camera.

Feel free to use this example as you want, no license required.
