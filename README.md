# sh-trash
Bash implementation of "trash-cli"

## Installation

1. Clone repo `git clone git@github.com:damiancypcar/sh-trash.git`
4. run `install.sh`
7. Done.

## Usage
    trash [file1] [file2]...
Moves the given file/s or directory to the trash folder (~/.trash/)
    
    trash -l
Shows the content of the trash folder
    
    trash -r file1 [-r file2 -r file3 ...]
Restores file/s or folder/s to their previous locations with their original attributes

    trash -R
Restores ALL file/s or folder/s to their previous locations with their original attributes
    
    trash -e
Empties the trash bin

    trash -p file1 [-p file2 -p file3 ...] 
Purge (delete permanently!) file/s or folder/s from the trash can.

    trash -v
Verbose. Add some additional information about the performed operation.

    trash -V
Show current version.

    trash -h
Show usage.

## Note
I not responsible for data loss! So know that if you use this script you MIGHT do some damage. Pay attention what you're doing and you'll be fine :)
