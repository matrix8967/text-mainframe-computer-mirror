---

layout: post
title:  "Securi-Tea: Drivethru Digital Street Smarts."
description: Be nobody in 30 minutes or less!
tags: Securi-tea NetSec Encryption-101 human-after-all

---

# Skwad Goalz!

## The problem: Click-Bait-And-Switch

The internet is rife with arm-chair advice on all matter of subjects. This is no different. _However_, I'm often frustrated by click-bait-and-switch articles that promise some kind of forbidden knowledge, only to discover the "article" or "tutorial" is just some advertisement.

It's just an advertisement with extra steps. 🤦️

These "articles" are often purposefully vague and full of jargon. It's arm-chair-psychology to inflate the _mystique_ of the subject matter, while painting the author as an authority. All while providing no _actionable_ information to help readers achieve their own goals.

## My Word-Salad Bar:

It's not lost on me this post is a _tome_ and probably as interesting as stereo instructions. Think of it as a _desk reference_ rather than a NatGeo article.

I'm going to lay out some quick-and-dirty things I do to customize my web browsers and tools I use to navigate the internet while minimizing my digital footprint.

I want to preface this by saying: _These are the things I do, based on years of testing, tweaking, failure, success, and introspection about HOW I use the internet._ 

It should be used as an example for readers to begin thinking about and developing their _own_ 7-layer-bean-dip of customizations, based on their needs.

---

## Beginner's Luck

A common mistake I seek to remedy here for people beginning their journey into taking their "digital-health" more seriously looks like this:

 1. Read a really good tutorial/article from a professional that gets your noggin' joggin'.
 2. Immediately follow that tutorial with reckless abandon.
 3. Something important breaks. Probably at the worst moment. Probably at work. Feelings get hurt. You get embarrassed.
 4. "Fuck it, this shit doesn't work. It's hopeless." (This is usually followed up with something like: "They've got my data anyway. What's the point.")
 5. Your wounded pride and ego-brain heal themselves with thoughts of Privacy Nihilism. (i.e. "This is stupid anyway, they already have my data. What's the point...")

---

So what happened? A bad habit even old pro's can be guilty of: _Shoot first; never ask questions._ Great for Han Solo. Bad for mission critical systems.

## Legal Disclaimer and Sage Wisdom

Don't make changes whole sale. Changing a lot of settings you don't fully understand *will* break your shit. You're in control of your own journey here. I'm not responsible if you break something, leading to a chain of events that turns you into The Joker.

Don't make any changes you don't understand. Don't make any changes you can't undo. Don't make more than one change at a time. And don't make more changes until you've thoroughly tested your previous change to verify it doesn't break any of your day-to-day or mission-critical services you need to do your job or something.

Sponsored by: A lot of mistakes.

Some ~~bad~~ IT Departments could argue these customizations are an attempt to bypass corporate firewalls or some other banal corporate violation of your employment agreement.

I've only ever seen this used as a technicality to indict an employee on more serious charges. But it's a good example of why you should always _understand_ the changes you're making before you make them. My time in the corporate world taught me boredom can turn people into animals.

Now that I'm legally in the clear...let's get started fucking around with your most vital tools you use on a daily basis to access the internet!

---

# Mozilla Firefox

We'll be leaning _HEAVILY_ into the Mozilla Firefox Ecosystem here for simplicities sake.

[Mozilla](https://www.mozilla.org/en-US/) (the non-profit that builds Firefox) offers *A LOT* of tools for free with their account service. They also provide a *ton* a excellent documentation and knowledge all for the public good and the health of the Internet.

* [Mozilla Developer Docs](https://developer.mozilla.org/en-US/docs/Learn)
* [Mozilla Security Tips](https://monitor.firefox.com/security-tips)
* [Mozilla - "How Hackers Work"](https://monitor.firefox.com/security-tips#how-hackers-work)
* [Mozilla's Yearly Internet Health Report](https://internethealthreport.org)



## Firefox Multi-Account Containers:

Multi-Account Containers allow you to Isolate and Jail off individual browser tabs from one another. This will stop advertisers and trackers from following you around the internet.

You can set up filters so that certain sites *only* open up in isolated tabs.

* [Link to the Addon.](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)

This also has benefits for Developers and other Tech-Savvy users who may need to be logged into multiple accounts at the same time, while maintaining separation between "church and state."

## Browser Add-ons:

Here's my list of Firefox Add-Ons I install first thing after installing Firefox.

* [Bitwarden.](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
* [UBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
* [Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
* [HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
* [Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
* [ClearURLS](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
* [DDG Firefox](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-for-firefox)
* [Mullvad Firefox](https://mullvad.net/en/download/firefox)

The list of plugins for Chrome and it's variants is here, sans the Mozilla Exclusive plugins:

* [Bitwarden.](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)
* [UBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
* [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
* [Decentraleyes](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
* [DDG Chrome](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg)
* [Privacy Badger](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)

-----

# Brave

[Brave](https://brave.com/) is an alternative to Google Chrome that's built on the same technology. It focuses on being more secure and privacy friendly, while still allowing you to be integrated into the Google Chrome ecosystem.

It has other interesting features, like allowing _vetted and approved_ advertisements in exchange for Crypto - But I'll be honest, I've never really used it.

Any chrome extension should translate over to working in Brave without issue.

-----

# Browser Agnostic Enhancements:

## Your passwords are terrible. Stop using them.

It's not your fault. Passwords are computing's _Original Sin._

It's an authentication mechanism as old as written history. Whoever said "Open Sesame!" never could have imagined _The Internet_.

Now _EVERY_ door must be opened with a different incantation.

If you choose to lock all your doors with "OpenSesame123" - you may as well just consider anything behind those doors public information.

So...what's the solution? Setup a Password Manager.

I use Bitwarden, but there are others like 1Password, KeepassXC, and Mozilla's Lockwise.

No matter which Password Manager you choose, the idea is the same:

* Download the App(s) and Browser Extensions for your Password Manager.
* Login using a _new_ and _secure_ password. If done correctly, this should be the last password you'll ever need. Make it a good one.
* Once you're logged in, your Password Manager will generate _random_ and _secure_ password for *ALL* your services, as well as remember them and handle logging in for you.

Ignorance is bliss.

If you want to check if an email address or password has been compromised, you can check using [this website](https://haveibeenpwned.com/). Note that once your password manager is setup, it will handle this for you.

**More on this later. Bonus points for finding the draft I've been working on.**

## Ad Blocker(s)

Using a good AdBlocker is a near-effortless step towards a better _digital diet_. If we think so much about what we put in our bodies, we should also think about what we put in our brains and where it comes from.

_MOST_ internet Ads are 'pay-per-click.' Meaning the ad creator holds a financial incentivize to get clicks. _This is not inherently a bad thing..._ But I choose to not even allow the opportunity for an Internet Ad to load on the page. It isn't a negotiation.

`uBlock Origin` is a great AdBlocker for your browser, and has a ton of features. Using it's `eyedropper` tool to get around websites fullscreen element paywalls is one use. You can add custom filters for blocking other annoying things on the web.

If you're wanting to take things to the next level for you and/or your family, the [Pi-hole Project](https://pi-hole.net/) is a great project you can use to take back control of what 3rd party advertisers get to show you on your home network. It requires less than `$50` in parts, basic network and terminal skills, and teaches a lot of real world practices for how powerful enterprise networks handle traffic.

It's great for beginners and/or curious teenagers, and will (inevitably) teach them important career soft-skills...Like communicating major infrastructure changes to users beforehand. 🙃️ Curiosity only _halfway_ killed the cat...

# Searching *wenk!* 🦆️

Lastly, changing your default search engine from `Google` (or `Bing` if ya _nasty_. 😏️) to `DuckDuckGo` is another great step towards increasing privacy *AANNDD* productivity.

I (personally) get *vastly* superior search results from `DDG` than I do from `Google`. _Especially_ for technical searches in my field of work.

[This Article I didn't read looks to validate my point](https://www.cnbc.com/2021/05/18/how-does-google-make-money-advertising-business-breakdown-.html) shows that `80%` of Google's profits come from Advertising. *NOT* from providing meaningful and relevant search results...Whoever pays the most becomes "king of the hill" for search terms, while what little remains of google's _actual_ search results take a backseat.

However, `DDG`'s [privacy first](https://duckduckgo.com/privacy) financial model goes above and beyond to prioritize user's privacy while also providing relevant, non-biased search results.

Their unwavering dedication to [openness](https://duckduckgo.com/traffic) and 

Can't find what you're looking for? `DDG` uses simple notation that can instantly search ~~hundreds~~ over 13,000 websites instantly and bring you directly to your results. You can read more [here.](https://duckduckgo.com/bang) This means that even if you don't find what you need by searching `DDG` - you're simply 2 keystrokes away from consulting another search engine or website for more accurate results. You get the added benefit of `DDG`'s attention to detail in User Privacy by their removal of various identifying information _before_ they process your search. Neat!

They also use a browser extension that helps you search, but also rates websites based on the sites privacy standards. I'll include it at the bottom with a list of other web extensions I use.

And like Mozilla, they provide lots of _great_ [documentation and tutorials](https://spreadprivacy.com/) for the good of the Internet and it's digital citizens. I have, and will continue to lean on it heavily. Great bathroom reading that'll get your noggin' joggin'.

## DuckDuckGo Email Protection

More validation that `DDG` is living right: They're currently [beta testing a new feature for protecting your email](https://www.spreadprivacy.com/introducing-email-protection-beta/), since the world still begrudgingly has to tolerate dealing with Email Technology.

There's _no way_ anyone is still reading anything by this point, and it's kind of a complicated concept for normies. `DDG`'s documentation is better than my trash.

# Conclusions and a ToDo list for some things:

> "If I had more time, I'd have written a short [post.]"
>  - Blaise Pascal
>> [And lots of other people.](https://quoteinvestigator.com/2012/04/28/shorter-letter/)

*WHEW* That was a fucking _grimoire_. I wrote the bones of this for a coworker at my last job, and I've been needing to expand and organize it for quite a while. In the past few weeks, I've needed to _copypasta_ some of these things to friends and family, so I hurried this final draft out the door.

# TO DO:

```
* Dissect longer sections into dedicated posts.
* Clean up the messy, redundant, and unclear language.
* Firefox about:config customizations & Profiles.
* Add visuals to break up the walls of text. (gifs, screenshots, screencaptures, etc.)
* Details about Email / Firefox Relay.
```

Thanks for coming to my TedTalk.
