---
title: "PST Export Misses Inbox Folders: Check Sync, Views, and Selection Before Re-Export"
description: "PST export finishes without expected folders? Diagnose missing inbox subfolders in classic Outlook with sync, view, and selection checks, then verify and roll back safely."
seo_title: "Outlook PST Missing Inbox Folders After Export: Targeted Fix"
seo_description: "PST export finishes without expected folders? Diagnose missing inbox subfolders in classic Outlook with sync, view, and selection checks, then verify and roll back safely."
keywords:
  - "outlook pst missing inbox folders"
date: 2026-11-25T11:03:25+08:00
publishDate: 2026-11-25T11:03:25+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Understand the failure

Your PST export completes, but the new file lacks the inbox folders or subfolders you selected, and you want a controlled diagnosis before re-exporting. This usually means the folders were not fully synchronized, hidden by a view, or excluded at the selection step, not that the export engine failed.

## Check synchronization and folder visibility

Open the source PST in classic Outlook and press F9 to send/receive. Wait until the status bar shows all folders updated. Then switch to Folder List view (Ctrl+6) and confirm the missing folders appear there. If they do not, right-click the parent folder, choose IMAP Folders or Folder Properties, and verify the subfolders are subscribed. A folder that is unsubscribed or still syncing will not be written to the new PST even when the export reports success.

Next, reset the view: View > Change View > Messages, then View > Reset View. Hidden or filtered views can make folders look absent when they are present. If the folders now appear, the export selection dialog will list them correctly.

## Re-run the export with explicit selection

Start File > Open & Export > Import/Export > Export to a file > Outlook Data File (.pst). At the folder selection step, tick the top-level mailbox and enable Include subfolders. Expand each branch and confirm the inbox subfolders carry a checkmark. If any remain greyed out, cancel and repeat the sync check above. This is the most common cause of **outlook pst missing inbox folders** after a completed export.

## Verification test

Open the new PST with File > Open & Export > Open Outlook Data File. Compare the folder count against the source using Folder List view. Send a test message to one restored subfolder and confirm it lands in the new PST, not the original.

## Rollback note

Keep the original PST untouched until verification passes. If folders are still absent, delete only the new PST and re-export; never overwrite the source. For a guided review,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
