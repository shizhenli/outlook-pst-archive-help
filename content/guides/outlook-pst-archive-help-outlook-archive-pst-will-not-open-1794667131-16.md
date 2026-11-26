---
title: "PST Password Prompt Repeats or Blocks Access: A Controlled Diagnosis"
description: "Stuck at a PST password prompt you cannot pass? Diagnose a repeating or unknown archive password in classic Outlook and restore access without risking the file."
seo_title: "Outlook Archive PST Will Not Open: Fix the Repeating Password Prompt"
seo_description: "Stuck at a PST password prompt you cannot pass? Diagnose a repeating or unknown archive password in classic Outlook and restore access without risking the file."
keywords:
  - "outlook archive pst will not open"
date: 2026-11-26T09:02:34+08:00
publishDate: 2026-11-26T09:02:34+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You open your classic Outlook archive and a PST password prompt appears, but the password you remember is rejected or the prompt keeps returning.

## Confirm the prompt type before typing again

Close Outlook. Locate the archive PST in File Explorer, right-click it, and check Properties. If a password is set, the prompt is genuine and repeated guesses will not help. If no password is listed but Outlook still asks, the prompt is likely tied to a stale profile entry, not the file itself.

## Test with a fresh profile

Create a new Outlook profile and add the PST there without setting a password. If the archive opens, the original profile is holding a bad credential cache; return to it and remove the PST entry, then re-add it. If the prompt persists in the fresh profile, treat the file as password-protected and stop guessing. This is the point where many users find their **outlook archive pst will not open** because the prompt blocks every attempt.

## Verification test

After re-adding the PST, open the archive folder tree and confirm at least one known subfolder and message preview load. If the tree appears but messages fail, the password layer is cleared and a separate repair step is needed.

## Rollback note

Before changing profiles, copy the PST to a safe location. If the new profile cannot open it, restore the original profile and keep the copy untouched rather than running repair tools on the only file.

If the prompt still repeats after these checks,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before attempting password removal, since a wrong tool can corrupt the archive.
