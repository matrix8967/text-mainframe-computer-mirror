---
layout: post
title:  "Networking_101"
description: TCP OR UDP!?
tags: init-1
---


# Layer_01: Physical
## I'm so sorry gender studies classes...

### Ethernet
The basic building block of networking resides in the physical equipment.

One of the most important - and varied parts of most networking equipment comes down to the physical media and network interfaces.

Let's start with a familiar ~~foe~~ connection - an "Ethernet Jack."

The connector type of most Male Ethernet jacks is an `RJ-45` connector type. It's a natural evolution of the `Plain Old Telephone System` (`POTS`) connector `RJ-11`.

Depending on your age, you maybe equally familiar with both, however it's been quite a while since the old `RJ11` connector type is used. I only bring it up to marry the evolution of Analog Telephony to Modern Networking, as they're directly related.

Almost all modern Ethernet Equipment is capable of speeds of `1gbps` - One _Gigabit_ per second. This is attainable by the cabling that our connectors are attaching. The CAT-5e standard introduced in 2004 allows speeds of 1gbps, and limited `PoE`. (Power Over Ethernet.)

Cat-6 allows for `1gbps` - but with greater `PoE` capabilities, as well as some other Quality of Life benefits. Most infrastructure run in the past 10-years will hopefully be at least CAT-6 or some variant.

Cat-6 has a maximum run-length of 300 yards.

Cat-7 is a standard _largely_ passed over in the US since it doesn't use a traditional RJ-45 Jack.

Cat-8 is a standard becoming more popular, and sees the return of our familiar RJ-45 that we know and love, while allowing speeds up to 10gbps.

However - at present time - the bandwidth, and cost are still too high for most day-to-day applications. Especially considereing the ease that multiple 1gbps interfaces can be bonded together to act as a single `Xgbps` redundant interface through the use of Link Aggregation. Usually for `10gbps+` speeds, the networking world is still leaning on Fiber Optics.

### Fiber
Fiber is where things start to get interersting, and where we start to separate the ~~boys from the men~~ Prosumer from the Enterprise.

While Fiber-To-The-Home is become more prevalent, we'll be focusing on traditional Enterprise Fiber Connectivity, and mainly focus on fiber connections using `LC` Lucent Connections, although there are _MANY_ different connections for Fiber.

Fiber Cabling can span from less than a meter, to hundreds of kilometers depending on the type of cabling, connectors, and network gear used on each node.

### Switches, Routers, Gateways, Modems, etc.

So what the fuck does all this connect to? What does it all connect?

Computational Power has finally started to reach a point where highly efficient computers can combine all the roles of a network into a single device called a `Gateway`. The Gateway will handle the functions of what used to be multiple devices:

* Router
* Modem
* Wireless Access Point


