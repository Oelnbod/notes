# Privacy testing apps
##emulating android
- https://www.geeksforgeeks.org/how-to-run-android-apps-on-linux/
- anbox (possibly deprecated)
- waydroid, will need to monitor for if this has telemetry and other requests for baseline - I expect that this works with little external connections. Does not work with x11, so am working to have wayland on server. Possible long term solution is to use a vm once switched to truenas. Probably best option currently.
- emulation of grapheneos: https://grapheneos.org/build#kernel-emulator this looks like a pain to setup and configure.
### vms
- https://www.howtogeek.com/164570/how-to-install-android-in-virtualbox/
- https://www.osboxes.org/android-x86/ Note, the lineage os box will only boot into commandline with the virtbox graphics driverr configured to be vboxsvga or vboxvga
