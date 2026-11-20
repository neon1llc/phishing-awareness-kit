---
title: Workplace teams
description: "Adapting the session for an office or team: money attacks, account attacks, and making reporting quick and blame-free."
---

## Pace and setup

- Hold the full 60 minutes during work hours so everyone comes, leadership included.
- Ask IT or the office manager for real phishing messages the company received, with names removed, and how staff report them.
- Ask the most senior person present to say up front that reporting is welcome, even after a mistake.

## Which scams to show

Slides 7 (texts), 8 (calls and codes), and 10 (invoices), plus [boss and gift card requests](../guide/boss-gift-cards.md). Swap your company's real phishing examples into the [spot the scam](../exercises/spot-the-scam.md) cards. Run the [supplier bank change](../exercises/role-plays.md#2-the-supplier-bank-change-workplace) role-play with whoever pays invoices.

## What to emphasize

- **The callback rule for money.** Any bank detail change, urgent payment request, or gift card request gets a call to a number already on file. Have the finance lead say it out loud.
- **Reporting in under 30 seconds.** Show the report button or address live on screen.
- **No blame.** A fast report after a click limits the damage.
- **Two-step sign-in on work and personal email.** Many workplace breaches start with a personal account.

## For IT and security readers

An awareness hour is one layer, not a replacement for technical controls. The NCSC says no training, simulations included, teaches people to spot every phishing message.

- Publish SPF, DKIM, and DMARC for your domains, and move DMARC toward quarantine or reject, so your domain is harder to spoof.
- Add a one-click report button, tell people what happened to their report, and count reports as well as clicks.
- If you run phishing simulations, don't punish clicks. Blame discourages reporting, and the NCSC suggests checking with HR first.
- Move administrators and finance staff to phishing-resistant sign-in (FIDO2 security keys or passkeys) first. CISA calls FIDO/WebAuthn the only widely available phishing-resistant MFA.
- Rehearse a bank-change or wire request with finance, including the recall call to your bank.

## For companies with compliance needs

A session can count toward yearly security awareness training, but whoever sets the requirement (an auditor, insurer, or client) decides. Record attendance and the date, and keep the slides and quiz results. [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness) covers what auditors look for.

## Sources

- [Phishing attacks: dealing with suspicious messages](https://www.ncsc.gov.uk/guidance/phishing), from the UK NCSC: layered defences, reporting without blame, DMARC, SPF, and DKIM, and the limits of training and simulations.
- [Phishing Guidance: Stopping the Attack Cycle at Phase One](https://www.cisa.gov/resources-tools/resources/phishing-guidance-stopping-attack-cycle-phase-one), from CISA, NSA, FBI, and MS-ISAC: guidance for network defenders and for small and medium-sized businesses.
- [More than a password](https://www.cisa.gov/MFA), from CISA: MFA types, and why FIDO/WebAuthn is the phishing-resistant option.
- [Business email compromise](https://www.fbi.gov/how-we-can-help-you/scams-and-safety/common-frauds-and-scams/business-email-compromise), from the FBI.
- [How to recognize and avoid phishing scams](https://consumer.ftc.gov/articles/how-recognize-avoid-phishing-scams), from the FTC.
