---
title: "PST Export Omits Inbox Folders: Diagnose Before You Rebuild"
description: "Export finished but inbox folders are missing from the new PST? Run these targeted checks to confirm the cause and recover your folder tree safely."
seo_title: "Outlook PST Missing Inbox Folders After Export: Fix"
seo_description: "Export finished but inbox folders are missing from the new PST? Run these targeted checks to confirm the cause and recover your folder tree safely."
keywords:
  - "outlook pst missing inbox folders"
date: 2026-11-18T11:09:47+08:00
publishDate: 2026-11-18T11:09:47+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Confirm what the export actually copied

You exported your classic Outlook local archive to a new PST, the progress bar completed, but the Inbox tree looks thinner than expected. Before changing anything, open the new PST in Outlook with File > Open & Export > Open Outlook Data File and compare it side by side with the source archive. Expand every parent folder; subfolders sometimes land under a different parent rather than disappearing. If the folders are truly absent, note exactly which ones and whether they are Inbox subfolders, custom folders, or search folders.

## Check the export scope and folder selection

Re-run the export dialog only to inspect, not to finish. In the folder list, confirm the Inbox and its subfolders carry check marks; a checked parent does not always include children in older builds. Also verify you chose the correct source file, not a secondary archive with a similar name. If the missing items are search folders, remember they are views, not stored data, and are not exported. This is the most common reason for **outlook pst missing inbox folders** after a clean export.

## Verification test

Create a small test folder under Inbox in the source PST, place one message inside, and export just that branch to a fresh PST. Open the result: if the test folder appears, your selection method is sound and the earlier miss was scope-related. If it does not, stop and diagnose the source file before any repair.

## Rollback and recovery

Keep the original PST untouched until verification passes; work from a copy. If the export overwrote a prior file, restore it from your backup or the Recycle Bin before retrying. For persistent omissions,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running repair tools, since repair can alter the source.
