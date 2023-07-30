Example showing blurry fonts on only some UI components when stretching.

With a screen resolution much higher than the default viewport size, run the only scene in the project and maximize the window.

You should see:
- file dialog title "Save a File" is crisp
- everything else in the file dialog is not

Only changes from defaults:
- Project Settings -> Window -> Stretch -> Mode set to "canvas_items"
- FileDialog -> Window -> Initial Position set to "Center of Primary Screen"
