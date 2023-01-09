# ARP Cache Logging Script

This is a simple script that automates the process of dumping the ARP cache to a log file every time the ARP cache is updated.

## How to Use

To use the script, make it executable with the `chmod` command and then execute it with `./script.sh`. You may also want to consider adding it to your system's startup scripts so that it runs automatically whenever the system boots.

## Script Details

The script first dumps the current ARP cache to the specified log file, and then it enters an infinite loop that checks the ARP cache for changes every second. If the ARP cache has been updated, the script appends the new ARP cache to the log file.

