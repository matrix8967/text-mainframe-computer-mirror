---
layout: post
title:  "This Machine"
description: This LAN is your LAN...
tags: desktop hardware
---

![RedWheelbarrow](../../../assets/images/RWB/RWB01.jpg)

# This Machine Kills Fascists.

[This Machine](https://en.wikipedia.org/wiki/This_machine_kills_fascists) is a return to my "Confidence is Quiet" roots.

It's a machine that's not trying _so hard_ to show it's sophistication.

As always, this build enjoys a new set efficiencies over any of my previous systems:

* 100% Linux. No more dual-booting into an adware shithole for games.
* No SATA allowed - ride or die for NVMe m.2.
* No Moving Parts (Except Fans.)
* All Fans are now PWM / Thermal Scaled on a Fan Curve.
* Re-Enforced PCIE Slots so I don't have to improv fixes for [gpu-sagging.](../../../assets/images/RWB/gpusag.jpeg)

I'll post about the software later, but here's a [snack.](../../../assets/images/RWB/shellbie.png)

# Ship of Theseus.

Something that made this much easier was replacing components slowly over time, rather than all at once. This not only eased the financial burden - it helped free me to choose the _right_ hardware for the job. It does involve research and staying on top of the trends for the direction hardware is heading so it can be a trade-off in time if you're not subscribed to `Obscure Hardware Trends Weekly`.

![Glitch](../../../assets/images/Glitch/Glitch.jpg)

In 2019, I began to rethink some of the choices I'd made ~~in life~~ for my hardware. The `tldr` is: I adopted some new methods in how I designed my systems. Some of these worked out well - some of them did not.

### What's in the box!?

NZXT's H510 Case seemed too good to be true on paper. Especially for it's modest price point (~$70USD.) However this case exceeds at almost every turn.

I'd seen this case show up in a million "Battlestation" Threads - but nobody explicitly drew attention to it. For such a striking appearance, very little is usually said. The utter failure of my previous corsair case was a huge drive to nail down some of the final components of this build.

Every piece of this case has a simple and well performing function. It's a few cubic inches smaller than my previous case(s). Without a doubt the space it occupies is maximized in purpose.

If I *had* to complain - I would say the build-quality of the metal feels a _little_ cheap. But Flint still doesn't have clean drinking water, and Nazi's are back so I'm not sure if I'll return it yet. 🤔

### Huge Fan

Noctua are the cadillac of the airflow / static pressure fan game, and there's just _no way_ to say something like that without coming off as an insufferable fucking prick.

The price was hard to swallow at first, but went down easier with more research. 6-year manufacturer warranty for bearing replacements is worth it on it's own. I'm not even sure I've had a fan last that long? 120mm case fans are a universal truth now so these should last quite a few miles.

### What's cooler than being cool?

![cooler](../../../assets/images/RWB/cooler.jpg)

Moving on with thermals: I went back to Air Cooling from the Closed Loop Liquid Cooler used in the previous design. It didn't have any problems, and performance was consistently 👌. However, I like to plan things to fail intelligently and gracefully, so when considering "...Not IF it fails, but WHEN it fails" air cooling seemed to be a better direction.

I've always avoided the term `Water Cooling` in favor of `Liquid Cooling`. Fluids in these systems are a *thermally-conductive* mineral oil that isn't *electrically-conductive.* ~~If~~ When a hose or seal leaks - this helps to minimize damage.

However, this is still what experts call _"pretty fuckin' bad"_ and I would rather move these issues to less mission critical systems. I'll likely revisit liquid cooling in the future.

### _WHOOSH_

The CPU Cooler consists of a [large metal heatsink](../../../assets/images/RWB/finland.jpg) with two fans configured in a "push/pull" arrangement. The heatsink is 👌 [*firmly*](../../../assets/images/RWB/screwd.jpeg) attached to the CPU by tension mounting.

A layer of [thermal paste](../../../assets/images/RWB/compounding.jpg) conducts heat away from the die of the CPU, and uses the 6 large heat pipes to distribute the heat throughout surface area of the layered fins.

[Cool air is pulled from the front,](../../../assets/images/RWB/whoosh.png) through the fins of the heatsink, where it's exhausted out of the back.

###### More like whoosh

The name of the game is to move heat *away* from the CPU and get it out of the case. For the first time every fan in the entire system is working on a "Fan Curve" which is to say each fan (even PSU, GPU Fans) speed is dependent on temperature. Idle temps mean the case and CPU fans lumber alone at leisurely `>400rpm` rate, while GPU and PSU fans don't engage at all.

Maybe confidence is a little _too_ quiet here, as I've actually had a hard time sleeping without the steady hum of case fans to occupy my lizard brain...

### No SATA? How could you be _so controversial yet so brave_?

I've removed my "Cold Storage" 7200 RPM Disk Drives. I've also pressed on into the future to remove SATA SSDs. ~~I promise I'll come back for you.~~

While looking over a friend's final draft for hardware, they'd opted for this approach. I was _vehimetly_ critical. Then I realized it was a good idea and I was wrong. I'm not sure how I'll ever recover.

Here I am, looking like a _horse's ass_, with all my Disk Drives in a NAS _like a fucking animal._

A `tldr` for `m.2 NVMe` - storage devices slot straight into the motherboard and use the faster `PCIe` bus, instead of the usual `SATA` bus. It's a very honest name. Not great. But at least it's specific. Here's a really blown out [shitty picture](../../../assets/images/RWB/nvme.jpeg) of my OS Drive.

### Download more RAM

32GB of Corsair RAM OC'd to `3600MHz` leaves 2 DIMM slots unoccupied. This helps thermals and allows for easy future upgrades. I may move from Corsair Vengeance RAM back to my _first love_: GSkill RipJaws as their Heat Spreaders are shaped to be less intrusive to larger CPU Heatsinks.

### Gas me tf up

A _fully_ modular 750W PSU is more house cleaning and making the most of my space. This also opens up options for custom length cables later on.

### Mama Bear ʕっ•ᴥ•ʔっ

ASUS TUF X570 was chosen considering AMD's vague language and [less than forthcoming](../../../assets/images/RWB/chipset.png) marketing about compatibility with new Gen 3 Ryzen CPUs.

This was the most feature rich Motherboard with the `X570` Chipset which should be pretty tolerant moving forward. I'm hoping to dig into an Audio Issue in the Linux Kernel LTS affecting this chipset's Audio.

### "A deal at twice the price!" -Faust

![gpu](../../../assets/images/RWB/the_debbil.jpg)


AMD Radeon 5700XT GPU is an attention-commanding center piece here.

This is the component I spent the most time wallowing about. The reasons for choosing this GPU have carried on in my mind since before I began planning the 2017 build. Budgets, timing, and the bitcoin boom kept me on my Nvidia GTX 1080. After 3 years of back-and-forth I decided to shoot my shot. The specific variant of this card was chosen due to it's aggressive thermal performance compared to other models of the same card.

I would be liar if I said the aggressive design wasn't also a contributing factor.

I'm a slave to appearances.

But the primary draw was to remove myself from Nvidia's Closed Source Prop drivers and reward one of AMD's biggest engineering strides: Pushing their Linux Graphics Drivers directly into the Linux Kernel - ensuring all linux distros booting a modern kernel will have full GPU support out of the box.

### Big Brain Time

![cpu](../../../assets/images/RWB/cpu_glam.jpg)

Finally we land at the CPU - an AMD Ryzen 2700X. This was the first component that kick-started the full rebuild almost a year ago.

On paper this was a modest spec-bump to the 1700X it replaced. But prices bottomed the absolute fuck out and this fixed some early-adoption kinks found in 1st Gen Ryzen chips.

Planning ahead was already paying off as I was able to use it as a direct drop-in replacement.

An 8-core, 16 thread fucking _beef bus_ for well under $300 bones. What a muther honking value dude.

