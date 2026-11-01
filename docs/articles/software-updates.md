---
title: Keep your computer, phone, and apps updated
description: Why software updates are security fixes, how to turn on automatic updates on a Mac, a Windows PC, and an iPhone, and what to do if your computer is too old to run a version that still gets security fixes, including Windows 10.
---

# Keep your computer, phone, and apps updated

!!! info "Last reviewed November 1, 2026"
    The macOS, Windows, and iOS versions named below are current as of this date. Apple and Microsoft each release a new major version every fall, so if you are reading this in late 2027 or later, the specific version names will have moved on, but the advice has not.

## The short version

Software updates are mostly security fixes. When Apple, Google, or any other company ships an update, it usually closes holes that attackers already know about, and in many cases are already using. The moment an update is published, the list of what it fixed is effectively public, and criminals start aiming at everyone who has not installed it yet. Apple puts it plainly on its own security page: keeping your software up to date is one of the most important things you can do to keep your Apple products secure. Microsoft says the same about Windows.

So the job is simple. Turn on automatic updates on your computer and your phone, turn on automatic updates for your apps, and restart your devices once in a while so the updates actually take effect. That takes about ten minutes, once.

The harder part of this guide is for people with older computers. If your Mac or PC is running an older version of its operating system because it cannot run a newer one, or because you are worried a newer one will make it slower, read [the section on older Macs](#if-your-mac-is-old) or [the section on older Windows PCs](#if-your-windows-pc-is-old) carefully. An old computer on an old operating system is one of the most common situations where a "my computer is acting strange" problem turns out to have no real fix except a new computer. If you are still on Windows 10, there is one five-minute step in that section that you should do today.

## Step 1: Turn on automatic updates on your computer

### On a Mac

1. Click the Apple menu in the top-left corner of the screen and choose **System Settings**.
2. Click **General** in the sidebar, then click **Software Update**.
3. Click the small **ⓘ** (info) button next to **Automatic Updates**.
4. Turn on everything in the list: **Download new updates when available**, **Install macOS updates**, and **Install Security Responses and system files**. Click **Done**.

<!-- SCREENSHOT: System Settings > General > Software Update > Automatic Updates panel with all toggles on -->

If the Software Update screen shows that an update is waiting, install it now rather than waiting for the automatic schedule. Apple's instructions: [Software Update settings on Mac](https://support.apple.com/guide/mac-help/mchla7037245/mac){target=_blank}.

A note on the difference between the two kinds of update you will see there. A small update, one that changes the number after the dot, such as 26.7.1 to 26.7.2, is almost entirely security and bug fixes; install it every time, as soon as it appears. A major upgrade, one that changes the name and the first number, such as Tahoe 26 to Golden Gate 27, adds new features and is a bigger change; the [older Macs section](#if-your-mac-is-old) explains how to think about those.

### On a Windows PC

1. Open the **Start** menu, choose **Settings**, then **Windows Update**.
2. Turn on **Get the latest updates as soon as they're available**.
3. Select **Check for updates**. If anything is waiting, let it download and install, and restart when asked.

Windows installs security updates automatically by default, so the toggle above mostly affects how soon you get them; the important part is not to keep postponing the restart. Microsoft's instructions: [Install Windows updates](https://support.microsoft.com/en-us/windows/install-windows-updates-3c5ae7fc-9fb6-9af1-1984-b5e0412c556a){target=_blank} and [Get Windows updates as soon as they're available](https://support.microsoft.com/en-us/windows/cad7b32b-001e-435b-9110-f18309b54168){target=_blank}.

If your PC is still running Windows 10, Step 1 is not enough; read [the Windows 10 part of the older-PC section](#which-versions-of-windows-are-still-being-fixed) before going on.

## Step 2: Turn on automatic updates on your iPhone and iPad

1. Open **Settings**, tap **General**, then tap **Software Update**.
2. Tap **Automatic Updates**.
3. Turn on **Automatically Install** for iOS updates. With this on, your iPhone installs updates overnight while it is charging and on Wi-Fi, and tells you before it does.
4. On the same screen, make sure the setting for **System Files** (security responses) is also turned on.

If an update is waiting when you open Software Update, tap **Download and Install** now. Apple's instructions: [Update your iPhone or iPad](https://support.apple.com/en-us/118575){target=_blank}.

On an Android phone the setting lives in a slightly different place on each brand, usually under **Settings**, then **System** or **Software update**; turn on automatic installation there and install anything waiting.

## Step 3: Keep your apps updated

**Apps from the App Store** update themselves once you turn this on. On a Mac, open the **App Store**, choose **App Store** from the menu bar, then **Settings**, and turn on **Automatic Updates**. Apple's instructions: [Use the App Store to update apps on Mac](https://support.apple.com/guide/app-store/fir9b01adda3){target=_blank}. On an iPhone, open **Settings**, tap **App Store**, and turn on **App Updates**. On a Windows PC, open the **Microsoft Store**, click your account icon, choose **Settings**, and turn on **App updates**; Microsoft's instructions: [Turn on automatic app updates](https://support.microsoft.com/en-us/windows/turn-on-automatic-app-updates-70634d32-4657-dc76-632b-66048978e51b){target=_blank}.

**Apps you downloaded from a company's website**, such as Chrome, Firefox, Zoom, Microsoft Office, and most password managers, have their own built-in updaters. When one of them asks to update or restart, let it.

**Your web browser matters most of all**, because it is the program that touches the most untrusted material: every website, every ad, every link in every email. Safari is updated as part of macOS, so Step 1 covers it. Microsoft Edge updates itself but only finishes when you restart it; to check, click the three-dot menu, choose **Help and feedback**, then **About Microsoft Edge** ([Microsoft's instructions](https://support.microsoft.com/en-us/Edge/getting-the-latest-microsoft-edge-update-just-got-easier){target=_blank}). Chrome updates itself in the background but only finishes when you restart it; if you see a **Relaunch** button or a colored dot at the top right of the Chrome window, click it. To check by hand, open Chrome, click the three-dot menu, choose **Help**, then **About Google Chrome**. Google's instructions: [Update Google Chrome](https://support.google.com/chrome/answer/95414){target=_blank}.

## Step 4: Restart once a week

Many updates download quietly but do not take effect until the device or the app restarts. A Mac that has not been restarted in two months, with a browser that has not been closed in two months, can be running old, vulnerable versions even with automatic updates turned on. Restart your computer and your phone about once a week. Friday evening is a good habit.

When a dialog says an update is ready and offers **Remind Me Tomorrow** or **Try Tonight**, the safe answer is almost always **Try Tonight** or **Restart Now**. Clicking "Remind me later" a few dozen times in a row is the single most common reason a computer with automatic updates turned on is still months out of date.

## If your Mac is old

This section is long because it is where the most harm happens, and because the decision involved is a real one, with a real cost, that deserves an honest explanation rather than a slogan.

### Find out which Mac and macOS you have

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

### What to do with your Mac, depending on what you found

**If your Mac has Apple silicon** (it says Chip), update to macOS 27 Golden Gate using Software Update. Every Apple silicon Mac ever made can run it.

**If your Mac is Intel and can run macOS 26 Tahoe**, update to Tahoe if you have not already. You will keep getting security fixes for now, but Tahoe is the last version Intel Macs will ever get, and Apple's fixes for it will stop after a limited period. Start planning to replace the Mac within the next couple of years, on your own schedule, rather than waiting for the day it stops being safe to use.

**If your Mac is Intel and can run macOS 15 Sequoia but not Tahoe**, update to Sequoia today; it is still receiving fixes. It is also next in line to stop, likely when Apple releases the next major version in the fall of 2027. Plan to replace this Mac within the next year.

**If your Mac cannot run macOS 15 Sequoia or newer**, it is no longer receiving security fixes, and there is nothing you can install to change that. The honest recommendation is to replace it. A current entry-level Mac with Apple silicon will be faster than the one you have, will receive security updates for many years, and will transfer everything from your old Mac using Apple's Migration Assistant, usually in an afternoon.

If you are not ready to replace it, the second-best option is to retire the old Mac from anything sensitive. Stop using it for email, banking, shopping, your password manager, or anything else you would mind a stranger seeing, and use your iPhone or another up-to-date device for those things instead. Keep the old Mac for the jobs that do not involve the internet or your accounts. That is a real reduction in risk; it is not the same as being safe, and it only works if you actually stick to it.

## If your iPhone or iPad is old

The same logic applies with fewer complications. The current iOS 27 runs on the iPhone 11 and every iPhone since. If your iPhone is older than that, Apple still issues some security fixes for the previous versions for a while, but you are on borrowed time; plan to replace it, and treat it the way the section above describes until you do. Your iPhone is very likely the place where your email, your bank's app, and your two-factor codes all live, which makes it the device where staying current matters most.

## If your Windows PC is old

### Find out which Windows you have

Right-click the **Start** button, choose **Settings**, then **System**, then **About**. Under **Windows specifications** you will see the edition (for example "Windows 11 Home" or "Windows 10 Home") and the version (for example "25H2"). Write both down. Microsoft's guide: [Find information about your Windows device](https://support.microsoft.com/en-us/windows/experience/find-information-about-your-windows-device){target=_blank}.

### Which versions of Windows are still being fixed

Windows is simpler than macOS here, because there are only two answers.

**Windows 11** is the current version and receives security fixes. Microsoft issues a new yearly release each fall, named by year and half, and keeps each one patched for about two years. As of this writing the supported releases are 25H2 and 26H1; version 24H2 stopped receiving fixes on October 13, 2026. If your version is 24H2 or earlier, Windows Update should offer you the newer release as an ordinary update; install it. Microsoft's table of supported versions: [Windows 11 release information](https://learn.microsoft.com/windows/release-health/supported-versions-windows-client){target=_blank}.

**Windows 10** reached the end of regular support on October 14, 2025. A Windows 10 computer gets no security fixes at all unless it is enrolled in Microsoft's Extended Security Updates program, which Microsoft has quietly extended through October 12, 2027. Enrollment is free if you sign in with a Microsoft account and let Windows sync your settings; the alternatives are 1,000 Microsoft Rewards points or a one-time payment of $30. To enroll, open **Settings**, then **Update & Security**, then **Windows Update**, and look for **Enroll now**. Your PC must be on Windows 10 version 22H2 with the latest updates installed. Microsoft's page: [Windows 10 Extended Security Updates](https://www.microsoft.com/en-us/windows/extended-security-updates){target=_blank}. If you are on Windows 10 and have not done this, do it today; it takes five minutes and is the difference between a patched computer and an unpatched one.

### Can your PC run Windows 11?

Windows 11 is a free upgrade for any PC that meets its requirements, and the upgrade is delivered through Windows Update like any other. The requirements that trip up older machines are a security chip called TPM 2.0 and a processor from roughly 2018 or later; Microsoft's list is at [Windows 11 system requirements](https://support.microsoft.com/topic/86c11283-ea52-4782-9efd-7674389a7ba3){target=_blank}. The easy way to find out is to open **Settings**, **Update & Security**, **Windows Update**, and select **Check for updates**; if your PC qualifies, Windows Update will say so and offer the upgrade. Microsoft also publishes a small **PC Health Check** app that gives a yes-or-no answer and explains any no.

The same worry about slowdown that comes up with Macs comes up here, and the same answer applies: a PC that qualifies for Windows 11 is recent enough to run it well, the first day after an upgrade is slow while the system re-indexes, and an unpatched computer does not stay fast anyway; it gets easier to compromise every month.

### What to do with your PC, depending on what you found

**If you have Windows 11**, make sure Step 1 is done and that your version is 25H2 or later. That is all.

**If you have Windows 10 and your PC can run Windows 11**, upgrade. It is free, it takes an hour or two, and it is the only path that keeps the computer fully supported past 2027.

**If you have Windows 10 and your PC cannot run Windows 11**, enroll in Extended Security Updates now, as described above. That keeps the computer patched until October 2027 and gives you time to replace it on your own schedule. Treat October 2027 as a hard deadline, and in the meantime apply the same advice as for an old Mac: if you are not going to replace it, keep it away from email, banking, shopping, and your password manager.

**If you have Windows 8.1 or earlier**, the computer has not received security fixes in years and should not be used on the internet at all.

## What not to bother with, and what to avoid

Do not install any update offered by a pop-up on a website. A web page that tells you your Flash, your browser, your video player, or your computer "needs an update" and offers a download button is a scam in every case; it is one of the most common ways malware gets onto both Macs and PCs. Real macOS updates come only from **System Settings**, real Windows updates only from **Settings**, real iPhone updates only from **Settings**, and real app updates from the App Store, the Microsoft Store, or inside the app itself. Microsoft states flatly that its own error and warning messages never include a phone number. If a pop-up worries you, close the browser tab, then open your computer's own settings and check.

Do not buy "cleaner," "speed booster," or "optimizer" software for either a Mac or a PC, including the ones that advertise with alarming scan results. They do not make your computer meaningfully faster or safer, many of them are themselves a source of the problems they claim to fix, and none of them can make an unsupported operating system safe again. On Windows you also do not need to buy antivirus software: Windows Security, with Microsoft Defender Antivirus, is built in, on by default, and updated through Windows Update, and it is what Microsoft itself recommends. Microsoft's page: [Help protect my device with Windows Security](https://support.microsoft.com/en-us/windows/help-protect-my-device-with-windows-security-1a5b8102-c93d-0573-8fd3-b2d33a1e5386){target=_blank}.

Do not delay updates to avoid "bugs." Occasionally an update has a problem, and Apple or Microsoft fixes it within days. The risk of a short-lived bug is tiny compared to the risk of running for months with known security holes.

## Trusted references

1. Cybersecurity and Infrastructure Security Agency: [Update Software](https://www.cisa.gov/secure-our-world/update-software){target=_blank}.
2. Apple: [Apple security releases](https://support.apple.com/en-us/100100){target=_blank}, [Software Update settings on Mac](https://support.apple.com/guide/mac-help/mchla7037245/mac){target=_blank}, [Update your iPhone or iPad](https://support.apple.com/en-us/118575){target=_blank}, [Find out which macOS your Mac is using](https://support.apple.com/en-us/109033){target=_blank}, and [Mac computers with Apple silicon](https://support.apple.com/en-us/116943){target=_blank}.
3. Apple: [Use the App Store to update apps on Mac](https://support.apple.com/guide/app-store/fir9b01adda3){target=_blank}.
4. Google: [Update Google Chrome](https://support.google.com/chrome/answer/95414){target=_blank} and [Chrome browser system requirements](https://support.google.com/chrome/a/answer/7100626){target=_blank}.
5. Microsoft: [Install Windows updates](https://support.microsoft.com/en-us/windows/install-windows-updates-3c5ae7fc-9fb6-9af1-1984-b5e0412c556a){target=_blank}, [Windows 11 release information](https://learn.microsoft.com/windows/release-health/supported-versions-windows-client){target=_blank}, [Windows 10 Extended Security Updates](https://www.microsoft.com/en-us/windows/extended-security-updates){target=_blank}, [Windows 11 system requirements](https://support.microsoft.com/topic/86c11283-ea52-4782-9efd-7674389a7ba3){target=_blank}, and [Help protect my device with Windows Security](https://support.microsoft.com/en-us/windows/help-protect-my-device-with-windows-security-1a5b8102-c93d-0573-8fd3-b2d33a1e5386){target=_blank}.

--8<-- "_includes/site-footer.md"
