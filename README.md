This script clears old screenshots out of OSX Desktop, which is the default location of screenshots in OSX.

Usage: Set cron job at desired interval or drop into /etc/periodic/daily (or desired period.)

If pasting command into a new .sh file be sure to run chmod +x filename.sh to make it executable.

TODO:
* Read com.apple.screencapture location to determine location to scan.
* Detect screenshots in file format or properties to avoid false positives.