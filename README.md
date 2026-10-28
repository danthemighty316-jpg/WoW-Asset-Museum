# Jeff Wayne's The War of the Worlds — Asset Museum

**Welcome to the Museum!** 🛸

Explore the original assets from the 1998 PC game, including Fighting Machines, buildings, terrain, battlefields, animations, artwork, sounds and more.

This is an unofficial, fan-made preservation project designed to let fans appreciate the incredible artwork and engineering behind the original game.

**You must provide your own original game files. No copyrighted game resources are included with the Museum.**

[**Download the latest Windows release**](https://github.com/danthemighty316-jpg/WoW-Asset-Museum/releases/latest)

**Windows x64 · Offline · Bring your own original game data**

## 1. Preparing your original game files

**IMPORTANT: The Museum requires the original, unmodified game resources from the 1998 Human and Martian discs.**

You can use your original physical CDs or original BIN/CUE disc images.

If using BIN/CUE images, mount or open each disc image using suitable software and extract the files and folders contained on the discs. Do not simply place the `.bin` and `.cue` files into the Museum's source folder.

### Combining both discs

1. Create a folder on your computer, for example `C:\War of the Worlds\Original Files`.
2. Extract or copy **all files and subfolders from the original Human CD first** into this folder.
3. Extract or copy **all files and subfolders from the original Martian CD second**, into the same folder.
4. **IMPORTANT: If Windows asks whether to overwrite or replace existing files, select NO / Skip these files / Do not overwrite.** Keep the Human files already present.
5. You should now have one combined folder containing the original resources from both discs.

**Do not use modified game files, patched resource archives or files from a WoWRevived/Thor-modified installation as the Museum's source.**

Thor's WoWRevived project provides valuable compatibility fixes for playing the game on modern systems. However, the Museum is designed to inspect the original, unmodified resources, rather than altered or patched game files.

Do not rename, modify or delete any of the original resource files.

## 2. Launching the Museum

1. Download the Windows ZIP from [Releases](https://github.com/danthemighty316-jpg/WoW-Asset-Museum/releases/latest), then extract the **whole Museum folder** into a separate folder. Keep its files together; do not copy only the EXE.
2. Double-click **WoWMuseum.exe**.
3. When prompted, select the combined folder containing your original Human and Martian disc resources.
4. Allow the Museum to validate and scan the files.
5. The Museum will open automatically in your default web browser.

**Keep the Museum launcher running while browsing.** Closing it will stop the local server.

No Python, Unity or programming knowledge should be required.

## 3. Exploring the Museum

Use the left-hand menu to browse the galleries:

- Fighting Machines and units
- Buildings
- Scenery and IOBs
- Battlefields and terrain
- Weapons and effects
- Artwork and interface elements
- Cinematics
- Sound effects and voice clips (CD music is not yet supported)
- Original resource archives

Select an exhibit to inspect it.

Depending on the resource, you may be able to rotate models, zoom, view animations, inspect components, examine original artwork or explore how objects were assembled.

The Museum is an ongoing preservation project. Some features may be experimental, incomplete or unavailable.

## 4. Battlefield loading — please read!

**Full battlefields can take a considerable amount of time to load. This is normal!**

Unlike a simple image viewer, the Museum reconstructs large original battlefields using the game's terrain and scenery data, including buildings, trees and other details.

Some maps contain millions of pixels and thousands of objects. Preparing a complete battlefield can take several minutes, depending on your computer.

Please allow the preparation to finish.

- Watch the progress indicator while the battlefield is being generated.
- Avoid repeatedly refreshing the browser during preparation.
- Once loaded, use the mouse wheel to zoom.
- Click and drag to explore the battlefield.
- Use **Fit map** to return to the full overview.
- Changing the time of day or scenery settings may require the map to be prepared again.

The Museum prepares the complete map before displaying it, allowing you to explore without continually loading new scenery as you move around.

## 5. Copyright and asset preservation

**The Museum opens your original game resources read-only and leaves them unchanged.**

All original game assets must be supplied by the user from their own original game media.

No original models, textures, audio, music, cinematics or proprietary game archives are distributed with the Museum.

The Museum runs locally on your computer. Your original game files are not uploaded to an online server and are not modified by browsing.

The Museum is intended for personal exploration, historical preservation and appreciation of the original game.

**This is not a playable copy of Jeff Wayne's The War of the Worlds.**

## 6. Known limitations

The Museum is still under development and may have rough edges.

Some objects, animations, visual effects and asset relationships are still being researched. Certain exhibits may not render perfectly or may lack complete functionality.

Original cinematics prepare locally when you press **Play movie**. The first play can take a little time; picture and PCM audio are decoded from your own SMK files. Temporary playback files are removed when the launcher closes. Unknown or modified movie versions may be unsupported. CD-audio music playback is not yet implemented.

Some regional editions or localized resources may not match the currently verified resource fingerprints. Missing or unsupported files are reported rather than replaced.

This initial Windows release is unsigned and is provided as an early-access preservation viewer.

Loading times can vary significantly, particularly for full battlefields.

If something doesn't work as expected, it may simply be a feature that hasn't been fully reconstructed yet.

## Enjoy exploring!

This Museum is part of a much larger, ongoing effort to understand, preserve and faithfully reconstruct Jeff Wayne's The War of the Worlds.

I hope you enjoy discovering the original game's artwork, models, battlefields and hidden details as much as I've enjoyed uncovering them.

Thanks to Thor and the wider War of the Worlds community for their ongoing dedication to keeping this classic game alive.

**ULLAAAA!** 🛸

---

*Unofficial, non-commercial fan preservation project. Not affiliated with or endorsed by the original game's rights holders. Original game assets remain the property of their respective rights holders.*

## Third-party notices

The download includes Python/Tcl/Tk licence notices and complete corresponding source, licence and rebuild instructions for the replaceable LGPL libsmacker cinematic decoder. No original game DLL is included. See `CREDITS_AND_LIMITATIONS.txt` and `third_party/libsmacker` inside the download.

This repository hosts Museum downloads, documentation and release-integrity information. Please report problems through its Issues page without attaching copyrighted game files or personal data.
