RPiRTC
=============

A deb package to handle RTC modules on the raspberry pi, reads RTC time on boot, if kernel is not configured with `RTC_SYSTOHC`, it checks ntp status every 5 minutes and updates RTC time is synchronised.

Install rpirtc package either by adding
`deb http://people.ds.cam.ac.uk/fa344/repos/apt/debian/ stretch main` to your repositories and using `apt` or by installing [the .deb directly](`http://people.ds.cam.ac.uk/fa344/repos/apt/debian/pool/main/r/rpirtc/rpirtc_0.2-1_all.deb`). The installation will enable i2c and setup the clock. Use hwclock to check the hardware clock time.
