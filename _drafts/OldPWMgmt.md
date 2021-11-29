---
layout: post
title: "Passwords"
description:
tags: Drafts Wordbench localhost-archives
---

Password Management is a pain point for almost every user who has to input a password. Ideally, you shouldn't know any of your own passwords. That sounds like a bold claim for the uninitiated, but it’s about as secure as a password can get. I have hundreds of passwords, all nearly 20 characters of randomly generated text, and I don't know a single one of them.

We accomplish this with a piece of software called a Password Manager. With a Password Manager you only need to memorize one password for the rest of your life. The Password Manager will handle the rest. Most Password Managers have standalone Desktop/Mobile Apps, as well as a browser Plugin. In the following example, we'll use a privacy respecting social media service like Mastodon as an example of how a Password Manager handles Passwords.

When you sign up for Mastodon, it will ask you to create a Password. Instead of trying to think of a password yourself which will probably be the same password you use for other services, your Password Manager will generate and store a password for you. You can set the complexity and requirements since different sites have different complexity requirements. From that point forward, instead of typing a Password into the Password field, you will consult your Password Manager and it will fill in the passwords for you. The only password you ever need to know, is the password that unlocks your Password Manager. If you've already setup a Mastodon account, then your Password Manager will ask to remember your Password. You can log in as normal, and change the password to one that your Password Manager has generated for you.

A good Password Manager will be FOSS and have Strong Encryption. There are a few that meet these requirements, but none do this as easily and conveniently as [BitWarden](https://bitwarden.com/) You can access the [Firefox Add-On Here](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/), and the [Chrome Add-On here.](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)

But, you’ll still need to setup a strong password to protect your Password Manager, so how do we do that? Some experts recommend the Dice Method. However, I’m personally not a fan of this method, as it relies on public wordlists. Instead, I would recommend that you pick words that are not going to be found next to each other in a dictionary or sentence. The most famous example of this comes from [XKCD](https://www.xkcd.com/936/), where the author generates the password: “Correct Horse Battery Staple.” Another good way is to think of your favorite passage from a book, or a sentence from a favorite movie. Don't think of your Password Manager's password as a password; instead think of a "Passphrase."
