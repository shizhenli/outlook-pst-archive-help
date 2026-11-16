---
title: "Outlook PST Import Shows No Messages: Why the Wizard Finishes Empty"
description: "Import wizard completes but no mail appears? Follow these checks to diagnose why Outlook PST import shows no messages and recover your archive safely."
seo_title: "Outlook PST Import Shows No Messages: Targeted Troubleshooting"
seo_description: "Import wizard completes but no mail appears? Follow these checks to diagnose why Outlook PST import shows no messages and recover your archive safely."
keywords:
  - "outlook pst import shows no messages"
date: 2026-11-16T08:03:18+08:00
publishDate: 2026-11-16T08:03:18+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished the import wizard expecting your archived mail, but the target mailbox still looks empty and you are stuck before any controlled diagnosis. Let's walk through this calmly.

## Confirm what the wizard actually imported

Open the import wizard's summary or log if it offered one. A completed wizard only means the file was read, not that items were placed where you expect. Check whether you chose "Import items into the same folder in" and selected the correct destination. If you picked a subfolder, expand that exact branch rather than the mailbox root. Also confirm the import filter was not limited to a date range or a single folder.

## Verify the source PST is not empty or misidentified

In Outlook, use File > Open & Export > Open Outlook Data File to attach the same PST as a separate data file. Expand it and count messages in Inbox and Sent Items. If the source shows mail but the import target does not, the issue is destination or filter. If the source also appears empty, the PST may be a stub, a different profile's file, or damaged. That distinction matters before you retry anything.

## Run a verification test

Create a temporary folder in the target mailbox, import only one small subfolder into it, and check the folder's item count in the status bar. If items appear, repeat with the full archive. If they do not, stop and record the exact wizard options used.

## Rollback and recovery

Before retrying, export a copy of the target mailbox or create a restore point for the PST. If duplicates appear after a second attempt, remove the temporary test folder rather than deleting original mail.

When the checks above still leave your **outlook pst import shows no messages** result unexplained, preserve the PST and ask for a guided review:

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
