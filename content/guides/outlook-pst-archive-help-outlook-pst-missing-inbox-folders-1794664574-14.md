---
title: "PST Export Completes but Inbox Folders Are Missing: A Step-by-Step Fix"
description: "Export finishes but inbox folders are missing from the new PST? Follow these targeted checks to restore the expected folder tree and verify the result."
seo_title: "Fix: Outlook PST Missing Inbox Folders After Export"
seo_description: "Export finishes but inbox folders are missing from the new PST? Follow these targeted checks to restore the expected folder tree and verify the result."
keywords:
  - "outlook pst missing inbox folders"
date: 2026-11-22T08:03:29+08:00
publishDate: 2026-11-22T08:03:29+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

## Check the source folder selection before re-exporting

You exported your classic Outlook mailbox to a new PST, but the finished file is missing the inbox subfolders you expected. Start by opening the source PST in Outlook and confirming the folders actually exist there. Right-click the top-level folder, choose Properties, and note the folder count. Then expand every subfolder manually; a collapsed parent can hide children during selection. If the folders are present in the source, the export filter is the likely cause.

## Run the export with the correct scope

In Outlook, go to File > Open & Export > Import/Export > Export to a file > Outlook Data File (.pst). Select the root mailbox folder, tick Include subfolders, and verify the filter field is empty. A filter such as a date range or category will silently drop folders whose items do not match. Complete the export, then open the new PST via File > Open & Export > Open Outlook Data File. Compare the folder tree side by side with the source. If the expected folders now appear, the issue was scope. If they are still absent, the source PST may have a damaged folder table, which is a common cause of **outlook pst missing inbox folders** after export.

## Verification test

Create a test subfolder under Inbox in the source PST, place one message inside, and export again using the same steps. If the test folder appears in the new PST, your original selection was incomplete. If it does not, stop exporting and repair the source before retrying.

## Rollback and recovery

Keep the original PST untouched and work from a copy. Before any repair, duplicate the file and store it separately. If a repair tool alters the source unexpectedly, restore the copy and re-run the diagnosis. For a guided review of your folder tree,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
