---
layout: post
title: "Linux-Distros"
description:
tags: Drafts Wordbench localhost-archives
---

# Linux

## Has your Operating System been installed _for_ you, or _upon_ you?

Linux is one of the most essential and versatile tools in your FOSS arsenal. From the humble $5 dollar [Raspberry Pi Zero](https://shop.pimoroni.com/products/raspberry-pi-zero), all the way to [100% of the top 500 super computers](https://itsfoss.com/linux-runs-top-supercomputers/) in the world; Linux is the software that runs it all. This also includes the majority of Smart Phones, Smart Devices, Embedded Systems, Appliances, and Web Servers you interact with on a daily basis.

But let’s start with an obvious question: What is Linux? Like Windows or MacOS, Linux is an Operating System. However, unlike Windows or MacOS, Linux is built for freedom, and openness. It’s Ability to be forked, rewritten, and redistributed as a new Linux Distribution (or Distro) forges it’s strength and flexibility.

This strength is also it’s weakness, as it can lead to another question that maybe overwhelming for new comers: “Which Linux Distro do I use?”

I’m going to go over a few Recommended Distros, and a few to avoid, and I will do my best to provide an unbiased and quick review of these, so that you may choose.

# For Beginners:

## If you're just taking your first steps into Software Freedom and Linux, this is a great place to start. Linux for kids!

### _**Ubuntu**_

Perhaps the most popular Distribution for the Desktop/Laptop use case, this operating system is made an maintained by Cannonical. It’s stability and ease of use make it a great introduction for new comers, and a reliable tool for seasoned vets. Ubuntu has been the subject of fair criticism for some of it’s privacy practices, but is still a welcome alternative to the adware of Windows 10, and walled garden of MacOS. These issues are also easily removed from the OS. With it’s longtime thriving community, and wide swath of support, this is the best Distro for beginners. [Get Ubuntu Here.](https://www.ubuntu.com/desktop)

### _**Pop_OS!**_

Pop_OS! started as another Ubuntu Dirivitive but quickly came into it’s own by adding many “sane defaults” and usability features. These "small" creature comforts make a world of difference for users coming from OSX or Windows. Many Linux Elitests look down on Distros like Pop_OS! (and others in this beginners section) but underestimate the value that a good UX (User Experience) can bring to the table. Since Pop_OS! is backed by System_76, a leader in Linux Hardware and software distribution, stability is rock solid. [Get Pop_OS! Here.](https://system76.com/pop)

### _**Linux Mint**_

A fork of Ubuntu, Linux Mint is a widely popular Linux Distribution catering to new users. While it doesn't have the wide array of support as it's upstream parent Ubuntu, it's a fully realized distribution that will make new users feel at home. [Get Linux Mint Here.](https://linuxmint.com/)

### _**Manjaro**_

A new and rising star in the Linux world, Manjaro combines the hardened software ecosystem of Arch Linux with the ease-of-use of Ubuntu. While this Distro is considered to be a new kid on the block, it’s forked from Arch, which has one of the most in depth (and THICK) Wiki’s that many Linux Users look to for guidance. Although it’s technical documentation maybe overwhelming to some new comers. This is why it’s listed in Intermediate, instead of Beginner. Also: User Beware -- many Arch users are a...proud, and vocal community with a tradition of trial by fire. [Get Manjaro Here.](https://manjaro.org/)

# For Intermediate:

## If you have some Linux experience and are looking to broaden your horizons, consider these distributions:

### _**Fedora**_

Fedora is maintained by RedHat Inc. which is one of the oldest and biggest names in the Linux Community. A fortune 100 Company, RedHat distributes it’s own enterprise grade operating systems for servers, mainframes, and everything in between. Fedora is a much more humble Linux Distro, lending itself to more home and small business use cases. The out of box experience is a bit lacking, but with a robust ecosystem of extensions for it’s desktop, it can be customized to look right as rain in just a few minutes. [Get Fedora Here.](https://getfedora.org/)

### _**Debian**_

Debian is the root of many MANY of the Linux operating systems we know today, including Ubuntu. What it lacks in out of box experience, it makes up for in flexibility, and security. I can't underscore Debian's role in the Linux Community. [Get Debian Here.](https://www.debian.org/)

# For Advanced users:

## If you’re here, and you’re considering these Distros, you’re probably just seeking the validation of them making it to the list, under the advanced category...

Void Linux, AntergOS, Linux From Scratch, Arch. You know who you are. You know where to get them.

# For Tin Foil Hat users:

## These Distros are not for the faint of heart. They do however, provide some of the best security and privacy available on an OS today.

### _**Tails**_

An Acronym for The Amnesiac Incognito Live System, Tails is a Debian based Linux OS that is only meant to be ran from a “live USB.” Which is to say, you’re only to install the Distro to a USB Drive, where it will not interact with the data already stored on the machine, and will forget any changes made after a reboot. It comes cram-jammed packed with Privacy Tools such as Tor. [Get Tails Here.](https://tails.boum.org/)

### _**PureOS**_

PureOS is a Linux Distro made and maintained by Purism. Purism also makes some of the most Secure Laptops money can buy, focusing on Open Source hardware and Software and are used by some of the most advanced data assurance agencies. At the time of this writing, they’re main focus is on the Purism Phone, which will have hardware kill switches for Mic, GPS, and Cameras, and use their custom Linux Distro. PureOS itself however, leaves a lot to be desired in terms of compatibility and usability. [Get PureOS Here.](https://puri.sm/)

### _**Qubes-OS**_

Much like Tails, Qubes-OS is mean to be run as a "live instance." Unlike Tails and other Live Boot OS's, Qubes-OS runs all applications in their own sandboxed container called a "Qube." This is to say if you opened an application like a web browser, it would actually be running inside of a micro-operating system of it's own. That way any malware or viruses would only be able to cause harm to a temporary sandbox, and not to the actual host operating system. [Get Qubes-OS Here.](https://www.qubes-os.org/)

## _**For Chromebook Users**_

### _**GalliumOS**_

GalliumOS makes the list for giving you the satisfaction of taking your privacy back from Google. Gallium OS is built to work specifically on Chromebook Hardware, effectively giving you a cheap and efficient Linux Laptop. It sips system resources, and has an active development community. While Install Instructions can be a bit to chew on, once you’re free of Google’s All Seeing Eye, you can enjoy the satisfaction of taking your freedom back from Big Brother. This is a very specific, and worthy OS. [Get GalliumOS Here.](https://galliumos.org/)

# Notes

### A Note on Ubuntu

In 2013 [Ubuntu won a Big Brother Award](https://www.omgubuntu.co.uk/2013/10/ubuntu-wins-big-brother-austria-privacy-award), for having their search function parter with Amazon Search to bring shopping results and ads from to the Dashboard. Eventually this was defaulted to "off" and eventually removed, the Amazon app remains in the basic install and should be removed.

As of the upcoming release of Ubuntu 18.04 on April 26, 2018, Ubuntu's installer will [prompt the user](https://fossbytes.com/ubuntu-data-collection/) to collect anonymous usage data. While this can be turned off, it begs the question if it should even be there at all. The data will be able to be viewed by the user before it is sent. Once sent, the data will be made publicly available.

Despite this, I still believe it is a great alternative to Windows and MacOS.

### A Note on Linux Mint

Linux Mint has some issues for users who maybe in between the Beginner and Intermediate stages. A [nasty hack in 2016](https://blog.linuxmint.com/?p=2994) comes to mind, as well as some of the following points. For users who are new to Linux, I encourage you to shop around and find the distro that you feel most comfortable using. But I'd be remiss if I didn't mentions some of Mint's policies I don't exactly agree with.

-   One stand out "feature" is that security updates are optional.

    (I'm sure there are those of you who see this as a great feature due to how awful Windows updates are. Rest assured, Linux updates are nowhere near as intrusive, painful, and sadistic as Windows Updates.)

-   Mint uses inconsistent package names, which conflict with packages from the Distro it was originally forked from. They often black list these packages, which is bad practice.

-   Mint also doesn't publish CVE's of security exploits, leading to a weaker, and more exposed code base for exploitation.

[Home](./)
