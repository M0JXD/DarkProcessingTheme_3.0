# Dark Processing Theme for 4.0

![Processing 4 Screenshot](https://user-images.githubusercontent.com/94254558/187070941-387a35ac-586b-41d8-a837-2eea174e1e21.png)

**This fork changes the "theme.txt" file so the theme works with Processing 4**

In Processing 4, the format of the theme.txt file was changed and was no longer compatible with version 3 files.
This fork implements the Dark Theme settings in to the newer format.

*Update: It seems since the latest Processing 4 update themes are included, rendering this unrequired*

## Original Readme

![screenshot](https://raw.github.com/jeffThompson/DarkProcessingTheme_3.0/master/screenshot.png)

A dark theme for the Processing IDE (a little easier on the eyes!) for Processing 3.0.T

For a Processing 2.0 theme, see [this repository](https://github.com/jeffThompson/DarkProcessingTheme_2.0), for P5 1.5, see [this repo](https://github.com/jeffThompson/DarkProcessingTheme).

## CONTENTS  

* `status` folder: updated png files for the bottom bar where error messages show up, mostly to clean up the colors and get rid of the gradient. You don't have to move this folder if you don't want to.  
* `theme.txt`: where the magic happens! Somewhat annotated to make it easier to modify yourself  
* `README.md`: this file  
* `screenshot.png`: a screenshot of the theme

## INSTALLATION  
Before installing anything, be sure to make a copy of the original in case you hate these changes or it breaks something! (If you do have issues, you can just re-install the Processing IDE again.) Just copy the files from this repo into the appropriate location.

* **Mac:** Go to the Processing app in your `Applications` folder, right click it and choose `Show Package Contents` and navigate to  `Java/lib`. Alternatively, just go to `~/Applications/Processing.app/Contents/Java/lib` from the Terminal.   
* **Windows:** `%HomeDrive%\processing64\processing-3.2.1\lib\`  
* **Linux:** Go to the `lib` folder of the directory where you installed Processing, likely `~/processing-{{version-number}}`. Replace the original `footer`, `status` and `toolbar` folders with those in this repo and add the `theme.txt` folder.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
