# VimLogViewer : log viewer like edit++ 

created by
Sung Keun Kim

maintained by
Aloys jiangxinnju@163.com
 
script type
utility
 
description
This script has useful utilities for viewing log files(ex. Android logcat) 
[Features] 
1. searching keyword 
you can searching the words you want to find from logs. and this results is put in the quick fix. 
,f          : search the word on current cursor position from current buffers(erase old list) 
,F         : search the word on current cursor position from current buffers(add to list) 
you'll see result at quickfix view atfer typing short key, type ": copen" 

2. keyword highlight 
If you want to highlight the keywords in the logs, you can do it by short cuts below. 
first, move the cursor to the keywords you want to highlight. and then type "\" + number 
you can highlight ten differect colors by typing "\1" or "\2", ..., "\0"   

[usefule functions] 
SearchPatternFromBuffer(pattern)            : search the pattern from all buffers 
SearchPatternFromCurrentBuffer(pattern) : search the pattern from current buffers
 
install details
just add script file into you plugin folder