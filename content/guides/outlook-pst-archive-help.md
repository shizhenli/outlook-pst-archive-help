---
title: 'Outlook PST Export Missing Folders: Check the Root and Subfolders'
description: Compare an Outlook PST folder tree, message counts, and attachments against the source before trusting the archive.
seo_title: Outlook PST Missing Folders? Verify the Export Root
seo_description: Compare an Outlook PST folder tree, message counts, and attachments against the source before trusting the archive.
keywords:
- outlook pst missing folders
- outlook pst export missing emails
- verify pst archive
date: '2026-11-13'
draft: false
categories:
- Email Archive
category_slug: email-archive
---

**outlook pst missing folders**. 

<p>A PST can open successfully and still omit nested folders if the export started at the wrong level. Compare the tree before deleting or moving the source.</p>
<h2>Before you start</h2><ul>
<li>Classic Outlook on Windows</li>
<li>A copy of the PST and its original path</li>
<li>Access to the source mailbox/folder tree</li>
<li>Enough free space for a second export</li>
</ul>
<h2>Step-by-step checks</h2>
<h3>Step 1: Preserve the original</h3>
<p>Copy the PST to a working drive and mark the original read-only. Record its size and the Outlook profile that opens it.</p>
<p>Check: The working copy opens without modifying the original file.</p>
<h3>Step 2: Map the expected tree</h3>
<p>Write down the mailbox root and the nested folders you expect. Include sent, archive, and project subfolders rather than only the inbox.</p>
<p>Check: The expected tree has a root and at least one nested branch.</p>
<h3>Step 3: Inspect the PST tree</h3>
<p>Open the copy in Outlook and expand every level. Compare folder names and counts with the written map; note missing branches and date gaps.</p>
<p>Check: Every expected top-level and nested folder is accounted for.</p>
<h3>Step 4: Re-export the missing branch</h3>
<p>If a branch is missing, repeat the export from the mailbox root or the exact parent folder. Do not merge blindly into the existing PST.</p>
<p>Check: The new export contains the missing branch and its parent.</p>
<h3>Step 5: Open messages and attachments</h3>
<p>Open representative emails from each branch and save/open attachments. Confirm dates, sender, body, and file readability.</p>
<p>Check: A sample from every branch opens with its attachment.</p>
<h2>Verify the result</h2>
<p>The PST tree matches the written map, message counts are plausible for the selected range, and sample attachments open from the copy.</p>
<h2>Rollback</h2>
<p>Keep the original PST and the first working copy until the new export is verified. Remove only clearly labeled test copies.</p>
<p><a href="/#consult">Ask for help with this exact symptom</a> · All troubleshooting guides</p>
