# Intro
Here will be a history of my GNU/Linux distro usage and issues that occurred.

# My machines

## Main
motherboard: h61
cpu: i3 2100
ram: 4gb 1333mhz
storage: 250gb ssd
video: geforce gt220

## Work
macmini 7.1 (late 2014)
cpu: i5 1.4ghz
ram: 4gb 1600mhz
storage: 120gb ssd
video: hd graphics 5000

# Fedora

## Silverblue 38
Installed on Main pc.
Issues:
- Couldn't install vpn app(Pritunl client).
  Silverblue is an immutable OS, so users can install apps using flatpak, ostree-rpm, or containers. However, Pritunl does not have a flatpak package and was buggy when I tested it in a container or with ostree-rpm.
