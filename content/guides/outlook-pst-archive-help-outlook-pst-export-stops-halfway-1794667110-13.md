---
title: "PST Export Finishes Without Expected Folders: A Controlled Fix"
description: "When your Outlook PST export completes but selected folders are missing, use this controlled diagnosis to restore the expected folder tree and verify the result."
seo_title: "Outlook PST Export Stops Halfway? Fix Missing Folders After Export"
seo_description: "When your Outlook PST export completes but selected folders are missing, use this controlled diagnosis to restore the expected folder tree and verify the result."
keywords:
  - "outlook pst export stops halfway"
date: 2026-11-25T12:03:27+08:00
publishDate: 2026-11-25T12:03:27+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You exported your classic Outlook archive to a new PST, but the finished file is missing the folders you selected, and you need to restore the expected outcome without guessing.

## Check the export scope before retrying

Open the export wizard again and stop at the folder selection screen. Expand every parent folder and confirm each subfolder has a check mark, not a filled square. A filled square means only some children are selected. Write down the exact folder paths you expect. Then cancel the wizard.

## Interpret the result correctly

If the new PST opens but lacks those paths, the export scope was incomplete or the source PST has a damaged folder tree. Do not delete the original archive. Instead, make a copy of the source PST and run Outlook's inbox repair tool (scanpst.exe) on the copy. If scanpst reports errors and repairs them, repeat the export from the repaired copy. If it reports no errors, the cause is selection scope, so reselect folders carefully.

## Run a verification test

Create a small test PST and export one parent folder with two subfolders. Open the test PST in Outlook and confirm all three appear. If they do, repeat the full export with the same careful selection. If they do not, the source profile is suspect; create a new Outlook profile, attach the source PST, and export again. This is where an **outlook pst export stops halfway** in effect, even though the progress bar completed.

## Rollback and recovery

Keep the original PST untouched until the new export is verified. If the new PST is incomplete, delete only the new file and restore from your backup copy before trying again. For a guided diagnosis of your specific folder tree,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult).
