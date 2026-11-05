# Mac Deficit

***Where did my space go?*** A disk space analyzer for the Mac, by [RawData Studio](https://rawdata.cloud).

Mac Deficit shows you, the moment it opens, what is filling your Mac's drive, and lets you clear it safely. It is built for Macs on Apple Silicon, and for anyone who has watched a 256 GB or 512 GB drive fill up and found macOS's own Storage panel no help.

**In development** · No release date yet

> This repository is Mac Deficit's public home: screenshots, progress, and a place for your questions and ideas. The app's source code is private while we build it.

## The Idea
- **See it at once**: your main drive's health the moment the app opens, external drives a click away
- **The Apple Treemap**: your drive drawn as an apple, the blocks inside it the folders and files eating its space. The bigger the block, the bigger the deficit
- **Go deeper with a click**: into any folder, block by block, or as a sorted list
- **Act with confidence**: Reveal in Finder, or move to the Trash after you see exactly how much space it gives back. Nothing is deleted for good without asking
- **Private by design**: everything stays on your Mac. No accounts, no analytics, no telemetry

## What's Built So Far
- **The Apple Treemap in the native app**: your drive drawn as blocks inside an apple, next to the list and always on the same folder. Folders take the colour of what fills them; hover for a block's name, size and share, click a folder to go inside
- **A native Mac app**, rebuilt in Swift: pick a drive or any folder, watch the scan count up with a Cancel button, then browse the results folder by folder, largest first, with Reveal in Finder
- Every drive as Finder sees it: its real name, capacity and free space, marked startup, internal, external or network
- A fast scan on every processor core: a whole internal drive of 1.9 million files and folders in about eight seconds, using about half a gigabyte of memory
- Sizes you can trust: the space files really take, hard-linked files counted once, shown in the same units as Finder
- Full Disk Access asked for, never assumed: the app explains why it helps and opens the right System Settings page, or carries on with limited access and lists every place it could not read

## From the Build
![The native app: a whole drive in a list and as an Apple Treemap](media/apple-treemap-native.png)
*The native app after a whole-drive scan: 305 GB in 1.7 million files, as a list and as an Apple Treemap. November 2026, work in progress.*

## Roadmap
| Phase | Status |
| --- | --- |
| Foundations | Complete · December 2025 |
| The Scanner | Complete · December 2025 |
| Seeing Your Drive | Complete · December 2025 |
| The Apple Treemap | In the native app · November 2026; blocks shaped to the apple next |
| Audit and Overhaul | In progress · scanner rebuilt (4× faster, half the memory), native Mac app with its Apple Treemap |
| Clearing Space (Trash, Reveal in Finder) | Next |
| Polish and Release | Planned |

## Get Involved
- **Questions, ideas, or just want to say hi?** Start a thread in [Discussions](../../discussions).
- **Feedback on something you've seen?** Open an [issue](../../issues/new/choose).
- **Follow along** at [rawdata.cloud](https://rawdata.cloud).
