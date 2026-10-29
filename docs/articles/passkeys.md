---
title: What is a passkey and why you should use them
description: Plain-language explanation of passkeys, why they are safer than passwords and cannot be phished, where they are stored, and how to set one up for your Google, Apple, Microsoft, Amazon, and PayPal accounts.
---

# What is a passkey, and why you should use them

!!! info "Last reviewed October 29, 2026"
    This guide assumes you have already set up a password manager and turned on two-factor authentication for your main accounts. If not, start with [Why you must use a password manager](password-manager.md) and [Turn on two-factor authentication](two-factor-authentication.md); passkeys build on both.

## The short version

A passkey replaces the password for a website or app with the thing you already use to unlock your phone: your face, your fingerprint, or your device passcode. There is nothing to remember, nothing to type, nothing that can leak in a data breach, and nothing a fake website can trick you into handing over. Signing in takes about two seconds.

Passkeys are the way the industry is moving. Apple, Google, Microsoft, Amazon, PayPal, and a growing list of banks and retailers already offer them. When a site you use offers to create one, say yes. For the big accounts, do not wait to be offered; go and set one up this week using the steps below. Keep your password manager; passkeys live inside it, next to the passwords they replace.

## What a passkey actually is

A password is a secret you know and the website also knows. That is the whole problem with passwords: because the website has a copy, a breach at the website exposes it, and because you type it in, a fake website can collect it.

A passkey works differently. When you create one, your device generates a matched pair of keys. One half stays on your device and never leaves it, protected by the same hardware that protects your face or fingerprint data. The other half goes to the website. When you sign in, the website sends your device a challenge, your device unlocks with your face or fingerprint and answers it using its half of the key, and the website checks the answer against its half. At no point does anything secret travel over the internet or get stored on the website. If the website is breached, the attacker gets the public half, which is useless on its own.

Two things follow from this. First, every passkey is unique to one site by construction; there is no way to reuse one, so the entire problem described in [the password-reuse guide](password-reuse.md) disappears for any account that uses a passkey. Second, a passkey is tied to the real website's address. If you land on a lookalike site, `arnazon.com` instead of `amazon.com`, your device simply will not offer the passkey, because it does not match. That is why passkeys are described as phishing-resistant, and why they are the method security agencies now recommend above all others. There is also no six-digit code involved, so the "read me the code you just received" phone scam described in [the two-factor guide](two-factor-authentication.md#what-two-factor-authentication-does-not-protect-against) has nothing to work with.

The standard behind passkeys is maintained by an industry group called the FIDO Alliance, whose [consumer explanation of passkeys](https://fidoalliance.org/passkeys/){target=_blank} is the authoritative version of this section.

## Where your passkeys live

A passkey has to be stored somewhere, synced between your devices, and backed up. You have the same three choices as for passwords, and the right answer is the same one you made in the password manager guide: use the one you already chose.

If you use **Apple Passwords**, passkeys are stored in the Passwords app and synced through iCloud Keychain to every Apple device signed in to your Apple Account. Apple's overview: [Use passkeys on iPhone and iPad](https://support.apple.com/guide/platform-support/use-passkeys-in-iphone-and-ipad-sup742154734/web){target=_blank}.

If you use **Google Password Manager**, passkeys are stored there and synced to every Android device and Chrome browser signed in to your Google Account.

If you use **Bitwarden** or **1Password**, their browser extensions and phone apps store passkeys as part of the login entry for each site, synced everywhere you use the manager, and this is the choice that works across an iPhone and a Windows PC, or an Android phone and a Mac. Bitwarden's instructions: [Autofill passkeys](https://bitwarden.com/help/storing-passkeys/){target=_blank}. 1Password's instructions: [Save and sign in with passkeys in your browser](https://support.1password.com/save-use-passkeys/){target=_blank}.

When a website offers to create a passkey, your phone or browser will ask where to save it, and the options above appear in that list. Pick the same one every time. A passkey saved to the wrong place is not lost, but it will not show up on your other devices, which is confusing for no good reason.

## Step 1: Your Google Account

1. On the phone or computer you use most, go to [myaccount.google.com/signinoptions/passkeys](https://myaccount.google.com/signinoptions/passkeys){target=_blank} and sign in if asked.
2. Tap or click **Create a passkey**.
3. Unlock your device when prompted (Face ID, fingerprint, or passcode) and confirm where to save it.
4. Repeat on any other device you regularly sign in from, or skip this if your passkeys are stored in a password manager that syncs between them.

From then on, the Google sign-in screen will offer the passkey first. Google's instructions: [Sign in with a passkey instead of a password](https://support.google.com/accounts/answer/13548313){target=_blank}. Google only creates passkeys on devices you choose, and it warns, correctly, that anyone who can unlock a device holding your passkey can get into your account; do not create one on a shared or borrowed computer.

## Step 2: Your Apple Account

Your Apple Account already works this way. The two-factor system you confirmed in the previous guide means that signing in to Apple services from a new device is approved on a device you already own, and on iOS 17 and later, Apple's own websites sign you in with a passkey automatically from your iPhone. There is nothing to set up.

What you do need to do on an Apple device is make sure passkeys for other sites can be created and synced: open **Settings**, tap your name, tap **iCloud**, tap **Passwords**, and confirm that syncing is on. If you store passkeys in Bitwarden or 1Password instead, confirm that app is selected under **Settings**, **General**, **AutoFill & Passwords**, as described in the password manager guide.

## Step 3: Your Microsoft account

If you have an Outlook.com, Hotmail, Xbox, or other personal Microsoft account:

1. Go to [account.microsoft.com/security](https://account.microsoft.com/security){target=_blank} and sign in.
2. Choose **Add a new way to sign in or verify**.
3. Choose **Face, fingerprint, PIN, or security key**.
4. Follow the prompts; when asked where to save the passkey, choose your password manager or your phone.

Microsoft's instructions: [Create and save a passkey](https://support.microsoft.com/en-us/account-billing/create-and-save-a-passkey-e92cd3e0-11fa-4630-a5ea-3ccc0396b3d9){target=_blank}.

## Step 4: Amazon and PayPal

These two are worth doing deliberately because they hold your payment details and are among the most impersonated sites on the internet.

**Amazon.** In the Amazon app or on the website, go to **Your Account**, then **Login & Security**, then select **Set up** next to **Passkeys**, and follow the prompts. Amazon's description: [Passwordless sign-in with passkeys](https://www.aboutamazon.com/news/retail/amazon-passwordless-sign-in-passkey){target=_blank}.

**PayPal.** Sign in on the website or app, then follow the prompts on PayPal's passkey creation page, linked from its help article [What is a passkey and how do I use it to log in to my PayPal account?](https://www.paypal.com/us/cshelp/article/what-is-a-passkey-help997){target=_blank}.

## Step 5: Everything else, as it comes

Most sites that support passkeys will offer to create one the next time you sign in, with a prompt along the lines of "Sign in faster next time with a passkey." Accept it. Beyond that, you do not need to go hunting; check the security settings of any account that holds money or personal information the next time you are in it, and look for the word passkey. 1Password's Watchtower feature and Bitwarden's reports will also flag saved logins for sites that now support passkeys.

## What to expect when you sign in

On the device where the passkey is stored, you will type or select your username, the site will ask for the passkey, you will unlock with your face, fingerprint, or passcode, and you will be in. Many sites skip the username step entirely and just offer the passkey.

On a device that does not have the passkey, say a friend's laptop or a hotel business-center computer, the site will show a QR code. Scan it with your phone's camera, approve on the phone, and the laptop signs in. Nothing is copied to the laptop; the passkey never leaves your phone. This is the one situation where you will be glad you kept a password as well, in case the QR step does not work, so do not delete the password yet.

## Keep the password and keep two-factor on, for now

For the next few years most sites will keep your password as a fallback alongside the passkey, which means an attacker who has the password can still use it. So, for now, the passkey is an upgrade to your login rather than a replacement for everything else: keep a long unique password for the site in your manager, and keep two-factor authentication turned on. Some sites, Google among them, let you choose to skip the password entirely once you have a passkey; that is a good setting to turn on once you have passkeys on all the devices you use. Over time, more sites will let you remove the password altogether, and when that option appears for an account you have a passkey on, take it.

## Questions people always ask

**Does the website get my fingerprint or my face?** No. Your face or fingerprint only unlocks your own device; the website receives a cryptographic answer, never any biometric data. Google and Apple both state this explicitly.

**What if I lose my phone?** If your passkeys are synced (Apple Passwords with iCloud, Google Password Manager, or a password manager), they appear on your new phone when you sign in to it. If you also kept the password and two-factor backup codes as the previous guides describe, you have a second way in regardless.

**What if I get a new phone?** Same answer: sign in to your password manager or your Apple or Google account on the new phone and the passkeys come with it.

**Can I share a passkey with my spouse?** Not by reading it out loud, which is the point. Both 1Password and Bitwarden family plans let you share a login entry that includes a passkey, so the other person's devices can use it.

**My bank does not offer passkeys.** Most do not yet. Keep the strong unique password and whatever two-factor the bank offers, and check again in a year.

**Is this the same as "Sign in with Apple" or "Sign in with Google"?** No. Those let one account log you in to another site. A passkey is a direct credential for the site itself and does not depend on a third account.

## What not to bother with

You do not need a hardware security key to use passkeys; your phone is the hardware. Security keys are the right tool for people who are specifically targeted, and if that describes you, open a ticket. You also do not need to go back and create passkeys for every account you own this week. The accounts above, plus anything with your money in it, are enough; let the rest happen as sites offer.

## Trusted references

1. FIDO Alliance: [Passkeys](https://fidoalliance.org/passkeys/){target=_blank}.
2. Google: [Sign in with a passkey instead of a password](https://support.google.com/accounts/answer/13548313){target=_blank}.
3. Apple: [Use passkeys on iPhone and iPad](https://support.apple.com/guide/platform-support/use-passkeys-in-iphone-and-ipad-sup742154734/web){target=_blank} and [Sign in to an account on your Mac with a passkey](https://support.apple.com/guide/passwords/mchl4af65d1a){target=_blank}.
4. Microsoft: [Create and save a passkey](https://support.microsoft.com/en-us/account-billing/create-and-save-a-passkey-e92cd3e0-11fa-4630-a5ea-3ccc0396b3d9){target=_blank}.
5. Bitwarden: [Autofill passkeys](https://bitwarden.com/help/storing-passkeys/){target=_blank}. 1Password: [Save and sign in with passkeys](https://support.1password.com/save-use-passkeys/){target=_blank}.
6. Amazon: [Passwordless sign-in with passkeys](https://www.aboutamazon.com/news/retail/amazon-passwordless-sign-in-passkey){target=_blank}. PayPal: [What is a passkey](https://www.paypal.com/us/cshelp/article/what-is-a-passkey-help997){target=_blank}.

--8<-- "_includes/still-need-help.md"
