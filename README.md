Changed app name and icon and it is reflected in the AVD.
Please find the screenshot.

Steps to change the launcher Icon
1. Added/ Imported the images by Selecting the Project in Andoid mode
2. Naviagate to app->res -> mipmap -> right click New-> Image Asset option to select the image in the png format for the new image.

Steps to change the App name
1. Naviagate to Android manifest file by changing the project in Project mode
2. app -> main -> and you will find the Androidmanifest file with .xml as extension
3. find the @string resource file to change the application name [android:label="@string/app_name"]
