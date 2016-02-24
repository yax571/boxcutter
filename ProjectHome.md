# boxcutter #

[boxcutter](http://rasm.ods.org/boxcutter) is a simple command-line driven screenshot program for Microsoft Windows. Unlike using the "Print Screen" key that takes a full-screen screenshot, boxcutter allows the user to screenshot a smaller portion of the screen by dragging a box and automatically saves the screenshot to a specified file. boxcutter can also run without the command line, in which case it will by default place a screenshot onto the clipboard. If the --coords option is given, a specified rectangle of the screen will be used for capture.


## Usage ##
```
usage: boxcutter [OPTIONS] [OUTPUT_FILENAME]

Saves a bitmap screenshot to 'OUTPUT_FILENAME' if given.  Otherwise, 
screenshot is stored on clipboard by default.

OPTIONS
  -c, --coords X1,Y1,X2,Y2    capture the rectange (X1,Y1)-(X2,Y2)
  -f, --fullscreen            fullscreen screenshot
  -v, --version               display version information
  -h, --help                  display help message
```


## Screenshots ##
![![](http://rasm.ods.org/boxcutter/images/thumbs/screenshot.png)](http://rasm.ods.org/boxcutter/images/screenshot.png)