## Overview

I'm setting up some old and new Cisco kit so that I can study/learn

As part of the hardware I have 6 [Raspberry Pi](https://www.raspberrypi.org)
computers with the [PoE HAT](https://www.raspberrypi.org/products/poe-hat/)
all connected to a Cisco Meraki [MS220-8P](https://meraki.cisco.com/lib/pdf/meraki_datasheet_ms220_compact.pdf) router.

One of these RPi's is being used as a controller with access to the 
serial consoles for all of the other Cisco kit.  I intend to install 
monitoring software on this computer since it is also connected to a display.

The other 5 RPi's are going to be configured as part of the various 
setups I'll be playing with and they are all equiped with two extra network 
ports using USB Ethernet adapters.

In order to make everything simple (or relatively so) I'm going to 
configure the RPis using Ansible.

