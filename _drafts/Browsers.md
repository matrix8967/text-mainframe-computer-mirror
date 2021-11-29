---
layout: post
title: "Communication"
description: Voice on the Wire.
tags: Drafts Wordbench localhost-archives
---

# Web Browsers:

Since the modern world orbits around browsing the web, I suspect this page will be the most viewed. I mean, how else are you reading this?

There are three browsers with Security and Privacy at the forefront of their focus: Firefox, Brave and TOR. **Most** of you have heard of Firefox. **Some** of you have heard of TOR.  Brave is a new browser from the former Mozilla (creators of Firefox) CEO. Firefox and Brave are great day-to-day browsers with a wide array of usability and privacy control. All three browsers have their strengths and weaknesses. I’ve used both Firefox and Brave as ‘daily drivers’ and have plenty of experience with them. TOR probably provides the most protection depending on a LOT of factors (which we'll go over) but at the cost of usability.

So, let’s jump in feet first. Don your Internet Condoms!

* * *

# Firefox

The Firefox section got big enough to warrant it's own page. It's a deep dive, but as it stands right now, while not perfect, it's the browser that I'd throw my weight in with. [Firefox Page is here.](Firefox)

* * *

# Brave

Brave is the new kid on the block in the browser space, and it’s already making quite a name for itself before it’s left Beta. I've updated this writing to reflect Brave's new and disappointing choice to join the leagues of other Chromium Based browsers. However, it’s a _very_ robust browser with password managers like Bitwarden built in. Built in Ad Blocking, and Script Blocking ensure brave is worth it’s (very light) weight in the Privacy Advocate’s field kit.  [Be Brave Here.](https://www.brave.com)

Unlike Firefox, Brave doesn't have as many settings to choose from, and it is still in Beta. However, I'd recommend you click through some of it's settings and explore it's privacy rich feature set. And if you installed Firefox and modded it out as described below, it'll be useful to have another browser around to test sites against in case a site doesn't play well with a modded Firefox.

* * *

# TOR

[TOR]\(<https://en.wikipedia.org/wiki/Tor_(anonymity_network>) is an acronym for "The Onion Router" which is a reference to the browser's encryption technology. Anytime you've heard the buzzword "DarkWeb" that is a reference to TOR Hidden Services, which will not be discussed here.

When you use TOR to navigate to <https://protonmail.com/> TOR will send it's traffic through different paths on it's way to the destination site. Each stop along the way will decrypt a different part of the request. The only part of this process that can see what sites you're visiting is the "Exit Node" which is the machine that hands off the final request to the destination site. Essentially it's the exit of the encrypted tunnel where you go back to relying on plain web encryption and privacy techniques we've discussed above.

## Caveats

TOR was originally developed by the US Naval Research Center, and is used the world over to protect anonymity and secure communication. TOR is FOSS, and very secure, however The Onion Routing protocol is maintained by volunteers, and could be deanonymized by the owner of an exit node. If you use TOR to navigate to a site, and then login to that site, those credentials will pass back and forth through the exit node and could be used to identify you. TOR also relies on an outdated version of Firefox, which could be exploited if you browse some of the afformentioned TOR Hidden Services. Three Letter Government Agencies have been known to specifically pursue TOR users through programs like [XKeyScore](https://en.wikipedia.org/wiki/XKeyscore) and many sites will have the TOR protocol blacklisted. TOR can also be deanonymized very simply in rural areas, where there are not many outgoing connections to TOR Nodes. So, if you live in a rural area, TOR would probably do more to make you stand out, than anonymize you.

I'm assuming I've lost most people by this point, so I'll summarize with this: TOR is secure, but you will need to reorder your typical browsing habits and rely on more security.  As an exercise in freedom, I recommend everyone download it. [Get TOR Here.](https://www.torproject.org/) It's of note, that TOR often is considered a firable offense at many jobs for violating the Terms of Service with your employer in regard to bypassing Internet restrictions.

...ya know. Just like an Onion...
