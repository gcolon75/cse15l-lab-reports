# Researching Commands
grep is a very useful command that searches for a pattern in text files. I will be finding ways
to incorperate grep with other options for interesting combinations.

## 1 ```grep -c "[search]" [path and file]```
This combination will search for whatever you replace ```[search]```  (do not include brackets) and ```-c``` will count
the number of matching lines in the file and ```[path and file]``` is where you are searching.
### Example 1
![Image]


## 2 ```grep -i "[search]" [path and file]```
This command will search for the word put in ```[search]``` (do not include brackets) in a case-insensitive manner in the file
and return all the lines that match.

## 3 ```grep -v  "[search]" [path and file]```
This command will search for all lines in the file that do not contain the word in ```[search]``` (do not include brackets).

## 4 ```grep -v"[search]" [path]/*```
This command will search for all lines in all the files inside the technical directory that do not contain the word in 
```[search]``` (do not include brackets) and return them along with the filenames.
