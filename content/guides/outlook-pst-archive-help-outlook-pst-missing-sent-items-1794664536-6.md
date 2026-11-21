---
title: "Outlook PST Missing Sent Items: Why the Export Skips That Folder"
description: "Sent Items absent from a new PST export? Check folder selection, view filters, and archive scope, then verify with a test export and restore from the original PST."
seo_title: "Outlook PST Missing Sent Items: Fix a Skipped Export Folder"
seo_description: "Sent Items absent from a new PST export? Check folder selection, view filters, and archive scope, then verify with a test export and restore from the original PST."
keywords:
  - "outlook pst missing sent items"
date: 2026-11-21T15:11:10+08:00
publishDate: 2026-11-21T15:11:10+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished exporting your local archive to a new PST, but Sent Items never appeared in the result, and you want to confirm why before changing anything else.

## Confirm the folder was actually selected

In Outlook, right-click the source PST root and choose New Folder or open Folder Properties to inspect the tree. Then rerun File > Open & Export > Import/Export > Export to a file and stop at the folder-selection step. Expand every branch and confirm the Sent Items checkbox is ticked, not just its parent. If the parent is selected but the child is not, Outlook exports only the parent's direct contents. That single unchecked box is the most common cause of an **outlook pst missing sent items** result.

## Check the view and archive scope

Switch the source Sent Items to View > Change View > Messages and clear any filter with View > Reset View. A filtered view does not remove items from export, but it hides them during your count, which makes a complete export look empty. Also confirm you are exporting the archive PST, not the live mailbox: the live Sent Items and the archived Sent Items are separate stores.

## Verification test

Create a small test PST and export only Sent Items into it. Open the test file with File > Open & Export > Open Outlook Data File and compare the item count in the status bar with the source folder. Matching counts mean the export is sound; a zero count means the folder was empty or excluded at selection.

## Rollback and recovery

Keep the original PST untouched until verification passes. If the new file is incomplete, delete it and re-export from the original rather than editing the source. For a guided review of your folder tree,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
