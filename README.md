# Push-notification-custom-icon-in-flutter

## 1. Create a transparent and white notification icon (you can use the following tool: AndroidAssetStudio )
## 2. Download the zip folder, unzip and you'll see it contains a res folder with different drawable folders. Copy and paste the contents of the res folder in "android\app\src\main\res" path

![image](https://github.com/EftiarHKhan/Push-notification-custom-icon-in-flutter/assets/105238792/9d889050-fdd8-40bf-8fb8-9adb4daf6809)


## 3. Folder Structure

Then open the AndroidManifest.xml file and add the following lines to it:

ic_stat_calendar_today is the name of my notification icon. And each of the drawable folders that have been pasted contain a different size of icon with the same name.

![image](https://github.com/EftiarHKhan/Push-notification-custom-icon-in-flutter/assets/105238792/1e1b3fc6-354d-4a0c-9062-bafd321e918d)


## 4. Android Manifest

If you want to change the color of the icon then check the above image. Add the metadata tag after the notification icon tag

Go to "android\app\src\main\res\values" and add a colors.xml file

![image](https://github.com/EftiarHKhan/Push-notification-custom-icon-in-flutter/assets/105238792/6771899e-b13a-4762-9540-38c08d276675)


colors.xml

<color name="colorAccent">#00FF00</color>
