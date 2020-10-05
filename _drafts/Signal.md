---
layout: post
title: "Securi-Tea: Opsec for Normies Part O1 - Signal/Noise"
description: A crash course in digital street smartz.
tags: NetSec Comms How2 Securi-tea
---

## A Lust Letter to the 4th amendment...

Ya know...

_Maybe_ it's my middle-class-liberal-white-guilt... or _Maybe_ it's watching the US devolve into a store-brand Orwellian nightmare...

But it just seems like right now is a great time to jot down my `secret sauce` for how to communicate on the ol' `Information Super Highway` in a post-Snowden world.

## Quick disclaimer...

This is my recipe for the 5-layer beandip of `OpSec` I've tailored for my daily life.

This isn't a fool-proof way to make sure you're untracable online. Like all tools - these are not inherintly good or evil. They're used to create, and used to destroy.

These are the things I consider when selecting a communcations platform:
  
>  tl;dr -	
-   End-to-End Encryption [^1]
?
-   Verifiable Trust. [^2]
?
-   Zero Knowledge. [^3]
?
-   Open Source. [^4]


## Signal / Noise

Step #1: 
* Use  [Signal.](https://signal.org/)

Signal isn't just a messaging application, it's an open protocol that's used by other encrypted messengers like `whatsapp`. However, `whatsapp` is owned by Facebook, and it's painfully obvious why you don't want The Zuck to be in control of your communication.

Other apps like Telegram are fine enough for most use cases, however Telegram's backend hasn't been evaluated to the extent that `Signal` has been. So there maybe security vulnerabilities being exploited that aren't known yet. This will probably get better with time. It also has less secure defaults - and *most* people hardly ever change defaults.

At the time of writing - `Signal` is the center of the venn-diagram of "Usable, Secure, Private, and verifiable." Each Signal user can verify each other with a unique signature, and if the signature changes, users are alerted.

You can read about what happens when Signal is required to hand over user data to the US Government in [this article](https://signal.org/blog/looking-back-as-the-world-moves-forward/) which shows how Signal protects your privacy. 

*Spoiler Alert* - Signal hands over the info -- which is nothing. Because that's all the info they allow themselves to have.

-----

[^1]: Messages/Content are encrypted on your device before it's ever transmitted.

[^2]: You're able to confirm the ID of the other party's device (usually from a unique signature.)

[^3]: The communication platform is verifiably unable to view the message contents, or breach user data.

[^4]: The code is open and available for you or anyone to view, test, and modify.
