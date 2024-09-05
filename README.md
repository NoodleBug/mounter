# mounter
## Simple script to list devices via lsblk and mount it to a place

Known bug: I wrote this super quick, so it lists everything from lsblk including the device itself, not just partitions like it should. Make sure you're choosing the number of a valid partition to mount, or it won't work :)

https://raw.githubusercontent.com/Noodle-Bug/mounter/main/mounter

To use, I usually just have the script somewhere my included in my $PATH, so just need to type `mounter` in terminal. 
Be sure to `chmod +x` it after downloading so you can actually run it.

Eventually I plan on making a little TUI interface around this concept. I'm sure there are many like it, but this one is mine :)
