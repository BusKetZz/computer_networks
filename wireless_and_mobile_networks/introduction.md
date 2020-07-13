# Introduction



## Wireless network basic components

* **Wireless host** - typical end-device, on which apps run (e.g. laptop,
    tablet, smartphone or desktop computer).
* **Wireless communication link** - depending on used technology, wireless
    links may differ in context of range and speed. Its main task is to connect
    end-devices or other network peripherals (e.g. routers, switches).
* **Base station** - a key element of wireless network infrastructure, which is
    responsible of data (i.e. packets) transmission and reception between base 
    station and connected end-devices (i.e. wireless hosts).
* **Network infrastructure** - generally bigger network to which wireless hosts
    are connected.



## General classification of wireless networks

At the most general level wireless networks can be classified based on two
criteria:

1. Are packets transmitted via exactly one _hop point_ or many of them?
2. Does network have an _infrastructure_ (e.g. does it have a base station)?

According to above mentioned criteria, one can distinguish four basic
categories:

* **Single-hop infrastructure networks** - these networks consist of base
    station connected to bigger wired network (e.g. to the internet). Also
    whole communication between base station and wireless host takes one hop
    in wireless channel. 802.11 and 4G LTE networks belong to this category.

* **Single-hop networks without infrastructure** - in this type of networks,
    there is a lack of base station connected to the wired network.
    Bluetooth and 802.11 (ad-hoc mode) networks belong to this category.

* **Multi-hop infrastructure networks** - in these networks base station is
    connected to the bigger network and some of the end-devices must transmit
    their data via other devices (so called nodes) to be able to communicate
    with whole network through base station. Most of the sensor wireless
    networks and wireless mesh networks belong to this category.

* **Multi-hop networks without infrastructure** - there is lack of base station
    and nodes must transfer their data via other hosts to be able to deliver
    information to the target. Examples of these networks are MANET and VANET.

