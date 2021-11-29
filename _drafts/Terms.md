---
layout: post
title: "Terms"
description: For when Merriam Webster isn't boring enough...
tags: Drafts Wordbench localhost-archives
---


# Terms

Let’s go over some terms real quick, of things you want to look for (in no particular order.)

## **Open Source**

Open Source software is software that exposes it’s code publicly. This has many benefits, which include potentially millions of unbiased eyes viewing the code and combing for bugs and security vulnerabilities. While closed source software usually only has a hand full of people who are paid to view the software in a more positive light; Open Source software exposes it’s code to the masses to forge more efficient and secure code.

----

## **Encryption**

Encryption is as old as secrets and privacy itself. A basic example of encryption would be Shift Value. Let’s start with a birds eye view example -- a Shift Value of 13 (this is what’s called a ROT 13 Algorithm.) If A=1, B=2, and C=3 then a shift value of 13 would move the letters down the alphabet by 13. This would result in A=14 B=15 and C=16.

H E L L O

⇅ ⇅ ⇅ ⇅ ⇅

U R Y Y B

This garbled output is referred to as “Cypher Text.” Since you and I both secretly know this is just a ROT13 Shift Value, we can easily communicate like this back and forth, without someone knowing what we’re saying. That knowledge would be our “Private Key” in this example. As the name suggests, it is to stay private.

----

## **End-to-End-Encryption**

Abbreviated E2EE, End to End encryption means that the data is encrypted locally, then sent through an encrypted tunnel to the destination, and is then decrypted locally on the recipients end. This is done with Public/Private Key Cryptography.

----

## **Zero Knowledge**

Zero Knowledge is exactly what it sounds like: Having Zero Knowledge of the information passing through the servers. There are many methods for this, but the idea is that the service provider has no access to the decryption keys to be able to see the user’s data. This is done so that Malicious Actors can hack, send warrants, or kick in all the doors they want; nothing will change the fact that the information is still encrypted and the service provider cannot decrypt it.

----

## **FOSS**

FOSS means Free and Open Source Software. Not just Open Source, but freely able to copy, distribute, and rewrite, usually under the GNU Public License.

----

## **Opt-In / Opt-Out**

Opt-In means that a setting or choice is *off* by default, and requires user action to enable it. It requires  the user to *opt-in*. Opt-Out means a choice has been made *for* the user, and a user must take it among themselves to opt-out of it.

----

## **Federated**

Federation is to say that not all of the data is stored in (or travels) the same location. So, if one server is compromised, nobody will be able to have all of the data.

----

## **Two Factor Authentication**

Also Abbreviated 2FA, this is a strong security practice that means you login with something you **know** and something you **have**. When you login with a password, the service will accept the password, and then send a text or email with a code to your phone. This is to say that a malicious actor would have to know your password, *and* be able to read your text messages....

However, this is not as hard as it would seem if you're not using a secure messaging service. The best option for this is a Timed One Time Password.

----

## **Timed One Time Password**

TOTP provides an incredible security benefit, and a small sacrifice to user experience. Like Two Factor Auth (and often times, these terms are interchanged) this relies on something you **know** and something you **have**. However, with TOTP, there's no risk of the code being stolen over text message or email. Instead the login codes are stored in a 2FA/TOTP app and are changed every 30 seconds. When you login, you'll have to open an app, and get the six digit code it requires to accept your password. Everytime you setup a 2FA/TOTP service, it will give you some failsafe burner codes to login with in case of a failure. Do *not* lose these.

----

[Page 2 - Choosing a Linux Distribution.](Linux-Distros)

[back](./)
