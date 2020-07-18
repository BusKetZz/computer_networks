# Bluetooth and Zigbee



## Bluetooth (IEEE 802.15.1)

Key features:

* **Range**: short
* **Power**: low
* **Cost**: low
* **Band**: 2.4 GHz (unlicensed)
* **Max transfer speed**: 4 Mb/s

Based on these features, Bluetooth network can be a good "replacement of
cable" for peripheral devices like keyboard, mouse, headphones or mobile phones
exchanging data with each other.

Bluetooth networks are sometimes called the **WPAN** (*Wireless Personal Area
Network*) because they are mostly used in a close range.

What is more they are *ad-hoc* networks, which means that none network
infrastructure is needed, 802.15.1 devices must organize themselves.

Firstly, they create *pico-network* consisting of maximum 8 active devices.
One of them is a parent device, rest of them are subdevices.

Parent device is a real leader, its clock sets the time and synchronizes
transmissions of each device.

Besides subdevices, there are up to 255 *parked* devices, which cannot
establish connection until parent node changes their status to active.

