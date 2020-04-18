![publish](https://github.com/dzervas/ansible-router/workflows/publish/badge.svg)

# Linux router ansible role

This is a linux router ansible role. I'm testing it on my Alix 2 by PCEngines
but any distro should do it.

This role is VERY opinionated and the whole idea is that you will have a single
machine (or VM) dedicated for this job. The requirements are quite minimal -
running perfectly fine at 256MB RAM with a decade old 32bit x86 AMD and
the system is idling mostly.

I was thinking to go "full-ansible" and just expose all the possible variables
to ansible but that is not exactly possible - configures network-intefaces,
dnsmasq, hostapd & ferm. If you see some usage that you want support for,
extend it and do an MR or open an issue and I might implement it.

Have fun!
