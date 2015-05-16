# OpenVPN-vps
OpenVPN -- A Secure tunneling daemon

Copyright (C) 2002-2010 OpenVPN Technologies, Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

This script will install a basic VPN setup.

# Requirements
A linux based VPS. Really, that's all.

# Manual
1. Download & install an OpenVPN client on your local machine
2. Download the client.opvn from your VPS to your local machine, and put it in
the config folder of the application. If you use the OpenVPN client, put it
in C:\Program Files\OpenVPN\config (Windows)
3. Connect the client, and you're done
4. Start browsing safe and secured from any Free Wifi location

# Useful information
* Local subnet 10.8.0.0/24 will be used
* Port 1194 will be default ( change if you would like to)
* Oh, and very useful. Start using systemd! ( it really rocks )
