# SimpleManager

## Release Log

### v1.5

Bug fixed:
* Fix can not start robotmon service on Android 4.1

### v1.4

New functions:
* Screenshot Panel for getting pixel color. (It is transfer by JPEG and Resize on canvas, so there is some blur effect on the image)

Bug fixed:
* Double click to run on mac and linux

### v1.3

New Robotmon Service Manager (Simple Manager)

Support functions:
* Multiple devices
* Find current adb path or download adb from web
* Restart adb server
* Add device: Phone and Emulator
* Run shell command (via adb shell)
* Forward port for connecting to service (for emulator)
* Build gRPC <-> HTTP proxy for connect to robotmon service
* Connect to Robotmon Service: watching logs and run scripts
* Save 10 scripts you writed
* Download log files (/sdcard/Robotmon/robotmon.log)