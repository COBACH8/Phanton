---
title: Test Ad Block - Toolz
source: https://d3ward.github.io/toolz/adblock
author:
  - "[[Ursu Eduard Cornelius]]"
published: 
created: 2024-12-14
description: Looking for an easy way to check the efficiency of your ad blocker?Toolz offers a simple and beautiful design test that allows you to quickly and easily test the performance of current ad/content blocker solution. Intuitive interface makes it easy to navigate and use, and the beautiful design ensures that the experience is visually appealing. With just a click, you can see how well the ad blocker is working and make any necessary adjustments.
tags:
  - clippings
---
Total : 135 133 blocked 2 not blocked

**The test may not work as expected with some browser/blocker combinations.  
To ensure a smooth experience, please check the compatibility list before testing.  
  
I ask that you please refrain from reporting them directly to the browser or adblock solution provider.  
Instead, I encourage you to report problems directly to the Toolz project issues  
**

[Create issue on Toolz](https://github.com/d3ward/toolz/issues/new/choose)

#####   Cosmetic Filter

Why Cosmetic Filter test fails?

If a cosmetic filter test fails, it simply means that the specific website being tested (in this case d3ward.github.io) isn't included in any of adblock's rules or lists.  
It's important to note that this does not mean that cosmetic filtering fails on all websites.  
You can confirm this by visiting a popular, ad-rich site where you're unlikely to see any ad boxes.  
The purpose of this test is to assess the functionality of the blocking feature, not to determine its scope or coverage. By adding the following rules to your adblock solution, you may be able to solve the problem:

```
d3ward.github.io##.adbox.banner_ads.adsbox
d3ward.github.io##.textads
```

**Adding these rules could lead to a successful test result proving your adblock solution have that feature of blocking with cosmetic filters**

#####   Ad Scripts Loading

Why Ad Script Loading test fails??

Same as the cosmetic tests. If an ad script load test fails, it usually means that the specific website being tested isn't covered by any of adblock's rules or lists, especially for blocking ad-related scripts like my fake `ads.js`  
However, this error doesn't indicate a general failure of ad script blocking on all websites.  
To check, you can visit a popular website known for its abundance of ads scripts.  
Chances are that you won't encounter any blocked ad scripts. It's important to understand that this test is designed to evaluate the functionality of ad script blocking, not its scope or effectiveness. To potentially fix the problem, consider adding the following rules to your adblock solution:

```
/pagead.js$domain=d3ward.github.io
/widget/ads.
```

**Adding these rules could lead to a successful test result proving your adblock solution have that feature of blocking script loading**

---

#####   Ads

Amazon

analyticsengine.s3.amazonaws.com

analytics.s3.amazonaws.com

advice-ads.s3.amazonaws.com

Doubleclick.net

mediavisor.doubleclick.net

 Google Ads

pagead2.googlesyndication.com

pagead2.googleadservices.com

afs.googlesyndication.com

#####   Analytics

 Google Analytics

click.googleanalytics.com

FreshWorks

claritybt.freshmarketer.com

fwtracks.freshmarketer.com

#####   Error Trackers

#####   Mix

 Yahoo

analytics.query.yahoo.com

 Unity

auction.unityads.unity3d.com

webview.unityads.unity3d.com

config.unityads.unity3d.com

adserver.unityads.unity3d.com

#####   OEMs

Realme

bdapi-ads.realmemobile.com

bdapi-in-ads.realmemobile.com

 Apple

books-analytics-events.apple.com

weather-analytics-events.apple.com

notes-analytics-events.apple.com

 Xiaomi

data.mistat.india.xiaomi.com

data.mistat.rus.xiaomi.com

sdkconfig.ad.intl.xiaomi.com

 Huawei

metrics2.data.hicloud.com

 Samsung

analytics-api.samsunghealthcn.com