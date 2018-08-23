RPiRTC
=============

A deb package to handle RTC modules on the raspberry pi, checks for ntp connection every 5 minutes and updates RTC if ntp connects, reads RTC time on boot.

Install rpirtc package either by adding
`deb http://people.ds.cam.ac.uk/fa344/repos/apt/debian/ stretch main` to your repositories and using `apt` or by installing [the .deb directly](`http://people.ds.cam.ac.uk/fa344/repos/apt/debian/pool/main/r/rpirtc/rpirtc_0.1-4_all.deb`). The installation will enable i2c and setup the clock. Use hwclock to check the hardware clock time.
