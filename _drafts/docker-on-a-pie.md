---
layout: post
title: Running Docker on a Raspberry Pi
---

# {{ page.title }}

*XX Oct 2014 - Stockholm, Sweden*


## Install Arch Linux on your Pie
Follow the steps at the [Raspberry Pi](http://archlinuxarm.org/platforms/armv6/raspberry-pi) site 

## WIFI!

There is a great wiki over at [archlinux](https://wiki.archlinux.org/index.php/Wireless_network_configuration),
but basically you just do the following:

`pacman -Syu`

To config your wifi connection, use the package [wireless_tools](https://www.archlinux.org/packages/?name=wireless_tools).

`pacman -S wireless_tools`

For WPA/WPA2, you need [wpa_supplicant](https://www.archlinux.org/packages/?name=wpa_supplicant), which provides a utility for key negotiation with WPA networks.

`pacman -S wpa_supplicant`

Now run `wifi-menu`, and select your wifi.

Use `netctl` to configure autostart of your wlan interface:

```
netctl list
netctl enable wlan0-<name>
```

## Install Docker
Installing docker just as easy as anything!

`pacman -S docker`


## Hello, World!
Now let's fire up an application.

## Further reading
* <http://docker.io>
* <https://www.archlinux.org/>
* <http://www.raspberrypi.org/>
