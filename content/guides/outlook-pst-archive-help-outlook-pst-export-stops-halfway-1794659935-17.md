---
title: "Why Your PST Export Skips Folders and How to Recover Them"
description: "Export completes but folders are missing? Learn why your PST export skips selected folders and how to recover the expected folder tree."
seo_title: "Outlook PST Export Stops Halfway: Fix Missing Folders"
seo_description: "Export completes but folders are missing? Learn why your PST export skips selected folders and how to recover the expected folder tree."
keywords:
  - "outlook pst export stops halfway"
date: 2026-11-18T12:04:36+08:00
publishDate: 2026-11-18T12:04:36+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You started a PST export expecting every selected folder, but the new file opened without them, and the export finished as if nothing went wrong.

## Check the export scope first

Open the export wizard again and stop at the folder selection screen. Expand every parent folder. A parent checkbox that looks selected may only be partially checked; subfolders are not included unless each one is ticked. Note exactly which folders are missing, then cancel without exporting.

## Check for filters and empty folders

In the same wizard, review the filter options. A date range or category filter can silently exclude entire folders. Also confirm the missing folders actually contain items in the source PST; empty folders are sometimes skipped. If a filter is active, clear it and note the result.

## Run a verification test

Create a small test PST: select one parent folder and two subfolders, export with no filters, then open the test file and count the folders. If all three appear, the original selection was incomplete. If they still vanish, the source PST likely has folder-tree damage, which is why **outlook pst export stops halfway** through the folder structure even though the progress bar completes.

## Repair before retrying

Close Outlook, back up the original PST, then run the Inbox Repair Tool (scanpst.exe) against it. Repeat the small test export afterward. Keep the backup until you confirm the folder tree is intact; if repair worsens things, restore the backup and do not overwrite the original.

## When the folder tree still will not export

If the test export keeps dropping folders after repair, stop repeating full exports. A controlled diagnosis of the PST structure is the safer next step; you can

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) with your test results.
