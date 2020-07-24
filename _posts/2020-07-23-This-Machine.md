---
layout: post
title:  "This Machine"
description: Nazi lives don't matter.
tags: hardware
---

![RedWheelbarrow](../../../assets/images/RWB/RWB01.jpg)

# This Machine Kills Fascists.

[This Machine](https://en.wikipedia.org/wiki/This_machine_kills_fascists) shows a marked correction back to foundational strengths in the systems I build.

It's a purpose built design that zeroes in on CPU and GPU performance.

As always, this build enjoys a new set efficiencies over any of my previous systems:

* 100% Linux. No more dual-booting into an adware ridden shithole for games.
* No SATA allowed - ride or die for NVMe m.2.
* No Moving Parts (Except Fans.)
* All Fans are now PWM / Thermal Scaled a Fan Curve.
* A Fully Modular PSU.
* A smaller form factor case for the Mid-ATX size category.
* Re-Enforced PCIE Slots so I don't have to improv fixes for [gpu-sagging.](../../../assets/images/RWB/gpusag.jpeg)

(I know this shit is long af, idk how I'm gonna organize it all yet. Still working on it. Sorry for typos don't `@` me.)

# Ship of Theseus.

Something that made this much easier was replacing components slowly over time, rather than all at once. This not only eased the financial burden - it helped free me to choose the _right_ hardware for the job. It does involve research and staying on top of the trends for the direction hardware is heading so it can be a trade-off in time if you're not subscribed to `Obscure Hardware Trends Weekly`.

![Glitch](../../../assets/images/Glitch/Glitch.jpg)

In 2019, I began to rethink some of the choices I'd made ~~in life~~ for my hardware. The `tldr` is: I adopted some new methods in how I designed my systems. Some of these worked out well - some of them did not.

### What's in the box!?

NZXT's H510 Case seemed too good to be true on paper. Especially for it's modest price point (~$70USD.) However this case exceeds at almost every turn.

I'd seen this case show up in a million "Battlestation" Threads in forums - but nobody explicitly drew attention to it. For such a striking appearance, very little is usually said.

Every piece of this case has a simple and well performing function. It's a few cubic inches smaller than my previous case(s). Without a doubt the space it occupies is maximized in purpose.

If I *had* to complain - I would say the build-quality of the metal feels a _little_ cheap. But Flint still doesn't have clean drinking water, and Nazi's are back so I'm not sure if I'll return it yet. 🤔

### Huge Fan

Noctua are the cadillac of the airflow / static pressure fan game, and there's just no way to say something like that without coming off as an insufferable fucking prick.

The price was hard to swallow at first, but went down easier with more research. 6-year manufacturer warranty for bearing replacements is worth it on it's own. I'm not even sure I've had a fan last that long? 120mm case fans are a universal truth now so these should last quite a few miles.

### What's cooler than being cool?

![cooler](../../../assets/images/RWB/cooler.jpg)

Moving on with thermals: I went back to Air Cooling from the Closed Loop Liquid Cooler used in the previous design. It didn't have any problems, and performance was consistently 👌. However, I like to plan things to fail intelligently and gracefully, so when considering "...Not IF it fails, but WHEN it fails" air cooling seemed to be a better direction.

I've always avoided the term `Water Cooling` in favor of `Liquid Cooling`. Fluids in these systems are a *thermally-conductive* mineral oil that isn't *electrically-conductive.* ~~If~~ When a hose or seal leaks - this helps to minimize damage.

However, this is still what experts call _"pretty fuckin' bad"_ and I would rather move these issues to less mission critical systems. I'll likely revisit liquid cooling in the future.

### _WHOOSH_

The CPU Cooler consists of a [large metal heatsink](../../../assets/images/RWB/finland.jpg) with two fans configured in a "push/pull" arrangement. The heatsink is [*firmly*](../../../assets/images/RWB/screwd.jpeg) attached to the CPU with tension mounting.

A layer of [thermal paste](../../../assets/images/RWB/compounding.jpg) conducts heat away from the die of the CPU, and distributes it through the surface area of the heatsink.

Two fans pull cool air into the case from the front, pushing it towards the GPU and CPU. The fan on the front of the heatsink pulls that cool air and pushes it through the fins of the heatsink. The fan on the other side "pulls" the hot air through and sends it towards a rear exhaust fan. A 4th case fan is mounted to the top of the case, pulling ambient heat out.

[Sorta like this.](../../../assets/images/RWB/whoosh.png)

### PSU, RAM, NVME M.2, SATA, SSDs, ALL, CAPS, ACRONYMS.

I've removed my "Cold Storage" 7200 RPM Disk Drives - as well as pressed on into the future to remove SATA SSDs. *Yoinked* this idea from a friend while looking over the final draft of hardware. I'm always ready to chow down on some humble pie, so I wanted to make public a spectacle of eating my fuckin' words I guess.

Here I am, looking like a _horse's ass_, with all my spinning Disk Drives in a NAS _like an idiot._

### Download more RAM

32GB of Corsair RAM OC'd to `3600MHz` leaves 2 DIMM slots unoccupied. This helps thermals and allows for easy future upgrades. I may move from Corsair Vengeance RAM back to my _first love_: GSkill RipJaws. RipJaws Heat Spreaders are shaped to be less intrusive to larger CPU Heatsinks.

### Gas me tf up

A fully modular 750W PSU is house cleaning and making the most of my space. This also opens up options for custom length cables later on.

### Mama Bear ʕっ•ᴥ•ʔっ

ASUS TUF X570 was chosen considering AMD's vague language and _less than forthcoming_ marketing about compatibility with new Gen 3 Ryzen CPUs.

This was the most feature rich Motherboard with the `X570` Chipset which should be pretty tolerant moving forward. I'm hoping to dig into an Audio Issue in the Linux Kernel LTS affecting this chipset's Audio.

### "A deal at twice the price!" -Faust

AMD Radeon 5700XT GPU is an attention-commanding center piece here.

This is the component I spent the most time thinking about. The reasons for choosing this GPU have carried on in my mind since before I began planning the 2017 build. Budgets, timing, many other factors played into me being gun-shy. After 3 years of back-and-forth I decided to shoot my shot. The specific variant of this card was chosen due to it's aggressive thermal performance compared to other models of the same card.

I would be liar if I said the aggressive design wasn't also a contributing factor.

I'm a slave to appearances.

### Big Brain Time

Finally we land at the CPU - an AMD Ryzen 2700X. This was the first component that kick-started the full rebuild.

On paper this was a modest spec-bump compared to the 1700X it was replacing. But prices bottomed the absolute fuck out and this fixes some early-adoption kinks in my 1700X.

Planning Ahead was already paying off since I was able to use it as a direct drop-in replacement.

An 8-core, 16 thread fucking _beef bus_ for well under $300 bones. What a muther honking value dude.

# The Zen Art of Hardware Maintenance

While I was finishing the cable management I stopped to reflect how this reignited a passion that I worried might have been lost. I was able to do something I've not been able to do in a long time: `I was able to slow down.` I could consider the *best* ways to approach problems. I was able to experiment, measure, and re-evaluate.

I'd forgotten what it was like to _enjoy_ this kind of work. I had started to doubt myself as an engineer. But I found a long-forgotten peace in the small acts of routing cables, cinching zip ties, and tightening screws.

I got lost in vacuum of muted reflection as I thought about heat, airflow, and tension.

I rediscovered my _mind of metal and wheels_.

I realized how each of these machines I've built were time capsules showing who I was when I made them.

I remembered how I'd spent a _lifetime_ ignoring time and making sure that things were done _once_ and were done _right_. Time is the only constant in the known universe. It is unyielding and relentless. It makes fools of us all. So I asked myself: "Why am I in such a fucking hurry?"

I've received plenty of (genuine) constructive criticism about my work not adhering to a manufactured deadline. During one of these reviews, I was told something that really re-framed how I approach problems:

> "You should have been a watch maker."

--