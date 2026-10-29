---
title: Keep your Mac, iPhone, and apps updated
description: Why software updates are security fixes, how to turn on automatic updates on a Mac and an iPhone, and what to do if your Mac is too old to run a version of macOS that still gets security fixes.
---

# Keep your Mac, iPhone, and apps updated

!!! info "Last reviewed October 29, 2026"
    The macOS and iOS versions named below are current as of this date. Apple releases a new major version every September, so if you are reading this in late 2027 or later, the specific version names will have moved on, but the advice has not.

## The short version

Software updates are mostly security fixes. When Apple, Google, or any other company ships an update, it usually closes holes that attackers already know about, and in many cases are already using. The moment an update is published, the list of what it fixed is effectively public, and criminals start aiming at everyone who has not installed it yet. Apple puts it plainly on its own security page: keeping your software up to date is one of the most important things you can do to keep your Apple products secure.

So the job is simple. Turn on automatic updates on your Mac and your iPhone, turn on automatic updates for your apps, and restart your devices once in a while so the updates actually take effect. That takes about ten minutes, once.

The harder part of this guide is for people with older Macs. If your Mac is running an older version of macOS because it cannot run a newer one, or because you are worried a newer one will make it slower, read [the section on older Macs](#if-your-mac-is-old) carefully. That situation is the most common reason a "my computer is acting strange" ticket ends with the only real fix being a new computer.

## Step 1: Turn on automatic updates on your Mac

1. Click the Apple menu in the top-left corner of the screen and choose **System Settings**.
2. Click **General** in the sidebar, then click **Software Update**.
3. Click the small **ⓘ** (info) button next to **Automatic Updates**.
4. Turn on everything in the list: **Download new updates when available**, **Install macOS updates**, and **Install Security Responses and system files**. Click **Done**.

<!-- SCREENSHOT: System Settings > General > Software Update > Automatic Updates panel with all toggles on -->

If the Software Update screen shows that an update is waiting, install it now rather than waiting for the automatic schedule. Apple's instructions: [Software Update settings on Mac](https://support.apple.com/guide/mac-help/mchla7037245/mac){target=_blank}.

A note on the difference between the two kinds of update you will see there. A small update, one that changes the number after the dot, such as 26.7.1 to 26.7.2, is almost entirely security and bug fixes; install it every time, as soon as it appears. A major upgrade, one that changes the name and the first number, such as Tahoe 26 to Golden Gate 27, adds new features and is a bigger change; the [older Macs section](#if-your-mac-is-old) explains how to think about those.

## Step 2: Turn on automatic updates on your iPhone and iPad

1. Open **Settings**, tap **General**, then tap **Software Update**.
2. Tap **Automatic Updates**.
3. Turn on **Automatically Install** for iOS updates. With this on, your iPhone installs updates overnight while it is charging and on Wi-Fi, and tells you before it does.
4. On the same screen, make sure the setting for **System Files** (security responses) is also turned on.

If an update is waiting when you open Software Update, tap **Download and Install** now. Apple's instructions: [Update your iPhone or iPad](https://support.apple.com/en-us/118575){target=_blank}.

## Step 3: Keep your apps updated

**Apps from the App Store** update themselves once you turn this on. On a Mac, open the **App Store**, choose **App Store** from the menu bar, then **Settings**, and turn on **Automatic Updates**. Apple's instructions: [Use the App Store to update apps on Mac](https://support.apple.com/guide/app-store/fir9b01adda3){target=_blank}. On an iPhone, open **Settings**, tap **App Store**, and turn on **App Updates**.

**Apps you downloaded from a company's website**, such as Chrome, Firefox, Zoom, Microsoft Office, and most password managers, have their own built-in updaters. When one of them asks to update or restart, let it.

**Your web browser matters most of all**, because it is the program that touches the most untrusted material: every website, every ad, every link in every email. Safari is updated as part of macOS, so Step 1 covers it. Chrome updates itself in the background but only finishes when you restart it; if you see a **Relaunch** button or a colored dot at the top right of the Chrome window, click it. To check by hand, open Chrome, click the three-dot menu, choose **Help**, then **About Google Chrome**. Google's instructions: [Update Google Chrome](https://support.google.com/chrome/answer/95414){target=_blank}.

## Step 4: Restart once a week

Many updates download quietly but do not take effect until the device or the app restarts. A Mac that has not been restarted in two months, with a browser that has not been closed in two months, can be running old, vulnerable versions even with automatic updates turned on. Restart your Mac and your iPhone about once a week. Friday evening is a good habit.

When a dialog says an update is ready and offers **Remind Me Tomorrow** or **Try Tonight**, the safe answer is almost always **Try Tonight** or **Restart Now**. Clicking "Remind me later" a few dozen times in a row is the single most common reason a Mac with automatic updates turned on is still months out of date.

## If your Mac is old

This section is long because it is where the most harm happens, and because the decision involved is a real one, with a real cost, that deserves an honest explanation rather than a slogan.

### Find out what you have

Click the Apple menu and choose **About This Mac**. The window shows two things you need. The first is the name and version of macOS, for example "macOS Sequoia 15.8.2" ([Apple's guide](https://support.apple.com/en-us/109033){target=_blank}). The second is the line labeled either **Chip** or **Processor**: if it says Chip followed by a name like "Apple M1" or "Apple M3," your Mac has Apple silicon; if it says Processor followed by an Intel name, your Mac is Intel-based ([Apple's guide](https://support.apple.com/en-us/116943){target=_blank}). Write both down.

### Which versions of macOS are still being fixed

Apple publishes a list of every security update it releases: [Apple security releases](https://support.apple.com/en-us/100100){target=_blank}. As of Apple's most recent round of security fixes, on October 26, 2026, the versions of macOS that received them were:

1. **macOS 27 Golden Gate**, the current version, which runs only on Macs with Apple silicon.
2. **macOS 26 Tahoe**, the previous version, and the last one that will ever run on Intel Macs.
3. **macOS 15 Sequoia**, the version before that.

Nothing older received any fixes. If your Mac is running macOS 14 Sonoma, 13 Ventura, 12 Monterey, or anything earlier, it is no longer getting security fixes from Apple, and every hole discovered from here on stays open on your computer permanently.

There is a further catch even for the three versions on that list. Apple fixes the most problems, and the most serious ones first, in the current version. Older versions get some fixes, sometimes later and sometimes not at all, and security researchers have documented several cases where a vulnerability that attackers were actively using was fixed in the newest macOS weeks before, or instead of, the older ones. Running the newest version your Mac supports is the only way to get everything.

### The browser problem

Even if the operating system were not the issue, the web browser would be. Safari only gets updated as part of macOS, so an old macOS means an old Safari. Chrome is the usual workaround, but Google stopped updating Chrome for macOS 12 Monterey in July 2026 and now requires macOS 13 Ventura or newer ([Google's requirements page](https://support.google.com/chrome/a/answer/7100626){target=_blank}). In practice, a Mac on Monterey or older has no current, supported browser from either Apple or Google, which means every website you visit is being handled by software with known, unfixed security holes. Banks and other sensitive sites also begin refusing old browsers, so the problem tends to announce itself eventually in the least convenient way.

### "But a newer macOS will make my Mac slower"

This belief is not entirely wrong, and it deserves a straight answer rather than a dismissal.

A major macOS upgrade on an older Mac, especially an older Intel Mac, can make it feel somewhat slower. Some of that is temporary: for the first day or two after an upgrade, the Mac re-indexes everything on the disk for search and re-optimizes its apps, and it is noticeably sluggish while that happens. Leave it plugged in and on overnight once or twice and most of that goes away. Some of it is permanent: newer versions do ask more of the hardware, and a Mac that was modest when new will feel more modest on a newer system.

But that is not the actual choice in front of you. The choice is not between a fast Mac and a slow one. It is between a Mac that is a little slower and still receiving security fixes, and a Mac that feels familiar while quietly accumulating holes that will never be patched, behind a browser that is no longer maintained. An unpatched Mac does not stay the same; it becomes easier to compromise every month, and the first sign of trouble is usually not a slowdown but a pop-up you do not recognize, a browser that keeps redirecting to strange pages, or an email from your bank about activity you did not make. At that point the speed question is moot, because the fix is the same one you were avoiding, done under worse conditions.

### What to do, depending on what you found

**If your Mac has Apple silicon** (it says Chip), update to macOS 27 Golden Gate using Software Update. Every Apple silicon Mac ever made can run it.

**If your Mac is Intel and can run macOS 26 Tahoe**, update to Tahoe if you have not already. You will keep getting security fixes for now, but Tahoe is the last version Intel Macs will ever get, and Apple's fixes for it will stop after a limited period. Start planning to replace the Mac within the next couple of years, on your own schedule, rather than waiting for the day it stops being safe to use.

**If your Mac is Intel and can run macOS 15 Sequoia but not Tahoe**, update to Sequoia today; it is still receiving fixes. It is also next in line to stop, likely when Apple releases the next major version in the fall of 2027. Plan to replace this Mac within the next year.

**If your Mac cannot run macOS 15 Sequoia or newer**, it is no longer receiving security fixes, and there is nothing you can install to change that. The honest recommendation is to replace it. A current entry-level Mac with Apple silicon will be faster than the one you have, will receive security updates for many years, and will transfer everything from your old Mac using Apple's Migration Assistant, usually in an afternoon.

If you are not ready to replace it, the second-best option is to retire the old Mac from anything sensitive. Stop using it for email, banking, shopping, your password manager, or anything else you would mind a stranger seeing, and use your iPhone or another up-to-date device for those things instead. Keep the old Mac for the jobs that do not involve the internet or your accounts. That is a real reduction in risk; it is not the same as being safe, and it only works if you actually stick to it.

## If your iPhone or iPad is old

The same logic applies with fewer complications. The current iOS 27 runs on the iPhone 11 and every iPhone since. If your iPhone is older than that, Apple still issues some security fixes for the previous versions for a while, but you are on borrowed time; plan to replace it, and treat it the way the section above describes until you do. Your iPhone is very likely the place where your email, your bank's app, and your two-factor codes all live, which makes it the device where staying current matters most.

## If you use Windows

Admin2x support does not cover Windows computers. If you use one, the same principles apply, and Microsoft is the right source of help. The one thing to know is that Microsoft ended support for Windows 10 on October 14, 2025, which means a Windows 10 computer that is not enrolled in Microsoft's paid Extended Security Updates program is no longer receiving security fixes. Microsoft's explanation and options are at [Windows 10 support has ended on October 14, 2025](https://support.microsoft.com/kb/5056949){target=_blank}.

## What not to bother with, and what to avoid

Do not install any update offered by a pop-up on a website. A web page that tells you your Flash, your browser, your video player, or your Mac "needs an update" and offers a download button is a scam in every case; it is one of the most common ways malware gets onto Macs. Real macOS updates come only from **System Settings**, real iPhone updates only from **Settings**, and real app updates from the App Store or from inside the app itself. If a pop-up worries you, close the browser tab, then open System Settings yourself and check.

Do not buy "Mac cleaner," "speed booster," or "optimizer" software, including the ones that advertise with alarming scan results. They do not make your Mac meaningfully faster or safer, many of them are themselves a source of the problems they claim to fix, and none of them can make an unsupported version of macOS safe again.

Do not delay updates to avoid "bugs." Occasionally an update has a problem, and Apple fixes it within days. The risk of a short-lived bug is tiny compared to the risk of running for months with known security holes.

## Trusted references

1. Cybersecurity and Infrastructure Security Agency: [Update Software](https://www.cisa.gov/secure-our-world/update-software){target=_blank}.
2. Apple: [Apple security releases](https://support.apple.com/en-us/100100){target=_blank}, [Software Update settings on Mac](https://support.apple.com/guide/mac-help/mchla7037245/mac){target=_blank}, [Update your iPhone or iPad](https://support.apple.com/en-us/118575){target=_blank}, [Find out which macOS your Mac is using](https://support.apple.com/en-us/109033){target=_blank}, and [Mac computers with Apple silicon](https://support.apple.com/en-us/116943){target=_blank}.
3. Apple: [Use the App Store to update apps on Mac](https://support.apple.com/guide/app-store/fir9b01adda3){target=_blank}.
4. Google: [Update Google Chrome](https://support.google.com/chrome/answer/95414){target=_blank} and [Chrome browser system requirements](https://support.google.com/chrome/a/answer/7100626){target=_blank}.
5. Microsoft: [Windows 10 support has ended on October 14, 2025](https://support.microsoft.com/kb/5056949){target=_blank}.

--8<-- "_includes/still-need-help.md"
