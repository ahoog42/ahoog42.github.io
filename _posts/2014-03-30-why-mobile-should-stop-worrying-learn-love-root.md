---
layout: post
title: Why Mobile Should Stop Worrying and Learn to Love the Root
---

One of my talks at RSA 2014 tried to convince attendees that they [shouldn't fear root on mobile](https://viaforensics.com/articles-presentations/mobile-stop-worrying-learn-love-root-slides-pdf.html).  The talk, while lightly attended, seemed well received.  Max Eddy of PCMag did a nice write up on it entitled [Phones Can't Be Trusted, Security Needs Root in Mobile](http://securitywatch.pcmag.com/mobile-security/321227-phones-can-t-be-trusted-security-needs-root-in-mobile).

## Abbreviated "history" of root access

It's funny if you think about the history of privilege on computer systems (this is a broad generalization of computer history).  In the early days, everyone had full access.  This was mostly academia or researchers so the focus was on sharing (check out Steven Levy's [Hackers: Heroes of the Computer Revolution](http://en.wikipedia.org/wiki/Hackers:_Heroes_of_the_Computer_Revolution) if you're looking for a great read on the topic).  Over time, restricting user access and addressing security issues became a major focus.  Interestingly, though, when modern smart phones hit the market (of the iOS and Android variants), root access was revoked.  We were all so enamored with these new shiny things that we didn't pause and say, "Hey, I'm not so sure I'm OK with this!".

## Motivations for restricting root access

So, the obvious question is, "Why do modern smart phones restrict root access?" Well, this is conjecture, but here are a few ideas I've heard or made up:

1. Bloatware - making it hard to remove OS, OEM and Carrier app bloat
1. Quality assurance - make sure phone works (arguably one of the less used features these days)
1. Carrier lock in
1. Forcing App Store model - walled garden lock in

The most common reason I hear from industry insiders is #2. However, most informed consumers believe it's #1, #3 or #4.  Anyway, maybe you have other ideas...[please feel free to share](https://twitter.com/ahoog42).

Regardless of the reason, it's no secret that people often can gain root privilege on mobile devices.

## Downsides of restricting root

There are some big downsides to restricting root access:

* Enormously valuable engineering cycles are wasted on the cat and mouse game of gaining root on mobile devices.  Think of the brilliant things some of the top names in this game might come up with if they were focused on exploring new ideas, building new utilities and apps.
* "Cyber criminals" can gain root privilege, thus tipping the balance. Everyday consumers rarely root their devices and they cannot install software to monitor such things. If there is a 0-day for their device and they are targeted, advantage simply goes to the adversary.
* Mobile operating systems (and especially mobile apps) have security issues. This happens often and many times the issues are quite serious.  With no privilege on the device, there's nothing we can do but carry on.
* The entire security industry is locked out from developing solutions that might address some of these issues.  That's the great thing about a market economy.  Even if only a limited number of people really care about mobile security, it's still probably enough to support innovative companies and research.  Apple and Google might not jump down the various rabbit holes since they are focused on the needs of a billion users, but security researchers can solve problems for a much more niche need.

## Stop your bellyaching (what do you want, man!?)

So, here's what I'd love to see:

1. Apple Developer phone - I'll pay double, even move.  Just let the industry have a device so we can tinker, make the platform and apps more secure.  Props to Google/Android for doing this from day one.
1. Security vendor program - I guess this is similar to MDM APIs, but allow security vendors to gain additional privilege on devices if the enterprise/consumer approves.  Make the vetting process significant.  But allow security vendors the ability to secure mobile platforms in ways that Google and Apple might overlook or pass on.
1. A process by which an organization (generally a large one) can sign and deploy their own operating system.  This is likely an Android-only thing and both Samsung and LG seem to be headed in this direction.  The idea is sufficiently large organizations might choose to push their own AOSP image to devices.  It would allow them to patch quickly instead of relying on the failed carrier strategy.  Again, this is not for the faint of heart but I know some large organizations are interested in this.

In the end, I don't trust Apple, Google or anyone exclusively with mobile security.  The reality is security is hard and the current mobile industry is not incentivized to develop secure systems.  By locking everyone else out of root access, we've given all the advantage to adversaries with little chance for the security industry to innovate and address these problems.

I'm hopeful for a more secure future.