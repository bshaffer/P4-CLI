P4-CLI
======

This library contains wrapper functions which make Perforce more intuitive on the command line.  

## main commands

`p4-new`
  - display files which exist on the filesystem but not in the repository

`p4-deleted`
  - display files in the repository which do not exist on the filesystem  

`p4-diff`
  - provides a variety of options to display the changes on the filesystem.   
  - options:
    - `--show=open` - only show the diff of opened files
    - `--show=unopen` - only show the diff of unopened files

`p4-revert`
  - opens a file if it isn't already opened and then reverts it

## other commands

`p4-open`
  - allows you to view all edited files and open them all if desired.  

`p4-submit`
  - much like `p4 submit`, but allows you to add a `-m` command to commit the message right there  

`p4-sync`
  - shortcut for syncing  
