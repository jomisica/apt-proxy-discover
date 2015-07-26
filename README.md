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

 # dpkg -i apt-proxy-discover_0.4.5_all.deb


# License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

