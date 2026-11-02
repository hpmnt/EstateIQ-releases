# Security Policy

Thank you for helping keep EstateIQ and its users safe. EstateIQ holds people's most private records: serial numbers, documents, valuables and firearms. If you believe you have found a security vulnerability, please report it privately as described below. **Please do not open a public issue for security problems.**

## Supported versions

EstateIQ updates itself automatically. Security fixes are made in the **latest release** only, so please check that the problem still exists in the newest version on the [Releases page](../../releases) before reporting.

| Version | Supported |
| --- | --- |
| Latest release | ✅ |
| Older releases | ❌ (update to the latest release) |

## How to report a vulnerability

Open the **Security** tab of this repository and click **[Report a vulnerability](../../security/advisories/new)**. Only the maintainers can see the report. You need a free GitHub account.

Please include as much of the following as you can:

- the EstateIQ version (Settings › Updates) and your Windows version, and the phone app's version and Android version if the phone is involved
- what kind of problem it is (for example: reading the vault without the password, a weakness in the encryption, a paired-phone or sync problem, a problem with the update process, running code from a crafted backup or file)
- step-by-step instructions to reproduce it
- what an attacker could achieve, and anything you know about how to fix it

Please do **not** include your real master password, a real vault or backup, or other people's personal data in a report. Make a test vault with made-up items instead.

## What happens next

- We aim to confirm that we received your report within **3 business days**.
- We will investigate, keep you updated on our progress, and may ask you for more details.
- Once a fix is ready, it is published as a new release. EstateIQ installs it automatically for users who have automatic updates switched on.
- With your permission, we will thank you by name in the release notes. If you would rather stay anonymous, just say so.

Please give us a reasonable amount of time to fix the problem before you share details publicly. We will agree on a disclosure date with you; normally that is no later than **90 days** after your report.

## Scope

**In scope:** the EstateIQ Windows app, its installer and its updater, and the EstateIQ Android app it installs on paired phones, as published on this repository's Releases page. This includes the encrypted vault and backups, phone pairing and sync on the home network, fingerprint unlock and the update signature check.

**Out of scope:**

- Attacks that need someone who already controls your Windows account, has administrator access to the PC, or has your unlocked phone in hand.
- Guessing a weak master password. EstateIQ slows guessing down, but it can't make a short password strong.
- Problems in other programs and services EstateIQ works with (Outlook, your email app, Android's share sheet, UPCitemdb.com). Please report those to their makers. If EstateIQ itself uses them in an unsafe way, that **is** in scope.
- Social engineering, physical access, denial-of-service and spam.
- Reports from automated scanners without a demonstrated, working problem.

## Safe harbor

We will not take legal action against anyone who acts in good faith under this policy, which means:

- testing only on your own computer, your own phone and a test vault
- not accessing, changing or deleting other people's data
- reporting the problem privately and giving us time to fix it before going public

There is no paid bug bounty.
