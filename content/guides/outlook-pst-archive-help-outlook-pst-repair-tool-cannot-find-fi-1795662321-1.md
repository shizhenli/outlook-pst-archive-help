---
title: "When the PST Repair Tool Can't Find Your Archive File"
description: "Outlook says your archive PST cannot be opened or is corrupt, but the repair tool cannot find the file. Check the real path, permissions, and hidden extensions before you repair."
seo_title: "Outlook PST Repair Tool Cannot Find File: Fix the Path"
seo_description: "Outlook says your archive PST cannot be opened or is corrupt, but the repair tool cannot find the file. Check the real path, permissions, and hidden extensions before you repair."
keywords:
  - "outlook pst repair tool cannot find file"
date: 2026-11-28T22:14:41+08:00
publishDate: 2026-11-28T22:14:41+08:00
draft: false
categories:
  - "Email Archive"
category_slug: "email-archive"
---

You are in classic Outlook, the archive PST will not open, and the repair tool reports it cannot find the file you just selected.

## Confirm the actual file path

Open File Explorer, paste the archive path from Outlook's account settings into the address bar, and press Enter. If Explorer opens the folder, the file exists and the repair tool is being pointed at the wrong location. If Explorer says the path is unavailable, the PST sits on a disconnected drive or a mapped network share that is offline. Copy the PST to a local folder such as C:\Users\YourName\Documents\Archive, then browse to that copy in the repair tool. The result you want is the tool listing the file and starting a scan; if it still says the file is missing, the selected item is a shortcut or a zero-byte placeholder, not the PST.

## Check hidden extensions and permissions

In File Explorer, enable file name extensions. A file named archive.pst.pst or archive.pst.tmp is not the archive. Rename only a copy, never the original. Right-click the PST, choose Properties, and confirm it is not marked read-only and that your Windows account has full control. A permission denial often surfaces as a missing file. If the tool still cannot see it, the **outlook pst repair tool cannot find file** error is usually a path or access problem, not corruption.

## Verify before repairing

Make a copy of the PST first. Run the repair tool on the copy and confirm it completes a scan. Then open the repaired copy in Outlook via File, Open, Outlook Data File.

## Rollback note

Keep the original PST untouched until the repaired copy opens and shows your folders. If the repair fails, delete the copy and retry with a fresh copy from the original.

If the path is correct and permissions are fine but the tool still fails,

![Outlook folder tree beside a PST archive verification checklist](/images/service-detail-960.webp "Outlook PST folder and attachment check")

[Ask for help](/#consult) before running further repairs.
