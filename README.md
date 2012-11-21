TET Packages
============

This is a repository of my build scripts for various [TinyCore Linux][1]
extensions. Most of these have not been submitted for official inclusion in
the repository. If you'd like to see any of these be included, send me a note
or feel free to use my scripts to do it yourself.

You'll need to install [tc-ext-tools][2] to make use of this repository. It's
an amazing tool that a few community members of TC have put a lot of real work
into.

[1]: http://www.tinycorelinux.net
[2]: http://code.google.com/p/tc-ext-tools/

The Extensions
--------------

### Tint2-svn

A panel for Openbox. This is an update of tint2 to a very recent commit. With this, we can get cool
new features like launchers, and the ability to access the window manager's menu
from the panel!

### Xcompmgr-tint2

Light weight compositer. The version of xcompmgr in xtrans is 1.1.0. This
extension will build 1.1.5, and also include a patch that lets tint2 see it,
thereby getting real transparency.

### Golang 

[Go][3], the programming language from Google. Packages up the x86 binaries.

[3]: http://golang.org

### Vala

Use the version in the TC repositories. Seriously. I was just too impatient to
wait for bmarkus to submit an update.

### Dmenu

Dynamic menu for X. 

### DWM-Custom

Builds DWM after applying some patches to configure it to my liking. Currently 
doesn't set $DESKTOP, so it's a bit broken on boot. The volume key config
settings are also maybe not portable, as they're the actual keysym codes sent
by my current keyboard.
