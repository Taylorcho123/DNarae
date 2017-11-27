Welcome to the Debugging Narae Project!

v 0.01.1.

A problem that users can not use command-line argument was resolved.

Usage : 
> python DNarae.py open [file1]

An Usage Example :
C:\Users\Jo>python C:\DNarae\DNarae.py open C:\Users\Jo\malware.bat
______ _   _
|  _  \ \ | |
| | | |  \| | __ _ _ __ __ _  ___
| | | | . ` |/ _` | '__/ _` |/ _ \
| |/ /| |\  | (_| | | | (_| |  __/
|___/ \_| \_/\__,_|_|  \__,_|\___|

Welcome to the DNarae v 0.01.1.

Usage:
    python DNarae.py open [filename|-]

Options:
    -h, --help     show this help message and exit
    -r, --restore  restore binary from hex dump

0x00000100 (01) 40                   INC AX
0x00000101 (04) 6563686f             ARPL [GS:BX+SI+0x6f], BP
0x00000105 (03) 206f66               AND [BX+0x66], CH
0x00000108 (01) 66                   DB 0x66
0x00000109 (01) 20                   DB 0x20
00000000: 40 65 63 68 6F 20 6F 66  66 20                    @echo off
