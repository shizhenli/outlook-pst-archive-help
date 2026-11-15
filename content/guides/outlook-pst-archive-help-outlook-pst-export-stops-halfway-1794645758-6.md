---
title: "PST Export Completes but Selected Folders Are Missing: A Targeted Fix"
description: "Export completes but selected folders are absent from the new PST. Follow these targeted checks to restore the expected folder tree and verify the result."
seo_title: "Outlook PST Export Stops Halfway? Fix Missing Folders"
seo_description: "Export completes but selected folders are absent from the new PST. Follow these targeted checks to restore the expected folder tree and verify the result."
keywords:
  - "outlook pst export stops halfway"
date: 2026-11-15T18:48:51+08:00
publishDate: 2026-11-15T18:48:51+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You selected folders for export, the progress bar finished, but the new PST is missing subfolders, so the **outlook pst export stops halfway** in effect even though Outlook reports success.

## Confirm What Was Actually Exported

Open the new PST in Outlook and expand every root folder. Compare the visible tree against your selection list. If a parent folder appears but its subfolders do not, the export likely skipped nested items because the parent was collapsed or only partially selected. Re-run the export from File > Open & Export > Import/Export, choose Export to a file, and when the folder list appears, click each parent and verify every subfolder checkbox is ticked. A checked parent does not always include children in classic Outlook.

## Check for Filters and View Limits

Before exporting, clear any active filter (View > View Settings > Filter) and set the message view to show all items. Export honors the current view in some builds. Also confirm the folders are not empty due to a sync delay; open each one and press F5. If items appear after refresh, wait for sync to finish, then export again.

## Verification Test

Create a small test folder with one subfolder and two messages, export just that branch, and open the result. If the subfolder and both messages appear, your selection method is sound and the original issue was a partial selection. If they do not, repair the source PST with Scanpst.exe before retrying.

## Rollback Note

Keep the original PST untouched and work on a copy. If the new export is incomplete, delete only the new PST and repeat from the copy; never overwrite the source archive.

If the folder tree still will not export correctly,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
