# Shell-data-processing 

## Basic commands 
 
- ``` mkdir ``` creates a new directory
- ``` rmdir ``` deletes the specified empty directory
- ``` cp  ```  copy the files and directories from source path to destination path
- ``` touch ``` Used to create or update a file
- ``` grep ``` This command is used to search for the specified text in a file
- ``` wc ``` Used to count the number of characters, words in a file

## Command used to fetch data from url:

```  curl "http://shakespeare.mit.edu/romeo_juliet/full.html" -o "data.txt" ```

## Command used to count unique words in a sequential order:

``` tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt ```  
- ``` tr ``` tranforms or deletes characters from strings  
- ``` sort ``` sorts  the contents of a file in a particular order  
- ``` uniq -c ```  returns the number of times a word is repeated  
- ``` sort -nr ``` option -n sorts numnerically and option -r sorts in reverse order  

## Command used to display top 5 unique words
```head-5 result.txt ```
