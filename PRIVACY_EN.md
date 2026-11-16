# Privacy Policy for sCollect

Last updated: 2026-11-16

## In brief

sCollect collects, stores and transmits **no** personal data. The app works
exclusively on your Mac or Windows PC. There are no accounts, no cloud connection, no analytics
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

## On Windows

The sections above describe the Mac. On Windows, sCollect stores the following exclusively locally:

In the app’s data folder (`%LOCALAPPDATA%\Packages\<package>\LocalState` and `Settings`):

- **Settings, window position and view** — recently opened libraries, the sidebar selection, the tracks played last, columns and
  sort order.
- **The mapping of a library’s Mac folders to folders on your PC** (folder paths only).
- **Input suggestions** — values you have already used in fields such as genre or language.
- **A random identifier for this PC.** It tells your computers apart for copies of a library and contains nothing about you.
- **A diagnostic log** with times, operations and the file paths involved, and an **error log** (`fehler.log`, seven days).
  Both stay on your PC; you can pass them on when you report a problem.

In the library folder you chose: the catalog data, artwork, the library’s trash and — if it has copies — their locations and the
synchronizations not yet carried out. While sCollect has a library open, it also keeps a **lock file** there with the **name of your PC**, so that two
computers don’t write to the same library at the same time. If the library is on a network drive, other users of that drive can
see the name.

What is in the app’s data folder is removed when you uninstall the app; the library stays until you delete it yourself.

sCollect reads and writes media files only in the folders you give it. The app makes no network connections of its own, uses no
analytics and shows no advertising. Files that Windows doesn’t play itself are handed to the default program for the file
type — which one that is, you set in Windows. To convert and trim audio and video it uses the bundled FFmpeg, also only on your PC.

If you send a playlist to iTunes, sCollect opens iTunes for Windows with that playlist; the app controls no other programs. If you
export a playlist for VLC or a device, the app copies its files to the folder you choose.

## Microsoft Store

On Windows, purchase, download and updates are handled by the Microsoft Store; Microsoft’s privacy statement applies to them.

## No sharing, no analytics

There is no advertising, there are no analytics services, no crash reports to third
parties and no accounts.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
