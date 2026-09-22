# Privacy Policy for sCollect

Last updated: 2026-09-16

## In brief

sCollect collects, stores and transmits **no** personal data. The app works
exclusively on your Mac. There are no accounts, no cloud connection, no analytics
services and no advertising.

## What data the app processes

sCollect reads and writes the media files in the folders you have explicitly handed to
it — by choosing them in the open dialog or by dragging them onto the window. What is
read is the file name, file size, date and the file’s metadata; what is written are the
entries you make in the editor.

Without your selection the app accesses no file at all. macOS enforces this through the
App Sandbox.

## What the app stores on your Mac

- **The library itself** in the folder you chose for it: the catalog data, the cover
  images and a log of the synchronizations not yet carried out.
- **Settings and window positions** in the app’s protected container folder.
- **The permission from macOS to reopen your folders at the next launch.** What is
  stored are folder paths, not file contents. It is the only way for the app not to have
  to ask again at every launch.
- **A diagnostic log** with the times and counts of operations. It stays on your Mac;
  you can save it and pass it on if you report a problem.

All of this is gone once you delete the app and its library.

## Two permissions that may raise questions

**Network access.** The app asks for it because macOS shows the built-in help window
empty without this permission — the help is rendered by a system component that needs
it, even though it only loads files from the program itself. sCollect calls up **no
address on the internet** of its own accord, downloads nothing and reports nothing.

Libraries on network volumes (SMB, NFS) are reached by the app through your Mac’s file
system, not through a connection of its own.

**Controlling Apple Music.** When a playlist is exported, sCollect opens Apple Music
with the file it has created. macOS asks for your consent for that, and it is asked the
first time. The app controls no other programs.

## Your files

sCollect changes the metadata in exactly those files that belong to your library, and
when filing them it moves them within the folders you have granted access to.

**Linked items are left untouched** — they lie outside the library, and the app writes
nothing there.

Deleted files first move to a trash of their own inside the library and can be brought
back from there. They are removed for good only when you empty it.

## No sharing, no analytics

There is no advertising, there are no analytics services, no crash reports to third
parties and no accounts.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
