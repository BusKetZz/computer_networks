# Bluetooth and Zigbee



## Bluetooth (IEEE 802.15.1)

Key features:

* **Range**: short
* **Power**: low
* **Energy consumption**: low
* **Band**: 2.4 GHz (unlicensed)
* **Transfer speed**: 4 Mb/s (max)

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



## Zigbee (IEEE 802.15.4)

Key features:

* **Power**: lower than Bluetooth
* **Energy consumption**: lower than Bluetooth
* **Transfer speed**: 20, 40, 100, 250 kb/s (depending upon channel frequency)

It may be counterintuitive: "what is the point to use even weaker than
Blutetooth kind of network?"... The answer is simple, there is no always need
for high power and long range networks. Temperature or light sensors do not
require such high capacity to transfer their data, they are simple, cheap and
low-power devices spending their time mostly in a sleep mode. That is why,
Zigbee standard is great for them.

Zigbee networks consist of one fully functional device (similar to parent in
Bluetooth) and many devices with limited functionality (similar to subdevices
in Bluetooth). Fully functional device plays the leader role and controls many
subdevices.

Group of fully functional devices may create a *mesh network*, which enables
them transfer of data frames with each other.

