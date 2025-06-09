Each binaries folder contains folders for each individual change. The change folder's numbers match up to the section in the paper that they refer to (4.1|2.x).

The change folders all contain:
 - A "firmware" folder with the binary and config used.
 - A "changes.txt" file listing the changes compared to the previous change folder.
 - 1-3x "runX" folders that are runs using the current changes.
 - 1-3x "runX.png" files showing the coverage graph for the corresponding run.
 - A "runsCombined.png" file showing the runs combined into one graph, where there are multiple runs in the folder.

NOTE: The "settings.json" file in each run folder will need to be adjusted for your installation to allow opening the workdirs in FuzzMonitor.