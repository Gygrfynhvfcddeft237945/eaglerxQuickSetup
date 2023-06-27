# eaglerxQuickSetup
EaglercraftX setup with TeaVM 0.8.1

Run setup.sh

Move ./org/teavm/jso into generated directory ./org/teavm

Change build.gradle file to be the one in this repo

Use the MakeOfflineDownload scripts in this repo, or manually redirect the js file path to point to javascript/js/classes.js

Ignore dependency errors

Compile with 
./gradlew generateJavaScript
./MakeOfflineDownload.sh
