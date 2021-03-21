# Definitions and Example

### 1. less/more
  **more** is a command that allows the viewing of text files in the command prompt and displays one screen at a time for big files.\
  The **less** command is similar to the **more** but has more advanced features and allows you to navigate both forward and backward through the file. The command displays the text file on page at a time. 
 #### Examples
 A **more** command looks like: ``` # more /var/log/auth.log ``` \
 To dictate the number of lines to reveal using a **less** command ``` # less +5 /var/log/auth.log ```


### 2. cat
  The **cat** command allows the creation of single or multiple files, view contain of file, concatenate files and redirect output in terminal or file. **cat** reads files sequentially, writing them to standard output. It is derived from con**cat**enate.
 #### Examples
  To display content ``` # cat /etc/passwd ```\
  To view contents of multiple files ``` # cat file1 file2 ```\
  To create a file ``` # cat >file3 ```
  
### 3. [head/tail](https://www.baeldung.com/linux/head-tail-commands#:~:text=Introduction%20to%20the%20head%20and%20the%20tail%20Commands&text=They%20are%2C%20by%20default%2C%20installed,the%20result%20to%20standard%20output.)
They are, by default, installed in all Linux distributions. As their names imply, the head command will output the first part of the file, while the tail command will print the last part of the file. Both commands write the result to standard output.
```
head [OPTIONS] FILES
head numbers_en.txt //The head command will, by default, write the first ten lines of the input file to the standard output
head -n 7 numbers_en.txt //With the -n option, we can let the head command output the first n lines instead of the default 10.
tail [OPTIONS] FILES
```
 #### Examples

### 4. touch 
 #### Examples
 
### 5. clear 
 #### Examples

### 6.  df
 #### Examples

### 7. diff
 #### Examples

### 8. locate/updatedb
 #### Examples

### 9. export
 #### Examples

### 10. source
The source command can be used to load any functions file into the current shell script or a command prompt. It read and execute commands from given FILENAME and return.
 #### Examples 
 ```
source filename [arguments]
source functions.sh
source /path/to/functions.sh arg1 arg2
source functions.sh WWWROOT=/apache.jail PHPROOT=/fastcgi.php_jail
 ```

### 11. wget
The **wget** command allows downloading files from the Internet. It supports downloading multiple files, downloading in the background, resuming downloads, limiting the bandwidth used for downloads and viewing headers.
 #### Examples
 ```
 wget [options] [url]
 wget -O sara_assignment_01.md https://github.com/sma589/robot_programming_essentials/linux/assignment_01.md //saves the file in downloads as sara_assignment_01.md
 wget -P /udg/RPE sara_assignment_01.md https://github.com/sma589/robot_programming_essentials/linux/assignment_01.md //saves the file in specific folder
 ```
### 12. kill/killall
The **kill** and **killall** commands are used to kill the specified processes. The difference between the two commands is that **killall** takes the process name instead of process ID or PID.


 #### Examples
 ```
 kill [OPTIONS] [PID]
 kill -l //shows the list of processes 
 killall -sKILL httpd //without interactive option
 killall -sKILL -i httpd //asks y/n before killing process
 ```
