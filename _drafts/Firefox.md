---
layout: post
title: "Firefox Guide"
description:
tags: Drafts Wordbench localhost-archives
---

# Firefox

Tried and True, Firefox offers the most reliability and support between the two browsers. With Mozilla at the helm, Firefox has led a long and successful life and is the greatest competitor to Google Chrome. Firefox has a vast and deep ecosystem of Addons, and a wide array of privacy tools and settings to protect you and your data. Here, I will go through my workflow of setting up and securing a brand new Firefox install. This will be faster and easier if you have Firefox installed, and are looking at this page in that browser, as I will provide hotlinks to addons and settings. [Get Firefox Here.](https://www.mozilla.org/en-US/firefox/new/)

## About:Preferences

Let's go over some settings. I'm going to be talking my way from top to bottom over each menu of Firefox 63's preferences.

In the URL bar at the top of the page (Where you would normally type a web address, like <https://www.startpage.com> ) type

`about:preferences`

### _General_

-   **Play DRM-controlled content** -- _Uncheck this._

-   **Performance** -- _Uncheck "Use Recommended performance settings..."_

### _Home_

-   **New Windows and Tabs** -- Set this to [DuckDuckGo](https://www.DuckDuckGo.com).

-   **Recommended by Pocket** -- _Uncheck this._

    -   **Sponsored Stories** -- _Uncheck this_

-   **Highlights** -- _Uncheck this._

    -   **Visited Pages** -- _Uncheck this._

    -   **Bookmarks** -- _Uncheck this._

    -   **Most Recent Download** -- _Uncheck this._

    -   **Pages Saved to Pocket** -- _Uncheck this._

-   **Snippets** -- _Uncheck this._

### _Search_

-   **Default Search** -- _DuckDuckGo_

-   **Show search suggestions ahead of browsing history in address bar results** -- _Uncheck this._

-   **One-Click Search Engines.** -- _Uncheck Bing, Amazon, Twitter, and eBay_

### _Privacy & Security_

-   **Content Blocking** - Check Custom and block

    -   Trackers in all windows.

    -   All third-party cookies.

    -   Cryptominers

    -   Fingerprinters

-   **Always send Do Not Track.**

-   **Cookies and Site Data** - Recommended to delete cookies and site data when firefox is closed, but that's up to you. `¯\_(ツ)_/¯`

#### Logins and Passwords

-   **"Ask to save logins and passwords..."** -- _Uncheck this._

-   **"Use a Mast Password..."** -- Uncheck this.

-   [See the Passwords Page.](Passwords)

#### History

It's recommended to tell firefox to not remember history.

#### Permissions

### _Sync_

**Don't use this at all.**

## Addons

[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/ "uBlock Origin")

uBlock Origin is a fantastic, FOSS Ad Blocker for Firefox. And even in the rare occasion an add slips through, you can right click, and block it to create a filter. Great for anything on a site you wish to hide.

[Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/ "Privacy Badger")

Privacy Badger is an amazing browser plugin from the Electronic Frontier Foundation. It alerts you to, and blocks, 3rd part canvasing and content scrapers using behavior analysis instead of just maintaining an always-out-of-date list.

[HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/ "HTTPS Everywhere")

HTTPS Everywhere is another browser plugin from our friends at the EFF. It simply forces HTTP pages to load through HTTPS if available.

[DuckDuckGo For Firefox](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-for-firefox/ "DuckDuckGo for Firefox")

Our pals over at DuckDuckGo have released a very suitable browser application that can work great along side this existing ecosystem of browser Addons. It functions similarly to Privacy Badger. Privacy Badger is a bit more functional, but DuckDuckGo's plugin is more informative, as it lists privacy practices of sites.

[Bitwarden Password Manager](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/ "Bitwarden Password Manager")

We'll talk more about Bitwarden when we cover [Passwords, and Password Managers.](Passwords)

[Firefox Multi Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)

This Addon will secure accounts into "containers" which will allow you to login with multiple accounts without them interfering with each other. This is great for convenience of having your work email, and your personal email open in different tabs but it also has great privacy implications by ensuring sites don't follow you out the site. This is similar to Mozilla's Facebook Container, however the Facebook Container specifically targets Facebook. If you're reading this -- just delete your Facebook. If you're still using it, use the [Facebook Container.](https://addons.mozilla.org/en-US/firefox/addon/facebook-container/)

## Advanced Addons

### These Addons are not for the faint of heart.

[NoScript](https://addons.mozilla.org/en-US/firefox/addon/noscript/ "NoScript")

NoScript is a great browser plugin. NoScript will break the freaking crap out of any website you browse to, thus ensuring you're cruising cyberspace as protected as you can get. Jokes aside, NoScript will disable all scripts on a site, and only allow the scripts you choose to run. Much like uBlock Origin, you can right click to create a filter with ease. But it will make browsing a complete pain in the ass.

## About:Config

Similar to how we got to our preferences, we're going to type the following into a navigation bar:

`about:config`

Click "I accept the Risk!" without reading any of the warnings, because we're in too deep now to be frightened by voided warranties. (But for real, read and understand the risk.) The About:Config page is a huge list of properties and back-end settings for your browser. It's not the place to try to get trigger happy and explore the inner workings. There's a really nice search bar we're going to strictly adhere to. Copy and paste the following settings, and change their value's to what I've listed here by double clicking on them in the about:config page. (You can easily select the text by triple clicking it.)

`geo.enable`

_Double Click to set this to False._ Disables sites ability to use your location.

`dom.event.clipboardevents.enabled`

_Double Click to set this to False._ Disables sites ability to see or be notified that you've selected or copied text.

`dom.battery.enabled`

_Double Click to set this to False._ This Disables sites ability to read your battery status.

`network.IDN_show_punycode`

_Double Click to set this to True._ This prevents Unicode URL Spoofing.

`privacy.firstparty.isolate`

_Double Click to set this to True._ This does some magic with site cookies to isolate the cookie and prevent cross domain tracking. Note: This will sign you out of all currently logged in sessions.

`extensions.pocket.enabled`

_Double Click to set this to False._ This disables that sleazy pocket plugin. Mozilla bout pocket, and is really insistent people use it. I don't even know what it does really. Shoo. Go away.

`browser.send_pings`

_Double Click to set this to False._ This is useful for websites to track visitor clicks.

`browser.urlbar.speculativeConnect.enabled`

_Double Click to set this to False._ This will disable Firefox preloading URLs.

## Advanced `about:config` settings.

`privacy.resistFingerprinting`

_Double Click to set this to True._ This makes Firefox more resistant to Fingerprinting. Note: You might have to come back real quick and re-enable this on some sites that require fingerprinting to work. If some sites can't read your browser version, they'll throw warnings assuming you're on outdated software. However, this change does not require you to restart your browser, so you can come back to the page and click this off and on as you need. It shouldn't cause too many headaches though.

`browser.sessionstore.max_tabs_undo`

_Double Click to change value to 0._ Even when Firefox is set to not remember history, your previous tabs are able to be recalled for opening.

`media.navigator.enabled`

_Double Click to change to False_ This will disable sites ability to use your camera and microphone.

`network.cookie.lifetimePolicy`

0 = Accept cookies normally
1 = Prompt for each cookie
2 = Accept for current session only
3 = Accept for N days
