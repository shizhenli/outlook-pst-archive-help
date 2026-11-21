---
title: "PST Export Finishes Without Expected Folders: A Step-by-Step Diagnosis"
description: "Export completes but folders are missing from your new PST? Follow these technician steps to diagnose and restore the expected folder tree in classic Outlook."
seo_title: "Fix PST Export Missing Folders: Targeted Diagnosis for Outlook"
seo_description: "Export completes but folders are missing from your new PST? Follow these technician steps to diagnose and restore the expected folder tree in classic Outlook."
keywords:
  - "outlook pst missing folders"
date: 2026-11-21T15:14:26+08:00
publishDate: 2026-11-21T15:14:26+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You finished a PST export, but when you open the new file, some selected folders or subfolders are simply not there. This is a common and frustrating issue, but it is usually fixable with a controlled approach.

## Check the Export Scope First

Open the export wizard again (File > Open & Export > Import/Export). When you reach the folder selection step, verify that the folders you expect are actually checked. A frequent cause is that subfolders are collapsed and not selected. Expand each parent folder and confirm every desired subfolder has a checkmark. If they are missing from the list entirely, the folders may not exist in the source PST or may be hidden. In Outlook, go to View > Folder Pane > Options and enable "Show hidden folders" to check.

## Verify the Source PST Structure

Before exporting, open the source PST directly. Right-click the root folder and choose Properties > Folder Size to see if subfolders are counted. If the folder count seems low, the PST may have structural damage. Run the Inbox Repair Tool (scanpst.exe) on the source file. After repair, reopen Outlook and check if the folders reappear. If they do, re-export.

## Perform a Verification Test

Create a small test folder with a few emails inside the source PST. Export only that folder to a new PST. Open the new PST and confirm the test folder and its contents are present. If they are, the export process works; the issue is likely selection or hidden folders. If they are not, the PST itself may be corrupt.

## Rollback and Recovery Note

Before any repair or re-export, make a backup copy of your original PST. If scanpst.exe makes changes you do not want, restore from the backup. For persistent **outlook pst missing folders** after these checks, consider professional assistance to avoid further damage.

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) if the folder tree remains incomplete after a verified export.
