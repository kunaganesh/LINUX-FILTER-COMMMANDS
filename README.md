
# LINUX-FILTER-COMMANDS
* To view first ten lines of a file :
```bash
 head <Filename>
```
* To view custom lines of a file :
```bash
 head -n <Filename>
```
* To view last ten lines of a file :
```bash
 tail <Filename>
```
* To view custom lines of file :
```bash
 tail -n <Filename>
```
* To calculate the no.of lines, words and characters of a file :
```bash
 wc <Filename>
```
* To calculate no.of lines in a file :
```bash
 wc -l <Filename>
```
* To calculate no.of words in a file :
```bash
 wc -w <Filename>
```
* To calculate no.of characters in a file :
```bash
 wc -c <Filename>
```
* Cut command is used to cut and display the chracters in each line of a file :
```bash
 cut -c1 <Filename>
```
* This command is used to cut mutiple char in each line of a file :
```bash
 cut -c1-3 <Filename>
``` 
* This command is used to cut the fields in each line of a file :
```bash
 cut -f1 -d ":" <Filename>
```
* This command is used cut multiple fields in each line of a file :
```bash
 cut -f1-3 -d ":" <Filename>
```
* diff command is used to display different lines in two files :
```bash
 diff <File1> <File2>
```
*  sdiff command is used to display two files side by side :
```bash
 sdiff <File1> <File2>
```
* cmp command is used to compare two files char by char :
```bash
 cmp <File1> <File2>
```
* uniq command is used to display only unique lines ina file not duplicates :
```bash
 uniq <Filename>
```
*  This command is used to dispaly duplicates :
```bash
 uniq -d <Filename>
```
* This command is used to display how many times duplicates :
```bash
uniq -D <Filename>
```
* This command is used to translate char from small to capital :
```bash
 tr '[a-z]' '[A-Z]' <Filename>
```
* This command is used to scroll a file page by page or line by line :
```bash
 more <Filename>
```
* This command is also similar to more command :
```bash
 less <Filename>
```
* This command is used to sort the content in alphabetical order :
```bash
 sort <Filename>
```
*  This command is used to sort the content reverse to the alpahabetical order :
```bash
 sort -r <Filename>
```
* This command is used to search and display a perticular word in a file:
```bash
 grep wordname <Filename>
```
* This command is used to search the word and calculate how many word in that file :
```bash
grep -wc wordname <Filename>
```
* This command is used to ignore the case sensitivity and search the word :
```bash
 grep -i wordname <Filename>
```
* This command is used to search and display the word with line number :
```bash
 grep -n wordname <Filename>
```
* This command is used to search and display if there any line is starting by this word :
```bash
 grep ^'wordname' <Filename>
```
* This command is used to search and display if there any line is ending by this word :
```bash
 grep $'wordname' <Filename>
```
* This command is used to search and display without that word containing :
```bash
 grep -v 'wordname' <Filename>
```
* This command is used to display perticular line in a file :
```bash
 sed -n 'np' <Filename>
```
* This command is used to display mutiple lines ina files :
```bash
 sed -n '1, np' <Filename>
```
* This command is used to display the all the lines excepting that line :
```bash
 sed 'nd' <Filename>
```
* This command is used to diplay all the line excepting that mutiple lines :
```bash
 sed '1, nd' <Filename>
```
* This command is used to replace the word with new one in a file :
```bash
 sed 's/word/newword/g' <Filename>
```
*  This command is used to find a perticular path or file with name :
```bash
 find / -name <Filename>
```
* This command is used to find a perticular file with size in mbs :
```bash
 find / -size +10M/-10M  
```
* This command is used to find a perticular files with permissions :
```bash
 find / -perm 666  
```
* it is used to search a perticular file path with time of creation :
```bash
 find / -ctime n(days ago)
```
* it is used to search a perticular file path with accessing time :
```bash
 find / -atime n(days ago) 
```
* it is used to search a perticular file path with modified time :
```bash
 find / -mtime n  
```
* it is used to search a perticular file path with min also :
```bash
 find / -cmin n(mins ago)  
```
*  it is used to search a perticular file path with accesing on mins :
```bash
 find / -amin   
```
*  it is used to search a perticular file path with modifying time in mins :
```bash
 find / -mmin  
```
* it is used to search a perticular file path with type of files like > file(f), linked file(l) and dir(d) :
```bash
 find / -type f/d/l  
```
* it is a pipe symbol which is used to combine commands :
```bash
 |  
```
