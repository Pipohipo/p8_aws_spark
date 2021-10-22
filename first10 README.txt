first10.cmd "C:\Temp\SourcePath" "C:\Temp\DestPath"

It reproduces the selected directory and only keeps the first 10 files of each subfolder.

First it prepares the destintation folder structure using xcopy.
Then it saves a list of all folders to a file, and loop over each one.
For each folder, it saves a list of all files in that folder, and loop over each file.
For each file, :docopy builds the copy command and executes it.

Source: https://serverfault.com/questions/237234/copy-first-10-files-from-a-folder-and-subfolders
