# winget-updater
A clone of Ubuntu Software Updater, but for Windows and winget. Written in PowerShell.

## Release Status
Incomplete, please wait for a release in the Releases tab.

## Goals
- Make a PowerShell script that would allow for checking `winget upgrade` and parsing the information into a rudimentary GUI.
  - The GUI would allow for the user to choose certain applications to upgrade, or just to defer to later.
  - The functionality of the GUI would be similar in nature to Ubuntu Software Updater.
- I don't want to have this run in the background all of the time, but instead to be ran with Task Scheduler.

### Disclaimer:
I'm not that well versed in PowerShell scripting and some (if not, most) of this code will be kinda jank. If you want to fix the jank, send in a pull request with cleaner code :).
