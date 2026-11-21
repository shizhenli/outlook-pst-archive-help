---
title: "Outlook Archive PST Will Not Open: Fix the Repeating Password Prompt"
description: "Stuck at a repeating PST password prompt that blocks access to your Outlook archive? Follow these targeted checks to diagnose and regain access."
seo_title: "Outlook Archive PST Will Not Open: Fix the PST Password Prompt"
seo_description: "Stuck at a repeating PST password prompt that blocks access to your Outlook archive? Follow these targeted checks to diagnose and regain access."
keywords:
  - "outlook archive pst will not open"
date: 2026-11-21T15:08:05+08:00
publishDate: 2026-11-21T15:08:05+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You are trying to open your local Outlook archive, but the PST password prompt keeps appearing or rejecting the password you thought you had, so the archive never opens.

## Confirm the prompt type and behavior

First, close Outlook. Press Ctrl+Shift+Esc to open Task Manager and end any lingering Outlook processes. Reopen Outlook and try the archive again. Note exactly when the prompt appears: before the folder tree loads, after you click the archive, or repeatedly after you cancel. If it repeats immediately after cancel, the PST is likely set to require a password each session. If it rejects every entry, treat it as a forgotten or corrupted password record, not a wrong keyboard layout.

## Test with a copy and a new profile

Make a copy of the PST file in File Explorer before changing anything. Then create a new Outlook profile (Control Panel > Mail > Show Profiles > Add) and add the copied PST there. If the prompt still blocks access, the password is stored in the file itself. If the copy opens without a prompt, the original profile's credential cache is the culprit. This verification test tells you whether to repair the file or reset the profile.

## Recover access and roll back safely

If the copy still prompts, do not keep guessing passwords; repeated attempts can lock the file further. Use a PST password recovery utility on the copy only, then reopen it in the new profile. If recovery fails, restore the original PST from your backup and repeat the copy test. Keep the untouched original until the archive opens reliably. For a guided diagnosis of why your **outlook archive pst will not open**,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).

Once the copy opens without a prompt, reconnect the original PST in your main profile and confirm the folder tree loads before deleting any copies.
