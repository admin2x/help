---
title: Why you must use a password manager
description: Why a password manager is the single most important thing you can do for your online security, which one to use, and step-by-step setup for Bitwarden, 1Password, Apple Passwords, and Google Password Manager.
---

# Why you must use a password manager (and how to set one up)

!!! info "Last reviewed October 26, 2026"
    Menu names below are for the current versions of Bitwarden, 1Password, iOS 26, and Android. These apps change their menus from time to time; if an item is missing, look for the closest wording, or follow the vendor's own link in that section.

## The short version

A password manager is an app that makes up a different long random password for every website and app you use, remembers all of them for you, and types them in when you log in. You remember exactly one password, the one that unlocks the manager. That is the whole idea.

This is not optional any more, and it is not a power-user thing. It is the single change that prevents the most common way people get hacked, which is not clever hacking at all. It is a criminal taking your email address and a password that leaked from some other website years ago and trying that combination on your bank, your email, and Amazon until one of them works. If you use the same password in more than one place, or small variations of it, you are exposed to this right now. A password manager fixes it, and the fix takes about an hour spread over a couple of weeks.

If you only do one thing from this article, do Step 1 and Step 2 today, then put your email account, your bank, and your Apple or Google account into the manager with new passwords. The rest can happen gradually.

## Why this matters

Nobody can remember a hundred different strong passwords, so nobody does. People use one or two passwords everywhere, or a pattern like `Fluffy2019!` and `Fluffy2020!`. The problem is that websites get breached constantly, and when they do, the passwords stored on them end up for sale. [Have I Been Pwned](https://haveibeenpwned.com/){target=_blank}, a free service run by a well-known security researcher, tracks these breaches; it currently holds billions of leaked email addresses and passwords from thousands of breached sites. Type your email address into it and you will almost certainly find that it has been in several breaches. That is normal; it is not a sign you did anything wrong.

What criminals do with those lists is called credential stuffing. They take every leaked email-and-password pair and try it automatically against hundreds of other sites. It costs them almost nothing, and it works on anyone who reused a password. The only reliable defense is a different password on every site, so that a breach at one place does not open the door anywhere else. You cannot do that from memory. A password manager does it for you.

You can also check whether a specific password you use has ever leaked at [Pwned Passwords](https://haveibeenpwned.com/Passwords){target=_blank}. The site never sees the password itself; your browser sends only a partial fingerprint of it. If a password you use comes back as found, stop using it everywhere, today.

## Which one to use

Pick one of these and do not spend time comparing. All of them are good, and the difference between any of them and no password manager is enormous, while the difference between them is small.

**Bitwarden** is our default recommendation. It is free for everything you need, it works on every phone, computer, and browser, it is open source and independently audited, and the company cannot read your passwords even if it wanted to. The paid tier is ten dollars a year and adds a few conveniences, but you do not need it.

**1Password** is the recommendation if you would rather pay a little for the most polished experience, or if you want a family plan where you can share some passwords with a spouse or kids and keep others private. It costs about three dollars a month for one person or five for a family. It is excellent.

**Apple Passwords** (built into iPhone, iPad, and Mac) or **Google Password Manager** (built into Android and Chrome) are acceptable if, and only if, every device you own is in one of those two worlds. If you have an iPhone and a Windows laptop, or an Android phone and a Mac, use Bitwarden or 1Password instead, because the built-in ones do not work well across the fence. They are also harder to leave later.

Do not use any of the following as your password system: a notebook, the Notes app, a spreadsheet, your browser's "remember this password" prompt without the full Google or Apple manager behind it, one password with small changes per site, or your memory. Also, do not use LastPass. Its encrypted customer vaults were stolen in 2022, and the company's handling of it was poor enough that we no longer recommend it.

The rest of this article assumes Bitwarden. The steps for the others are the same in substance, and each section links to that vendor's own instructions.

## Step 1: Choose your one master password, and write it down

This is the only password you will have to remember from now on, and it is the one password the manager cannot help you with. If you forget it, Bitwarden cannot reset it or recover your passwords; [Bitwarden says so plainly](https://bitwarden.com/help/forgot-master-password/){target=_blank}, and 1Password works the same way. That is by design: a company that could recover your master password could also be forced or tricked into handing it to someone else.

So make it long and memorable rather than short and complicated. The best approach is four or five unrelated words with spaces, something like `copper giraffe thursday lantern`, made up by you and never used anywhere before. That is far stronger than `P@ssw0rd!23` and far easier to type on a phone. Do not use a song lyric, a quote, your address, or anything about you that someone could look up. The U.S. Cybersecurity and Infrastructure Security Agency gives the same advice in its [Use Strong Passwords](https://www.cisa.gov/secure-our-world/use-strong-passwords){target=_blank} guide.

Then write it down on paper. Put the paper somewhere you keep important documents, such as with your passport or in the folder where your tax records live. The risk that a burglar finds that paper and also knows what it is for is tiny. The risk that you forget a password you made up last month and type twice a day on autopilot is not tiny at all. Writing down your master password is correct practice, not a mistake.

## Step 2: Create the account and install it everywhere

Bitwarden has a short video course, [First Steps with Bitwarden](https://bitwarden.com/help/courses/first-steps-with-bitwarden/){target=_blank}, that walks through everything in this step and the next one. Watch it if you prefer to follow along on screen; the written steps follow.

### Create the account

1. On a computer, go to [bitwarden.com](https://bitwarden.com/){target=_blank} and click **Get started**.
2. Enter your email address and a name.
3. Enter the master password you chose in Step 1. Add a hint if you like, but remember that the hint is emailed to anyone who asks for it, so do not make it the password itself.
4. Confirm your email address when the verification message arrives.

Bitwarden's written version: [Create a Bitwarden account](https://bitwarden.com/help/create-bitwarden-account/){target=_blank}.

### Install the browser extension on your computer

The extension is what fills in passwords on websites and offers to save new ones. Install it in every browser you use.

1. Go to [bitwarden.com/download](https://bitwarden.com/download/){target=_blank} and pick your browser (Chrome, Safari, Firefox, or Edge).
2. After it installs, click the puzzle-piece or extensions icon in your browser's toolbar and pin Bitwarden so its shield icon is always visible.
3. Click the shield and log in with your email and master password.
4. When the extension asks whether to turn off your browser's built-in password saving, say yes. Two password managers fighting over the same login box is the most common cause of confusion later.

Bitwarden's written version: [Get started with the browser extension](https://bitwarden.com/help/getting-started-browserext/){target=_blank}.

### Install the app on your phone and turn on autofill

1. Install **Bitwarden Password Manager** from the App Store or Google Play, open it, and log in.
2. On **iPhone**: open **Settings**, tap **General**, tap **AutoFill & Passwords**, turn on **AutoFill Passwords and Passkeys**, and under **AutoFill From** turn on **Bitwarden**. Turn off **Passwords** (Apple's built-in one) in that same list so only one app offers to fill.
3. On **Android**: open the Bitwarden app, tap **Settings**, tap **Autofill**, and turn on **Autofill services**. Android will take you to a system screen where you choose Bitwarden as the autofill service. On some phones you also need to turn on **Use accessibility** on the same screen for autofill to work inside apps.

<!-- SCREENSHOT: iOS Settings > General > AutoFill & Passwords with Bitwarden toggled on -->

Bitwarden's written versions: [Get started with mobile apps](https://bitwarden.com/help/getting-started-mobile/){target=_blank} and the [iOS autofill guide](https://bitwarden.com/help/getting-started-ios/){target=_blank}.

### If you chose 1Password, Apple, or Google instead

1Password's setup is nearly identical and is laid out at [Get started with 1Password](https://support.1password.com/explore/get-started/){target=_blank}. The one extra thing 1Password gives you is an **Emergency Kit**, a one-page PDF containing your account's Secret Key with a blank for your password. Print it, write the password on it, and store it with the paper from Step 1. [What the Emergency Kit is and where to keep it](https://support.1password.com/emergency-kit/){target=_blank}.

Apple Passwords is already on your iPhone; you only need to make sure it syncs between your devices. Apple's instructions: [Set up iCloud Keychain](https://support.apple.com/en-us/109016){target=_blank} and [Find saved passwords and passkeys on your iPhone](https://support.apple.com/en-us/104955){target=_blank}.

Google Password Manager is built into Chrome and Android. Google's instructions: [Get started with Google Password Manager](https://support.google.com/accounts/answer/6208650){target=_blank}; your saved passwords live at [passwords.google.com](https://passwords.google.com){target=_blank}.

## Step 3: Bring in the passwords you already have

Your browser has probably been saving passwords for years. Move them into Bitwarden so you are not starting from zero.

1. Export the saved passwords from your browser to a file. In Chrome and Edge, open the browser's password manager settings and look for **Export passwords**. In Safari on a Mac, open the **Passwords** app, choose **File**, then **Export All Passwords to File**.
2. In Bitwarden's web app at [vault.bitwarden.com](https://vault.bitwarden.com){target=_blank}, go to **Tools**, then **Import data**, choose the matching format, select the file, and click **Import data**.
3. Delete the exported file from your computer. It contains every password in plain text and should not sit in your Downloads folder.

Step-by-step from Bitwarden: [Import from Chrome, Edge, and Chromium browsers](https://bitwarden.com/help/import-from-chrome/){target=_blank}; the same help section has guides for Safari, Firefox, and every other password manager.

If exporting sounds like too much, skip it. Bitwarden will offer to save each password the next time you log in to a site, and within a few weeks the vault fills itself.

## Step 4: Protect the manager itself with two-step login

The manager now holds the keys to everything, so it should be the most protected account you have. Turn on two-step login (also called two-factor authentication or 2FA) for Bitwarden itself. That means logging in on a new device requires your master password plus a code from your phone.

1. In the Bitwarden web app, click your profile icon, then **Account settings**, then **Security**, then **Two-step login**.
2. Choose **Authenticator app** and follow the prompts. If you do not already have an authenticator app, the Bitwarden app itself can be one, as can the Google Authenticator or Microsoft Authenticator apps.
3. Click **View recovery code**, write that code on the same paper as your master password, and store it with it. The recovery code is how you get back in if you lose your phone.

Bitwarden's instructions and video: [Set up two-step login](https://bitwarden.com/help/setup-two-step-login/){target=_blank}. [Turn on two-factor authentication](two-factor-authentication.md) covers doing the same for all your other accounts.

## Step 5: Replace the worst passwords first

You do not need to change every password today. Do these three now, because they are the ones that unlock everything else: your main email account, your bank, and your Apple Account or Google Account. For each one, log in, go to the change-password page, click the Bitwarden shield in the new-password field, and let it generate a long random password. Save it when Bitwarden offers.

Then let the manager tell you what else is bad. Apple Passwords has a **Security** section listing weak, reused, and leaked passwords ([Change weak or compromised passwords on iPhone](https://support.apple.com/guide/iphone/iphd5d8daf4f/ios){target=_blank}). Google has [Password Checkup](https://support.google.com/accounts/answer/9457609){target=_blank} at passwords.google.com. Bitwarden's equivalent, **Vault Health Reports**, is in the paid tier; if you are on the free tier, work from Have I Been Pwned instead, and change any password it flags. Work through the list a few at a time whenever you happen to log in to a site. Within a month or two every password you use regularly will be unique and strong without it ever having felt like a project.

## Questions people always ask

**What if the password manager company gets hacked?** Bitwarden and 1Password are built so that the company never has your master password and cannot decrypt your vault. If their servers were stolen outright, the thief would have an encrypted blob they cannot open without your master password. That is exactly why Step 1 matters, and why it has to be long. This is also why we no longer recommend LastPass: their vaults were stolen, and customers with short master passwords were exposed.

**Isn't it dangerous to have all my passwords in one place?** They are already in one place: your head, and your browser's memory. The question is whether that place has a strong lock and a backup. A password manager with a long master password and two-step login is far safer than anything you were doing before.

**What if I forget the master password?** You wrote it down in Step 1. If you did not, go do that now.

**What happens to my passwords if something happens to me?** The paper from Step 1 is the answer for family. 1Password's family plan and Bitwarden's paid tier both also offer a formal emergency-access feature where a named person can request access after a waiting period.

## What not to bother with

Do not pay for a password manager "security suite" bundled with antivirus or a VPN; the password manager inside those bundles is usually weaker than the free Bitwarden. Do not change your passwords on a schedule for no reason; change a password when it is weak, reused, or leaked, and otherwise leave it alone. Do not use "security questions" honestly; the name of your first pet is on your social media. Have the manager generate a random answer and save it in the notes for that site.

## Trusted references

1. Have I Been Pwned: [check whether your email address has been in a breach](https://haveibeenpwned.com/){target=_blank}, [check a password](https://haveibeenpwned.com/Passwords){target=_blank}, and [how the service works](https://haveibeenpwned.com/FAQs){target=_blank}.
2. Cybersecurity and Infrastructure Security Agency: [Use Strong Passwords](https://www.cisa.gov/secure-our-world/use-strong-passwords){target=_blank}.
3. Bitwarden: [First Steps with Bitwarden video course](https://bitwarden.com/help/courses/first-steps-with-bitwarden/){target=_blank} and the [Bitwarden Help Center](https://bitwarden.com/help/){target=_blank}.
4. 1Password: [Get started with 1Password](https://support.1password.com/explore/get-started/){target=_blank}.
5. Apple: [Set up iCloud Keychain](https://support.apple.com/en-us/109016){target=_blank}.
6. Google: [Get started with Google Password Manager](https://support.google.com/accounts/answer/6208650){target=_blank}.

--8<-- "_includes/site-footer.md"
