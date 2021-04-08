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
