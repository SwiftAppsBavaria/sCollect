# sCollect Help

## What the app does

sCollect manages media collections — music, films, home videos, audiobooks, podcasts,
e-books — and collectibles that are not media files at all, such as coins or stamps. What
the categories are called you set yourself under **Settings → Category Labels**.

What you enter in the editor the app writes **back into the file**, not just into its
own catalog.

## First steps

1. At the first launch, choose a folder for the library. That is where the catalog data
   lives later and, if you want it that way, the media files too.
2. Bring files or folders in via **File → Import Files** (⌘O) or **File → Import Folder**
   (⇧⌘O), or drag them onto the window.
3. On import you decide, run by run, whether the files are **copied to the library** or
   merely **linked**.

## Managed or linked?

| | |
|---|---|
| **Managed** | The file lies in the library. sCollect files it, names it according to your scheme and writes the tags. |
| **Linked** | The file stays where it is. sCollect remembers the location and **does not touch the file**. |

The “Linked” column in the list shows which applies.

## Frequently asked questions

**An entry has an orange warning triangle.**
Its file could not be found during the last run of **File → Library → Mark Missing Items**. The
entry cannot be edited then — there is nothing to write to. The context menu offers
**Find File…**; the file you point it to is brought back into the library.

**The context menu says “Drive not connected”, dimmed.**
Then it is not the file that is gone, but the disk. sCollect keeps the two cases
expressly apart: what is not connected cannot be checked either — and is therefore not
marked as missing. Connect the disk and run the pass again.

**A media type is gray and cannot be changed.**
Its folder is currently unreachable. sCollect locks such types instead of quietly filing
the files somewhere else. As soon as the disk is back, the lock is over.

**The editor says “One field differs from the file”.**
In one field the file carries something other than the library does — usually because
another program has edited it in the meantime. The strip above the fields shows which
ones are affected, and you decide field by field whether the value from the file is
adopted.

**I cannot find a field I need.**
For collectibles there are three freely nameable fields. What they are to be called you
set per category under **Settings → Field Labels**.

**Can I take my iTunes or Music collection with me?**
Yes. sCollect reads the iTunes XML including ratings and playlists. The tracks are
matched by their file paths; existing ratings are not overwritten.

**How do I get my collection out again?**
Through the **sCollect-XML** — it is lossless and serves as a backup at the same time.
Besides that there is the export as iTunes XML and as a playlist for Apple Music.

**What does the synchronization with copies do?**
A library can register other libraries as copies. Changes to the main library are
carried over to them, files and tags included. If a copy is offline, the change waits
and is made up later.

⚠️ **This is not a backup.** A deleted file is deleted in the copies as well — that is
what a synchronization is for. For the case that something goes wrong you need a real
backup in addition.

**Does my file lose quality when the tags are written?**
No. The audio and image data are taken over unchanged; nothing is re-encoded. Where it
is possible, sCollect changes only the few bytes of the tag instead of rewriting the
file.

**Do I need a backup?**
Yes. sCollect writes into your files, not into a copy of them. Make a backup before large changes to many entries at once; Time Machine is enough.

**Can I undo a change?**
⌘Z brings deleted entries back. Changes to metadata it does not — so make a backup
before a large batch run.

## Something went wrong?

sCollect writes a log into the folder of your library — it records what the app did and
when. Please send it along with your description of the problem.

## Contact

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
