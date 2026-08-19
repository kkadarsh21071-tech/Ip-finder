# IP Finder

Android app prototype for scanning the Wi-Fi LAN and finding reachable devices, with a heuristic label for possible IP cameras.

## Build
Open this project in Android Studio and build/install the `app` module.

## Important
The scanner is limited to the local Wi-Fi network/subnet visible to the phone. It cannot discover cameras on unrelated remote networks, and some routers/VLANs/client isolation can hide devices. Camera identification is heuristic in this first version; ONVIF discovery can be added as the next step.
