# Stream Editor(sed)
```
sed used to find and replace text within a file

sed -i 's/Mahesh/Shivaya/gI' s.txt

In the above command:

s - substitute command of sed of find and replace
g - global replace i,e find all occurrences of Mahesh and replace with Shivaya
    so, if we remove /g only first occurance will change
-i - to update the file

```
# How to print 5th line of top command?
```
First save the output of top command in text file.

top -b -n 1 > top.txt

now use the awk command

Syntax of awk command:
awk options 'selection _criteria {action}' input-file > output-file

Below is the command to print 5th line of top command:
awk '{print $5}' top.txt
```
# Process Management
```
Process management:

Up on we hosted the application on the server, there are many processors running to see the process we use the command called PS

PS aux

It shows User Name, Process ID, %CPU, % Memory, Start time

It shows which processor is consuming more CPU

It shows which processor is consuming more memory

It shows at what time the processor is started.
```
