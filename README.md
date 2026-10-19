>[!NOTE]
>Hello! I decided to archive this repository since I don't see much of a reason to update it for now, unless a critical reason shows up, so feel free to fork it and do your things if you want!
>
>I wanted to see further into which type of license I could put here, but the original artist for the cursors has deleted their account/site or something else has happened, so I don't know how I should approach this, Sorry about that.

# Hatsune Miku cursors for Windows/Linux!

![alt text](https://github.com/supermariofps/hatsune-miku-linux-cursors/blob/main/thumb.png?raw=true)

This cursor set is a modified version of a small Windows set created by [petit devil (ぷちでびる)](https://petitcan.blog.shinobi.jp) with a few original ones made by myself!
Thanks a lot to [@AshtakaOOf](https://github.com/AshtakaOOf) for [locating the original artist](https://github.com/supermariofps/hatsune-miku-windows-linux-cursors/issues/16)!

Hope you like it!

## Installation Instructions
You can download a ZIP of this repository by clicking the green _Code_ button above and selecting _Download ZIP_ or by cloning it.

### Linux
1. Copy the `miku-cursor-linux/` dir to `/usr/share/icons/` (system-wide) or `~/.local/share/icons/` (per-user).
2. [Select the theme through your DE's settings manager.](https://wiki.archlinux.org/title/Cursor_themes#Desktop_environments)
3. On KDE, the desktop and some apps may default back to a different cursor set that isn't the one you chose. To fix this, add the following to `/usr/share/icons/default/index.theme` or `~/.local/share/icons/default/index.theme`:
	```ini
	[Icon Theme]
	Inherits=miku-cursor-linux
	```

### Windows
1. Open the `miku-cursor-windows\` folder in the ZIP.
2. Right-click on `Install.inf` and select _Install_.

