# apt-proxy-discover

Try to find automatically the existence of an APT proxy on the network.
If found a proxy configure the system to use it.

# Description

Apt-proxy-discover is a script that aims to discover the existence of a proxy APT on the LAN.

This script does not need configuration.

It is run whenever a network interface is started or stopped.

When it finds a proxy configures the system to use it.

Apt-proxy-discover works only with Debian / Ubuntu and perhaps others using .DEB packages.

# Installation

The manual installation of the script can be made as follows:

 # cp apt-proxy-discover /etc/network/if-up.d/

 # cd /etc/network/if-post-down.d/

 # ln -s ../if-up.d/apt-proxy-discover apt-proxy-discover

 # chmod 764 apt-proxy-discover

The installation of .DEB package can be made as follows:

 # dpkg -i apt-proxy-discover_0.4.1_all.deb





