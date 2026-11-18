---
title: "Outlook PST Import No Emails: Diagnose the Empty Import"
description: "Import wizard completes but the target mailbox shows no messages? Follow these checks to diagnose an empty PST import in classic Outlook and recover your mail."
seo_title: "Outlook PST Import No Emails: Fix the Empty Import"
seo_description: "Import wizard completes but the target mailbox shows no messages? Follow these checks to diagnose an empty PST import in classic Outlook and recover your mail."
keywords:
  - "outlook pst import no emails"
date: 2026-11-18T08:03:32+08:00
publishDate: 2026-11-18T08:03:32+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You ran the import wizard on your classic Outlook local PST archive, it finished successfully, but the target mailbox shows no imported mail. This is a common **outlook pst import no emails** symptom that usually points to a filter, a wrong target, or a hidden folder rather than a corrupt file. Work through these checks before assuming data loss.

## Check the import target and view

First, confirm where the wizard actually placed the data. In Outlook, open Folder List view (Ctrl+6) and expand every store under your profile. Look for a new top-level folder or a subfolder named after the PST. If you see it, the import worked and the messages are simply not in the view you expected. Next, check the View settings: apply View > Change View > Messages and clear any active filter (View > View Settings > Filter). A filter such as "unread" or a date range can hide every imported item.

## Check the PST file itself

Open the source PST directly with File > Open & Export > Open Outlook Data File. If the file opens and shows messages, the import target was wrong. If it opens empty, the PST may be an archive of only deleted items or a stub. Also verify the import option you chose: importing into the same folder as the source can create duplicates that appear missing.

## Verification test

Create a test folder in the target mailbox, import a single known subfolder into it, and count the items. If the count matches the source, your main import likely landed elsewhere; search All Mail Items for a unique subject line from the source PST.

## Rollback and recovery

Before retrying, export the current target mailbox to a backup PST so you can roll back. Then re-run the import, selecting the explicit destination folder. If the source PST still shows empty when opened directly, stop and

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before further imports.
