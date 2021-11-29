---
layout: post
title:  Putting "Server" in "Serverless"
description: The Devil of Convenience...
tags: Drafts Wordbench Development, Engineering
---

For the past few years, I've consistently had my hands slapped when conversations roll around to our always ballooning AWS bills.

People seemed _shocked_ that the benevolent Jeff Corp would spin a web of confusion as a way to nickle-and-dime developers. AWS Presents itself as the benevolent Ferryman on the digital River Styx.

I'll never understand people _willingly_ giving money to a company as malevolent *AND* mediocre as AWS. And to their credit - Jeff Corp has made billing as easy as it ever could be. No need to worry about usage hours, peak times, etc.

Just ask yourself: "What does `[some service]` cost in AWS?" And the answer will be the same no matter what Region, Availability Zone: `Unlimited Money.` Boom - done and dusted.

### Well - Self-hosting is Expensive...

It can be. Sure. Power, HVAC, Hardware, Networking... I've been working in Systems and Network Engineering for over 10 years. I still grimace when it comes time to pay the piper.

_However_ that same discomfort I feel about spending tons of money on hardware has plenty of benefits. It forces me to consider things I probably wouldn't have otherwise, since I'm signing _my name_ to something. It makes me take a second, third, as-many-as-it-takes look at things. What it costs now. What it costs in 3 years, 5 years, etc. It reminds me: "_Take only what you need._" Experience is what tells you where you can save money easily, and what not to haggle over - but like all things that comes with time and experience, and hopefully very few casualties.





-----

There's something to be said for the Freedom of AWS, and being able to spin up data-centers with a few commands. 1 Credit card, a keyboard, and an internet connection, and the benevolent Jeff Corp will be sure that _you too_ can have a datacenter to rival anything I've ever helped build.



When troubleshooting NFS, [Amazon's documentation casually mentions](https://docs.aws.amazon.com/efs/latest/ug/accessing-fs-nfs-permissions.html) one of the carnal sins of Unix File Permissions: `chmod 777`. Instead of conveying the severity of the security hole that the `777` permissions set creates, AWS carries on as if the issue is resolved, briefly mentioning this gives `rwx` permissions to anyone on the instance.
