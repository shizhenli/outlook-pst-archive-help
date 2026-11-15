---
title: "PST Export Finishes Without the Expected Folders: Fixing Missing Inbox Subfolders"
description: "PST export completes but inbox folders are missing? Check selection scope, folder depth, and view filters, then verify with a test export and recover safely."
seo_title: "Outlook PST Missing Inbox Folders After Export: Targeted Fix"
seo_description: "PST export completes but inbox folders are missing? Check selection scope, folder depth, and view filters, then verify with a test export and recover safely."
keywords:
  - "outlook pst missing inbox folders"
date: 2026-11-15T18:48:51+08:00
publishDate: 2026-11-15T18:48:51+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## What you are seeing

You exported a local PST archive from classic Outlook, the progress bar completed, but the new PST is missing the inbox folders or subfolders you expected, leaving you stuck before a controlled diagnosis.

## Check the export scope first

In Outlook, open File > Open & Export > Import/Export > Export to a file. Walk back to the folder selection screen and confirm the inbox parent is expanded and every subfolder has a checkmark. A checked parent does not always include children in older builds; expand each level manually. If a subfolder is unchecked, the export finishes cleanly but omits it. Result interpretation: a completed export with unchecked children means the data was never copied, not corrupted.

## Confirm folder depth and filters

Switch to Folder view and check whether the missing folders sit under a search folder or a filter. Search folders export as empty containers. Also confirm the folders are not delegated or shared mailboxes, which do not export into a local PST. If they are shared, copy the items into a local folder first, then re-export.

## Verification test

Create a small test PST and export only the inbox plus one subfolder. Open it via File > Open & Export > Open Outlook Data File. If the subfolder appears, your original selection was incomplete. If it still does not, the source folder may be a search folder or the PST has reached its size limit.

## Rollback and recovery

Do not delete the original PST. Rename the incomplete export, keep the source intact, and repeat the export with corrected selections. If folders remain absent, this is the **outlook pst missing inbox folders** pattern that needs a deeper scan before you overwrite anything. For a guided diagnosis,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
