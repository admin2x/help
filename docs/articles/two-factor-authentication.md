---
title: Turn on two-factor authentication
description: What two-factor authentication is, which kind to choose, and step-by-step instructions for turning it on for your email, your Apple or Google account, your bank, and your mobile carrier, including how to stop SIM-swap attacks.
---

# Turn on two-factor authentication (and pick the right kind)

!!! info "Last reviewed October 29, 2026"
    Menu names below are for the current versions of Google, Apple, Microsoft, Verizon, AT&T, and T-Mobile account settings. These change often; if a menu item is missing, look for the closest wording or follow the vendor's own link in that section.

## The short version

Two-factor authentication means that logging in to an account takes your password plus one more thing that only you have, usually your phone. With it turned on, a criminal who has your password, which after reading [the password-reuse guide](password-reuse.md) you should assume is possible, still cannot get in, because they do not have your phone. It is the single biggest improvement you can make to an account after giving it a unique password, and on most accounts it takes about three minutes to set up.

You will see it called two-factor authentication, 2FA, two-step verification, 2SV, multi-factor authentication, MFA, or login verification. These are all the same thing.

Turn it on for your main email account, your Apple or Google account, your bank, and your mobile carrier account, in that order, this week. Where you get a choice of method, choose a passkey or an app rather than a text message, for reasons explained below. Everything else can follow over time, but those four are the accounts that unlock all the others.

## Which kind to choose

Most accounts offer several ways to do the second step, and they are not equally good. From best to worst:

A **passkey or a device prompt** means the account recognizes your phone itself. You unlock the phone with your face or fingerprint, tap Yes, and you are in. There is no code to type and nothing for a scammer to trick you into reading out loud. Google calls its version "Google prompt," Apple's trusted-device system works the same way, and passkeys are now offered by most large sites. If an account offers this, use it. [What is a passkey and why you should use them](passkeys.md) covers passkeys in detail.

An **authenticator app** shows a six-digit code that changes every thirty seconds. You type the current code when you log in. It works with no cell service and no internet, and it cannot be intercepted the way a text message can. This is the right choice for any account that does not offer a passkey or prompt.

A **text message or voice call** to your phone number is the weakest option, because your phone number can be stolen (see the carrier section below) and because scammers have gotten very good at talking people into reading a code aloud. It is still much better than nothing. If text messages are the only option an account offers, as is true of many banks, turn it on anyway.

A **hardware security key**, a small USB or NFC device, is the strongest option of all and is what security professionals use. It is more than most people need, and it is not covered here. If you handle large sums of money or are a likely target for some other reason, open a ticket and ask.

## Where to keep your authenticator codes

If you choose the authenticator-app method, you need an app to hold the codes. Keep this simple. On an iPhone, the built-in **Passwords** app can store and show verification codes alongside the password for each site, and Apple explains how in [Use the Passwords app](https://support.apple.com/en-us/120758){target=_blank}: open the site's entry, and under Security choose **Set Up Verification Code**. On Android, use **Google Authenticator** from the Play Store and sign in to it with your Google Account so your codes are backed up and move with you to a new phone automatically; Google's instructions are at [Get verification codes with Google Authenticator](https://support.google.com/accounts/answer/1066447){target=_blank}. Bitwarden and 1Password can also generate codes in their paid tiers, which puts the password and the code in one place and is the most convenient setup of all.

Whichever you pick, the thing to avoid is an authenticator with no backup, where losing your phone means losing every code. That was the standard failure mode for years, and all of the options above now solve it.

## Step 1: Your email account

Email first, always, because every other account sends its password-reset link there.

**Gmail.** Go to [myaccount.google.com](https://myaccount.google.com){target=_blank}, open **Security**, and under "How you sign in to Google" choose **2-Step Verification**, then follow the prompts. Google will offer **Google prompt** by default on any phone where you are signed in to Gmail or the Google app; accept it. You can add an authenticator app as a second method on the same screen. Before you leave, scroll to **Backup codes**, generate them, and print or write them down (see Step 5). Google's instructions: [Turn on 2-Step Verification](https://support.google.com/accounts/answer/185839){target=_blank}.

**iCloud Mail.** Your iCloud email is protected by the two-factor setting on your Apple Account, covered in Step 2.

**Outlook.com, Hotmail, or Live.** Go to [account.microsoft.com/security](https://account.microsoft.com/security){target=_blank}, open **Advanced security options**, and turn on **Two-step verification**. Microsoft will walk you through installing its Authenticator app. Microsoft's instructions: [How to use two-step verification with your Microsoft account](https://support.microsoft.com/en-us/help/12408){target=_blank}.

**Yahoo, AOL, Comcast, Spectrum, or another provider.** Log in on a computer, look for **Account security** or **Security settings**, and find the two-step option there. If the provider offers only text messages, use that.

## Step 2: Your Apple Account or Google Account

If you use Gmail, your Google Account is already done; Step 1 covered it.

For your Apple Account, two-factor authentication is on by default for any account created in the last several years and cannot be turned off. To check: on your iPhone, open **Settings**, tap your name at the top, tap **Sign-In & Security**, and look for **Two-Factor Authentication**. If it says On, you are done. If not, tap it and follow the prompts. While you are on that screen, confirm that the **trusted phone number** listed is a number you still control. Apple's instructions: [Two-factor authentication for Apple Account](https://support.apple.com/en-us/102660){target=_blank}.

## Step 3: Your bank and payment apps

Every bank, credit card, and payment app does this a little differently, so there is no single set of steps. Log in on a computer, open your profile or settings, and look for **Security**, **Login security**, or **Two-step verification**. Turn on whatever the strongest offered method is. Many banks still offer only text-message codes; accept that, since it is still a large improvement, and check back once a year because banks are gradually adding app-based options.

Two notes. If your bank's own app offers to be the second factor (a notification you approve inside the app), prefer that over text messages. And if you use Venmo, PayPal, Zelle, Cash App, or a brokerage, treat each of them as a bank for this purpose.

## Step 4: Your mobile carrier account, and locking your phone number

This step is different from the others and more important than it looks. Your phone number is the backup key to nearly everything: it receives text-message codes, it is where "forgot my password" sends the reset link when email is unavailable, and your bank uses it to confirm it is you. An attacker who takes control of your number takes control of all of that at once.

That is exactly what a **SIM-swap attack** does. The attacker calls your carrier, or walks into a store, pretends to be you using details from a data breach, and asks to move your number to a new phone. If it works, your phone goes dead and theirs starts receiving all your calls and texts, including every verification code. The Federal Trade Commission describes the attack and the defenses in [SIM Swap Scams: How to Protect Yourself](https://consumer.ftc.gov/consumer-alerts/2019/10/sim-swap-scams-how-protect-yourself){target=_blank}. The defenses are an account PIN, so that the carrier will not make changes without it, and a lock that blocks SIM changes and number transfers outright. All three major carriers now offer the lock for free; turn it on.

**Verizon.** In the My Verizon app, go to the **Account** tab, then **Edit Profile and Settings**, then the **Security** menu, then **SIM Protection**, and turn it on for each line. Also set or confirm your **Account PIN** in the same security area. Verizon's page: [SIM Swapping](https://www.verizon.com/about/privacy/account-security/sim-swapping){target=_blank}.

**AT&T.** In the AT&T app, on a phone that is active on your account, tap the person icon, scroll to **Wireless account lock**, and swipe to lock. This blocks SIM changes, number transfers, device upgrades, and billing changes until you unlock it from the app. AT&T's page: [Learn about Wireless Account Lock](https://www.att.com/support/article/wireless/000102016){target=_blank}.

**T-Mobile.** There are two separate switches. In the T-Life app, open the **Manage** tab, tap the gear icon, go to **Security**, then **SIM Protection**, and turn it on. Then, for each line, go to **See plans** under My account, **Manage add-ons**, and check **Port Out Protection**. T-Mobile's page: [Protect your T-Mobile account from fraud](https://www.t-mobile.com/support/plans-features/help-with-t-mobile-account-fraud){target=_blank}.

**Other carriers.** Mint, Visible, Cricket, Metro, Boost, Google Fi, and the rest all have an account PIN and most have a port-out lock; search your carrier's support site for "port out" or "SIM protection." Set the PIN at a minimum.

Remember that you will need to turn the lock off yourself the next time you legitimately get a new phone or change carriers. That is a thirty-second inconvenience once every few years, which is the point.

## Step 5: Save your backup codes on paper

Most accounts give you a set of one-time **backup codes** (Google calls them backup codes, others say recovery codes) when you turn on two-factor authentication. They exist for the day you lose your phone, drop it in the ocean, or buy a new one and forget to move the authenticator over. Without them, getting back into an account with two-factor enabled can take days or weeks of identity verification; Microsoft, for example, says its recovery process can take up to 30 days.

Print the codes or write them down, and keep them with the paper that holds your password-manager master password, as described in [the password manager guide](password-manager.md#step-1-choose-your-one-master-password-and-write-it-down). Do not store them as a photo on the phone they are meant to replace.

## What two-factor authentication does not protect against

It does not protect you from reading a code to someone who asks for it. The most common attack against two-factor accounts today is not technical at all: someone calls or texts claiming to be from your bank, Amazon, or Apple, says there is suspicious activity, and asks you to confirm the six-digit code that was "just sent to you." The code was sent because the attacker is logging in as you at that moment, and reading it to them completes their login. No legitimate company will ever ask you to read a verification code to them, by phone or by text. If anyone does, hang up. [Recognize and stop phishing and scams](phishing-and-scams.md) goes into this further.

It also does not help if the second factor is a text message and your number has been swapped, which is why Step 4 matters, and it does not help an account you have not turned it on for, which is why the four accounts above come first.

## Questions people always ask

**Is it going to ask me every single time?** Almost never. Nearly every service lets you mark a device as trusted so that it asks only when someone logs in from a new phone or computer, which is exactly the case you want it to catch.

**What if I lose my phone?** You use a backup code from Step 5 to log in, then set up the authenticator on the new phone. If your authenticator codes are backed up (Apple Passwords, Google Authenticator signed in to your Google Account, or a password manager), they simply reappear on the new phone.

**My bank already texts me a code. Isn't that enough?** It is far better than a password alone, and if that is all the bank offers, keep it. But text messages are the method attackers know how to defeat, so for your email and your Apple or Google account, where you do have a choice, choose the prompt or an app.

**Do I really have to do this for the carrier?** Yes. Of the four accounts, it is the one people skip, and it is the one that undoes the other three if an attacker gets it.

## Trusted references

1. Cybersecurity and Infrastructure Security Agency: [Protect Our World with MFA](https://www.cisa.gov/secure-our-world/turn-mfa){target=_blank}, which includes a short explanatory video.
2. Federal Trade Commission: [SIM Swap Scams: How to Protect Yourself](https://consumer.ftc.gov/consumer-alerts/2019/10/sim-swap-scams-how-protect-yourself){target=_blank}.
3. Google: [Turn on 2-Step Verification](https://support.google.com/accounts/answer/185839){target=_blank} and [Get verification codes with Google Authenticator](https://support.google.com/accounts/answer/1066447){target=_blank}.
4. Apple: [Two-factor authentication for Apple Account](https://support.apple.com/en-us/102660){target=_blank} and [Use the Passwords app](https://support.apple.com/en-us/120758){target=_blank}.
5. Microsoft: [How to use two-step verification with your Microsoft account](https://support.microsoft.com/en-us/help/12408){target=_blank}.
6. Carriers: Verizon [SIM Swapping](https://www.verizon.com/about/privacy/account-security/sim-swapping){target=_blank}, AT&T [Wireless Account Lock](https://www.att.com/support/article/wireless/000102016){target=_blank}, T-Mobile [Protect your T-Mobile account from fraud](https://www.t-mobile.com/support/plans-features/help-with-t-mobile-account-fraud){target=_blank}.

--8<-- "_includes/still-need-help.md"
