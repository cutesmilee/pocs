# pocs
repo containing my own pocs / exploits

# cve-2019-2215-exploit.c
an exploit for [CVE-2019-2215](https://cutesmilee.github.io/kernel/linux/android/2022/02/17/cve-2019-2215_writeup.html), a use-after-free vulnerability in the Android Binder driver, it achieves arbitrary kernel r/w through pipes then achieves root by overwriting fields in the proc struct and then disables SELinux enforcing by overwriting the selinux_enforcing variable.
