# Definitions and Example

* less/more\
  **more** is a command that allows the viewing of text files in the command prompt and displays one screen at a time for big files.\
  The **less** command is similar to the **more** but has more advanced features and allows you to navigate both forward and backward through the file. The command displays the text file on page at a time. 
 #### Examples
 A **more** command looks like: ``` # more /var/log/auth.log ``` \
 To dictate the number of lines to reveal using a **less** command ``` # less +5 /var/log/auth.log ```


* cat\
  The **cat** command allows the creation of single or multiple files, view contain of file, concatenate files and redirect output in terminal or file. **cat** reads files sequentially, writing them to standard output. It is derived from con**cat**enate.
 #### Examples
  To display content ``` # cat /etc/passwd ```\
  To view contents of multiple files ``` # cat file1 file2 ```\
  To create a file ``` # cat >file3 ```\
  
* head/tail \
 #### Examples

* touch \
 #### Examples
 
* clear \
 #### Examples

*  df\
 #### Examples

* diff\
 #### Examples

* locate/updatedb\
 #### Examples

* export\
 #### Examples

* source\
 #### Examples
 **source** command examples
 
 ```
source filename [arguments]
source functions.sh
source /path/to/functions.sh arg1 arg2
source functions.sh WWWROOT=/apache.jail PHPROOT=/fastcgi.php_jail
 ```

* wget\
The **wget** command allows downloading files from the Internet. It supports downloading multiple files, downloading in the background, resuming downloads, limiting the bandwidth used for downloads and viewing headers.
 #### Examples

* kill/killallv\
The **kill** and **killall** commands are used to kill the specified processes.
 #### Examples
