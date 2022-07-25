pi-video-stream
===============

This is a simple `mjpg` web server suitable for displaying as an image in HomeAssistant.

Usage
-----

Install dependencies: `make install`

Check dependencies: `make check`

Start the server: `make start`

Install the server as a `systemd` unit: `make service-install service-start`

Uninstall the server as a `systemd` unit: `make service-stop service-uninstall`

Tech
----

Python script using `picamera` to monitor a Raspberry Pi Camera and using the python `http.server` module as a basic vehicle.
