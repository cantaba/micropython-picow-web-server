# micropython-web-server
MircoPython web server on a Raspberry Pico W
Code includes an async web server on a Pico W switching a GPIO pin by calling a certain URL

First try with MicroPython on a Raspberry Pico W

Code has been copied and adapted to fit the usage of a simple garage door opener by calling a certain URL, like http://< PicoW IP address >/button/pushed

Code includes Async Web server. If a certain URL is identifed a GPIO pin is triggered for 0.5 seconds. Like it would be with the button/key to open and close the garage door manually.

Needed hardware: Pico W, a small DC relay, power adapter for the Pico, USB cable and some wiring cable.

Total cost, less then 20 $
