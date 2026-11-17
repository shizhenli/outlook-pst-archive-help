---
title: "PST Export Finishes Without the Expected Folders: Diagnosing a Missing Sent Items Folder"
description: "When your PST export completes but the Sent Items folder is missing, use this focused diagnostic to restore the expected folder tree."
seo_title: "Outlook PST Missing Sent Items: Fix Incomplete Export"
seo_description: "When your PST export completes but the Sent Items folder is missing, use this focused diagnostic to restore the expected folder tree."
keywords:
  - "outlook pst missing sent items"
date: 2026-11-17T08:06:32+08:00
publishDate: 2026-11-17T08:06:32+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished exporting your classic Outlook mailbox to a local PST archive, but the new file is missing the Sent Items folder and possibly its subfolders.

## Confirm the Export Scope Before Re-Exporting

Open the original PST in Outlook and right-click the Sent Items folder. Choose Properties and note the exact folder path. Then re-run the export wizard and, at the folder selection step, expand every parent node. A common cause is that Sent Items sits under a collapsed parent that was never checked. After export, open the new PST and compare the folder count against the source. If the count is lower, the selection was incomplete, not corrupt.

## Check for Folder Name and View Filtering

In the new PST, switch to Folder List view (Ctrl+6). If Sent Items is absent there but present in the source, the export skipped it. If it appears but looks empty, check View > Current View > Messages and clear any active filter. Also verify the folder is not hidden by a search folder. A folder that exists but shows zero items points to a filter or sync issue, not a missing export.

## Run a Verification Test

Create a temporary subfolder under Sent Items in the source PST, move one message into it, and export only that subfolder to a test PST. If the test PST contains the subfolder and message, your export method works and the original selection was at fault. If the test PST is also missing the subfolder, the source PST likely has a damaged folder tree, which explains your **outlook pst missing sent items** result.

## Rollback and Recovery

Do not overwrite the original PST. Keep the incomplete export as a reference, then repair the source with Scanpst.exe before repeating the export. If the folder tree remains incomplete,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before making further changes.
