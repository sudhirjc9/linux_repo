# Insert
- i --> insert
- a append at the end of line 
- o line below current line
- 0 line above current line

# deleting 
- x delete current charecter
- 3x delete current charectre and next two
- dd delete current line
- 5dd delete current line and next 4 line
 -dG current line to end of line


 # coping
 - yy copies current line
 - 5yy current line and next 4 line
 - yG cuurent line to end of file



 # search 
 /<text_to_search> and press enter and then press n for next occurance

 # global search and replace

 ## :%s/Line/line/g
-[:]  start an ex command

-[%s] specifies range for oepration

-[s] specifies the operation

-[/Line/line]  search pattern and replace text

-[g] global

# Editiing multiple files

``` test
There are two ways we can edit multiple files
```


1. add all the files with vim command
2. open one file and then use :e and add the other files

Difference is that only in first case we can use :n to go to next file and :N to go for previous file not in the second case.

use :r <file_name> to enter whole content of one file to other.
