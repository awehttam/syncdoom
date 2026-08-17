This is a nativedoor configuration for BinktermPHP, for the SyncDOOM door
game by Rob Swindell.

SyncTERM 1.10+ is required for JPEG-XL and audio, otherwise the game will
fall back to ANSI graphics and not look so great.

These instructions are a bit terse ATM, and only provides for a single
player deathmatch instance.

You'll need a copy of syncdoom from a deployed installation on a Synchronet
BBS:
 * Compile/Build syncdoom
 * Deploy
 * Install in Synchronet
 * Archive xtrn/syncdoom and extract the contents to this directory
   (nativedoors/doors/syncdoom)

Then in BinktermPHP install/activate the SyncDOOM door.

Your syncdoom nativedoor/doors/syncdoom directory should end up looking
something like this:

```text
total 3508
drwxr-xr-x 3 claudebbs claudebbs    4096 Aug 17 12:13 .
drwxr-xr-x 8 claudebbs claudebbs    4096 Aug 16 20:26 ..
-rw-r--r-- 1 claudebbs claudebbs     343 Aug 17 12:11 README.md
-rw-r--r-- 1 claudebbs claudebbs    7039 Aug 16 19:31 README.syncdoom.md
-rw-r--r-- 1 claudebbs claudebbs    1227 Aug 16 19:31 controls.msg
-rw-r--r-- 1 claudebbs claudebbs    1162 Aug 16 21:51 default.cfg
-rw-r--r-- 1 claudebbs claudebbs    1178 Aug 16 21:51 doomgenericdoom.cfg
-rw-r--r-- 1 claudebbs claudebbs    2739 Aug 16 19:31 get-binary.js
-rw-r--r-- 1 claudebbs claudebbs    6067 Aug 16 19:31 getwads.js
-rw-r--r-- 1 claudebbs claudebbs    5292 Aug 16 19:31 install-xtrn.ini
-rw-r--r-- 1 claudebbs claudebbs   35455 Aug 16 19:31 lobby.js
-rw-r--r-- 1 claudebbs claudebbs    3275 Aug 16 19:31 lobby.msg
-rw-rw-rw- 1 claudebbs claudebbs    1293 Aug 17 12:04 nativedoor.json
-rwx--x--x 1 claudebbs claudebbs 3409120 Aug 17 11:06 syncdoom
-rw-r--r-- 1 claudebbs claudebbs   22229 Aug 16 19:31 syncdoom.example.ini
-rw-r--r-- 1 claudebbs claudebbs   22229 Aug 16 19:31 syncdoom.ini
-rw-r--r-- 1 claudebbs claudebbs     606 Aug 17 12:12 syncdoom.log
-rwxr-xr-x 1 claudebbs claudebbs      70 Aug 17 12:03 syncdoom.sh
-rw-r--r-- 1 claudebbs claudebbs   13883 Aug 16 19:31 syncdoom_lib.js
drwx------ 3 claudebbs claudebbs    4096 Aug 16 20:29 wads
-rw-r--r-- 1 claudebbs claudebbs    4000 Aug 16 19:31 waiting.bin
```
