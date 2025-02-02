---
title: "yokoffing/Betterfox: Firefox user.js for speed, privacy, and security. Your favorite browser, but better."
source: "https://github.com/yokoffing/Betterfox"
author:
  - "[[GitHub]]"
published:
created: 2025-02-02
description: "Firefox user.js for speed, privacy, and security. Your favorite browser, but better. - yokoffing/Betterfox"
tags:
  - "clippings"
---
[![GitHub Maintained](https://camo.githubusercontent.com/8dcb8fa5cc5ad8dd3e6df8db669063693e6ea9d545ce113c867ce1665b2d25bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6f70656e253230736f757263652d7965732d6f72616e6765)](https://camo.githubusercontent.com/8dcb8fa5cc5ad8dd3e6df8db669063693e6ea9d545ce113c867ce1665b2d25bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6f70656e253230736f757263652d7965732d6f72616e6765) [![GitHub Maintained](https://camo.githubusercontent.com/96a400ea0e2bf1be5658a45d639d8600495422fc1362fe380dac74e6b38dd9b8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61696e7461696e65642d7965732d79656c6c6f77)](https://camo.githubusercontent.com/96a400ea0e2bf1be5658a45d639d8600495422fc1362fe380dac74e6b38dd9b8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61696e7461696e65642d7965732d79656c6c6f77) [![Visitors](https://camo.githubusercontent.com/38015ae3e63bfc1c3e2da8b26e2fc3b677f74847c97314891a8d72b114133123/68747470733a2f2f686974732e736565796f756661726d2e636f6d2f6170692f636f756e742f696e63722f62616467652e7376673f75726c3d68747470732533412532462532466769746875622e636f6d253246796f6b6f6666696e672532464265747465722d466f7826636f756e745f62673d253233373943383344267469746c655f62673d2532333535353535352669636f6e3d2669636f6e5f636f6c6f723d253233453745374537267469746c653d76697369746f727326656467655f666c61743d66616c7365)](https://hits.seeyoufarm.com/)

## Betterfox

[about:config](https://support.mozilla.org/en-US/kb/about-config-editor-firefox) tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).

31% [faster](https://medium.com/@mihirgrand/comparing-popular-firefox-forks-6fa83fdfdaad#:~:text=31%25%20more%20than%20vanilla%20Firefox) than regular Firefox 🚀

Now with support for ESR [128](https://github.com/yokoffing/Betterfox/tree/esr128) 🆕

## Required reading

0. Create a [backup profile](https://github.com/yokoffing/Betterfox/wiki/Backup).
1. Download the user.js file [here](https://raw.githubusercontent.com/yokoffing/Betterfox/main/user.js) (Right click > `Save Link As…`).
2. Review [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and make any necessary changes.
- See also [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) for other recommendations.
3. Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
4. For the profile you want to use (or use default), click **Open Folder** in the **Root Directory** section.
5. Move the `user.js` file into the folder.

*After restarting Firefox:*

1. Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with our [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2. Enable **DNS-level protection** with [NextDNS](https://nextdns.io/?from=xujj63g5). <sup><i>Use the link and support this page!</i></sup>
- Check out our configuration [guide](https://github.com/yokoffing/NextDNS-Config) for the best experience.
- See how to [quickly enable](https://support.mozilla.org/en-US/kb/dns-over-https) **secure DNS** in Firefox.

## Made for everyday browsing

**A secure, blazing fast browsing experience. Without breakage.**

Betterfox is an opinionated preference list inspired by the [law of diminishing returns](https://miro.medium.com/v2/resize:fit:1206/1*lcOcxriV_II_lZuXQYLoXg.jpeg) and the [minimum effective dose](https://medium.com/the-mission/less-is-more-the-minimum-effective-dose-e6d56625931e).

## Simple goals

1. **Minimalism:** get what isn't needed out of the way
2. **Efficiency:** unleash Firefox's ability to be fast and performant
3. **Privacy:** protect your data without causing site breakage

## Simple configs

`Fastfox`, `Securefox`, `Peskyfox`, and `Smoothfox` are guides to settings within Firefox.

The `user.js` — a configuration file that controls Firefox settings — is curated from these guides.

| List | Description |
| --- | --- |
| [Fastfox](https://github.com/yokoffing/Betterfox/blob/main/Fastfox.js) | Increase Firefox's browsing speed. Give Chrome a run for its money! |
| [Securefox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js) | Protect user data without causing site breakage. |
| [Peskyfox](https://github.com/yokoffing/Betterfox/blob/main/Peskyfox.js) | Provide a clean, distraction-free browsing experience. |
| [Smoothfox](https://github.com/yokoffing/Betterfox/blob/main/Smoothfox.js) | Get Edge-like smooth scrolling on your favorite browser — or choose something more your style. |
| [user.js](https://github.com/yokoffing/Betterfox/blob/main/user.js) | All the essentials. None of the breakage. This is your `user.js`. |

## Recognition

### Browser Integration

Important

While the browsers listed below incorporate Betterfox to some extent, they often modify it in ways that reduce its effectiveness. For optimal results, apply the `user.js` file even when using Firefox forks.

- [Zen](https://github.com/zen-browser/desktop?tab=readme-ov-file) | [files](https://github.com/zen-browser/desktop/blob/main/src/browser/app/profile/better-fox.js) (July 2024)
- [Midori](https://github.com/goastian/midori-desktop/blob/ESR115/README.md) | [files](https://github.com/goastian/midori-desktop/blob/f3d8d96eb8e08f35a64e3c957bea4e839d7c7730/floorp/browser/components/userjsUtils.sys.mjs#L28-L33) (Dec 2023?)
- [Mercury](https://github.com/Alex313031/Mercury/releases/tag/v.115.3.0) | [files](https://github.com/Alex313031/Mercury/commit/eb9600f9fb8f48c8f5b5c6f3264fbcdb5caff7f5) (Sep 2023)
- [Waterfox](https://www.waterfox.net/en-US/docs/releases/G6.0/) | [files](https://github.com/WaterfoxCo/Waterfox/tree/current/waterfox/browser/app/profile) (Sep 2023)
- [Floorp](https://github.com/Floorp-Projects/Floorp#-betterfox) <sup><a href="https://github.com/Floorp-Projects/Floorp/issues/233#issuecomment-1543557167" data-hovercard-type="issue" data-hovercard-url="/Floorp-Projects/Floorp/issues/233/hovercard" class="rgh-seen-34153418431">1</a> <a href="https://blog.ablaze.one/3135/2023-04-01/" rel="nofollow">2</a></sup> | [files](https://github.com/Floorp-Projects/Floorp/blob/ESR115/floorp/browser/components/preferences/userjs.inc.xhtml) (Apr 2023)
- [Pulse](https://github.com/pulse-browser/browser#%EF%B8%8F-credits) | [files](https://github.com/pulse-browser/browser/tree/alpha/src/browser/app/profile) (Dec 2021)
- [Ghostery Private Browser](https://github.com/ghostery/user-agent-desktop#community) <sup><a href="https://web.archive.org/web/20210509171835/https://www.ghostery.com/ghostery-dawn-update-more/" rel="nofollow">1</a> <a href="https://web.archive.org/web/20210921114333/https://www.ghostery.com/ghostery-dawn-product-update/" rel="nofollow">2</a></sup> | [files](https://github.com/ghostery/user-agent-desktop/tree/main/brands/ghostery/branding/pref) (Feb 2021)

### YouTube

- [Ditch Chrome for One Of These BETTER BROWSERS!](https://youtu.be/ygkxFc8SZlc?si=m5NQe-b_oFXs5crb&t=230) (Aug 2024)
- [The ULTIMATE Browser Tier List](https://youtu.be/j5r6jFE8gic?t=560) (Mar 2023)
- [I Hate Firefox. But I'm Still Switching Back to It.](https://youtu.be/w0SJFED5xK0?t=220) (Nov 2022)
- \[Español\] [Optimize and Accelerate Firefox](https://www.youtube.com/watch?v=3XtoONmq5_Q) (Nov 2022)
- [How To Improve Firefox Performance](https://www.youtube.com/watch?v=N8IOJiOFVEk) (Dec 2021)

### Podcasts

- \[Italian\] [Digitalia.fm](https://digitalia.fm/684/) | 1:41:35–1:42:41 (July 2023)
- [GhoSTORIES with Franz & Pete](https://anchor.fm/ghostories/episodes/S2E6-We-Talking-Ghostery-Dawn----Again-er0q02/a-a4o5vmh) | 17:05–18:40 (Feb 2021)

### Articles

- [Browsers for Daily Use](https://anhkhoakz.neocities.org/blog/browsers-for-daily-using/#firefox-but-hardened) (Jan 2024)
- [Avoiding Manifest V3 – Escaping the Ad-Pocalypse](https://www.xbitlabs.com/avoiding-manifest-v3/) (Dec 2023)
- \[German\] [Pulse Browser Review: Firefox fork with Turbo tweaks and Opera sidebar](https://www.computerbild.de/artikel/cb-Tipps-Software-Pulse-Browser-Review-ein-Firefox-Fork-mit-Seitenleiste-wie-bei-Opera-35644139.html#:~:text=Noch%20mehr%20Speed%2DFeatures) (Apr 2023)
- [2023 Browser Showdown: Comparing Chrome, Brave, Firefox, Vivaldi, and Opera](https://www.appdate.lk/technology/2023-browser-showdown/) (Jan 2023)

### Guides

- [FMHY Browser Tools: Privacy Tweaks](https://www.reddit.com/r/FREEMEDIAHECKYEAH/wiki/storage/#wiki_privacy_based_browsers)
- [Firefox-UI-Fix](https://github.com/black7375/Firefox-UI-Fix/wiki/Tips#privacy)
- [Narsil/desktop\_user.js](https://git.nixnet.services/Narsil/desktop_user.js#thanks)
- [pyllyukko/user.js](https://github.com/pyllyukko/user.js) [comparator](https://jm42.github.io/compare-user.js/)

### Reviews

- “I use this one ... The performance is absolutely amazing. There’s definitely a huge difference when it comes to loading sites.” - [DIRIKtv](https://youtu.be/N8IOJiOFVEk?t=16)
- "BetterFox ... will provide good-enough privacy and help with performance." - [Qdoit12Super](https://old.reddit.com/r/browsers/comments/139h4my/suggestion_for_finding_3_good_privacy_focus/jj3n3qn/?context=2)
- "...drastically changed the experience with Firefox for me. Improved speed, security, smoothness, and removed clutter." - [AppDate](https://www.appdate.lk/technology/2023-browser-showdown/#:~:text=Used%20the%20BetterFox%20user%20config%20settings%20with%20some%20overrides%20which%20drastically%20changed%20the%20experience)
- "Firefox with uBlock Origin extension and tuned with Betterfox is faster than Safari." - [cugeloid](https://elephas.app/blog/best-browsers-mac#what-is-the-best-browser-for-mac-according-to-redditandnbsp)
- "I don't think I could use Firefox without Betterfox." - [Professional\_Fun4616](https://old.reddit.com/r/nextdns/comments/15y815f/the_people_behind_betterfox_have_this_awesome/jxb7cir/?context=3)
- "The best collection of tweaks available." - [AuRiMaS](https://old.reddit.com/r/MozillaFirefox/comments/15cc1vk/about_changes_in_aboutconfig/jtyx910/?context=3)
- "FF is now much snappier!" - [whotheff](https://old.reddit.com/r/firefox/comments/z5auzi/firefox_not_properly_usingrecognizing_gpu_poor/iy36hyz/)
- "...the experience is so good now I don’t think I’ll go back to any of the chromium based browsers." - [Mr\_Compromise](https://old.reddit.com/r/pcmasterrace/comments/zwioe1/what_browser_will_you_be_using_in_2023_please/j1wmbxo/)

## Support

If you like the project, leave a ⭐ (top right) and become a [stargazer](https://github.com/yokoffing/Betterfox/stargazers)!

[![Stargazers repo roster for @yokoffing/Betterfox](https://camo.githubusercontent.com/4636c575036d8562c362158db0ab756451993820ba1cf6a9fd9a2f143ef96847/68747470733a2f2f7265706f726f737465722e636f6d2f73746172732f6461726b2f796f6b6f6666696e672f426574746572666f78)](https://github.com/yokoffing/Betterfox/stargazers)

[![Buy Me a Coffee at ko-fi.com](https://camo.githubusercontent.com/12752e6ba8f4fcfcdcef03ecb0827601a3c605a92b9d8cc1025447728259ca39/68747470733a2f2f73746f726167652e6b6f2d66692e636f6d2f63646e2f6b6f6669322e706e673f763d33)](https://ko-fi.com/Q5Q5G8EPH) [![Donate using Liberapay](https://camo.githubusercontent.com/086b694e3435ed6a9aa49e896ce866c7a49c97e101f331792aba5ed42d9429ca/68747470733a2f2f6c69626572617061792e636f6d2f6173736574732f776964676574732f646f6e6174652e737667)](https://liberapay.com/yokoffing/donate)

## Credit

- Betterfox mirrors the ongoing work provided by [arkenfox](https://github.com/arkenfox/user.js). Additionally, this repository includes content reproduced or adapted from other sources. Credit for overlapping material goes to the original authors.
- Appreciation goes to the [Firefox](https://www.mozilla.org/en-US/firefox/new/) team and developers working on [Bugzilla](https://bugzilla.mozilla.org/home), fighting for the open web.
- Thanks to [Denperidge](https://github.com/Denperidge) for adding [`install.py`](https://github.com/yokoffing/Betterfox/blob/main/install.py) for advanced users in v.131.
- A special thanks to [Alex Kontos](https://github.com/MrAlex94) of [Waterfox](https://github.com/WaterfoxCo/Waterfox) for his collaboration in v.116.
- Many thanks to the 2021 [Ghostery](https://github.com/ghostery) team for testing Betterfox at scale in its early days.

[![Free Website Counter](https://camo.githubusercontent.com/85a297b87167e3d5753d0790341b1480def9d5310c1df04f6c45e53650a6dc82/68747470733a2f2f7777772e77656273697465636f756e746572667265652e636f6d2f632e7068703f643d392669643d313936353326733d31)](https://www.websitecounterfree.com/)  
since 23 July 2022