# Lingmo OS Privacy Policy

Effective date: to be filled in
Scope: the Lingmo OS operating system and its official components

## 1. Overview

Lingmo OS is an open source operating system based on Debian. We respect your
privacy. This policy explains what information Lingmo OS handles while running
on your machine, where that information lives, and when - if ever - it leaves
your device.

Please note: **Lingmo OS requires no account to use and does not collect usage
data in the background by default.** There is no telemetry that is on unless you
turn it on.

## 2. Information kept on your device

The following stays on your machine and is never uploaded by us:

- system and package versions, installation time, partition and hardware details;
- your system settings, desktop configuration, wallpapers and themes;
- the local user name, host name, language and time zone;
- data and logs produced by the applications you run.

This content lives on your disk (for example under `/etc`, `/var` and
`~/.config`). You can inspect, change or delete it at any time.

## 3. When the system goes online

The system accesses the network only in these cases:

1. **Checking for and installing updates** - the package manager contacts the
   repositories configured in `/etc/apt/sources.list` (by default the official
   Lingmo OS repository and its mirrors) to fetch package indexes and updates.
   These requests contain nothing that identifies you personally.
2. **Time synchronisation** - it asks the time server you have configured for
   the current time.
3. **Actions you start yourself** - opening a browser, signing in to an online
   account, sending a bug report, and so on.

## 4. User Experience Program (optional, off by default)

Lingmo OS offers an optional User Experience Program. **It is disabled by
default**; only after you switch it on under Control Centre - System Information
does the system collect anonymous statistics (for example component crash counts,
feature usage frequency and hardware class) to find defects and improve the
experience.

You can switch it off at any time, and collection stops immediately. The program
never collects the contents of your files, what you type, your browsing history,
account credentials or your precise location.

## 5. Crash reports and logs

The system keeps logs locally so that problems can be diagnosed. They do not
leave your device unless you choose to upload them, for example by attaching them
to a bug report. Please review logs before sharing them.

## 6. Third-party software

Lingmo OS includes a large amount of free software from Debian and the wider
community. Those components may have privacy-relevant behaviour of their own
(browsers, messengers, cloud storage clients and so on). Their behaviour is
governed by their own privacy policies, which are outside the scope of this
document.

## 7. What we do not do

- we do not collect personal data without your consent;
- we do not sell, rent or trade your personal information;
- we do not put advertising or hidden tracking into your system;
- we do not record your keystrokes, screen contents or file contents at the
  operating system level.

## 8. Your rights

You may:

- inspect and delete any data the system produces on your machine;
- turn the optional User Experience Program off;
- uninstall any application that ships with the system;
- contact us through the channels below about how your data is handled.

## 9. Changes to this policy

This policy may be updated as the system evolves. Updated versions ship with
system updates and carry a new effective date. Significant changes will be
mentioned in the release notes or on our website.

## 10. Contact

- Website: https://lingmo.org/
- Support: https://lingmo.org/support
- Bug reports: https://bugs.lingmo.org/

---

This document describes the privacy practices of Lingmo OS. Where local law
grants you stronger protection of personal information, that law prevails.
