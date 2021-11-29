---
layout: post
title: "2FA Scraps"
description:
tags: Drafts Wordbench localhost-archives
---


# Password Management

Quick Note - I completely wiped this page out and am starting fresh with less "wall of text" and more quick and actionable items. Still under construction... 6-14-19.

## The Short Summary:

There are many password managers out there, but we'll be using Bitwarden in this example. Bitwarden has an excellent free-tier, but is also a minimal expense for the service that it provides. You can also host it on your own server, if you'd rather not trust Bitwarden's own infrastructure. It has a stand alone application, or is compatible with Firefox and Chrome based web browsers.

1.) Bitwarden is a [FOSS](Terms) Password Manager. It will generate and store long and complex passwords for each of your online accounts.

2.) When a service is breached, only that unique password will be burned, and it will not allow access to your other online accounts.

## Choosing a Master Password.

### DO:

-   Think of a passphrase, instead of a password. There's no upper limit on characters, so a favorite quote from a book, movie, or game is great.
-   **Example:** "_The ships hung in the sky in much the same way that bricks don't._"
-   Use words that would not appear next to each other in a dictionary. (1Password can generate these for you.)
-   **Example:** _modesty-variant-malice-carven_
-   Use complex and interesting characters. (Brackets, Backticks, Pipes, ASCII, Unicode, and Emojis.)
-   **Example:** " (つ•̀ᴥ•́)つ:･ﾟ✧ \|V\| @G\|CAL"

### DON'T:

-   Use any of the examples above without chaging them. :)

-   Use a password you've ever used before. New Year; New You.

-   Use any dates of any format.

-   Use names of any kind.

## Links

-   [BitWarden App](https://bitwarden.com/)
-   [Firefox Add-On](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
-   [Chrome Add-On here.](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)

* * *

# Password Manament:

What does a good password look like? The best passwords make it look like a cat took an hour nap on your keyboard. For example:`zy>iHt-OXkc[mTk]OX/V_P:O=b2^Z]L]` is a great password. But it's next to impossible to remember. Even if you could remember it, if it ever became compromised, then it would have to be considered public knowledge. So what's the point in memorizing passwords?

There's not one. Memorizing Passwords is a flawed way to access an account for quite a few reasons:

-   Computers can guess any combination of dictionary words in a matter of seconds, no matter how clever you belive you're mutating them.

-   The responsibility to create unique and complex passwords falls upon users.

-   To help with memorization, many users will write down their password in what they imagine is a safe place. "Security by Obscurity" is not really anykind of security at all.

* * *

Password Management is a pain point for almost every user who has to input a password. Ideally, you shouldn't know any of your own passwords. That sounds likea bold claim for the uninitiated, but it’s about as secure as a password can get. I have hundreds of passwords, all nearly 20 characters of randomly generatedtext, and I don't know a single one of them.

We accomplish this with a piece of software called a Password Manager. With a Password Manager you only need to memorize one password for the rest of your life. The Password Manager will handle the rest. Most Password Managers have standalone Desktop/Mobile Apps, as well as a browser Plugin. In the following example, we'll use a privacy respecting social media service like Mastodon as an example of how a Password Manager handles Passwords.

When you sign up for Mastodon, it will ask you to create a Password. Instead of trying to think of a password yourself which will probably be the same password you use for other services, your Password Manager will generate and store a password for you. You can set the complexity and requirements since different sites have different complexity requirements. From that point forward, instead of typing a Password into the Password field, you will consult your Password Manager and it will fill in the passwords for you. The only password you ever need to know, is the password that unlocks your Password Manager. If you've already setup a Mastodon account, then your Password Manager will ask to remember your Password. You can log in as normal, and change the password to one that your Password Manager has generated for you.

A good Password Manager will be FOSS and have Strong Encryption. There are a few that meet these requirements, but none do this as easily and conveniently as [BitWarden](https://bitwarden.com/) You can access the [Firefox Add-On Here](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/), and the [Chrome Add-On here.](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)

But, you’ll still need to setup a strong password to protect your Password Manager, so how do we do that? Some experts recommend the Dice Method. However, I’mpersonally not a fan of this method, as it relies on public wordlists. Instead, I would recommend that you pick words that are not going to be found next to each other in a dictionary or sentence. The most famous example of this comes from [XKCD](https://www.xkcd.com/936/), where the author generates the password: “Correct Horse Battery Staple.” Another good way is to think of your favorite passage from a book, or a sentence from a favorite movie. Don't think of your Password Manager's password as a password; instead think of a "Passphrase."
