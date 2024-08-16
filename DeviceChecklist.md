Device Checklist
================

Working
-------
* Actors: Manual brightness
* Actors: Vibration (works in QML apps, notifications, keyboard)
* Bluetooth: Driver loaded at startup
* Bluetooth: Enable/disable and flightmode works
* Camera: Photo
* Camera: Switch between back and front camera
* Camera: Video
* GPU: Boot into Spinner animation and Lomiri UI
* Misc: AppArmor patches applied to kernel
* Misc: Battery percentage
* Misc: Date and time are correct after reboot (go to flight mode before)
* Misc: logcat, dmesg & syslog do not spam errors and service restarts
* Misc: Offline charging (Power down, connect USB cable, device should not boot to UT)
* Misc: Online charging (Green charging symbol, percentage increase in stats etc)
* Misc: SD card detection and access
* Misc: Shutdown / Reboot
* Sensors: Rotation works in Lomiri
* Sensors: Touchscreen registers input across whole surface
* Sound: Loudspeaker, volume control ok
* Sound: Microphone, recording works
* Sound: System sounds and effects plays correctly (Camera shutter, Screenshot taken, Notifications)
* USB: ADB access
* WiFi: Driver loaded at startup
* WiFi: Enable/disable and flightmode works
* WiFi: Hotspot can be configured, switched on and off, can serve data to clients
* WiFi: Persistent MAC address between reboots

Working to some extent but with issues
-----------------------------

* Sensors: Keyboard and touchpad works (touchpad stops working after reconnecting the keyboard)

Untested
--------
* Bluetooth: Pairing with headset works, volume control ok
* Bluetooth: Persistent MAC address between reboots
* Cellular: Carrier info, signal strength
* Cellular: Switch connection speed between 2G/3G/4G works for all SIMs
* Cellular: Switch preferred SIM for calling and SMS
* Cellular: Change audio routings (Speakerphone, Earphone)
* Cellular: Data connection
* Cellular: Enable/disable mobile data and flightmode works
* Cellular: Incoming, outgoing calls
* Cellular: MMS in, out
* Cellular: PIN unlock
* Cellular: SMS in, out
* Cellular: Voice in calls
* Endurance: Battery lifetime > 24h from 100%
* Endurance: No reboot needed for 1 week
* GPU: Hardware video decoding
* Sensors: Proximity works during a phone call

Not working
-----------

* Misc: Recovery image builds and works
* Misc: Reset to factory defaults
* Sensors: Automatic brightness
* Sensors: Double-tap to wake
* Sensors: GPS
* USB: MTP access
