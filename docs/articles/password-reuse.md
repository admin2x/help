---
title: Reusing passwords means you will get hacked
description: Why using the same password on more than one site, or sharing passwords with other people, leads to account takeover; how to find out whether it has already happened to you; and what to do about it this week.
---

# If you reuse passwords, you will get hacked (and you may have been already)

!!! info "Last reviewed October 26, 2026"
    This guide explains the problem and tells you how to check your own exposure. The fix is a password manager; the setup steps for that live in [Why you must use a password manager](password-manager.md).

## The short version

If you use the same password, or close variations of one password, on more than one website, it is not a question of whether one of your accounts gets taken over. It is a question of when, and of which account it will be. This is not an exaggeration for effect. It is how the majority of ordinary people get hacked, and it happens without the victim doing anything that feels careless at the time.

The reason is simple. Websites get breached constantly, and when they do, the email addresses and passwords stored on them are copied, traded, and eventually published. Criminals run software that takes those lists and tries every email-and-password pair against hundreds of other sites automatically. If your Netflix password from 2017 is also your email password today, that software will find it. The attack costs almost nothing to run, so it is run against everyone, all the time.

There is a good chance this has already happened to you in some form. Later in this article you will check. The repair takes about an hour of focused work plus a few weeks of small follow-ups, and every hour of it is an hour you would otherwise spend, under much worse conditions, after the fact.

## If you are planning to get to this later

Most people who read the paragraphs above already agree with them and intend to do something about it at some point. It is worth being precise about what "at some point" means. The breach data containing your old passwords is already circulating; the software that tries them against other sites is already running; the only thing not yet settled is the date on which one of your reused passwords gets tried against an account that matters. Putting the fix off does not pause any of that. It quietly moves you from the group of people who spent an hour on prevention to the group who spent twenty hours on recovery, and it does so without any announcement that the switch has happened.

So the decision in front of you is not whether to spend the time. The time will be spent either way. The decision is whether to spend one hour this week, on your own schedule, or many hours later, on the attacker's. Nobody can make that choice for you, and nobody can unmake it for you afterward. If you already know you are going to stop reading soon, skip to [What to do, in order](#what-to-do-in-order), do the first two items today, and come back to the rest when you can.

## How you get hacked without doing anything wrong

The attack is called credential stuffing. The security organization OWASP [describes it](https://community.owasp.org/attacks/Credential_stuffing){target=_blank} as an automated attempt to log in to websites using stolen username and password pairs, and it works, in OWASP's words, because many users reuse the same password and email across sites.

Here is what that looks like from your side. In 2019 you signed up for an online store or a forum or a food-delivery app, and you used the password you use for most things. In 2022 that company was breached; you may have received an email about it, or you may never have heard. The stolen database circulated privately for a while, then was dumped publicly. In 2026 a criminal takes that dump, which contains your email address and your password, and feeds it to a program that tries the pair against Gmail, Apple, Amazon, PayPal, Chase, Venmo, and a few hundred other sites. Wherever the password still works, the program logs in, and a human takes over from there.

Nothing in that story required you to click a bad link, fall for a scam, or have a virus. The weak point was a company you had forgotten about, and the only thing that connected that company to your bank was the password you used in both places.

## You have probably already been breached

[Have I Been Pwned](https://haveibeenpwned.com/){target=_blank} is a free, widely respected service that collects publicly circulating breach data so people can check whether their own information is in it. Go there now and enter your email address.

Almost everyone who has used the internet for more than a few years comes back with several results. That is not a sign that you did something wrong, and it does not by itself mean an account of yours has been taken over. It means that at least one company you trusted lost your data, and that the password you used there is now in the hands of people who will try it elsewhere. If any of the breaches listed exposed passwords, and you used that password anywhere else, treat every one of those other accounts as compromised and change them, starting with the ones in the next section.

You can also check a specific password at [Pwned Passwords](https://haveibeenpwned.com/Passwords){target=_blank}. The site never receives the password itself, only a partial fingerprint of it, which Have I Been Pwned [explains in its FAQ](https://haveibeenpwned.com/FAQs){target=_blank}. If a password you use comes back as having been seen even once, it is on the lists the attack software uses. Retire it everywhere.

While you are there, sign up for [free breach notifications](https://haveibeenpwned.com/NotifyMe){target=_blank}. From then on you get an email when your address appears in a new breach, which turns a problem you would have discovered months later into one you fix the same day.

## Variations do not count, and neither does "only for unimportant sites"

Two beliefs get people into trouble here. The first is that a pattern is as good as a unique password: `Sunshine2019!` for one site, `Sunshine2020!` for the next, `Sunshine!2021` after that. Attack software is written by people who know this is what humans do. Once one version leaks, the tooling tries the obvious variations automatically. A pattern is one password.

The second belief is that reuse is fine for accounts that do not matter. The problem is that the accounts that do not matter are exactly the ones run by companies with weak security, and they are the ones that leak. The password is the link between the throwaway account and the important one. It does not matter which end of the chain is weak; the chain is only as strong as the weakest site that ever stored that password.

## Sharing passwords with family counts as reuse

Sharing a streaming login with your household is a question of the streaming company's terms of service, not your security, and this article is not about that. Sharing the password to your email, your Apple or Google account, your bank, or anything with your payment details in it is a different matter. Every person who knows that password is another phone that can be lost, another person who can be phished, and another browser that can be saving it in plain sight. You cannot control their habits, and if they also use that password for their own accounts, your account is now exposed to every breach they are ever in.

The right way to share access, for a couple or a family, is a family plan in a password manager, where each person has their own vault and a shared vault holds the handful of logins that are legitimately joint. Both Bitwarden and 1Password offer this, and it is covered in [the password manager guide](password-manager.md#which-one-to-use).

## The accounts that matter most

If you do nothing else this week, make sure these four have passwords that are long, random, and used nowhere else.

Your main email account comes first, because it is the master key. Nearly every other account you own sends its password reset link to that address. Whoever controls your email can reset your bank, your Amazon, your social media, and your phone carrier, and usually does so within minutes of getting in.

Your Apple Account or Google Account comes second, because it holds your photos, your backups, your location, and the ability to wipe or lock your phone.

Your bank and any payment app comes third, for obvious reasons.

Your mobile carrier account comes fourth, because an attacker who can log in there can move your phone number to their own device, and from then on every text-message verification code meant for you goes to them.

## What to do, in order

First, run your email address through Have I Been Pwned and subscribe to its notifications, as described above. Five minutes.

Second, change the passwords on the four accounts above to long random ones, today, even if you have not set up a password manager yet. If you are not ready for a manager, write them on paper for now and keep the paper with your important documents; a paper list of four unique passwords is vastly safer than one memorized password used everywhere.

Third, set up a password manager by following [Why you must use a password manager](password-manager.md). That is where the hour of real work is, and it is the step that makes the problem go away permanently rather than for one round.

Fourth, once your old passwords are in the manager, let it find the rest. Apple Passwords lists reused and leaked passwords under its [Security section](https://support.apple.com/guide/iphone/iphd5d8daf4f/ios){target=_blank}, Google's [Password Checkup](https://support.google.com/accounts/answer/9457609){target=_blank} does the same, and the paid tiers of Bitwarden and 1Password include equivalent reports. Change a few at a time whenever you happen to log in somewhere. Within a month or two, every password you use regularly is unique.

Fifth, turn on two-factor authentication for the four accounts above. [Turn on two-factor authentication](two-factor-authentication.md) covers that step in detail.

If you receive a breach notification after all this is done, the Federal Trade Commission's [advice for breach victims](https://consumer.ftc.gov/consumer-alerts/2022/10/have-you-been-affected-data-breach-read){target=_blank} applies: change that one password, confirm two-factor is on, and check what else was exposed. With unique passwords, a breach at one company is a five-minute inconvenience rather than an emergency.

## What the alternative actually costs

It is worth being concrete about what happens when the attack described above succeeds, because the cost is almost always underestimated beforehand.

Account takeover is not usually discovered when it happens. It is discovered when a friend asks why you sent them a strange message, when a charge appears that you do not recognize, when a password reset email arrives that you did not request, or when you simply cannot log in to your email one morning. By that point the attacker has typically had access for days or weeks, has read your messages, knows which banks and services you use, and has already used your email to reset the passwords on some of them.

Recovering from that is a job of somewhere between ten and twenty hours, spread across several days, most of it on the phone and much of it on hold. It means proving your identity to your email provider through an account-recovery process designed to be slow. It means calling each bank and card issuer, disputing charges, and waiting for replacement cards. It means contacting your carrier to make sure your number was not moved. It means warning everyone in your contacts that messages from you may not be from you. And it means, at the end of all of that, changing every single password you have to a unique one and setting up a password manager, because that is the only way to make the attacker's copy of your old password worthless. In other words, the recovery ends with exactly the work described in this article, done under pressure, after the damage, instead of calmly, in an hour, before it.

Anyone you ask to help you through that process, whether a friend who knows about computers or a paid service, cannot shortcut it. The recovery steps are the same regardless of who performs them, the identity checks have to be done by you, and the hold music is the same length for everyone. What a helper can do is sit with you for those hours. What they cannot do is undo the fact that the password was shared with the attacker years earlier by a company you no longer remember.

Read [the password manager guide](password-manager.md), do Steps 1 and 2 today, and the question is closed.

## Trusted references

1. Have I Been Pwned: [check your email address](https://haveibeenpwned.com/){target=_blank}, [check a password](https://haveibeenpwned.com/Passwords){target=_blank}, [get breach notifications](https://haveibeenpwned.com/NotifyMe){target=_blank}, and [how the service works](https://haveibeenpwned.com/FAQs){target=_blank}.
2. OWASP Foundation: [Credential stuffing](https://community.owasp.org/attacks/Credential_stuffing){target=_blank}.
3. Federal Trade Commission: [Have you been affected by a data breach? Read on](https://consumer.ftc.gov/consumer-alerts/2022/10/have-you-been-affected-data-breach-read){target=_blank} and [IdentityTheft.gov](https://www.identitytheft.gov/){target=_blank} for when a breach has led to misuse of your identity.
4. Cybersecurity and Infrastructure Security Agency: [Use Strong Passwords](https://www.cisa.gov/secure-our-world/use-strong-passwords){target=_blank}.
5. Google: [Change compromised passwords in your Google Account](https://support.google.com/accounts/answer/9457609){target=_blank}.
6. Apple: [Change weak or compromised passwords on iPhone](https://support.apple.com/guide/iphone/iphd5d8daf4f/ios){target=_blank}.

--8<-- "_includes/still-need-help.md"
